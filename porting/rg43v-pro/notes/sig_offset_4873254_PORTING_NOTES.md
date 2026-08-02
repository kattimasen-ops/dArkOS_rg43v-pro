# Porting-Notizen: sig_offset_4873254
Quelle: `sig_offset_4873254.dts`  
Gefundene Knoten insgesamt: 40

## SoC / Board (Root-Eigenschaften)
- **compatible** = "rockchip,rk3562-evb\0rockchip,rk3562"
- **model** = "Rockchip RK3562 Evaluation Board"

## Speicher (memory-Knoten)
_Nichts gefunden._

## CPU / OPP-Tabelle (Taktstufen)
_Nichts gefunden._

## Rockchip System-Controller (GRF/PMU)
### `syscon@ff010000` (Zeile 55-60)
```dts
	syscon@ff010000 {
		compatible = "rockchip,rk3562-pmu-grf\0syscon\0simple-mfd";
		reg = <0x00 0xff010000 0x00 0x10000>;
		u-boot,dm-spl;
		status = "okay";
	};
```

### `syscon@ff030000` (Zeile 62-68)
```dts
	syscon@ff030000 {
		compatible = "rockchip,rk3562-sys-grf\0syscon\0simple-mfd";
		reg = <0x00 0xff030000 0x00 0x10000>;
		u-boot,dm-spl;
		status = "okay";
		phandle = <0x10000022>;
	};
```

### `syscon@ff060000` (Zeile 70-76)
```dts
	syscon@ff060000 {
		compatible = "rockchip,rk3562-ioc-grf\0syscon";
		reg = <0x00 0xff060000 0x00 0x30000>;
		u-boot,dm-spl;
		status = "okay";
		phandle = <0x10000085>;
	};
```

### `syscon@ff090000` (Zeile 78-84)
```dts
	syscon@ff090000 {
		compatible = "rockchip,rk3562-usbphy-grf\0syscon";
		reg = <0x00 0xff090000 0x00 0x8000>;
		u-boot,dm-pre-reloc;
		status = "okay";
		phandle = <0x1000005b>;
	};
```

### `clock-controller@ff100000` (Zeile 86-95)
```dts
	clock-controller@ff100000 {
		compatible = "rockchip,rk3562-cru";
		reg = <0x00 0xff100000 0x00 0x40000>;
		rockchip,grf = <0x10000022>;
		#clock-cells = <0x01>;
		#reset-cells = <0x01>;
		u-boot,dm-spl;
		status = "okay";
		phandle = <0x10000001>;
	};
```

### `usb2-phy@ff740000` (Zeile 123-142)
```dts
	usb2-phy@ff740000 {
		compatible = "rockchip,rk3562-usb2phy";
		reg = <0x00 0xff740000 0x00 0x10000>;
		clocks = <0x10000001 0x13d 0x10000001 0xfb>;
		#clock-cells = <0x00>;
		clock-output-names = "usb480m_phy";
		rockchip,usbgrf = <0x1000005b>;
		status = "okay";
		u-boot,dm-pre-reloc;
		phandle = <0x1000001a>;

		otg-port {
			#phy-cells = <0x00>;
			interrupts = <0x00 0x99 0x04 0x00 0x9a 0x04 0x00 0x9b 0x04>;
			interrupt-names = "otg-bvalid\0otg-id\0linestate";
			status = "okay";
			u-boot,dm-pre-reloc;
			phandle = <0x10000017>;
		};
	};
```

