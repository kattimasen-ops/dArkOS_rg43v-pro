# Porting-Notizen: sig_offset_4873254
Quelle: `sig_offset_4873254.dts`  
Gefundene Knoten insgesamt: 40

## SoC / Board (Root-Eigenschaften)
- **compatible** = "rockchip,rk3562-evb\0rockchip,rk3562"
- **model** = "Rockchip RK3562 Evaluation Board"

## Speicher (memory-Knoten)
_Nichts gefunden._

## CPU / Taktstufen (OPP-Tabelle)
_Nichts gefunden._

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

## Analog-Sticks (ADC-Joystick)
_Nichts gefunden._

## Akku / Ladeschaltung / Fuel-Gauge
_Nichts gefunden._

## WiFi / Bluetooth
_Nichts gefunden._

## Audio (Codec / I2S)
_Nichts gefunden._

## Display / Panel / Backlight
_Nichts gefunden._

## Touchscreen
_Nichts gefunden._

## USB / OTG
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

## LEDs
_Nichts gefunden._

## RTC (Echtzeituhr)
_Nichts gefunden._

## Sensoren (Gyro / Accel)
_Nichts gefunden._

## Thermal-Zonen
_Nichts gefunden._

## Regulatoren (Spannungsversorgung)
_Nichts gefunden._

## Pinctrl (Pin-Multiplexing)
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
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

## Kurze GPIO-Referenzliste (alle `&gpioX ...`)
_Keine gefunden._