### `pinctrl` (Zeile 227-344)
```dts
	pinctrl {
		compatible = "rockchip,rk3562-pinctrl";
		rockchip,grf = <0x10000085>;
		#address-cells = <0x02>;
		#size-cells = <0x02>;
		ranges;
		u-boot,dm-spl;
		status = "okay";
		phandle = <0x1000008b>;

		gpio@ff260000 {
			compatible = "rockchip,gpio-bank";
			reg = <0x00 0xff260000 0x00 0x100>;
			interrupts = <0x00 0x00 0x04>;
			clocks = <0x10000001 0x11d 0x10000001 0x11e>;
			gpio-controller;
			#gpio-cells = <0x02>;
			gpio-ranges = <0x1000008b 0x00 0x00 0x20>;
			interrupt-controller;
			#interrupt-cells = <0x02>;
			u-boot,dm-pre-reloc;
		};

		gpio@ff620000 {
			compatible = "rockchip,gpio-bank";
			reg = <0x00 0xff620000 0x00 0x100>;
			interrupts = <0x00 0x02 0x04>;
			clocks = <0x10000001 0x100 0x10000001 0x103>;
			gpio-controller;
			#gpio-cells = <0x02>;
			gpio-ranges = <0x1000008b 0x00 0x20 0x20>;
			interrupt-controller;
			#interrupt-cells = <0x02>;
			u-boot,dm-pre-reloc;
		};

		gpio@ff630000 {
			compatible = "rockchip,gpio-bank";
			reg = <0x00 0xff630000 0x00 0x100>;
			interrupts = <0x00 0x04 0x04>;
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `secure-otp@ff920000` (Zeile 351-359)
```dts
	secure-otp@ff920000 {
		compatible = "rockchip,rk3562-secure-otp";
		reg = <0x00 0xff920000 0x00 0x4000>;
		secure_conf = <0xff020034>;
		mask_addr = <0x00>;
		cru_rst_addr = <0xff130438>;
		u-boot,dm-spl;
		status = "okay";
	};
```

## Buttons (gpio-keys / adc-keys)
### `adc-keys` (Zeile 361-375)
```dts
	adc-keys {
		compatible = "adc-keys";
		io-channels = <0x10000091 0x01>;
		io-channel-names = "buttons";
		keyup-threshold-microvolt = <0x1b7740>;
		u-boot,dm-pre-reloc;
		status = "okay";

		volumeup-key {
			u-boot,dm-pre-reloc;
			linux,code = <0x73>;
			label = "volume up";
			press-threshold-microvolt = <0x09>;
		};
	};
```

## Analog-Sticks / Joystick
_Nichts gefunden._

## Akku / Ladeschaltung / PMIC
_Nichts gefunden._

## WiFi / Bluetooth / SDIO
_Nichts gefunden._

## Audio (Codec / I2S / Sound)
_Nichts gefunden._

## Display / Panel / VOP / DSI
_Nichts gefunden._

## Touchscreen
_Nichts gefunden._

## USB / OTG / PHY
### `syscon@ff090000` (Zeile 78-84)
```dts
	syscon@ff090000 {
		compatible = "rockchip,rk3562-usbphy-grf\0syscon";
		reg = <0x00 0xff090000 0x00 0x8000>;
		u-boot,dm-pre-reloc;
		status = "okay";
		phandle = <0x1000005b>;
	};
```

### `otg-port` (Zeile 134-141)
```dts
		otg-port {
			#phy-cells = <0x00>;
			interrupts = <0x00 0x99 0x04 0x00 0x9a 0x04 0x00 0x9b 0x04>;
			interrupt-names = "otg-bvalid\0otg-id\0linestate";
			status = "okay";
			u-boot,dm-pre-reloc;
			phandle = <0x10000017>;
		};
```

## LEDs / PWM
_Nichts gefunden._

## Thermal-Zonen & Kühlung
_Nichts gefunden._

## Pinctrl (Pin-Multiplexing - Auszüge)
### `aliases` (Zeile 9-19)
```dts
	aliases {
		gpio0 = "/pinctrl/gpio@ff260000";
		gpio1 = "/pinctrl/gpio@ff620000";
		gpio2 = "/pinctrl/gpio@ff630000";
		gpio3 = "/pinctrl/gpio@ffac0000";
		gpio4 = "/pinctrl/gpio@ffad0000";
		serial2 = "/serial@ff680000";
		spi3 = "/spi@ff860000";
		mmc0 = "/mmc@ff870000";
		mmc1 = "/mmc@ff880000";
	};
```

### `mmc@ff880000` (Zeile 190-203)
```dts
	mmc@ff880000 {
		compatible = "rockchip,rk3562-dw-mshc\0rockchip,rk3288-dw-mshc";
		reg = <0x00 0xff880000 0x00 0x10000>;
		interrupts = <0x00 0x38 0x04>;
		max-frequency = <0x8f0d180>;
		clocks = <0x10000001 0x8f 0x10000001 0x90 0x10000001 0x93 0x10000001 0x94>;
		resets = <0x10000001 0xc0040>;
		reset-names = "reset";
		fifo-depth = <0x100>;
		status = "okay";
		u-boot,dm-spl;
		pinctrl-names = "default";
		pinctrl-0 = <0x1000007b 0x1000007c 0x1000007d 0x1000007e>;
	};
```

### `pinctrl` (Zeile 227-344)
```dts
	pinctrl {
		compatible = "rockchip,rk3562-pinctrl";
		rockchip,grf = <0x10000085>;
		#address-cells = <0x02>;
		#size-cells = <0x02>;
		ranges;
		u-boot,dm-spl;
		status = "okay";
		phandle = <0x1000008b>;

		gpio@ff260000 {
			compatible = "rockchip,gpio-bank";
			reg = <0x00 0xff260000 0x00 0x100>;
			interrupts = <0x00 0x00 0x04>;
			clocks = <0x10000001 0x11d 0x10000001 0x11e>;
			gpio-controller;
			#gpio-cells = <0x02>;
			gpio-ranges = <0x1000008b 0x00 0x00 0x20>;
			interrupt-controller;
			#interrupt-cells = <0x02>;
			u-boot,dm-pre-reloc;
		};

		gpio@ff620000 {
			compatible = "rockchip,gpio-bank";
			reg = <0x00 0xff620000 0x00 0x100>;
			interrupts = <0x00 0x02 0x04>;
			clocks = <0x10000001 0x100 0x10000001 0x103>;
			gpio-controller;
			#gpio-cells = <0x02>;
			gpio-ranges = <0x1000008b 0x00 0x20 0x20>;
			interrupt-controller;
			#interrupt-cells = <0x02>;
			u-boot,dm-pre-reloc;
		};

		gpio@ff630000 {
			compatible = "rockchip,gpio-bank";
			reg = <0x00 0xff630000 0x00 0x100>;
			interrupts = <0x00 0x04 0x04>;
			clocks = <0x10000001 0x101 0x10000001 0x104>;
			gpio-controller;
			#gpio-cells = <0x02>;
			gpio-ranges = <0x1000008b 0x00 0x40 0x20>;
			interrupt-controller;
			#interrupt-cells = <0x02>;
			u-boot,dm-pre-reloc;
		};

		gpio@ffac0000 {
			compatible = "rockchip,gpio-bank";
			reg = <0x00 0xffac0000 0x00 0x100>;
			interrupts = <0x00 0x06 0x04>;
			clocks = <0x10000001 0x54 0x10000001 0x26>;
			gpio-controller;
			#gpio-cells = <0x02>;
			gpio-ranges = <0x1000008b 0x00 0x60 0x20>;
			interrupt-controller;
			#interrupt-cells = <0x02>;
			u-boot,dm-pre-reloc;
		};

		gpio@ffad0000 {
			compatible = "rockchip,gpio-bank";
			reg = <0x00 0xffad0000 0x00 0x100>;
			interrupts = <0x00 0x08 0x04>;
			clocks = <0x10000001 0x55 0x10000001 0x27>;
			gpio-controller;
			#gpio-cells = <0x02>;
			gpio-ranges = <0x1000008b 0x00 0x80 0x20>;
			interrupt-controller;
			#interrupt-cells = <0x02>;
			u-boot,dm-pre-reloc;
		};

		pcfg-pull-up {
			bias-pull-up;
			u-boot,dm-spl;
			status = "okay";
			phandle = <0x1000008f>;
		};

		pcfg-pull-up-drv-level-2 {
			bias-pull-up;
			drive-strength = <0x02>;
			u-boot,dm-spl;
			status = "okay";
			phandle = <0x1000008d>;
		};

		sdmmc0-pins {
			u-boot,dm-spl;

			sdmmc0-bus4 {
				rockchip,pins = <0x01 0x0b 0x01 0x1000008d 0x01 0x0c 0x01 0x1000008d 0x01 0x0d 0x01 0x1000008d 0x01 0x0e 0x01 0x1000008d>;
				u-boot,dm-spl;
				phandle = <0x1000007e>;
			};

			sdmmc0-clk {
				rockchip,pins = <0x01 0x10 0x01 0x1000008d>;
				u-boot,dm-spl;
				phandle = <0x1000007b>;
			};

			sdmmc0-cmd {
				rockchip,pins = <0x01 0x0f 0x01 0x1000008d>;
				u-boot,dm-spl;
				phandle = <0x1000007c>;
			};

			sdmmc0-det {
				rockchip,pins = <0x00 0x04 0x01 0x1000008f>;
				u-boot,dm-spl;
				phandle = <0x1000007d>;
			};
		};
	};
```

