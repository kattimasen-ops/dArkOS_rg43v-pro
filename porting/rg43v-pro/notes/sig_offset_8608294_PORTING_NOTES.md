# Porting-Notizen: sig_offset_8608294
Quelle: `sig_offset_8608294.dts`  
Gefundene Knoten insgesamt: 895

## SoC / Board (Root-Eigenschaften)
- **compatible** = "rockchip,rk3562-evb1-lp4x-v10\0rockchip,rk3562"
- **model** = "Rockchip RK3562 EVB1 LP4X V10 Board"

## Speicher (memory-Knoten)
_Nichts gefunden._

## CPU / Taktstufen (OPP-Tabelle)
### `cpu@0` (Zeile 194-206)
```dts
		cpu@0 {
			device_type = "cpu";
			compatible = "arm,cortex-a53";
			reg = <0x00 0x00>;
			enable-method = "psci";
			clocks = <0x05 0x08>;
			cpu-idle-states = <0x06>;
			operating-points-v2 = <0x07>;
			#cooling-cells = <0x02>;
			dynamic-power-coefficient = <0x8a>;
			cpu-supply = <0x08>;
			phandle = <0x0f>;
		};
```

### `cpu@1` (Zeile 208-219)
```dts
		cpu@1 {
			device_type = "cpu";
			compatible = "arm,cortex-a53";
			reg = <0x00 0x01>;
			enable-method = "psci";
			clocks = <0x05 0x08>;
			cpu-idle-states = <0x06>;
			operating-points-v2 = <0x07>;
			#cooling-cells = <0x02>;
			dynamic-power-coefficient = <0x8a>;
			phandle = <0x10>;
		};
```

### `cpu@2` (Zeile 221-232)
```dts
		cpu@2 {
			device_type = "cpu";
			compatible = "arm,cortex-a53";
			reg = <0x00 0x02>;
			enable-method = "psci";
			clocks = <0x05 0x08>;
			cpu-idle-states = <0x06>;
			operating-points-v2 = <0x07>;
			#cooling-cells = <0x02>;
			dynamic-power-coefficient = <0x8a>;
			phandle = <0x11>;
		};
```

### `cpu@3` (Zeile 234-245)
```dts
		cpu@3 {
			device_type = "cpu";
			compatible = "arm,cortex-a53";
			reg = <0x00 0x03>;
			enable-method = "psci";
			clocks = <0x05 0x08>;
			cpu-idle-states = <0x06>;
			operating-points-v2 = <0x07>;
			#cooling-cells = <0x02>;
			dynamic-power-coefficient = <0x8a>;
			phandle = <0x12>;
		};
```

### `opp-408000000` (Zeile 284-290)
```dts
		opp-408000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x18519600>;
			opp-microvolt = <0xc96a8 0xc96a8 0x118c30>;
			clock-latency-ns = <0x9c40>;
			opp-suspend;
		};
```

### `opp-600000000` (Zeile 292-297)
```dts
		opp-600000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x23c34600>;
			opp-microvolt = <0xc96a8 0xc96a8 0x118c30>;
			clock-latency-ns = <0x9c40>;
		};
```

### `opp-816000000` (Zeile 299-304)
```dts
		opp-816000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x30a32c00>;
			opp-microvolt = <0xc96a8 0xc96a8 0x118c30>;
			clock-latency-ns = <0x9c40>;
		};
```

### `opp-1008000000` (Zeile 306-316)
```dts
		opp-1008000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x3c14dc00>;
			opp-microvolt = <0xcf850 0xcf850 0x118c30>;
			opp-microvolt-L0 = <0xcf850 0xcf850 0x118c30>;
			opp-microvolt-L1 = <0xc96a8 0xc96a8 0x118c30>;
			opp-microvolt-L2 = <0xc96a8 0xc96a8 0x118c30>;
			opp-microvolt-L3 = <0xc96a8 0xc96a8 0x118c30>;
			opp-microvolt-L4 = <0xc96a8 0xc96a8 0x118c30>;
			clock-latency-ns = <0x9c40>;
		};
```

### `opp-1200000000` (Zeile 318-328)
```dts
		opp-1200000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x47868c00>;
			opp-microvolt = <0xe1d48 0xe1d48 0x118c30>;
			opp-microvolt-L0 = <0xe1d48 0xe1d48 0x118c30>;
			opp-microvolt-L1 = <0xdbba0 0xdbba0 0x118c30>;
			opp-microvolt-L2 = <0xd59f8 0xd59f8 0x118c30>;
			opp-microvolt-L3 = <0xcf850 0xcf850 0x118c30>;
			opp-microvolt-L4 = <0xc96a8 0xc96a8 0x118c30>;
			clock-latency-ns = <0x9c40>;
		};
```

### `opp-1416000000` (Zeile 330-340)
```dts
		opp-1416000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x54667200>;
			opp-microvolt = <0xf4240 0xf4240 0x118c30>;
			opp-microvolt-L0 = <0xf4240 0xf4240 0x118c30>;
			opp-microvolt-L1 = <0xee098 0xee098 0x118c30>;
			opp-microvolt-L2 = <0xe7ef0 0xe7ef0 0x118c30>;
			opp-microvolt-L3 = <0xe1d48 0xe1d48 0x118c30>;
			opp-microvolt-L4 = <0xdbba0 0xdbba0 0x118c30>;
			clock-latency-ns = <0x9c40>;
		};
```

### `opp-1608000000` (Zeile 342-352)
```dts
		opp-1608000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x5fd82200>;
			opp-microvolt = <0xfd4bc 0xfd4bc 0x118c30>;
			opp-microvolt-L0 = <0xfd4bc 0xfd4bc 0x118c30>;
			opp-microvolt-L1 = <0xf7314 0xf7314 0x118c30>;
			opp-microvolt-L2 = <0xf116c 0xf116c 0x118c30>;
			opp-microvolt-L3 = <0xeafc4 0xeafc4 0x118c30>;
			opp-microvolt-L4 = <0xe4e1c 0xe4e1c 0x118c30>;
			clock-latency-ns = <0x9c40>;
		};
```

### `opp-1800000000` (Zeile 354-364)
```dts
		opp-1800000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x6b49d200>;
			opp-microvolt = <0x112a88 0x112a88 0x118c30>;
			opp-microvolt-L0 = <0x112a88 0x112a88 0x118c30>;
			opp-microvolt-L1 = <0x10c8e0 0x10c8e0 0x118c30>;
			opp-microvolt-L2 = <0x106738 0x106738 0x118c30>;
			opp-microvolt-L3 = <0x100590 0x100590 0x118c30>;
			opp-microvolt-L4 = <0xfa3e8 0xfa3e8 0x118c30>;
			clock-latency-ns = <0x9c40>;
		};
```

### `opp-2016000000` (Zeile 366-376)
```dts
		opp-2016000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x7829b800>;
			opp-microvolt = <0x118c30 0x118c30 0x118c30>;
			opp-microvolt-L0 = <0x118c30 0x118c30 0x118c30>;
			opp-microvolt-L1 = <0x118c30 0x118c30 0x118c30>;
			opp-microvolt-L2 = <0x112a88 0x112a88 0x118c30>;
			opp-microvolt-L3 = <0x10c8e0 0x10c8e0 0x118c30>;
			opp-microvolt-L4 = <0x106738 0x106738 0x118c30>;
			clock-latency-ns = <0x9c40>;
		};
```

### `opp-j-408000000` (Zeile 378-383)
```dts
		opp-j-408000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x18519600>;
			opp-microvolt = <0xdbba0 0xdbba0 0x118c30>;
			clock-latency-ns = <0x9c40>;
		};
```

### `opp-j-600000000` (Zeile 385-390)
```dts
		opp-j-600000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x23c34600>;
			opp-microvolt = <0xdbba0 0xdbba0 0x118c30>;
			clock-latency-ns = <0x9c40>;
		};
```

### `opp-j-816000000` (Zeile 392-397)
```dts
		opp-j-816000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x30a32c00>;
			opp-microvolt = <0xdbba0 0xdbba0 0x118c30>;
			clock-latency-ns = <0x9c40>;
		};
```

### `opp-j-1008000000` (Zeile 399-404)
```dts
		opp-j-1008000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x3c14dc00>;
			opp-microvolt = <0xdbba0 0xdbba0 0x118c30>;
			clock-latency-ns = <0x9c40>;
		};
```

### `opp-j-1200000000` (Zeile 406-412)
```dts
		opp-j-1200000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x47868c00>;
			opp-microvolt = <0xdbba0 0xdbba0 0x118c30>;
			opp-microvolt-L0 = <0xe1d48 0xe1d48 0x118c30>;
			clock-latency-ns = <0x9c40>;
		};
```

### `opp-j-od-1416000000` (Zeile 414-426)
```dts
		opp-j-od-1416000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x54667200>;
			opp-microvolt = <0xf4240 0xf4240 0x118c30>;
			opp-microvolt-L0 = <0xf4240 0xf4240 0x118c30>;
			opp-microvolt-L1 = <0xee098 0xee098 0x118c30>;
			opp-microvolt-L2 = <0xe7ef0 0xe7ef0 0x118c30>;
			opp-microvolt-L3 = <0xe1d48 0xe1d48 0x118c30>;
			opp-microvolt-L4 = <0xdbba0 0xdbba0 0x118c30>;
			clock-latency-ns = <0x9c40>;
			status = "disabled";
			phandle = <0x100>;
		};
```

### `opp-j-od-1608000000` (Zeile 428-440)
```dts
		opp-j-od-1608000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x5fd82200>;
			opp-microvolt = <0xfd4bc 0xfd4bc 0x118c30>;
			opp-microvolt-L0 = <0xfd4bc 0xfd4bc 0x118c30>;
			opp-microvolt-L1 = <0xf7314 0xf7314 0x118c30>;
			opp-microvolt-L2 = <0xf116c 0xf116c 0x118c30>;
			opp-microvolt-L3 = <0xeafc4 0xeafc4 0x118c30>;
			opp-microvolt-L4 = <0xe4e1c 0xe4e1c 0x118c30>;
			clock-latency-ns = <0x9c40>;
			status = "disabled";
			phandle = <0x101>;
		};
```

### `opp-j-od-1800000000` (Zeile 442-454)
```dts
		opp-j-od-1800000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x6b49d200>;
			opp-microvolt = <0x112a88 0x112a88 0x118c30>;
			opp-microvolt-L0 = <0x112a88 0x112a88 0x118c30>;
			opp-microvolt-L1 = <0x10c8e0 0x10c8e0 0x118c30>;
			opp-microvolt-L2 = <0x106738 0x106738 0x118c30>;
			opp-microvolt-L3 = <0x100590 0x100590 0x118c30>;
			opp-microvolt-L4 = <0xfa3e8 0xfa3e8 0x118c30>;
			clock-latency-ns = <0x9c40>;
			status = "disabled";
			phandle = <0x102>;
		};
```

### `opp-1560000000` (Zeile 592-599)
```dts
		opp-1560000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x5cfbb600>;
			opp-microvolt = <0xdbba0 0xdbba0 0xe7ef0>;
			opp-microvolt-L0 = <0xdbba0 0xdbba0 0xe7ef0>;
			opp-microvolt-L1 = <0xd59f8 0xd59f8 0xe7ef0>;
			opp-microvolt-L2 = <0xcf850 0xcf850 0xe7ef0>;
		};
```

### `opp-j-1560000000` (Zeile 601-605)
```dts
		opp-j-1560000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x5cfbb600>;
			opp-microvolt = <0xdbba0 0xdbba0 0xdbba0>;
		};
```

### `opp-300000000` (Zeile 2064-2068)
```dts
		opp-300000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x11e1a300>;
			opp-microvolt = <0xc96a8 0xc96a8 0xf4240>;
		};
```

### `opp-400000000` (Zeile 2070-2074)
```dts
		opp-400000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x17d78400>;
			opp-microvolt = <0xc96a8 0xc96a8 0xf4240>;
		};
```

### `opp-500000000` (Zeile 2076-2080)
```dts
		opp-500000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x1dcd6500>;
			opp-microvolt = <0xc96a8 0xc96a8 0xf4240>;
		};
```

### `opp-600000000` (Zeile 2082-2091)
```dts
		opp-600000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x23c34600>;
			opp-microvolt = <0xd59f8 0xd59f8 0xf4240>;
			opp-microvolt-L0 = <0xd59f8 0xd59f8 0xf4240>;
			opp-microvolt-L1 = <0xcf850 0xcf850 0xf4240>;
			opp-microvolt-L2 = <0xc96a8 0xc96a8 0xf4240>;
			opp-microvolt-L3 = <0xc96a8 0xc96a8 0xf4240>;
			opp-microvolt-L4 = <0xc96a8 0xc96a8 0xf4240>;
		};
```

### `opp-700000000` (Zeile 2093-2102)
```dts
		opp-700000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x29b92700>;
			opp-microvolt = <0xe1d48 0xe1d48 0xf4240>;
			opp-microvolt-L0 = <0xe1d48 0xe1d48 0xf4240>;
			opp-microvolt-L1 = <0xdbba0 0xdbba0 0xf4240>;
			opp-microvolt-L2 = <0xd59f8 0xd59f8 0xf4240>;
			opp-microvolt-L3 = <0xcf850 0xcf850 0xf4240>;
			opp-microvolt-L4 = <0xc96a8 0xc96a8 0xf4240>;
		};
```

### `opp-800000000` (Zeile 2104-2113)
```dts
		opp-800000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x2faf0800>;
			opp-microvolt = <0xee098 0xee098 0xf4240>;
			opp-microvolt-L0 = <0xee098 0xee098 0xf4240>;
			opp-microvolt-L1 = <0xe7ef0 0xe7ef0 0xf4240>;
			opp-microvolt-L2 = <0xe1d48 0xe1d48 0xf4240>;
			opp-microvolt-L3 = <0xdbba0 0xdbba0 0xf4240>;
			opp-microvolt-L4 = <0xd59f8 0xd59f8 0xf4240>;
		};
```

### `opp-900000000` (Zeile 2115-2124)
```dts
		opp-900000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x35a4e900>;
			opp-microvolt = <0xf4240 0xf4240 0xf4240>;
			opp-microvolt-L0 = <0xf4240 0xf4240 0xf4240>;
			opp-microvolt-L1 = <0xf4240 0xf4240 0xf4240>;
			opp-microvolt-L2 = <0xee098 0xee098 0xf4240>;
			opp-microvolt-L3 = <0xe7ef0 0xe7ef0 0xf4240>;
			opp-microvolt-L4 = <0xe1d48 0xe1d48 0xf4240>;
		};
```

### `opp-1000000000` (Zeile 2126-2135)
```dts
		opp-1000000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x3b9aca00>;
			opp-microvolt = <0xf4240 0xf4240 0xf4240>;
			opp-microvolt-L0 = <0xf4240 0xf4240 0xf4240>;
			opp-microvolt-L1 = <0xf4240 0xf4240 0xf4240>;
			opp-microvolt-L2 = <0xf4240 0xf4240 0xf4240>;
			opp-microvolt-L3 = <0xee098 0xee098 0xf4240>;
			opp-microvolt-L4 = <0xe7ef0 0xe7ef0 0xf4240>;
		};
```

### `opp-j-300000000` (Zeile 2137-2141)
```dts
		opp-j-300000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x11e1a300>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
		};
```

### `opp-j-400000000` (Zeile 2143-2147)
```dts
		opp-j-400000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x17d78400>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
		};
```

### `opp-j-500000000` (Zeile 2149-2153)
```dts
		opp-j-500000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x1dcd6500>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
		};
```

### `opp-j-600000000` (Zeile 2155-2159)
```dts
		opp-j-600000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x23c34600>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
		};
```

### `opp-j-700000000` (Zeile 2161-2166)
```dts
		opp-j-700000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x29b92700>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
			opp-microvolt-L0 = <0xe1d48 0xe1d48 0xf4240>;
		};
```

### `opp-j-od-800000000` (Zeile 2168-2179)
```dts
		opp-j-od-800000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x2faf0800>;
			opp-microvolt = <0xee098 0xee098 0xf4240>;
			opp-microvolt-L0 = <0xee098 0xee098 0xf4240>;
			opp-microvolt-L1 = <0xe7ef0 0xe7ef0 0xf4240>;
			opp-microvolt-L2 = <0xe1d48 0xe1d48 0xf4240>;
			opp-microvolt-L3 = <0xdbba0 0xdbba0 0xf4240>;
			opp-microvolt-L4 = <0xdbba0 0xdbba0 0xf4240>;
			status = "disabled";
			phandle = <0x173>;
		};
```

### `opp-j-od-900000000` (Zeile 2181-2192)
```dts
		opp-j-od-900000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x35a4e900>;
			opp-microvolt = <0xf4240 0xf4240 0xf4240>;
			opp-microvolt-L0 = <0xf4240 0xf4240 0xf4240>;
			opp-microvolt-L1 = <0xf4240 0xf4240 0xf4240>;
			opp-microvolt-L2 = <0xee098 0xee098 0xf4240>;
			opp-microvolt-L3 = <0xe7ef0 0xe7ef0 0xf4240>;
			opp-microvolt-L4 = <0xe1d48 0xe1d48 0xf4240>;
			status = "disabled";
			phandle = <0x174>;
		};
```

### `opp-j-od-1000000000` (Zeile 2194-2205)
```dts
		opp-j-od-1000000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x3b9aca00>;
			opp-microvolt = <0xf4240 0xf4240 0xf4240>;
			opp-microvolt-L0 = <0xf4240 0xf4240 0xf4240>;
			opp-microvolt-L1 = <0xf4240 0xf4240 0xf4240>;
			opp-microvolt-L2 = <0xf4240 0xf4240 0xf4240>;
			opp-microvolt-L3 = <0xee098 0xee098 0xf4240>;
			opp-microvolt-L4 = <0xe7ef0 0xe7ef0 0xf4240>;
			status = "disabled";
			phandle = <0x175>;
		};
```

### `opp-300000000` (Zeile 2260-2264)
```dts
		opp-300000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x11e1a300>;
			opp-microvolt = <0xc96a8 0xc96a8 0xf4240>;
		};
```

### `opp-400000000` (Zeile 2266-2270)
```dts
		opp-400000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x17d78400>;
			opp-microvolt = <0xc96a8 0xc96a8 0xf4240>;
		};
```

### `opp-500000000` (Zeile 2272-2276)
```dts
		opp-500000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x1dcd6500>;
			opp-microvolt = <0xc96a8 0xc96a8 0xf4240>;
		};
```

### `opp-600000000` (Zeile 2278-2282)
```dts
		opp-600000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x23c34600>;
			opp-microvolt = <0xc96a8 0xc96a8 0xf4240>;
		};
```

### `opp-700000000` (Zeile 2284-2293)
```dts
		opp-700000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x29b92700>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
			opp-microvolt-L0 = <0xdbba0 0xdbba0 0xf4240>;
			opp-microvolt-L1 = <0xd59f8 0xd59f8 0xf4240>;
			opp-microvolt-L2 = <0xcf850 0xcf850 0xf4240>;
			opp-microvolt-L3 = <0xc96a8 0xc96a8 0xf4240>;
			opp-microvolt-L4 = <0xc96a8 0xc96a8 0xf4240>;
		};
```

### `opp-800000000` (Zeile 2295-2304)
```dts
		opp-800000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x2faf0800>;
			opp-microvolt = <0xe7ef0 0xe7ef0 0xf4240>;
			opp-microvolt-L0 = <0xe7ef0 0xe7ef0 0xf4240>;
			opp-microvolt-L1 = <0xe1d48 0xe1d48 0xf4240>;
			opp-microvolt-L2 = <0xdbba0 0xdbba0 0xf4240>;
			opp-microvolt-L3 = <0xd59f8 0xd59f8 0xf4240>;
			opp-microvolt-L4 = <0xcf850 0xcf850 0xf4240>;
		};
```

### `opp-900000000` (Zeile 2306-2315)
```dts
		opp-900000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x35a4e900>;
			opp-microvolt = <0xf4240 0xf4240 0xf4240>;
			opp-microvolt-L0 = <0xf4240 0xf4240 0xf4240>;
			opp-microvolt-L1 = <0xee098 0xee098 0xf4240>;
			opp-microvolt-L2 = <0xe7ef0 0xe7ef0 0xf4240>;
			opp-microvolt-L3 = <0xe1d48 0xe1d48 0xf4240>;
			opp-microvolt-L4 = <0xdbba0 0xdbba0 0xf4240>;
		};
```

### `opp-j-300000000` (Zeile 2317-2321)
```dts
		opp-j-300000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x11e1a300>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
		};
```

### `opp-j-400000000` (Zeile 2323-2327)
```dts
		opp-j-400000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x17d78400>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
		};
```

### `opp-j-500000000` (Zeile 2329-2333)
```dts
		opp-j-500000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x1dcd6500>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
		};
```

### `opp-j-600000000` (Zeile 2335-2339)
```dts
		opp-j-600000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x23c34600>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
		};
```

### `opp-j-700000000` (Zeile 2341-2345)
```dts
		opp-j-700000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x29b92700>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
		};
```

### `opp-j-od-800000000` (Zeile 2347-2358)
```dts
		opp-j-od-800000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x2faf0800>;
			opp-microvolt = <0xe7ef0 0xe7ef0 0xf4240>;
			opp-microvolt-L0 = <0xe7ef0 0xe7ef0 0xf4240>;
			opp-microvolt-L1 = <0xe1d48 0xe1d48 0xf4240>;
			opp-microvolt-L2 = <0xdbba0 0xdbba0 0xf4240>;
			opp-microvolt-L3 = <0xd59f8 0xd59f8 0xf4240>;
			opp-microvolt-L4 = <0xcf850 0xcf850 0xf4240>;
			status = "disabled";
			phandle = <0x176>;
		};
```

### `opp-j-od-900000000` (Zeile 2360-2371)
```dts
		opp-j-od-900000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x35a4e900>;
			opp-microvolt = <0xf4240 0xf4240 0xf4240>;
			opp-microvolt-L0 = <0xf4240 0xf4240 0xf4240>;
			opp-microvolt-L1 = <0xee098 0xee098 0xf4240>;
			opp-microvolt-L2 = <0xe7ef0 0xe7ef0 0xf4240>;
			opp-microvolt-L3 = <0xe1d48 0xe1d48 0xf4240>;
			opp-microvolt-L4 = <0xdbba0 0xdbba0 0xf4240>;
			status = "disabled";
			phandle = <0x177>;
		};
```

### `__symbols__` (Zeile 6356-7054)
```dts
	__symbols__ {
		xin32k = "/clocks/xin32k";
		xin24m = "/clocks/xin24m";
		hclk_vepu = "/clocks/hclk_vepu@ff100324";
		aclk_vdpu = "/clocks/aclk_vdpu@ff100328";
		aclk_vi_isp = "/clocks/aclk_vi_isp@ff10032c";
		aclk_vo = "/clocks/aclk_vo@ff100334";
		aclk_vepu = "/clocks/aclk_vepu@ff100324";
		aclk_rga_jdec = "/clocks/aclk_rga_jdec@ff100338";
		mclkin_sai0 = "/clocks/mclkin-sai0";
		mclkin_sai1 = "/clocks/mclkin-sai1";
		mclkin_sai2 = "/clocks/mclkin-sai2";
		mclkout_sai0 = "/clocks/mclkout-sai0@ff040070";
		mclkout_sai1 = "/clocks/mclkout-sai1@ff040070";
		mclkout_sai2 = "/clocks/mclkout-sai2@ff040070";
		cpu0 = "/cpus/cpu@0";
		cpu1 = "/cpus/cpu@1";
		cpu2 = "/cpus/cpu@2";
		cpu3 = "/cpus/cpu@3";
		CPU_SLEEP = "/cpus/idle-states/cpu-sleep";
		cpu0_opp_table = "/cpu0-opp-table";
		cpu_opp_j_od_1416000000 = "/cpu0-opp-table/opp-j-od-1416000000";
		cpu_opp_j_od_1608000000 = "/cpu0-opp-table/opp-j-od-1608000000";
		cpu_opp_j_od_1800000000 = "/cpu0-opp-table/opp-j-od-1800000000";
		arm_pmu = "/arm-pmu";
		csi2_dphy0 = "/csi2-dphy0";
		csi2_dphy1 = "/csi2-dphy1";
		csi2_dphy2 = "/csi2-dphy2";
		csi2_dphy3 = "/csi2-dphy3";
		csi2_dphy4 = "/csi2-dphy4";
		csi2_dphy5 = "/csi2-dphy5";
		csu = "/csu";
		display_subsystem = "/display-subsystem";
		route_dsi = "/display-subsystem/route/route-dsi";
		route_lvds = "/display-subsystem/route/route-lvds";
		route_rgb = "/display-subsystem/route/route-rgb";
		dmc = "/dmc";
		dmc_opp_table = "/dmc-opp-table";
		scmi = "/firmware/scmi";
		scmi_clk = "/firmware/scmi/protocol@14";
		optee = "/firmware/optee";
		mpp_srv = "/mpp-srv";
		mipi0_csi2 = "/mipi0-csi2";
		mipi1_csi2 = "/mipi1-csi2";
		mipi2_csi2 = "/mipi2-csi2";
		mipi3_csi2 = "/mipi3-csi2";
		reserved_memory = "/reserved-memory";
		drm_logo = "/reserved-memory/drm-logo@00000000";
		vendor_storage_rm = "/reserved-memory/vendor-storage-rm@00000000";
		drm_cubic_lut = "/reserved-memory/drm-cubic-lut@00000000";
		ramoops = "/reserved-memory/ramoops@110000";
		rkcif_mipi_lvds = "/rkcif-mipi-lvds";
		rkcif_mipi_lvds_sditf = "/rkcif-mipi-lvds-sditf";
		rkcif_mipi_lvds_sditf_vir1 = "/rkcif-mipi-lvds-sditf-vir1";
		rkcif_mipi_lvds_sditf_vir2 = "/rkcif-mipi-lvds-sditf-vir2";
		rkcif_mipi_lvds_sditf_vir3 = "/rkcif-mipi-lvds-sditf-vir3";
		rkcif_mipi_lvds1 = "/rkcif-mipi-lvds1";
		rkcif_mipi_lvds1_sditf = "/rkcif-mipi-lvds1-sditf";
		rkcif_mipi_lvds1_sditf_vir1 = "/rkcif-mipi-lvds1-sditf-vir1";
		rkcif_mipi_lvds1_sditf_vir2 = "/rkcif-mipi-lvds1-sditf-vir2";
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

## Buttons (gpio-keys / adc-keys)
### `adc-keys` (Zeile 6013-6032)
```dts
	adc-keys {
		compatible = "adc-keys";
		io-channels = <0xdd 0x01>;
		io-channel-names = "buttons";
		keyup-threshold-microvolt = <0x1b7740>;
		poll-interval = <0x64>;
		phandle = <0x2b0>;

		vol-up-key {
			linux,code = <0x73>;
			label = "volume up";
			press-threshold-microvolt = <0x4268>;
		};

		vol-down-key {
			linux,code = <0x72>;
			label = "volume down";
			press-threshold-microvolt = <0x124f80>;
		};
	};
```

### `rst-keys` (Zeile 6254-6267)
```dts
	rst-keys {
		compatible = "adc-keys";
		io-channels = <0xdd 0x07>;
		io-channel-names = "buttons";
		keyup-threshold-microvolt = <0x1b7740>;
		poll-interval = <0x64>;
		phandle = <0x2b8>;

		reset-key {
			linux,code = <0x3b>;
			label = "reset";
			press-threshold-microvolt = <0x927c0>;
		};
	};
```

### `__symbols__` (Zeile 6356-7054)
```dts
	__symbols__ {
		xin32k = "/clocks/xin32k";
		xin24m = "/clocks/xin24m";
		hclk_vepu = "/clocks/hclk_vepu@ff100324";
		aclk_vdpu = "/clocks/aclk_vdpu@ff100328";
		aclk_vi_isp = "/clocks/aclk_vi_isp@ff10032c";
		aclk_vo = "/clocks/aclk_vo@ff100334";
		aclk_vepu = "/clocks/aclk_vepu@ff100324";
		aclk_rga_jdec = "/clocks/aclk_rga_jdec@ff100338";
		mclkin_sai0 = "/clocks/mclkin-sai0";
		mclkin_sai1 = "/clocks/mclkin-sai1";
		mclkin_sai2 = "/clocks/mclkin-sai2";
		mclkout_sai0 = "/clocks/mclkout-sai0@ff040070";
		mclkout_sai1 = "/clocks/mclkout-sai1@ff040070";
		mclkout_sai2 = "/clocks/mclkout-sai2@ff040070";
		cpu0 = "/cpus/cpu@0";
		cpu1 = "/cpus/cpu@1";
		cpu2 = "/cpus/cpu@2";
		cpu3 = "/cpus/cpu@3";
		CPU_SLEEP = "/cpus/idle-states/cpu-sleep";
		cpu0_opp_table = "/cpu0-opp-table";
		cpu_opp_j_od_1416000000 = "/cpu0-opp-table/opp-j-od-1416000000";
		cpu_opp_j_od_1608000000 = "/cpu0-opp-table/opp-j-od-1608000000";
		cpu_opp_j_od_1800000000 = "/cpu0-opp-table/opp-j-od-1800000000";
		arm_pmu = "/arm-pmu";
		csi2_dphy0 = "/csi2-dphy0";
		csi2_dphy1 = "/csi2-dphy1";
		csi2_dphy2 = "/csi2-dphy2";
		csi2_dphy3 = "/csi2-dphy3";
		csi2_dphy4 = "/csi2-dphy4";
		csi2_dphy5 = "/csi2-dphy5";
		csu = "/csu";
		display_subsystem = "/display-subsystem";
		route_dsi = "/display-subsystem/route/route-dsi";
		route_lvds = "/display-subsystem/route/route-lvds";
		route_rgb = "/display-subsystem/route/route-rgb";
		dmc = "/dmc";
		dmc_opp_table = "/dmc-opp-table";
		scmi = "/firmware/scmi";
		scmi_clk = "/firmware/scmi/protocol@14";
		optee = "/firmware/optee";
		mpp_srv = "/mpp-srv";
		mipi0_csi2 = "/mipi0-csi2";
		mipi1_csi2 = "/mipi1-csi2";
		mipi2_csi2 = "/mipi2-csi2";
		mipi3_csi2 = "/mipi3-csi2";
		reserved_memory = "/reserved-memory";
		drm_logo = "/reserved-memory/drm-logo@00000000";
		vendor_storage_rm = "/reserved-memory/vendor-storage-rm@00000000";
		drm_cubic_lut = "/reserved-memory/drm-cubic-lut@00000000";
		ramoops = "/reserved-memory/ramoops@110000";
		rkcif_mipi_lvds = "/rkcif-mipi-lvds";
		rkcif_mipi_lvds_sditf = "/rkcif-mipi-lvds-sditf";
		rkcif_mipi_lvds_sditf_vir1 = "/rkcif-mipi-lvds-sditf-vir1";
		rkcif_mipi_lvds_sditf_vir2 = "/rkcif-mipi-lvds-sditf-vir2";
		rkcif_mipi_lvds_sditf_vir3 = "/rkcif-mipi-lvds-sditf-vir3";
		rkcif_mipi_lvds1 = "/rkcif-mipi-lvds1";
		rkcif_mipi_lvds1_sditf = "/rkcif-mipi-lvds1-sditf";
		rkcif_mipi_lvds1_sditf_vir1 = "/rkcif-mipi-lvds1-sditf-vir1";
		rkcif_mipi_lvds1_sditf_vir2 = "/rkcif-mipi-lvds1-sditf-vir2";
		rkcif_mipi_lvds1_sditf_vir3 = "/rkcif-mipi-lvds1-sditf-vir3";
		rkcif_mipi_lvds2 = "/rkcif-mipi-lvds2";
		rkcif_mipi_lvds2_sditf = "/rkcif-mipi-lvds2-sditf";
		rkcif_mipi_lvds2_sditf_vir1 = "/rkcif-mipi-lvds2-sditf-vir1";
		rkcif_mipi_lvds2_sditf_vir2 = "/rkcif-mipi-lvds2-sditf-vir2";
		rkcif_mipi_lvds2_sditf_vir3 = "/rkcif-mipi-lvds2-sditf-vir3";
		rkcif_mipi_lvds3 = "/rkcif-mipi-lvds3";
		rkcif_mipi_lvds3_sditf = "/rkcif-mipi-lvds3-sditf";
		rkcif_mipi_lvds3_sditf_vir1 = "/rkcif-mipi-lvds3-sditf-vir1";
		rkcif_mipi_lvds3_sditf_vir2 = "/rkcif-mipi-lvds3-sditf-vir2";
		rkcif_mipi_lvds3_sditf_vir3 = "/rkcif-mipi-lvds3-sditf-vir3";
		rkisp_vir0 = "/rkisp-vir0";
		rkisp_vir1 = "/rkisp-vir1";
		rkisp_vir2 = "/rkisp-vir2";
		rkisp_vir3 = "/rkisp-vir3";
		rockchip_system_monitor = "/rockchip-system-monitor";
		thermal_zones = "/thermal-zones";
		soc_thermal = "/thermal-zones/soc-thermal";
		threshold = "/thermal-zones/soc-thermal/trips/trip-point-0";
		target = "/thermal-zones/soc-thermal/trips/trip-point-1";
		soc_crit = "/thermal-zones/soc-thermal/trips/soc-crit";
		vendor_storage = "/vendor-storage";
		scmi_shmem = "/scmi-shmem@10f000";
		usbdrd30 = "/usbdrd";
		usbdrd_dwc3 = "/usbdrd/usb@fe500000";
		dwc3_0_role_switch = "/usbdrd/usb@fe500000/port/endpoint@0";
		gic = "/interrupt-controller@fe901000";
		usb_host0_ehci = "/usb@fed00000";
		usb_host0_ohci = "/usb@fed40000";
		debug = "/debug@fed90000";
		qos_dma2ddr = "/qos@fee03800";
		shaping_dam2ddr = "/shaping@fee03888";
		qos_mcu = "/qos@fee10000";
		shaping_mcu = "/shaping@fee10088";
		qos_dft_apb = "/qos@fee10100";
		shaping_dft_apb = "/shaping@fee10188";
		qos_gmac = "/qos@fee10200";
		shaping_gmac = "/shaping@fee10288";
		qos_mac100 = "/qos@fee10300";
		shaping_mac100 = "/shaping@fee10388";
		qos_dcf = "/qos@fee10400";
		qos_cpu = "/qos@fee20000";
		shaping_cpu = "/shaping@fee20088";
		qos_daplite_apb = "/qos@fee20100";
		shaping_daplite_apb = "/shaping@fee20188";
		qos_gpu = "/qos@fee30000";
		shaping_gpu = "/shaping@fee30088";
		qos_npu = "/qos@fee40000";
		shaping_npu = "/shaping@fee40088";
		qos_rkvdec = "/qos@fee50000";
		shaping_rkvdec = "/shaping@fee50088";
		qos_vepu = "/qos@fee60000";
		shaping_vepu = "/shaping@fee60088";
		qos_isp = "/qos@fee70000";
		shaping_isp = "/shaping@fee70088";
		qos_vicap = "/qos@fee70100";
		shaping_vicap = "/shaping@fee70188";
		qos_vop = "/qos@fee80000";
		shaping_vop = "/shaping@fee80088";
		qos_jpeg = "/qos@fee90000";
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

## Analog-Sticks (ADC-Joystick)
### `play_joystick` (Zeile 6286-6354)
```dts
	play_joystick {
		compatible = "play_joystick";
		io-channels = <0xdd 0x02 0xdd 0x03 0xdd 0x05 0xdd 0x06 0xf1 0x01 0xf1 0x04 0xf1 0x00 0xf1 0x02 0xf1 0x03 0xf1 0x05 0xf1 0x06 0xf1 0x07>;
		io-channel-names = "button0\0button1\0button2\0button3\0l2-abs\0r2-abs\0left-key\0right-key\0down-key\0b-key\0x-key\0y-key";
		joysticks_numbers = <0x02>;
		l_x_swap;
		l_y_swap;
		axis-min-value-mv = <0xfa>;
		axis-max-value-mv = <0x60e>;
		axis-dead-zone-l = <0x316>;
		axis-dead-zone-h = <0x3f2>;
		axis-division-value = <0x3c>;
		keyup-threshold-microvolt = <0x1b7740>;
		poll-interval = <0x10>;
		debounce-interval = <0x64>;
		pinctrl-names = "default";
		pinctrl-0 = <0xf2 0xf3>;
		moto-gpio = <0x49 0x07 0x00>;
		moto-r-gpio = <0x49 0x08 0x00>;
		gpio-key-num = <0x0a>;
		key-gpios = <0xf4 0x17 0x01 0xf4 0x18 0x01 0xf4 0x1d 0x01 0xf4 0x1e 0x01 0xf4 0x1b 0x01 0xf4 0x1f 0x01 0xf4 0x1c 0x01 0x3d 0x15 0x01 0x3d 0x16 0x01>;
		key-gpios-map = <0x136 0x220 0x137 0x131 0x13a 0x13b 0x1d0 0x13d 0x13e>;
		l2-r2-min-value-mv = <0x32>;
		l2-r2-max-value-mv = <0x320>;
		l2-r2-division-value-mv = <0x4b>;
		l2_r2_abs;

		left-key {
			label = "left-key";
			adc-chan = <0x00>;
			linux,code = <0x222>;
			press-threshold-microvolt = <0x927c0>;
		};

		right-key {
			label = "right-key";
			adc-chan = <0x02>;
			linux,code = <0x223>;
			press-threshold-microvolt = <0x927c0>;
		};

		down-key {
			label = "down-key";
			adc-chan = <0x03>;
			linux,code = <0x221>;
			press-threshold-microvolt = <0x927c0>;
		};

		b-key {
			label = "b-key";
			adc-chan = <0x05>;
			linux,code = <0x130>;
			press-threshold-microvolt = <0x927c0>;
		};

		x-key {
			label = "x-key";
			adc-chan = <0x06>;
			linux,code = <0x133>;
			press-threshold-microvolt = <0x927c0>;
		};

		y-key {
			label = "y-key";
			adc-chan = <0x07>;
			linux,code = <0x134>;
			press-threshold-microvolt = <0x927c0>;
		};
	};
```

## Akku / Ladeschaltung / Fuel-Gauge
### `pinctrl_rk8xx` (Zeile 1561-1601)
```dts
			pinctrl_rk8xx {
				gpio-controller;
				#gpio-cells = <0x02>;
				phandle = <0x15c>;

				rk817_slppin_null {
					pins = "gpio_slp";
					function = "pin_fun0";
					phandle = <0x15d>;
				};

				rk817_slppin_slp {
					pins = "gpio_slp";
					function = "pin_fun1";
					phandle = <0x40>;
				};

				rk817_slppin_pwrdn {
					pins = "gpio_slp";
					function = "pin_fun2";
					phandle = <0x42>;
				};

				rk817_slppin_rst {
					pins = "gpio_slp";
					function = "pin_fun3";
					phandle = <0x43>;
				};

				rk817_ts_gpio1 {
					pins = "gpio_ts";
					function = "pin_fun1";
					phandle = <0x15e>;
				};

				rk817_pin_ts {
					pins = "gpio_ts";
					function = "pin_fun0";
					phandle = <0x15f>;
				};
			};
```

### `battery` (Zeile 1824-1846)
```dts
			battery {
				compatible = "rk817,battery";
				ocv_table = <0xdac 0xdc9 0xdf2 0xe15 0xe3c 0xe67 0xe9a 0xecd 0xeef 0xf07 0xf1f 0xf3f 0xf56 0xf75 0xf9f 0xfbb 0xfc4 0xfc9 0xfd6 0xffa 0x104f>;
				design_capacity = <0xb5a>;
				design_qmax = <0xc7d>;
				bat_res = <0x66>;
				sleep_enter_current = <0x12c>;
				sleep_exit_current = <0x12c>;
				sleep_filter_current = <0x64>;
				power_off_thresd = <0xdac>;
				zero_algorithm_vol = <0xf0a>;
				max_soc_offset = <0x3c>;
				monitor_sec = <0x05>;
				sample_res = <0x0a>;
				virtual_power = <0x00>;
				pinctrl-names = "default";
				pinctrl-0 = <0x4a>;
				charge_red_gpio = <0x49 0x01 0x00>;
				charge_green_gpio = <0x49 0x00 0x00>;
				moto_gpio = <0x49 0x07 0x00>;
				moto_r_gpio = <0x49 0x08 0x00>;
				phandle = <0x169>;
			};
```

### `charger` (Zeile 1848-1861)
```dts
			charger {
				compatible = "rk817,charger";
				min_input_voltage = <0x1194>;
				max_input_current = <0x5dc>;
				max_chrg_current = <0x5dc>;
				max_chrg_voltage = <0x10b8>;
				chrg_term_mode = <0x00>;
				chrg_finish_cur = <0x12c>;
				virtual_power = <0x00>;
				dc_det_adc = <0x00>;
				otg5v_suspend_enable = <0x01>;
				extcon = <0x4b>;
				gate_function_disable = <0x01>;
			};
```

### `__symbols__` (Zeile 6356-7054)
```dts
	__symbols__ {
		xin32k = "/clocks/xin32k";
		xin24m = "/clocks/xin24m";
		hclk_vepu = "/clocks/hclk_vepu@ff100324";
		aclk_vdpu = "/clocks/aclk_vdpu@ff100328";
		aclk_vi_isp = "/clocks/aclk_vi_isp@ff10032c";
		aclk_vo = "/clocks/aclk_vo@ff100334";
		aclk_vepu = "/clocks/aclk_vepu@ff100324";
		aclk_rga_jdec = "/clocks/aclk_rga_jdec@ff100338";
		mclkin_sai0 = "/clocks/mclkin-sai0";
		mclkin_sai1 = "/clocks/mclkin-sai1";
		mclkin_sai2 = "/clocks/mclkin-sai2";
		mclkout_sai0 = "/clocks/mclkout-sai0@ff040070";
		mclkout_sai1 = "/clocks/mclkout-sai1@ff040070";
		mclkout_sai2 = "/clocks/mclkout-sai2@ff040070";
		cpu0 = "/cpus/cpu@0";
		cpu1 = "/cpus/cpu@1";
		cpu2 = "/cpus/cpu@2";
		cpu3 = "/cpus/cpu@3";
		CPU_SLEEP = "/cpus/idle-states/cpu-sleep";
		cpu0_opp_table = "/cpu0-opp-table";
		cpu_opp_j_od_1416000000 = "/cpu0-opp-table/opp-j-od-1416000000";
		cpu_opp_j_od_1608000000 = "/cpu0-opp-table/opp-j-od-1608000000";
		cpu_opp_j_od_1800000000 = "/cpu0-opp-table/opp-j-od-1800000000";
		arm_pmu = "/arm-pmu";
		csi2_dphy0 = "/csi2-dphy0";
		csi2_dphy1 = "/csi2-dphy1";
		csi2_dphy2 = "/csi2-dphy2";
		csi2_dphy3 = "/csi2-dphy3";
		csi2_dphy4 = "/csi2-dphy4";
		csi2_dphy5 = "/csi2-dphy5";
		csu = "/csu";
		display_subsystem = "/display-subsystem";
		route_dsi = "/display-subsystem/route/route-dsi";
		route_lvds = "/display-subsystem/route/route-lvds";
		route_rgb = "/display-subsystem/route/route-rgb";
		dmc = "/dmc";
		dmc_opp_table = "/dmc-opp-table";
		scmi = "/firmware/scmi";
		scmi_clk = "/firmware/scmi/protocol@14";
		optee = "/firmware/optee";
		mpp_srv = "/mpp-srv";
		mipi0_csi2 = "/mipi0-csi2";
		mipi1_csi2 = "/mipi1-csi2";
		mipi2_csi2 = "/mipi2-csi2";
		mipi3_csi2 = "/mipi3-csi2";
		reserved_memory = "/reserved-memory";
		drm_logo = "/reserved-memory/drm-logo@00000000";
		vendor_storage_rm = "/reserved-memory/vendor-storage-rm@00000000";
		drm_cubic_lut = "/reserved-memory/drm-cubic-lut@00000000";
		ramoops = "/reserved-memory/ramoops@110000";
		rkcif_mipi_lvds = "/rkcif-mipi-lvds";
		rkcif_mipi_lvds_sditf = "/rkcif-mipi-lvds-sditf";
		rkcif_mipi_lvds_sditf_vir1 = "/rkcif-mipi-lvds-sditf-vir1";
		rkcif_mipi_lvds_sditf_vir2 = "/rkcif-mipi-lvds-sditf-vir2";
		rkcif_mipi_lvds_sditf_vir3 = "/rkcif-mipi-lvds-sditf-vir3";
		rkcif_mipi_lvds1 = "/rkcif-mipi-lvds1";
		rkcif_mipi_lvds1_sditf = "/rkcif-mipi-lvds1-sditf";
		rkcif_mipi_lvds1_sditf_vir1 = "/rkcif-mipi-lvds1-sditf-vir1";
		rkcif_mipi_lvds1_sditf_vir2 = "/rkcif-mipi-lvds1-sditf-vir2";
		rkcif_mipi_lvds1_sditf_vir3 = "/rkcif-mipi-lvds1-sditf-vir3";
		rkcif_mipi_lvds2 = "/rkcif-mipi-lvds2";
		rkcif_mipi_lvds2_sditf = "/rkcif-mipi-lvds2-sditf";
		rkcif_mipi_lvds2_sditf_vir1 = "/rkcif-mipi-lvds2-sditf-vir1";
		rkcif_mipi_lvds2_sditf_vir2 = "/rkcif-mipi-lvds2-sditf-vir2";
		rkcif_mipi_lvds2_sditf_vir3 = "/rkcif-mipi-lvds2-sditf-vir3";
		rkcif_mipi_lvds3 = "/rkcif-mipi-lvds3";
		rkcif_mipi_lvds3_sditf = "/rkcif-mipi-lvds3-sditf";
		rkcif_mipi_lvds3_sditf_vir1 = "/rkcif-mipi-lvds3-sditf-vir1";
		rkcif_mipi_lvds3_sditf_vir2 = "/rkcif-mipi-lvds3-sditf-vir2";
		rkcif_mipi_lvds3_sditf_vir3 = "/rkcif-mipi-lvds3-sditf-vir3";
		rkisp_vir0 = "/rkisp-vir0";
		rkisp_vir1 = "/rkisp-vir1";
		rkisp_vir2 = "/rkisp-vir2";
		rkisp_vir3 = "/rkisp-vir3";
		rockchip_system_monitor = "/rockchip-system-monitor";
		thermal_zones = "/thermal-zones";
		soc_thermal = "/thermal-zones/soc-thermal";
		threshold = "/thermal-zones/soc-thermal/trips/trip-point-0";
		target = "/thermal-zones/soc-thermal/trips/trip-point-1";
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

## WiFi / Bluetooth
### `mmc@ff870000` (Zeile 3266-3286)
```dts
	mmc@ff870000 {
		compatible = "rockchip,rk3562-dwcmshc\0rockchip,rk3528-dwcmshc";
		reg = <0x00 0xff870000 0x00 0x10000>;
		interrupts = <0x00 0x3f 0x04>;
		assigned-clocks = <0x02 0x9a 0x02 0x99>;
		assigned-clock-rates = <0xbebc200 0xbebc200>;
		clocks = <0x02 0x99 0x02 0x97 0x02 0x98 0x02 0x9a 0x02 0x9b>;
		clock-names = "core\0bus\0axi\0block\0timer";
		resets = <0x02 0xc004a 0x02 0xc0048 0x02 0xc0049 0x02 0xc004b 0x02 0xc004c>;
		reset-names = "core\0bus\0axi\0block\0timer";
		max-frequency = <0xbebc200>;
		status = "okay";
		bus-width = <0x08>;
		no-sdio;
		no-sd;
		non-removable;
		mmc-hs400-1_8v;
		mmc-hs400-enhanced-strobe;
		full-pwr-cycle-in-suspend;
		phandle = <0x198>;
	};
```

### `mmc@ff880000` (Zeile 3288-3311)
```dts
	mmc@ff880000 {
		compatible = "rockchip,rk3562-dw-mshc\0rockchip,rk3288-dw-mshc";
		reg = <0x00 0xff880000 0x00 0x10000>;
		interrupts = <0x00 0x38 0x04>;
		max-frequency = <0xbebc200>;
		clocks = <0x02 0x8f 0x02 0x90 0x02 0x93 0x02 0x94>;
		clock-names = "biu\0ciu\0ciu-drive\0ciu-sample";
		resets = <0x02 0xc0040>;
		reset-names = "reset";
		fifo-depth = <0x100>;
		status = "okay";
		no-sdio;
		no-mmc;
		bus-width = <0x04>;
		cap-mmc-highspeed;
		cap-sd-highspeed;
		disable-wp;
		sd-uhs-sdr104;
		vmmc-supply = <0xb1>;
		vqmmc-supply = <0xb2>;
		pinctrl-names = "default";
		pinctrl-0 = <0xb3 0xb4 0xb5 0xb6>;
		phandle = <0x199>;
	};
```

### `mmc@ff890000` (Zeile 3313-3339)
```dts
	mmc@ff890000 {
		compatible = "rockchip,rk3562-dw-mshc\0rockchip,rk3288-dw-mshc";
		reg = <0x00 0xff890000 0x00 0x10000>;
		interrupts = <0x00 0x39 0x04>;
		max-frequency = <0xbebc200>;
		clocks = <0x02 0x91 0x02 0x92 0x02 0x95 0x02 0x96>;
		clock-names = "biu\0ciu\0ciu-drive\0ciu-sample";
		resets = <0x02 0xc0042>;
		reset-names = "reset";
		fifo-depth = <0x100>;
		status = "okay";
		no-sd;
		no-mmc;
		supports-sdio;
		bus-width = <0x04>;
		disable-wp;
		cap-sd-highspeed;
		cap-sdio-irq;
		keep-power-in-suspend;
		supports-aic8800DL;
		mmc-pwrseq = <0xb7>;
		broken-cd;
		pinctrl-names = "default";
		pinctrl-0 = <0xb8 0xb9 0xba>;
		sd-uhs-sdr104;
		phandle = <0x19a>;
	};
```

### `wifi-enable-h` (Zeile 5918-5921)
```dts
			wifi-enable-h {
				rockchip,pins = <0x00 0x0b 0x00 0xd4>;
				phandle = <0xe9>;
			};
```

### `wifi-host-wake-irq` (Zeile 5950-5953)
```dts
			wifi-host-wake-irq {
				rockchip,pins = <0x00 0x0c 0x00 0xdc>;
				phandle = <0xee>;
			};
```

### `wifi-poweren-gpio` (Zeile 5955-5958)
```dts
			wifi-poweren-gpio {
				rockchip,pins = <0x00 0x06 0x00 0xd7>;
				phandle = <0xef>;
			};
```

### `sdio-pwrseq` (Zeile 6143-6152)
```dts
	sdio-pwrseq {
		compatible = "mmc-pwrseq-simple";
		clocks = <0xe8 0x01>;
		clock-names = "ext_clock";
		pinctrl-names = "default";
		pinctrl-0 = <0xe9>;
		post-power-on-delay-ms = <0xc8>;
		reset-gpios = <0x3d 0x0b 0x01>;
		phandle = <0xb7>;
	};
```

### `wireless-wlan` (Zeile 6228-6238)
```dts
	wireless-wlan {
		compatible = "wlan-platdata";
		rockchip,grf = <0x0e>;
		wifi_chip_type = "aic8800DL";
		pinctrl-names = "default";
		pinctrl-0 = <0xee 0xef>;
		WIFI,host_wake_irq = <0x3d 0x0c 0x00>;
		WIFI,poweren_gpio = <0x3d 0x06 0x01>;
		sdio_vref = <0x708>;
		status = "okay";
	};
```

### `wireless-bluetooth` (Zeile 6240-6243)
```dts
	wireless-bluetooth {
		compatible = "bluetooth-platdata";
		status = "disabled";
	};
```

### `__symbols__` (Zeile 6356-7054)
```dts
	__symbols__ {
		xin32k = "/clocks/xin32k";
		xin24m = "/clocks/xin24m";
		hclk_vepu = "/clocks/hclk_vepu@ff100324";
		aclk_vdpu = "/clocks/aclk_vdpu@ff100328";
		aclk_vi_isp = "/clocks/aclk_vi_isp@ff10032c";
		aclk_vo = "/clocks/aclk_vo@ff100334";
		aclk_vepu = "/clocks/aclk_vepu@ff100324";
		aclk_rga_jdec = "/clocks/aclk_rga_jdec@ff100338";
		mclkin_sai0 = "/clocks/mclkin-sai0";
		mclkin_sai1 = "/clocks/mclkin-sai1";
		mclkin_sai2 = "/clocks/mclkin-sai2";
		mclkout_sai0 = "/clocks/mclkout-sai0@ff040070";
		mclkout_sai1 = "/clocks/mclkout-sai1@ff040070";
		mclkout_sai2 = "/clocks/mclkout-sai2@ff040070";
		cpu0 = "/cpus/cpu@0";
		cpu1 = "/cpus/cpu@1";
		cpu2 = "/cpus/cpu@2";
		cpu3 = "/cpus/cpu@3";
		CPU_SLEEP = "/cpus/idle-states/cpu-sleep";
		cpu0_opp_table = "/cpu0-opp-table";
		cpu_opp_j_od_1416000000 = "/cpu0-opp-table/opp-j-od-1416000000";
		cpu_opp_j_od_1608000000 = "/cpu0-opp-table/opp-j-od-1608000000";
		cpu_opp_j_od_1800000000 = "/cpu0-opp-table/opp-j-od-1800000000";
		arm_pmu = "/arm-pmu";
		csi2_dphy0 = "/csi2-dphy0";
		csi2_dphy1 = "/csi2-dphy1";
		csi2_dphy2 = "/csi2-dphy2";
		csi2_dphy3 = "/csi2-dphy3";
		csi2_dphy4 = "/csi2-dphy4";
		csi2_dphy5 = "/csi2-dphy5";
		csu = "/csu";
		display_subsystem = "/display-subsystem";
		route_dsi = "/display-subsystem/route/route-dsi";
		route_lvds = "/display-subsystem/route/route-lvds";
		route_rgb = "/display-subsystem/route/route-rgb";
		dmc = "/dmc";
		dmc_opp_table = "/dmc-opp-table";
		scmi = "/firmware/scmi";
		scmi_clk = "/firmware/scmi/protocol@14";
		optee = "/firmware/optee";
		mpp_srv = "/mpp-srv";
		mipi0_csi2 = "/mipi0-csi2";
		mipi1_csi2 = "/mipi1-csi2";
		mipi2_csi2 = "/mipi2-csi2";
		mipi3_csi2 = "/mipi3-csi2";
		reserved_memory = "/reserved-memory";
		drm_logo = "/reserved-memory/drm-logo@00000000";
		vendor_storage_rm = "/reserved-memory/vendor-storage-rm@00000000";
		drm_cubic_lut = "/reserved-memory/drm-cubic-lut@00000000";
		ramoops = "/reserved-memory/ramoops@110000";
		rkcif_mipi_lvds = "/rkcif-mipi-lvds";
		rkcif_mipi_lvds_sditf = "/rkcif-mipi-lvds-sditf";
		rkcif_mipi_lvds_sditf_vir1 = "/rkcif-mipi-lvds-sditf-vir1";
		rkcif_mipi_lvds_sditf_vir2 = "/rkcif-mipi-lvds-sditf-vir2";
		rkcif_mipi_lvds_sditf_vir3 = "/rkcif-mipi-lvds-sditf-vir3";
		rkcif_mipi_lvds1 = "/rkcif-mipi-lvds1";
		rkcif_mipi_lvds1_sditf = "/rkcif-mipi-lvds1-sditf";
		rkcif_mipi_lvds1_sditf_vir1 = "/rkcif-mipi-lvds1-sditf-vir1";
		rkcif_mipi_lvds1_sditf_vir2 = "/rkcif-mipi-lvds1-sditf-vir2";
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

## Audio (Codec / I2S)
### `LDO_REG4` (Zeile 1706-1717)
```dts
				LDO_REG4 {
					regulator-always-on;
					regulator-boot-on;
					regulator-min-microvolt = <0x2dc6c0>;
					regulator-max-microvolt = <0x2dc6c0>;
					regulator-name = "vccio_acodec";
					phandle = <0x165>;

					regulator-state-mem {
						regulator-off-in-suspend;
					};
				};
```

### `codec` (Zeile 1804-1822)
```dts
			codec {
				#sound-dai-cells = <0x00>;
				compatible = "rockchip,rk817-codec";
				clocks = <0x46>;
				clock-names = "mclk";
				assigned-clocks = <0x46>;
				assigned-clock-rates = <0xbb8000>;
				pinctrl-names = "default";
				pinctrl-0 = <0x47 0x48>;
				hp-volume = <0x3c>;
				spk-volume = <0x03>;
				mic-in-differential;
				status = "okay";
				use-ext-amplifier;
				hp2extamplifier;
				hp-mute-delay-ms = <0x64>;
				hp-ctl-gpios = <0x49 0x13 0x00>;
				phandle = <0xe4>;
			};
```

### `rkvdec@ff340100` (Zeile 2374-2395)
```dts
	rkvdec@ff340100 {
		compatible = "rockchip,rkv-decoder-rk3562\0rockchip,rkv-decoder-v2";
		reg = <0x00 0xff340100 0x00 0x400 0x00 0xff340000 0x00 0x100>;
		reg-names = "regs\0link";
		interrupts = <0x00 0x7a 0x04>;
		interrupt-names = "irq_dec";
		clocks = <0x02 0x14a 0x02 0x14b 0x02 0x148>;
		clock-names = "aclk_vcodec\0hclk_vcodec\0clk_hevc_cabac";
		rockchip,normal-rates = <0xbcd3d80 0x00 0x179a7b00>;
		assigned-clocks = <0x02 0x14a 0x02 0x148>;
		assigned-clock-rates = <0xbcd3d80 0x179a7b00>;
		resets = <0x02 0xa7 0x02 0xa8 0x02 0xa2>;
		reset-names = "video_a\0video_h\0video_hevc_cabac";
		power-domains = <0x35 0x0b>;
		iommus = <0x77>;
		rockchip,srv = <0x78>;
		rockchip,taskqueue-node = <0x00>;
		rockchip,resetgroup-node = <0x00>;
		rockchip,task-capacity = <0x10>;
		status = "okay";
		phandle = <0x178>;
	};
```

### `rkvenc@ff360000` (Zeile 2411-2430)
```dts
	rkvenc@ff360000 {
		compatible = "rockchip,rkv-encoder-rk3562\0rockchip,rkv-encoder-v2";
		reg = <0x00 0xff360000 0x00 0x6000>;
		interrupts = <0x00 0x88 0x04>;
		interrupt-names = "irq_rkvenc";
		clocks = <0x02 0x14f 0x02 0x150 0x02 0x14c>;
		clock-names = "aclk_vcodec\0hclk_vcodec\0clk_core";
		rockchip,normal-rates = <0x11b3dc40 0x00 0x11b3dc40>;
		resets = <0x02 0x95 0x02 0x96 0x02 0x90>;
		reset-names = "video_a\0video_h\0video_core";
		assigned-clocks = <0x02 0x14f 0x02 0x14c>;
		assigned-clock-rates = <0x11b3dc40 0x11b3dc40>;
		power-domains = <0x35 0x0a>;
		iommus = <0x79>;
		rockchip,srv = <0x78>;
		rockchip,taskqueue-node = <0x01>;
		rockchip,resetgroup-node = <0x01>;
		status = "okay";
		phandle = <0x179>;
	};
```

### `jpegd@ff450000` (Zeile 2675-2691)
```dts
	jpegd@ff450000 {
		compatible = "rockchip,rkv-jpeg-decoder-v1";
		reg = <0x00 0xff450000 0x00 0x400>;
		interrupts = <0x00 0x79 0x04>;
		clocks = <0x02 0x145 0x02 0x146>;
		clock-names = "aclk_vcodec\0hclk_vcodec";
		rockchip,disable-auto-freq;
		resets = <0x02 0xe9 0x02 0xea>;
		reset-names = "video_a\0video_h";
		power-domains = <0x35 0x0e>;
		iommus = <0x82>;
		rockchip,srv = <0x78>;
		rockchip,taskqueue-node = <0x02>;
		rockchip,resetgroup-node = <0x02>;
		status = "okay";
		phandle = <0x17d>;
	};
```

### `sai@ff800000` (Zeile 3146-3164)
```dts
	sai@ff800000 {
		compatible = "rockchip,rk3562-sai\0rockchip,sai-v1";
		reg = <0x00 0xff800000 0x00 0x1000>;
		interrupts = <0x00 0x4e 0x04>;
		clocks = <0x02 0x78 0x02 0x74>;
		clock-names = "mclk\0hclk";
		assigned-clocks = <0x02 0x75>;
		assigned-clock-parents = <0x02 0x04>;
		dmas = <0x4c 0x13 0x4c 0x12>;
		dma-names = "tx\0rx";
		resets = <0x02 0xc0023 0x02 0xc0020>;
		reset-names = "m\0h";
		pinctrl-names = "default";
		pinctrl-0 = <0x9d 0x9e 0x9f 0xa0>;
		#sound-dai-cells = <0x00>;
		sound-name-prefix = "SAI0";
		status = "okay";
		phandle = <0xe3>;
	};
```

### `sai@ff810000` (Zeile 3166-3184)
```dts
	sai@ff810000 {
		compatible = "rockchip,rk3562-sai\0rockchip,sai-v1";
		reg = <0x00 0xff810000 0x00 0x1000>;
		interrupts = <0x00 0x4f 0x04>;
		clocks = <0x02 0x7e 0x02 0x7a>;
		clock-names = "mclk\0hclk";
		assigned-clocks = <0x02 0x7b>;
		assigned-clock-parents = <0x02 0x04>;
		dmas = <0x4c 0x15 0x4c 0x14>;
		dma-names = "tx\0rx";
		resets = <0x02 0xc0028 0x02 0xc0025>;
		reset-names = "m\0h";
		pinctrl-names = "default";
		pinctrl-0 = <0xa1 0xa2 0xa3 0xa4>;
		#sound-dai-cells = <0x00>;
		sound-name-prefix = "SAI1";
		status = "okay";
		phandle = <0xe6>;
	};
```

### `sai@ff820000` (Zeile 3186-3204)
```dts
	sai@ff820000 {
		compatible = "rockchip,rk3562-sai\0rockchip,sai-v1";
		reg = <0x00 0xff820000 0x00 0x1000>;
		interrupts = <0x00 0x50 0x04>;
		clocks = <0x02 0x84 0x02 0x80>;
		clock-names = "mclk\0hclk";
		assigned-clocks = <0x02 0x81>;
		assigned-clock-parents = <0x02 0x04>;
		dmas = <0x4c 0x17 0x4c 0x16>;
		dma-names = "tx\0rx";
		resets = <0x02 0xc002d 0x02 0xc002a>;
		reset-names = "m\0h";
		pinctrl-names = "default";
		pinctrl-0 = <0xa5 0xa6 0xa7 0xa8>;
		#sound-dai-cells = <0x00>;
		sound-name-prefix = "SAI2";
		status = "disabled";
		phandle = <0x195>;
	};
```

### `pdm@ff830000` (Zeile 3206-3220)
```dts
	pdm@ff830000 {
		compatible = "rockchip,rk3562-pdm\0rockchip,rv1126-pdm";
		reg = <0x00 0xff830000 0x00 0x1000>;
		clocks = <0x02 0x89 0x02 0x88>;
		clock-names = "pdm_clk\0pdm_hclk";
		assigned-clocks = <0x02 0x89>;
		assigned-clock-parents = <0x02 0x04>;
		dmas = <0x4c 0x1f>;
		dma-names = "rx";
		pinctrl-names = "default";
		pinctrl-0 = <0xa9 0xaa 0xab 0xac 0xad 0xae>;
		#sound-dai-cells = <0x00>;
		status = "disabled";
		phandle = <0xdf>;
	};
```

### `spdif@ff840000` (Zeile 3222-3237)
```dts
	spdif@ff840000 {
		compatible = "rockchip,rk3562-spdif\0rockchip,rk3568-spdif";
		reg = <0x00 0xff840000 0x00 0x1000>;
		interrupts = <0x00 0x7f 0x04>;
		dmas = <0x4c 0x1e>;
		dma-names = "tx";
		clock-names = "mclk\0hclk";
		clocks = <0x02 0x8e 0x02 0x8a>;
		assigned-clocks = <0x02 0x8b>;
		assigned-clock-parents = <0x02 0x04>;
		#sound-dai-cells = <0x00>;
		pinctrl-names = "default";
		pinctrl-0 = <0xaf>;
		status = "disabled";
		phandle = <0xe1>;
	};
```

### `dsm@ff850000` (Zeile 3239-3252)
```dts
	dsm@ff850000 {
		compatible = "rockchip,rk3562-dsm";
		reg = <0x00 0xff850000 0x00 0x1000>;
		clocks = <0x02 0x87 0x02 0x86>;
		clock-names = "dac\0pclk";
		resets = <0x02 0xc0032>;
		reset-names = "reset";
		rockchip,grf = <0x9b>;
		pinctrl-names = "default";
		pinctrl-0 = <0xb0>;
		#sound-dai-cells = <0x00>;
		status = "disabled";
		phandle = <0x196>;
	};
```

### `rk628@50` (Zeile 3615-3641)
```dts
		rk628@50 {
			status = "okay";
			compatible = "rockchip,rk628";
			reg = <0x50>;
			#sound-dai-cells = <0x00>;
			interrupt-parent = <0x49>;
			interrupts = <0x12 0x04>;
			enable-gpios = <0x49 0x10 0x00>;
			reset-gpios = <0x49 0x11 0x01>;
			pinctrl-names = "default";
			pinctrl-0 = <0xc2 0xc3>;
			assigned-clocks = <0x02 0x132>;
			assigned-clock-rates = <0x16e3600>;
			clocks = <0x02 0x132>;
			clock-names = "soc_24M";
			rk628-rgb-in;
			rk628-hdmi-out;
			phandle = <0xe7>;

			port {

				endpoint {
					remote-endpoint = <0xc4>;
					phandle = <0x3b>;
				};
			};
		};
```

### `i2s0m0-lrck` (Zeile 4642-4645)
```dts
			i2s0m0-lrck {
				rockchip,pins = <0x03 0x04 0x01 0xd6>;
				phandle = <0x9d>;
			};
```

### `i2s0m0-mclk` (Zeile 4647-4650)
```dts
			i2s0m0-mclk {
				rockchip,pins = <0x03 0x02 0x01 0xd6>;
				phandle = <0x47>;
			};
```

### `i2s0m0-sclk` (Zeile 4652-4655)
```dts
			i2s0m0-sclk {
				rockchip,pins = <0x03 0x03 0x01 0xd6>;
				phandle = <0x9e>;
			};
```

### `i2s0m0-sdi0` (Zeile 4657-4660)
```dts
			i2s0m0-sdi0 {
				rockchip,pins = <0x03 0x09 0x01 0xd4>;
				phandle = <0x9f>;
			};
```

### `i2s0m0-sdi1` (Zeile 4662-4665)
```dts
			i2s0m0-sdi1 {
				rockchip,pins = <0x03 0x08 0x02 0xd4>;
				phandle = <0x20c>;
			};
```

### `i2s0m0-sdi2` (Zeile 4667-4670)
```dts
			i2s0m0-sdi2 {
				rockchip,pins = <0x03 0x07 0x02 0xd4>;
				phandle = <0x20d>;
			};
```

### `i2s0m0-sdi3` (Zeile 4672-4675)
```dts
			i2s0m0-sdi3 {
				rockchip,pins = <0x03 0x06 0x02 0xd4>;
				phandle = <0x20e>;
			};
```

### `i2s0m0-sdo0` (Zeile 4677-4680)
```dts
			i2s0m0-sdo0 {
				rockchip,pins = <0x03 0x05 0x01 0xd4>;
				phandle = <0xa0>;
			};
```

### `i2s0m0-sdo1` (Zeile 4682-4685)
```dts
			i2s0m0-sdo1 {
				rockchip,pins = <0x03 0x06 0x01 0xd4>;
				phandle = <0x20f>;
			};
```

### `i2s0m0-sdo2` (Zeile 4687-4690)
```dts
			i2s0m0-sdo2 {
				rockchip,pins = <0x03 0x07 0x01 0xd4>;
				phandle = <0x210>;
			};
```

### `i2s0m0-sdo3` (Zeile 4692-4695)
```dts
			i2s0m0-sdo3 {
				rockchip,pins = <0x03 0x08 0x01 0xd4>;
				phandle = <0x211>;
			};
```

### `i2s0m1-lrck` (Zeile 4697-4700)
```dts
			i2s0m1-lrck {
				rockchip,pins = <0x01 0x14 0x03 0xd6>;
				phandle = <0x212>;
			};
```

### `i2s0m1-mclk` (Zeile 4702-4705)
```dts
			i2s0m1-mclk {
				rockchip,pins = <0x01 0x16 0x03 0xd6>;
				phandle = <0x213>;
			};
```

### `i2s0m1-sclk` (Zeile 4707-4710)
```dts
			i2s0m1-sclk {
				rockchip,pins = <0x01 0x15 0x03 0xd6>;
				phandle = <0x214>;
			};
```

### `i2s0m1-sdi0` (Zeile 4712-4715)
```dts
			i2s0m1-sdi0 {
				rockchip,pins = <0x01 0x11 0x03 0xd4>;
				phandle = <0x215>;
			};
```

### `i2s0m1-sdi1` (Zeile 4717-4720)
```dts
			i2s0m1-sdi1 {
				rockchip,pins = <0x01 0x12 0x03 0xd4>;
				phandle = <0x216>;
			};
```

### `i2s0m1-sdi2` (Zeile 4722-4725)
```dts
			i2s0m1-sdi2 {
				rockchip,pins = <0x01 0x1b 0x03 0xd4>;
				phandle = <0x217>;
			};
```

### `i2s0m1-sdi3` (Zeile 4727-4730)
```dts
			i2s0m1-sdi3 {
				rockchip,pins = <0x01 0x1c 0x03 0xd4>;
				phandle = <0x218>;
			};
```

### `i2s0m1-sdo0` (Zeile 4732-4735)
```dts
			i2s0m1-sdo0 {
				rockchip,pins = <0x01 0x13 0x03 0xd4>;
				phandle = <0x219>;
			};
```

### `i2s0m1-sdo1` (Zeile 4737-4740)
```dts
			i2s0m1-sdo1 {
				rockchip,pins = <0x01 0x19 0x03 0xd4>;
				phandle = <0x21a>;
			};
```

### `i2s0m1-sdo2` (Zeile 4742-4745)
```dts
			i2s0m1-sdo2 {
				rockchip,pins = <0x01 0x1a 0x03 0xd4>;
				phandle = <0x21b>;
			};
```

### `i2s0m1-sdo3` (Zeile 4747-4750)
```dts
			i2s0m1-sdo3 {
				rockchip,pins = <0x02 0x01 0x05 0xd4>;
				phandle = <0x21c>;
			};
```

### `i2s1m0-lrck` (Zeile 4755-4758)
```dts
			i2s1m0-lrck {
				rockchip,pins = <0x03 0x16 0x02 0xd6>;
				phandle = <0x21d>;
			};
```

### `i2s1m0-mclk` (Zeile 4760-4763)
```dts
			i2s1m0-mclk {
				rockchip,pins = <0x03 0x14 0x02 0xd6>;
				phandle = <0x21e>;
			};
```

### `i2s1m0-sclk` (Zeile 4765-4768)
```dts
			i2s1m0-sclk {
				rockchip,pins = <0x03 0x15 0x02 0xd6>;
				phandle = <0x21f>;
			};
```

### `i2s1m0-sdi0` (Zeile 4770-4773)
```dts
			i2s1m0-sdi0 {
				rockchip,pins = <0x03 0x18 0x02 0xd4>;
				phandle = <0x220>;
			};
```

### `i2s1m0-sdi1` (Zeile 4775-4778)
```dts
			i2s1m0-sdi1 {
				rockchip,pins = <0x03 0x19 0x02 0xd4>;
				phandle = <0x221>;
			};
```

### `i2s1m0-sdi2` (Zeile 4780-4783)
```dts
			i2s1m0-sdi2 {
				rockchip,pins = <0x03 0x1a 0x02 0xd4>;
				phandle = <0x222>;
			};
```

### `i2s1m0-sdi3` (Zeile 4785-4788)
```dts
			i2s1m0-sdi3 {
				rockchip,pins = <0x03 0x1b 0x02 0xd4>;
				phandle = <0x223>;
			};
```

### `i2s1m0-sdo0` (Zeile 4790-4793)
```dts
			i2s1m0-sdo0 {
				rockchip,pins = <0x03 0x17 0x02 0xd4>;
				phandle = <0x224>;
			};
```

### `i2s1m0-sdo1` (Zeile 4795-4798)
```dts
			i2s1m0-sdo1 {
				rockchip,pins = <0x04 0x0c 0x02 0xd4>;
				phandle = <0x225>;
			};
```

### `i2s1m0-sdo2` (Zeile 4800-4803)
```dts
			i2s1m0-sdo2 {
				rockchip,pins = <0x04 0x0d 0x02 0xd4>;
				phandle = <0x226>;
			};
```

### `i2s1m0-sdo3` (Zeile 4805-4808)
```dts
			i2s1m0-sdo3 {
				rockchip,pins = <0x04 0x0e 0x02 0xd4>;
				phandle = <0x227>;
			};
```

### `i2s1m1-lrck` (Zeile 4810-4813)
```dts
			i2s1m1-lrck {
				rockchip,pins = <0x03 0x0c 0x01 0xd6>;
				phandle = <0xa3>;
			};
```

### `i2s1m1-mclk` (Zeile 4815-4818)
```dts
			i2s1m1-mclk {
				rockchip,pins = <0x03 0x0a 0x01 0xd6>;
				phandle = <0xa1>;
			};
```

### `i2s1m1-sclk` (Zeile 4820-4823)
```dts
			i2s1m1-sclk {
				rockchip,pins = <0x03 0x0b 0x01 0xd6>;
				phandle = <0xa2>;
			};
```

### `i2s1m1-sdi0` (Zeile 4825-4828)
```dts
			i2s1m1-sdi0 {
				rockchip,pins = <0x03 0x11 0x01 0xd4>;
				phandle = <0x228>;
			};
```

### `i2s1m1-sdi1` (Zeile 4830-4833)
```dts
			i2s1m1-sdi1 {
				rockchip,pins = <0x03 0x10 0x02 0xd4>;
				phandle = <0x229>;
			};
```

### `i2s1m1-sdi2` (Zeile 4835-4838)
```dts
			i2s1m1-sdi2 {
				rockchip,pins = <0x03 0x0f 0x02 0xd4>;
				phandle = <0x22a>;
			};
```

### `i2s1m1-sdi3` (Zeile 4840-4843)
```dts
			i2s1m1-sdi3 {
				rockchip,pins = <0x03 0x0e 0x02 0xd4>;
				phandle = <0x22b>;
			};
```

### `i2s1m1-sdo0` (Zeile 4845-4848)
```dts
			i2s1m1-sdo0 {
				rockchip,pins = <0x03 0x0d 0x01 0xd4>;
				phandle = <0xa4>;
			};
```

### `i2s1m1-sdo1` (Zeile 4850-4853)
```dts
			i2s1m1-sdo1 {
				rockchip,pins = <0x03 0x0e 0x01 0xd4>;
				phandle = <0x22c>;
			};
```

### `i2s1m1-sdo2` (Zeile 4855-4858)
```dts
			i2s1m1-sdo2 {
				rockchip,pins = <0x03 0x0f 0x01 0xd4>;
				phandle = <0x22d>;
			};
```

### `i2s1m1-sdo3` (Zeile 4860-4863)
```dts
			i2s1m1-sdo3 {
				rockchip,pins = <0x03 0x10 0x01 0xd4>;
				phandle = <0x22e>;
			};
```

### `i2s2m0-lrck` (Zeile 4868-4871)
```dts
			i2s2m0-lrck {
				rockchip,pins = <0x01 0x1e 0x01 0xd6>;
				phandle = <0xa5>;
			};
```

### `i2s2m0-mclk` (Zeile 4873-4876)
```dts
			i2s2m0-mclk {
				rockchip,pins = <0x02 0x01 0x01 0xd6>;
				phandle = <0x22f>;
			};
```

### `i2s2m0-sclk` (Zeile 4878-4881)
```dts
			i2s2m0-sclk {
				rockchip,pins = <0x01 0x1d 0x01 0xd6>;
				phandle = <0xa6>;
			};
```

### `i2s2m0-sdi` (Zeile 4883-4886)
```dts
			i2s2m0-sdi {
				rockchip,pins = <0x02 0x00 0x01 0xd4>;
				phandle = <0xa7>;
			};
```

### `i2s2m0-sdo` (Zeile 4888-4891)
```dts
			i2s2m0-sdo {
				rockchip,pins = <0x01 0x1f 0x01 0xd4>;
				phandle = <0xa8>;
			};
```

### `i2s2m1-lrck` (Zeile 4893-4896)
```dts
			i2s2m1-lrck {
				rockchip,pins = <0x04 0x01 0x03 0xd6>;
				phandle = <0x230>;
			};
```

### `i2s2m1-mclk` (Zeile 4898-4901)
```dts
			i2s2m1-mclk {
				rockchip,pins = <0x03 0x1e 0x03 0xd6>;
				phandle = <0x231>;
			};
```

### `i2s2m1-sclk` (Zeile 4903-4906)
```dts
			i2s2m1-sclk {
				rockchip,pins = <0x04 0x09 0x04 0xd6>;
				phandle = <0x232>;
			};
```

### `i2s2m1-sdi` (Zeile 4908-4911)
```dts
			i2s2m1-sdi {
				rockchip,pins = <0x03 0x1c 0x04 0xd4>;
				phandle = <0x233>;
			};
```

### `i2s2m1-sdo` (Zeile 4913-4916)
```dts
			i2s2m1-sdo {
				rockchip,pins = <0x03 0x1d 0x04 0xd4>;
				phandle = <0x234>;
			};
```

### `dummy-codec` (Zeile 6042-6047)
```dts
	dummy-codec {
		status = "okay";
		compatible = "rockchip,dummy-codec";
		#sound-dai-cells = <0x00>;
		phandle = <0xe0>;
	};
```

### `simple-audio-card,cpu` (Zeile 6055-6057)
```dts
		simple-audio-card,cpu {
			sound-dai = <0xdf>;
		};
```

### `simple-audio-card,codec` (Zeile 6059-6061)
```dts
		simple-audio-card,codec {
			sound-dai = <0xe0>;
		};
```

### `spdif-out` (Zeile 6064-6069)
```dts
	spdif-out {
		status = "disabled";
		compatible = "linux,spdif-dit";
		#sound-dai-cells = <0x00>;
		phandle = <0xe2>;
	};
```

### `simple-audio-card,cpu` (Zeile 6078-6080)
```dts
		simple-audio-card,cpu {
			sound-dai = <0xe1>;
		};
```

### `simple-audio-card,codec` (Zeile 6082-6084)
```dts
		simple-audio-card,codec {
			sound-dai = <0xe2>;
		};
```

### `rk817-sound` (Zeile 6102-6124)
```dts
	rk817-sound {
		status = "okay";
		compatible = "rockchip,multicodecs-card";
		rockchip,card-name = "rockchip-rk817";
		hp-det-gpio = <0x3d 0x07 0x00>;
		io-channels = <0xdd 0x04>;
		io-channel-names = "adc-detect";
		keyup-threshold-microvolt = <0x1b7740>;
		poll-interval = <0x64>;
		rockchip,format = "i2s";
		rockchip,mclk-fs = <0x100>;
		rockchip,cpu = <0xe3>;
		rockchip,codec = <0xe4>;
		pinctrl-names = "default";
		pinctrl-0 = <0xe5>;
		phandle = <0x2b4>;

		play-pause-key {
			label = "playpause";
			linux,code = <0xa4>;
			press-threshold-microvolt = <0x7d0>;
		};
	};
```

### `simple-audio-card,cpu` (Zeile 6134-6136)
```dts
		simple-audio-card,cpu {
			sound-dai = <0xe6>;
		};
```

### `simple-audio-card,codec` (Zeile 6138-6140)
```dts
		simple-audio-card,codec {
			sound-dai = <0xe7>;
		};
```

### `__symbols__` (Zeile 6356-7054)
```dts
	__symbols__ {
		xin32k = "/clocks/xin32k";
		xin24m = "/clocks/xin24m";
		hclk_vepu = "/clocks/hclk_vepu@ff100324";
		aclk_vdpu = "/clocks/aclk_vdpu@ff100328";
		aclk_vi_isp = "/clocks/aclk_vi_isp@ff10032c";
		aclk_vo = "/clocks/aclk_vo@ff100334";
		aclk_vepu = "/clocks/aclk_vepu@ff100324";
		aclk_rga_jdec = "/clocks/aclk_rga_jdec@ff100338";
		mclkin_sai0 = "/clocks/mclkin-sai0";
		mclkin_sai1 = "/clocks/mclkin-sai1";
		mclkin_sai2 = "/clocks/mclkin-sai2";
		mclkout_sai0 = "/clocks/mclkout-sai0@ff040070";
		mclkout_sai1 = "/clocks/mclkout-sai1@ff040070";
		mclkout_sai2 = "/clocks/mclkout-sai2@ff040070";
		cpu0 = "/cpus/cpu@0";
		cpu1 = "/cpus/cpu@1";
		cpu2 = "/cpus/cpu@2";
		cpu3 = "/cpus/cpu@3";
		CPU_SLEEP = "/cpus/idle-states/cpu-sleep";
		cpu0_opp_table = "/cpu0-opp-table";
		cpu_opp_j_od_1416000000 = "/cpu0-opp-table/opp-j-od-1416000000";
		cpu_opp_j_od_1608000000 = "/cpu0-opp-table/opp-j-od-1608000000";
		cpu_opp_j_od_1800000000 = "/cpu0-opp-table/opp-j-od-1800000000";
		arm_pmu = "/arm-pmu";
		csi2_dphy0 = "/csi2-dphy0";
		csi2_dphy1 = "/csi2-dphy1";
		csi2_dphy2 = "/csi2-dphy2";
		csi2_dphy3 = "/csi2-dphy3";
		csi2_dphy4 = "/csi2-dphy4";
		csi2_dphy5 = "/csi2-dphy5";
		csu = "/csu";
		display_subsystem = "/display-subsystem";
		route_dsi = "/display-subsystem/route/route-dsi";
		route_lvds = "/display-subsystem/route/route-lvds";
		route_rgb = "/display-subsystem/route/route-rgb";
		dmc = "/dmc";
		dmc_opp_table = "/dmc-opp-table";
		scmi = "/firmware/scmi";
		scmi_clk = "/firmware/scmi/protocol@14";
		optee = "/firmware/optee";
		mpp_srv = "/mpp-srv";
		mipi0_csi2 = "/mipi0-csi2";
		mipi1_csi2 = "/mipi1-csi2";
		mipi2_csi2 = "/mipi2-csi2";
		mipi3_csi2 = "/mipi3-csi2";
		reserved_memory = "/reserved-memory";
		drm_logo = "/reserved-memory/drm-logo@00000000";
		vendor_storage_rm = "/reserved-memory/vendor-storage-rm@00000000";
		drm_cubic_lut = "/reserved-memory/drm-cubic-lut@00000000";
		ramoops = "/reserved-memory/ramoops@110000";
		rkcif_mipi_lvds = "/rkcif-mipi-lvds";
		rkcif_mipi_lvds_sditf = "/rkcif-mipi-lvds-sditf";
		rkcif_mipi_lvds_sditf_vir1 = "/rkcif-mipi-lvds-sditf-vir1";
		rkcif_mipi_lvds_sditf_vir2 = "/rkcif-mipi-lvds-sditf-vir2";
		rkcif_mipi_lvds_sditf_vir3 = "/rkcif-mipi-lvds-sditf-vir3";
		rkcif_mipi_lvds1 = "/rkcif-mipi-lvds1";
		rkcif_mipi_lvds1_sditf = "/rkcif-mipi-lvds1-sditf";
		rkcif_mipi_lvds1_sditf_vir1 = "/rkcif-mipi-lvds1-sditf-vir1";
		rkcif_mipi_lvds1_sditf_vir2 = "/rkcif-mipi-lvds1-sditf-vir2";
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

## Display / Panel / Backlight
### `route-dsi` (Zeile 529-537)
```dts
			route-dsi {
				status = "okay";
				logo,uboot = "logo.bmp";
				logo,kernel = "logo_kernel.bmp";
				logo,mode = "center";
				charge_logo,mode = "center";
				connect = <0x1b>;
				phandle = <0x10b>;
			};
```

### `rk628@50` (Zeile 3615-3641)
```dts
		rk628@50 {
			status = "okay";
			compatible = "rockchip,rk628";
			reg = <0x50>;
			#sound-dai-cells = <0x00>;
			interrupt-parent = <0x49>;
			interrupts = <0x12 0x04>;
			enable-gpios = <0x49 0x10 0x00>;
			reset-gpios = <0x49 0x11 0x01>;
			pinctrl-names = "default";
			pinctrl-0 = <0xc2 0xc3>;
			assigned-clocks = <0x02 0x132>;
			assigned-clock-rates = <0x16e3600>;
			clocks = <0x02 0x132>;
			clock-names = "soc_24M";
			rk628-rgb-in;
			rk628-hdmi-out;
			phandle = <0xe7>;

			port {

				endpoint {
					remote-endpoint = <0xc4>;
					phandle = <0x3b>;
				};
			};
		};
```

### `panel@0` (Zeile 3819-3878)
```dts
		panel@0 {
			status = "okay";
			compatible = "simple-panel-dsi";
			reg = <0x00>;
			backlight = <0xce>;
			reset-delay-ms = <0x14>;
			enable-delay-ms = <0x78>;
			prepare-delay-ms = <0x14>;
			unprepare-delay-ms = <0x14>;
			disable-delay-ms = <0x14>;
			width-mm = <0x44>;
			height-mm = <0x79>;
			dsi,flags = <0xa03>;
			dsi,format = <0x00>;
			dsi,lanes = <0x04>;
			panel-init-sequence = [15 00 02 ee 01 15 00 02 ea 07 15 00 02 eb 12 15 00 02 0a 5e 15 00 02 13 14 15 00 02 17 35 15 00 02 1d 33 15 00 02 21 01 15 00 02 28 28 15 00 02 29 18 15 00 02 2a 63 15 00 02 2f f3 15 00 02 ee 02 15 00 02 39 a9 15 00 02 00 00 15 00 02 01 0d 15 00 02 02 12 15 00 02 03 08 15 00 02 04 0e 15 00 02 05 30 15 00 02 06 0b 15 00 02 07 0e 15 00 02 08 0f 15 00 02 09 0e 15 00 02 0a 11 15 00 02 0b 4e 15 00 02 0c 14 15 00 02 0d 1a 15 00 02 0e 2f 15 00 02 0f 36 15 00 02 10 3f 15 00 02 20 00 15 00 02 21 0d 15 00 02 22 12 15 00 02 23 08 15 00 02 24 0e 15 00 02 25 30 15 00 02 26 0b 15 00 02 27 0e 15 00 02 28 0f 15 00 02 29 0e 15 00 02 2a 11 15 00 02 2b 4e 15 00 02 2c 14 15 00 02 2d 1a 15 00 02 2e 2f 15 00 02 2f 36 15 00 02 30 3f 15 00 02 ee 04 15 00 02 00 05 15 00 02 01 01 15 00 02 02 80 15 00 02 03 04 15 00 02 04 00 15 00 02 06 06 15 00 02 07 05 15 00 02 08 1a 15 00 02 09 20 15 00 02 0a 0e 15 00 02 0b 00 15 00 02 20 40 15 00 02 24 08 15 00 02 ee 05 15 00 02 00 01 15 00 02 01 09 15 00 02 02 05 15 00 02 03 05 15 00 02 07 05 15 00 02 08 0d 15 00 02 09 00 15 00 02 0a 12 15 00 02 0b 14 15 00 02 0c 66 15 00 02 10 03 15 00 02 11 07 15 00 02 12 05 15 00 02 13 05 15 00 02 19 12 15 00 02 1a f6 15 00 02 40 55 15 00 02 41 00 15 00 02 43 03 15 00 02 44 01 15 00 02 45 81 15 00 02 46 06 15 00 02 47 00 15 00 02 ee 06 15 00 02 00 45 15 00 02 02 01 15 00 02 04 88 15 00 02 06 cd 15 00 02 08 ef 15 00 02 09 cd 15 00 02 0a ab 15 00 02 0b 89 15 00 02 0c 67 15 00 02 0d 45 15 00 02 0e 23 15 00 02 0f 01 15 00 02 ee 07 15 00 02 00 3c 15 00 02 01 3c 15 00 02 02 3c 15 00 02 03 3c 15 00 02 04 0d 15 00 02 05 3c 15 00 02 06 3c 15 00 02 07 3c 15 00 02 08 08 15 00 02 09 10 15 00 02 0a 12 15 00 02 0b 14 15 00 02 0c 16 15 00 02 0d 18 15 00 02 0e 1a 15 00 02 0f 1c 15 00 02 10 1e 15 00 02 11 04 15 00 02 12 00 15 00 02 13 3c 15 00 02 14 0c 15 00 02 15 3c 15 00 02 20 3c 15 00 02 21 3c 15 00 02 22 3c 15 00 02 23 3c 15 00 02 24 0d 15 00 02 25 3c 15 00 02 26 3c 15 00 02 27 3c 15 00 02 28 08 15 00 02 29 11 15 00 02 2a 13 15 00 02 2b 15 15 00 02 2c 17 15 00 02 2d 19 15 00 02 2e 1b 15 00 02 2f 1d 15 00 02 30 1f 15 00 02 31 05 15 00 02 32 01 15 00 02 33 3c 15 00 02 34 0c 15 00 02 35 3c 15 00 02 ee 08 15 00 02 10 00 15 00 02 12 dc 15 00 02 13 1c 15 00 02 17 23 15 00 02 18 20 15 00 02 20 80 15 00 02 ee 0f 15 00 02 00 01 15 00 02 01 00 15 00 02 ee 00 15 00 02 ea 00 15 00 02 eb 00 15 00 02 36 00 05 c8 01 11 05 14 01 29];
			panel-exit-sequence = <0x5000128 0x5000110>;
			enable-gpios = <0x3d 0x08 0x00>;
			reset-gpios = <0x3d 0x14 0x01>;
			pinctrl-names = "default";
			pinctrl-0 = <0xcf 0xd0>;
			init-delay-ms = <0x14>;
			phandle = <0x1ad>;

			display-timings {
				native-mode = <0xd1>;
				phandle = <0x1ae>;

				timing0 {
					clock-frequency = <0x3a2c940>;
					hactive = <0x400>;
					vactive = <0x300>;
					hfront-porch = <0x5a>;
					hsync-len = <0x50>;
					hback-porch = <0x50>;
					vfront-porch = <0x10>;
					vsync-len = <0x08>;
					vback-porch = <0x08>;
					hsync-active = <0x00>;
					vsync-active = <0x00>;
					de-active = <0x00>;
					pixelclk-active = <0x00>;
					phandle = <0xd1>;
				};
			};

			ports {
				#address-cells = <0x01>;
				#size-cells = <0x00>;

				port@0 {
					reg = <0x00>;

					endpoint {
						remote-endpoint = <0xd2>;
						phandle = <0xcd>;
					};
				};
			};
		};
```

### `phy@ffb20000` (Zeile 3881-3893)
```dts
	phy@ffb20000 {
		compatible = "rockchip,rk3562-dsi-dphy\0rockchip,rk3562-video-phy\0rockchip,rk3568-dsi-dphy\0rockchip,rk3568-video-phy";
		reg = <0x00 0xffb20000 0x00 0x10000 0x00 0xffb10000 0x00 0x10000>;
		reg-names = "phy\0host";
		clocks = <0x02 0x13f 0x02 0x4d 0x02 0x4e>;
		clock-names = "ref\0pclk\0pclk_host";
		#clock-cells = <0x00>;
		resets = <0x02 0x198>;
		reset-names = "apb";
		#phy-cells = <0x00>;
		status = "okay";
		phandle = <0x39>;
	};
```

### `lcd-rst-gpio` (Zeile 5905-5908)
```dts
			lcd-rst-gpio {
				rockchip,pins = <0x00 0x14 0x00 0xd4>;
				phandle = <0xcf>;
			};
```

### `lcd-powerctrl-gpio` (Zeile 5910-5913)
```dts
			lcd-powerctrl-gpio {
				rockchip,pins = <0x00 0x08 0x00 0xd4>;
				phandle = <0xd0>;
			};
```

### `lcd-pwren-h` (Zeile 5934-5937)
```dts
			lcd-pwren-h {
				rockchip,pins = <0x00 0x08 0x00 0xd7>;
				phandle = <0x2ae>;
			};
```

### `backlight` (Zeile 6034-6040)
```dts
	backlight {
		compatible = "pwm-backlight";
		pwms = <0xde 0x00 0x61a8 0x00>;
		brightness-levels = <0x00 0x14 0x14 0x15 0x15 0x16 0x16 0x17 0x17 0x18 0x18 0x19 0x19 0x1a 0x1a 0x1b 0x1b 0x1c 0x1c 0x1d 0x1d 0x1e 0x1e 0x1f 0x1f 0x20 0x20 0x21 0x21 0x22 0x22 0x23 0x23 0x24 0x24 0x25 0x25 0x26 0x26 0x27 0x28 0x29 0x2a 0x2b 0x2c 0x2d 0x2e 0x2f 0x30 0x31 0x32 0x33 0x34 0x35 0x36 0x37 0x38 0x39 0x3a 0x3b 0x3c 0x3d 0x3e 0x3f 0x40 0x41 0x42 0x43 0x44 0x45 0x46 0x47 0x48 0x49 0x4a 0x4b 0x4c 0x4d 0x4e 0x4f 0x50 0x51 0x52 0x53 0x54 0x55 0x56 0x57 0x58 0x59 0x5a 0x5b 0x5c 0x5d 0x5e 0x5f 0x60 0x61 0x62 0x63 0x64 0x65 0x66 0x67 0x68 0x69 0x6a 0x6b 0x6c 0x6d 0x6e 0x6f 0x70 0x71 0x72 0x73 0x74 0x75 0x76 0x77 0x78 0x79 0x7a 0x7b 0x7c 0x7d 0x7e 0x7f 0x80 0x81 0x82 0x83 0x84 0x85 0x86 0x87 0x88 0x89 0x8a 0x8b 0x8c 0x8d 0x8e 0x8f 0x90 0x91 0x92 0x93 0x94 0x95 0x96 0x97 0x98 0x99 0x9a 0x9b 0x9c 0x9d 0x9e 0x9f 0xa0 0xa1 0xa2 0xa3 0xa4 0xa5 0xa6 0xa7 0xa8 0xa9 0xaa 0xab 0xac 0xad 0xae 0xaf 0xb0 0xb1 0xb2 0xb3 0xb4 0xb5 0xb6 0xb7 0xb8 0xb9 0xba 0xbb 0xbc 0xbd 0xbe 0xbf 0xc0 0xc1 0xc2 0xc3 0xc4 0xc5 0xc6 0xc7 0xc8 0xc9 0xca 0xcb 0xcc 0xcd 0xce 0xcf 0xd0 0xd1 0xd2 0xd3 0xd4 0xd5 0xd6 0xd7 0xd8 0xd9 0xda 0xdb 0xdc 0xdd 0xde 0xdf 0xe0 0xe1 0xe2 0xe3 0xe4 0xe5 0xe6 0xe7 0xe8 0xe9 0xea 0xeb 0xec 0xed 0xee 0xef 0xf0 0xf1 0xf2 0xf3 0xf4 0xf5 0xf6 0xf7 0xf8 0xf9 0xfa 0xfb 0xfc 0xfd 0xfe 0xff>;
		default-brightness-level = <0xc8>;
		phandle = <0xce>;
	};
```

### `vcc3v3-lcd0-n` (Zeile 6091-6100)
```dts
	vcc3v3-lcd0-n {
		compatible = "regulator-fixed";
		regulator-name = "vcc3v3_lcd_n";
		regulator-boot-on;
		phandle = <0x2b3>;

		regulator-state-mem {
			regulator-off-in-suspend;
		};
	};
```

### `rk628-sound` (Zeile 6126-6141)
```dts
	rk628-sound {
		compatible = "simple-audio-card";
		simple-audio-card,format = "i2s";
		simple-audio-card,mclk-fs = <0x80>;
		simple-audio-card,name = "rockchip,hdmi-rk628";
		status = "okay";
		phandle = <0x2b5>;

		simple-audio-card,cpu {
			sound-dai = <0xe6>;
		};

		simple-audio-card,codec {
			sound-dai = <0xe7>;
		};
	};
```

### `__symbols__` (Zeile 6356-7054)
```dts
	__symbols__ {
		xin32k = "/clocks/xin32k";
		xin24m = "/clocks/xin24m";
		hclk_vepu = "/clocks/hclk_vepu@ff100324";
		aclk_vdpu = "/clocks/aclk_vdpu@ff100328";
		aclk_vi_isp = "/clocks/aclk_vi_isp@ff10032c";
		aclk_vo = "/clocks/aclk_vo@ff100334";
		aclk_vepu = "/clocks/aclk_vepu@ff100324";
		aclk_rga_jdec = "/clocks/aclk_rga_jdec@ff100338";
		mclkin_sai0 = "/clocks/mclkin-sai0";
		mclkin_sai1 = "/clocks/mclkin-sai1";
		mclkin_sai2 = "/clocks/mclkin-sai2";
		mclkout_sai0 = "/clocks/mclkout-sai0@ff040070";
		mclkout_sai1 = "/clocks/mclkout-sai1@ff040070";
		mclkout_sai2 = "/clocks/mclkout-sai2@ff040070";
		cpu0 = "/cpus/cpu@0";
		cpu1 = "/cpus/cpu@1";
		cpu2 = "/cpus/cpu@2";
		cpu3 = "/cpus/cpu@3";
		CPU_SLEEP = "/cpus/idle-states/cpu-sleep";
		cpu0_opp_table = "/cpu0-opp-table";
		cpu_opp_j_od_1416000000 = "/cpu0-opp-table/opp-j-od-1416000000";
		cpu_opp_j_od_1608000000 = "/cpu0-opp-table/opp-j-od-1608000000";
		cpu_opp_j_od_1800000000 = "/cpu0-opp-table/opp-j-od-1800000000";
		arm_pmu = "/arm-pmu";
		csi2_dphy0 = "/csi2-dphy0";
		csi2_dphy1 = "/csi2-dphy1";
		csi2_dphy2 = "/csi2-dphy2";
		csi2_dphy3 = "/csi2-dphy3";
		csi2_dphy4 = "/csi2-dphy4";
		csi2_dphy5 = "/csi2-dphy5";
		csu = "/csu";
		display_subsystem = "/display-subsystem";
		route_dsi = "/display-subsystem/route/route-dsi";
		route_lvds = "/display-subsystem/route/route-lvds";
		route_rgb = "/display-subsystem/route/route-rgb";
		dmc = "/dmc";
		dmc_opp_table = "/dmc-opp-table";
		scmi = "/firmware/scmi";
		scmi_clk = "/firmware/scmi/protocol@14";
		optee = "/firmware/optee";
		mpp_srv = "/mpp-srv";
		mipi0_csi2 = "/mipi0-csi2";
		mipi1_csi2 = "/mipi1-csi2";
		mipi2_csi2 = "/mipi2-csi2";
		mipi3_csi2 = "/mipi3-csi2";
		reserved_memory = "/reserved-memory";
		drm_logo = "/reserved-memory/drm-logo@00000000";
		vendor_storage_rm = "/reserved-memory/vendor-storage-rm@00000000";
		drm_cubic_lut = "/reserved-memory/drm-cubic-lut@00000000";
		ramoops = "/reserved-memory/ramoops@110000";
		rkcif_mipi_lvds = "/rkcif-mipi-lvds";
		rkcif_mipi_lvds_sditf = "/rkcif-mipi-lvds-sditf";
		rkcif_mipi_lvds_sditf_vir1 = "/rkcif-mipi-lvds-sditf-vir1";
		rkcif_mipi_lvds_sditf_vir2 = "/rkcif-mipi-lvds-sditf-vir2";
		rkcif_mipi_lvds_sditf_vir3 = "/rkcif-mipi-lvds-sditf-vir3";
		rkcif_mipi_lvds1 = "/rkcif-mipi-lvds1";
		rkcif_mipi_lvds1_sditf = "/rkcif-mipi-lvds1-sditf";
		rkcif_mipi_lvds1_sditf_vir1 = "/rkcif-mipi-lvds1-sditf-vir1";
		rkcif_mipi_lvds1_sditf_vir2 = "/rkcif-mipi-lvds1-sditf-vir2";
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

## Touchscreen
_Nichts gefunden._

## USB / OTG
### `usb@fe500000` (Zeile 968-1006)
```dts
		usb@fe500000 {
			compatible = "snps,dwc3";
			reg = <0x00 0xfe500000 0x00 0x400000>;
			interrupts = <0x00 0x95 0x04>;
			dr_mode = "otg";
			phys = <0x34>;
			phy-names = "usb2-phy";
			phy_type = "utmi_wide";
			power-domains = <0x35 0x0f>;
			resets = <0x02 0x10a>;
			reset-names = "usb3-otg";
			snps,dis_enblslpm_quirk;
			snps,dis-u1-entry-quirk;
			snps,dis-u2-entry-quirk;
			snps,dis-u2-freeclk-exists-quirk;
			snps,dis-del-phy-power-chg-quirk;
			snps,dis-tx-ipgap-linecheck-quirk;
			snps,dis_rxdet_inp3_quirk;
			snps,parkmode-disable-hs-quirk;
			snps,parkmode-disable-ss-quirk;
			quirk-skip-phy-init;
			status = "okay";
			usb-role-switch;
			maximum-speed = "high-speed";
			snps,dis_u2_susphy_quirk;
			snps,usb2-lpm-disable;
			phandle = <0x132>;

			port {
				#address-cells = <0x01>;
				#size-cells = <0x00>;

				endpoint@0 {
					reg = <0x00>;
					remote-endpoint = <0x36>;
					phandle = <0xbf>;
				};
			};
		};
```

### `usb@fed00000` (Zeile 1019-1029)
```dts
	usb@fed00000 {
		compatible = "generic-ehci";
		reg = <0x00 0xfed00000 0x00 0x40000>;
		interrupts = <0x00 0x96 0x04>;
		clocks = <0x02 0x9e 0x02 0x9f 0x37>;
		clock-names = "usbhost\0arbiter\0utmi";
		phys = <0x38>;
		phy-names = "usb2-phy";
		status = "disabled";
		phandle = <0x133>;
	};
```

### `usb@fed40000` (Zeile 1031-1041)
```dts
	usb@fed40000 {
		compatible = "generic-ohci";
		reg = <0x00 0xfed40000 0x00 0x40000>;
		interrupts = <0x00 0x97 0x04>;
		clocks = <0x02 0x9e 0x02 0x9f 0x37>;
		clock-names = "usbhost\0arbiter\0utmi";
		phys = <0x38>;
		phy-names = "usb2-phy";
		status = "disabled";
		phandle = <0x134>;
	};
```

### `syscon@ff090000` (Zeile 1493-1497)
```dts
	syscon@ff090000 {
		compatible = "rockchip,rk3562-usbphy-grf\0syscon";
		reg = <0x00 0xff090000 0x00 0x8000>;
		phandle = <0x9a>;
	};
```

### `OTG_SWITCH` (Zeile 1794-1801)
```dts
				OTG_SWITCH {
					regulator-name = "otg_switch";
					phandle = <0xbe>;

					regulator-state-mem {
						regulator-off-in-suspend;
					};
				};
```

### `charger` (Zeile 1848-1861)
```dts
			charger {
				compatible = "rk817,charger";
				min_input_voltage = <0x1194>;
				max_input_current = <0x5dc>;
				max_chrg_current = <0x5dc>;
				max_chrg_voltage = <0x10b8>;
				chrg_term_mode = <0x00>;
				chrg_finish_cur = <0x12c>;
				virtual_power = <0x00>;
				dc_det_adc = <0x00>;
				otg5v_suspend_enable = <0x01>;
				extcon = <0x4b>;
				gate_function_disable = <0x01>;
			};
```

### `otg-port` (Zeile 3112-3119)
```dts
		otg-port {
			#phy-cells = <0x00>;
			interrupts = <0x00 0x99 0x04 0x00 0x9a 0x04 0x00 0x9b 0x04>;
			interrupt-names = "otg-bvalid\0otg-id\0linestate";
			status = "okay";
			rockchip,vbus-always-on;
			phandle = <0x34>;
		};
```

### `connector` (Zeile 3573-3583)
```dts
			connector {
				compatible = "usb-c-connector";
				label = "USB-C";
				data-role = "dual";
				power-role = "dual";
				try-power-role = "sink";
				op-sink-microwatt = <0xf4240>;
				sink-pdos = <0x401912c>;
				source-pdos = <0x260190c8>;
				phandle = <0x1a2>;
			};
```

### `usbc0-int` (Zeile 5926-5929)
```dts
			usbc0-int {
				rockchip,pins = <0x00 0x0f 0x00 0xd7>;
				phandle = <0xbd>;
			};
```

### `__symbols__` (Zeile 6356-7054)
```dts
	__symbols__ {
		xin32k = "/clocks/xin32k";
		xin24m = "/clocks/xin24m";
		hclk_vepu = "/clocks/hclk_vepu@ff100324";
		aclk_vdpu = "/clocks/aclk_vdpu@ff100328";
		aclk_vi_isp = "/clocks/aclk_vi_isp@ff10032c";
		aclk_vo = "/clocks/aclk_vo@ff100334";
		aclk_vepu = "/clocks/aclk_vepu@ff100324";
		aclk_rga_jdec = "/clocks/aclk_rga_jdec@ff100338";
		mclkin_sai0 = "/clocks/mclkin-sai0";
		mclkin_sai1 = "/clocks/mclkin-sai1";
		mclkin_sai2 = "/clocks/mclkin-sai2";
		mclkout_sai0 = "/clocks/mclkout-sai0@ff040070";
		mclkout_sai1 = "/clocks/mclkout-sai1@ff040070";
		mclkout_sai2 = "/clocks/mclkout-sai2@ff040070";
		cpu0 = "/cpus/cpu@0";
		cpu1 = "/cpus/cpu@1";
		cpu2 = "/cpus/cpu@2";
		cpu3 = "/cpus/cpu@3";
		CPU_SLEEP = "/cpus/idle-states/cpu-sleep";
		cpu0_opp_table = "/cpu0-opp-table";
		cpu_opp_j_od_1416000000 = "/cpu0-opp-table/opp-j-od-1416000000";
		cpu_opp_j_od_1608000000 = "/cpu0-opp-table/opp-j-od-1608000000";
		cpu_opp_j_od_1800000000 = "/cpu0-opp-table/opp-j-od-1800000000";
		arm_pmu = "/arm-pmu";
		csi2_dphy0 = "/csi2-dphy0";
		csi2_dphy1 = "/csi2-dphy1";
		csi2_dphy2 = "/csi2-dphy2";
		csi2_dphy3 = "/csi2-dphy3";
		csi2_dphy4 = "/csi2-dphy4";
		csi2_dphy5 = "/csi2-dphy5";
		csu = "/csu";
		display_subsystem = "/display-subsystem";
		route_dsi = "/display-subsystem/route/route-dsi";
		route_lvds = "/display-subsystem/route/route-lvds";
		route_rgb = "/display-subsystem/route/route-rgb";
		dmc = "/dmc";
		dmc_opp_table = "/dmc-opp-table";
		scmi = "/firmware/scmi";
		scmi_clk = "/firmware/scmi/protocol@14";
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

## LEDs
### `led-en-gpio` (Zeile 5976-5979)
```dts
			led-en-gpio {
				rockchip,pins = <0x00 0x17 0x00 0xd7>;
				phandle = <0xed>;
			};
```

### `charge-led-gpio` (Zeile 5984-5987)
```dts
			charge-led-gpio {
				rockchip,pins = <0x03 0x00 0x00 0xd7 0x03 0x01 0x00 0xd7>;
				phandle = <0x4a>;
			};
```

### `led-vcc` (Zeile 6218-6226)
```dts
	led-vcc {
		compatible = "regulator-fixed";
		regulator-name = "vcc-led";
		pinctrl-0 = <0xed>;
		pinctrl-names = "default";
		gpios = <0x3d 0x17 0x00>;
		enable-active-high;
		phandle = <0x2b7>;
	};
```

### `__symbols__` (Zeile 6356-7054)
```dts
	__symbols__ {
		xin32k = "/clocks/xin32k";
		xin24m = "/clocks/xin24m";
		hclk_vepu = "/clocks/hclk_vepu@ff100324";
		aclk_vdpu = "/clocks/aclk_vdpu@ff100328";
		aclk_vi_isp = "/clocks/aclk_vi_isp@ff10032c";
		aclk_vo = "/clocks/aclk_vo@ff100334";
		aclk_vepu = "/clocks/aclk_vepu@ff100324";
		aclk_rga_jdec = "/clocks/aclk_rga_jdec@ff100338";
		mclkin_sai0 = "/clocks/mclkin-sai0";
		mclkin_sai1 = "/clocks/mclkin-sai1";
		mclkin_sai2 = "/clocks/mclkin-sai2";
		mclkout_sai0 = "/clocks/mclkout-sai0@ff040070";
		mclkout_sai1 = "/clocks/mclkout-sai1@ff040070";
		mclkout_sai2 = "/clocks/mclkout-sai2@ff040070";
		cpu0 = "/cpus/cpu@0";
		cpu1 = "/cpus/cpu@1";
		cpu2 = "/cpus/cpu@2";
		cpu3 = "/cpus/cpu@3";
		CPU_SLEEP = "/cpus/idle-states/cpu-sleep";
		cpu0_opp_table = "/cpu0-opp-table";
		cpu_opp_j_od_1416000000 = "/cpu0-opp-table/opp-j-od-1416000000";
		cpu_opp_j_od_1608000000 = "/cpu0-opp-table/opp-j-od-1608000000";
		cpu_opp_j_od_1800000000 = "/cpu0-opp-table/opp-j-od-1800000000";
		arm_pmu = "/arm-pmu";
		csi2_dphy0 = "/csi2-dphy0";
		csi2_dphy1 = "/csi2-dphy1";
		csi2_dphy2 = "/csi2-dphy2";
		csi2_dphy3 = "/csi2-dphy3";
		csi2_dphy4 = "/csi2-dphy4";
		csi2_dphy5 = "/csi2-dphy5";
		csu = "/csu";
		display_subsystem = "/display-subsystem";
		route_dsi = "/display-subsystem/route/route-dsi";
		route_lvds = "/display-subsystem/route/route-lvds";
		route_rgb = "/display-subsystem/route/route-rgb";
		dmc = "/dmc";
		dmc_opp_table = "/dmc-opp-table";
		scmi = "/firmware/scmi";
		scmi_clk = "/firmware/scmi/protocol@14";
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

## RTC (Echtzeituhr)
_Nichts gefunden._

## Sensoren (Gyro / Accel)
_Nichts gefunden._

## Thermal-Zonen
### `cpu0-opp-table` (Zeile 262-455)
```dts
	cpu0-opp-table {
		compatible = "operating-points-v2";
		opp-shared;
		mbist-vmin = <0xc96a8 0xdbba0 0xee098>;
		nvmem-cells = <0x09 0x0a 0x0b 0x0c 0x0d>;
		nvmem-cell-names = "leakage\0opp-info\0mbist-vmin\0pvtm\0specification_serial_number";
		rockchip,supported-hw;
		rockchip,pvtm-voltage-sel = <0x00 0x500 0x00 0x501 0x546 0x01 0x547 0x58c 0x02 0x58d 0x5d2 0x03 0x5d3 0x270f 0x04>;
		rockchip,pvtm-pvtpll;
		rockchip,pvtm-offset = <0x634>;
		rockchip,pvtm-sample-time = <0x44c>;
		rockchip,pvtm-freq = <0x188940>;
		rockchip,pvtm-volt = <0xdbba0>;
		rockchip,pvtm-ref-temp = <0x28>;
		rockchip,pvtm-temp-prop = <0x00 0x00>;
		rockchip,pvtm-thermal-zone = "soc-thermal";
		rockchip,grf = <0x0e>;
		rockchip,temp-hysteresis = <0x1388>;
		rockchip,low-temp = <0x2710>;
		rockchip,low-temp-min-volt = <0x100590>;
		phandle = <0x07>;

		opp-408000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x18519600>;
			opp-microvolt = <0xc96a8 0xc96a8 0x118c30>;
			clock-latency-ns = <0x9c40>;
			opp-suspend;
		};

		opp-600000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x23c34600>;
			opp-microvolt = <0xc96a8 0xc96a8 0x118c30>;
			clock-latency-ns = <0x9c40>;
		};

		opp-816000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x30a32c00>;
			opp-microvolt = <0xc96a8 0xc96a8 0x118c30>;
			clock-latency-ns = <0x9c40>;
		};

		opp-1008000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x3c14dc00>;
			opp-microvolt = <0xcf850 0xcf850 0x118c30>;
			opp-microvolt-L0 = <0xcf850 0xcf850 0x118c30>;
			opp-microvolt-L1 = <0xc96a8 0xc96a8 0x118c30>;
			opp-microvolt-L2 = <0xc96a8 0xc96a8 0x118c30>;
			opp-microvolt-L3 = <0xc96a8 0xc96a8 0x118c30>;
			opp-microvolt-L4 = <0xc96a8 0xc96a8 0x118c30>;
			clock-latency-ns = <0x9c40>;
		};

		opp-1200000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x47868c00>;
			opp-microvolt = <0xe1d48 0xe1d48 0x118c30>;
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `rockchip-system-monitor` (Zeile 883-887)
```dts
	rockchip-system-monitor {
		compatible = "rockchip,system-monitor";
		rockchip,thermal-zone = "soc-thermal";
		phandle = <0x12b>;
	};
```

### `map0` (Zeile 925-929)
```dts
				map0 {
					trip = <0x31>;
					cooling-device = <0x0f 0xffffffff 0xffffffff>;
					contribution = <0x400>;
				};
```

### `map1` (Zeile 931-935)
```dts
				map1 {
					trip = <0x31>;
					cooling-device = <0x32 0xffffffff 0xffffffff>;
					contribution = <0x400>;
				};
```

### `npu-opp-table` (Zeile 2043-2206)
```dts
	npu-opp-table {
		compatible = "operating-points-v2";
		mbist-vmin = <0xc96a8 0xdbba0 0xee098>;
		nvmem-cells = <0x6f 0x70 0x0b 0x71 0x0d>;
		nvmem-cell-names = "leakage\0opp-info\0mbist-vmin\0pvtm\0specification_serial_number";
		rockchip,supported-hw;
		rockchip,pvtm-voltage-sel = <0x00 0x2f8 0x00 0x2f9 0x320 0x01 0x321 0x348 0x02 0x349 0x370 0x03 0x371 0x270f 0x04>;
		rockchip,pvtm-pvtpll;
		rockchip,pvtm-offset = <0x674>;
		rockchip,pvtm-sample-time = <0x44c>;
		rockchip,pvtm-freq = <0xdbba0>;
		rockchip,pvtm-volt = <0xdbba0>;
		rockchip,pvtm-ref-temp = <0x28>;
		rockchip,pvtm-temp-prop = <0x00 0x00>;
		rockchip,pvtm-thermal-zone = "soc-thermal";
		rockchip,grf = <0x0e>;
		rockchip,temp-hysteresis = <0x1388>;
		rockchip,low-temp = <0x2710>;
		rockchip,low-temp-min-volt = <0xe1d48>;
		phandle = <0x6c>;

		opp-300000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x11e1a300>;
			opp-microvolt = <0xc96a8 0xc96a8 0xf4240>;
		};

		opp-400000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x17d78400>;
			opp-microvolt = <0xc96a8 0xc96a8 0xf4240>;
		};

		opp-500000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x1dcd6500>;
			opp-microvolt = <0xc96a8 0xc96a8 0xf4240>;
		};

		opp-600000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x23c34600>;
			opp-microvolt = <0xd59f8 0xd59f8 0xf4240>;
			opp-microvolt-L0 = <0xd59f8 0xd59f8 0xf4240>;
			opp-microvolt-L1 = <0xcf850 0xcf850 0xf4240>;
			opp-microvolt-L2 = <0xc96a8 0xc96a8 0xf4240>;
			opp-microvolt-L3 = <0xc96a8 0xc96a8 0xf4240>;
			opp-microvolt-L4 = <0xc96a8 0xc96a8 0xf4240>;
		};

		opp-700000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x29b92700>;
			opp-microvolt = <0xe1d48 0xe1d48 0xf4240>;
			opp-microvolt-L0 = <0xe1d48 0xe1d48 0xf4240>;
			opp-microvolt-L1 = <0xdbba0 0xdbba0 0xf4240>;
			opp-microvolt-L2 = <0xd59f8 0xd59f8 0xf4240>;
			opp-microvolt-L3 = <0xcf850 0xcf850 0xf4240>;
			opp-microvolt-L4 = <0xc96a8 0xc96a8 0xf4240>;
		};
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `gpu-opp-table` (Zeile 2239-2372)
```dts
	gpu-opp-table {
		compatible = "operating-points-v2";
		mbist-vmin = <0xc96a8 0xdbba0 0xee098>;
		nvmem-cells = <0x74 0x75 0x0b 0x76 0x0d>;
		nvmem-cell-names = "leakage\0opp-info\0mbist-vmin\0pvtm\0specification_serial_number";
		rockchip,supported-hw;
		rockchip,pvtm-voltage-sel = <0x00 0x30c 0x00 0x30d 0x334 0x01 0x335 0x35c 0x02 0x35d 0x384 0x03 0x385 0x270f 0x04>;
		rockchip,pvtm-pvtpll;
		rockchip,pvtm-offset = <0x654>;
		rockchip,pvtm-sample-time = <0x44c>;
		rockchip,pvtm-freq = <0xdbba0>;
		rockchip,pvtm-volt = <0xdbba0>;
		rockchip,pvtm-ref-temp = <0x28>;
		rockchip,pvtm-temp-prop = <0x00 0x00>;
		rockchip,pvtm-thermal-zone = "soc-thermal";
		rockchip,grf = <0x0e>;
		rockchip,temp-hysteresis = <0x1388>;
		rockchip,low-temp = <0x2710>;
		rockchip,low-temp-min-volt = <0xe1d48>;
		phandle = <0x72>;

		opp-300000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x11e1a300>;
			opp-microvolt = <0xc96a8 0xc96a8 0xf4240>;
		};

		opp-400000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x17d78400>;
			opp-microvolt = <0xc96a8 0xc96a8 0xf4240>;
		};

		opp-500000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x1dcd6500>;
			opp-microvolt = <0xc96a8 0xc96a8 0xf4240>;
		};

		opp-600000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x23c34600>;
			opp-microvolt = <0xc96a8 0xc96a8 0xf4240>;
		};

		opp-700000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x29b92700>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
			opp-microvolt-L0 = <0xdbba0 0xdbba0 0xf4240>;
			opp-microvolt-L1 = <0xd59f8 0xd59f8 0xf4240>;
			opp-microvolt-L2 = <0xcf850 0xcf850 0xf4240>;
			opp-microvolt-L3 = <0xc96a8 0xc96a8 0xf4240>;
			opp-microvolt-L4 = <0xc96a8 0xc96a8 0xf4240>;
		};

		opp-800000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x2faf0800>;
			opp-microvolt = <0xe7ef0 0xe7ef0 0xf4240>;
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `__symbols__` (Zeile 6356-7054)
```dts
	__symbols__ {
		xin32k = "/clocks/xin32k";
		xin24m = "/clocks/xin24m";
		hclk_vepu = "/clocks/hclk_vepu@ff100324";
		aclk_vdpu = "/clocks/aclk_vdpu@ff100328";
		aclk_vi_isp = "/clocks/aclk_vi_isp@ff10032c";
		aclk_vo = "/clocks/aclk_vo@ff100334";
		aclk_vepu = "/clocks/aclk_vepu@ff100324";
		aclk_rga_jdec = "/clocks/aclk_rga_jdec@ff100338";
		mclkin_sai0 = "/clocks/mclkin-sai0";
		mclkin_sai1 = "/clocks/mclkin-sai1";
		mclkin_sai2 = "/clocks/mclkin-sai2";
		mclkout_sai0 = "/clocks/mclkout-sai0@ff040070";
		mclkout_sai1 = "/clocks/mclkout-sai1@ff040070";
		mclkout_sai2 = "/clocks/mclkout-sai2@ff040070";
		cpu0 = "/cpus/cpu@0";
		cpu1 = "/cpus/cpu@1";
		cpu2 = "/cpus/cpu@2";
		cpu3 = "/cpus/cpu@3";
		CPU_SLEEP = "/cpus/idle-states/cpu-sleep";
		cpu0_opp_table = "/cpu0-opp-table";
		cpu_opp_j_od_1416000000 = "/cpu0-opp-table/opp-j-od-1416000000";
		cpu_opp_j_od_1608000000 = "/cpu0-opp-table/opp-j-od-1608000000";
		cpu_opp_j_od_1800000000 = "/cpu0-opp-table/opp-j-od-1800000000";
		arm_pmu = "/arm-pmu";
		csi2_dphy0 = "/csi2-dphy0";
		csi2_dphy1 = "/csi2-dphy1";
		csi2_dphy2 = "/csi2-dphy2";
		csi2_dphy3 = "/csi2-dphy3";
		csi2_dphy4 = "/csi2-dphy4";
		csi2_dphy5 = "/csi2-dphy5";
		csu = "/csu";
		display_subsystem = "/display-subsystem";
		route_dsi = "/display-subsystem/route/route-dsi";
		route_lvds = "/display-subsystem/route/route-lvds";
		route_rgb = "/display-subsystem/route/route-rgb";
		dmc = "/dmc";
		dmc_opp_table = "/dmc-opp-table";
		scmi = "/firmware/scmi";
		scmi_clk = "/firmware/scmi/protocol@14";
		optee = "/firmware/optee";
		mpp_srv = "/mpp-srv";
		mipi0_csi2 = "/mipi0-csi2";
		mipi1_csi2 = "/mipi1-csi2";
		mipi2_csi2 = "/mipi2-csi2";
		mipi3_csi2 = "/mipi3-csi2";
		reserved_memory = "/reserved-memory";
		drm_logo = "/reserved-memory/drm-logo@00000000";
		vendor_storage_rm = "/reserved-memory/vendor-storage-rm@00000000";
		drm_cubic_lut = "/reserved-memory/drm-cubic-lut@00000000";
		ramoops = "/reserved-memory/ramoops@110000";
		rkcif_mipi_lvds = "/rkcif-mipi-lvds";
		rkcif_mipi_lvds_sditf = "/rkcif-mipi-lvds-sditf";
		rkcif_mipi_lvds_sditf_vir1 = "/rkcif-mipi-lvds-sditf-vir1";
		rkcif_mipi_lvds_sditf_vir2 = "/rkcif-mipi-lvds-sditf-vir2";
		rkcif_mipi_lvds_sditf_vir3 = "/rkcif-mipi-lvds-sditf-vir3";
		rkcif_mipi_lvds1 = "/rkcif-mipi-lvds1";
		rkcif_mipi_lvds1_sditf = "/rkcif-mipi-lvds1-sditf";
		rkcif_mipi_lvds1_sditf_vir1 = "/rkcif-mipi-lvds1-sditf-vir1";
		rkcif_mipi_lvds1_sditf_vir2 = "/rkcif-mipi-lvds1-sditf-vir2";
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

## Regulatoren (Spannungsversorgung)
### `regulator-state-mem` (Zeile 1616-1619)
```dts
					regulator-state-mem {
						regulator-off-in-suspend;
						regulator-suspend-microvolt = <0xdbba0>;
					};
```

### `regulator-state-mem` (Zeile 1633-1635)
```dts
					regulator-state-mem {
						regulator-off-in-suspend;
					};
```

### `regulator-state-mem` (Zeile 1645-1647)
```dts
					regulator-state-mem {
						regulator-on-in-suspend;
					};
```

### `regulator-state-mem` (Zeile 1659-1662)
```dts
					regulator-state-mem {
						regulator-on-in-suspend;
						regulator-suspend-microvolt = <0x325aa0>;
					};
```

### `regulator-state-mem` (Zeile 1673-1676)
```dts
					regulator-state-mem {
						regulator-on-in-suspend;
						regulator-suspend-microvolt = <0x1b7740>;
					};
```

### `regulator-state-mem` (Zeile 1687-1689)
```dts
					regulator-state-mem {
						regulator-off-in-suspend;
					};
```

### `regulator-state-mem` (Zeile 1700-1703)
```dts
					regulator-state-mem {
						regulator-on-in-suspend;
						regulator-suspend-microvolt = <0xdbba0>;
					};
```

### `regulator-state-mem` (Zeile 1714-1716)
```dts
					regulator-state-mem {
						regulator-off-in-suspend;
					};
```

### `regulator-state-mem` (Zeile 1727-1729)
```dts
					regulator-state-mem {
						regulator-off-in-suspend;
					};
```

### `regulator-state-mem` (Zeile 1740-1743)
```dts
					regulator-state-mem {
						regulator-on-in-suspend;
						regulator-suspend-microvolt = <0x2dc6c0>;
					};
```

### `regulator-state-mem` (Zeile 1754-1756)
```dts
					regulator-state-mem {
						regulator-off-in-suspend;
					};
```

### `regulator-state-mem` (Zeile 1765-1767)
```dts
					regulator-state-mem {
						regulator-off-in-suspend;
					};
```

### `regulator-state-mem` (Zeile 1776-1778)
```dts
					regulator-state-mem {
						regulator-off-in-suspend;
					};
```

### `regulator-state-mem` (Zeile 1789-1791)
```dts
					regulator-state-mem {
						regulator-off-in-suspend;
					};
```

### `regulator-state-mem` (Zeile 1798-1800)
```dts
					regulator-state-mem {
						regulator-off-in-suspend;
					};
```

### `regulator-state-mem` (Zeile 6097-6099)
```dts
		regulator-state-mem {
			regulator-off-in-suspend;
		};
```

### `vbat-3v8` (Zeile 6154-6162)
```dts
	vbat-3v8 {
		compatible = "regulator-fixed";
		regulator-name = "vbat_3v8";
		regulator-always-on;
		regulator-boot-on;
		regulator-min-microvolt = <0x39fbc0>;
		regulator-max-microvolt = <0x39fbc0>;
		phandle = <0x2b6>;
	};
```

### `vcc-sd` (Zeile 6164-6176)
```dts
	vcc-sd {
		compatible = "regulator-gpio";
		enable-active-low;
		regulator-boot-on;
		gpios = <0x3d 0x05 0x01>;
		regulator-min-microvolt = <0x325aa0>;
		regulator-max-microvolt = <0x325aa0>;
		pinctrl-names = "default";
		pinctrl-0 = <0xea>;
		regulator-name = "vcc_sd";
		states = <0x00 0x00 0x325aa0 0x01>;
		phandle = <0xb1>;
	};
```

### `vcc-sys` (Zeile 6178-6186)
```dts
	vcc-sys {
		compatible = "regulator-fixed";
		regulator-name = "vcc_sys";
		regulator-always-on;
		regulator-boot-on;
		regulator-min-microvolt = <0x39fbc0>;
		regulator-max-microvolt = <0x39fbc0>;
		phandle = <0x44>;
	};
```

### `vdd-gpu` (Zeile 6188-6201)
```dts
	vdd-gpu {
		compatible = "pwm-regulator";
		pwms = <0xeb 0x00 0x1388 0x01>;
		regulator-name = "vdd_gpu";
		regulator-min-microvolt = "\0\f5";
		regulator-max-microvolt = <0x10c8e0>;
		regulator-init-microvolt = <0xdbba0>;
		regulator-always-on;
		regulator-boot-on;
		regulator-settling-time-up-us = <0xfa>;
		pwm-supply = <0x44>;
		status = "okay";
		phandle = <0x73>;
	};
```

### `vdd-npu` (Zeile 6203-6216)
```dts
	vdd-npu {
		compatible = "pwm-regulator";
		pwms = <0xec 0x00 0x1388 0x01>;
		regulator-name = "vdd_npu";
		regulator-min-microvolt = "\0\f5";
		regulator-max-microvolt = <0x10c8e0>;
		regulator-init-microvolt = <0xdbba0>;
		regulator-always-on;
		regulator-boot-on;
		regulator-settling-time-up-us = <0xfa>;
		pwm-supply = <0x44>;
		status = "disabled";
		phandle = <0x6e>;
	};
```

### `led-vcc` (Zeile 6218-6226)
```dts
	led-vcc {
		compatible = "regulator-fixed";
		regulator-name = "vcc-led";
		pinctrl-0 = <0xed>;
		pinctrl-names = "default";
		gpios = <0x3d 0x17 0x00>;
		enable-active-high;
		phandle = <0x2b7>;
	};
```

### `__symbols__` (Zeile 6356-7054)
```dts
	__symbols__ {
		xin32k = "/clocks/xin32k";
		xin24m = "/clocks/xin24m";
		hclk_vepu = "/clocks/hclk_vepu@ff100324";
		aclk_vdpu = "/clocks/aclk_vdpu@ff100328";
		aclk_vi_isp = "/clocks/aclk_vi_isp@ff10032c";
		aclk_vo = "/clocks/aclk_vo@ff100334";
		aclk_vepu = "/clocks/aclk_vepu@ff100324";
		aclk_rga_jdec = "/clocks/aclk_rga_jdec@ff100338";
		mclkin_sai0 = "/clocks/mclkin-sai0";
		mclkin_sai1 = "/clocks/mclkin-sai1";
		mclkin_sai2 = "/clocks/mclkin-sai2";
		mclkout_sai0 = "/clocks/mclkout-sai0@ff040070";
		mclkout_sai1 = "/clocks/mclkout-sai1@ff040070";
		mclkout_sai2 = "/clocks/mclkout-sai2@ff040070";
		cpu0 = "/cpus/cpu@0";
		cpu1 = "/cpus/cpu@1";
		cpu2 = "/cpus/cpu@2";
		cpu3 = "/cpus/cpu@3";
		CPU_SLEEP = "/cpus/idle-states/cpu-sleep";
		cpu0_opp_table = "/cpu0-opp-table";
		cpu_opp_j_od_1416000000 = "/cpu0-opp-table/opp-j-od-1416000000";
		cpu_opp_j_od_1608000000 = "/cpu0-opp-table/opp-j-od-1608000000";
		cpu_opp_j_od_1800000000 = "/cpu0-opp-table/opp-j-od-1800000000";
		arm_pmu = "/arm-pmu";
		csi2_dphy0 = "/csi2-dphy0";
		csi2_dphy1 = "/csi2-dphy1";
		csi2_dphy2 = "/csi2-dphy2";
		csi2_dphy3 = "/csi2-dphy3";
		csi2_dphy4 = "/csi2-dphy4";
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

## Pinctrl (Pin-Multiplexing)
### `aliases` (Zeile 10-51)
```dts
	aliases {
		csi2dphy0 = "/csi2-dphy0";
		csi2dphy1 = "/csi2-dphy1";
		csi2dphy2 = "/csi2-dphy2";
		csi2dphy3 = "/csi2-dphy3";
		csi2dphy4 = "/csi2-dphy4";
		csi2dphy5 = "/csi2-dphy5";
		ethernet0 = "/ethernet@ffa80000";
		ethernet1 = "/ethernet@ffb30000";
		gpio0 = "/pinctrl/gpio@ff260000";
		gpio1 = "/pinctrl/gpio@ff620000";
		gpio2 = "/pinctrl/gpio@ff630000";
		gpio3 = "/pinctrl/gpio@ffac0000";
		gpio4 = "/pinctrl/gpio@ffad0000";
		i2c0 = "/i2c@ff200000";
		i2c1 = "/i2c@ffa00000";
		i2c2 = "/i2c@ffa10000";
		i2c3 = "/i2c@ffa20000";
		i2c4 = "/i2c@ffa30000";
		i2c5 = "/i2c@ffa40000";
		rkcif_mipi_lvds0 = "/rkcif-mipi-lvds";
		rkcif_mipi_lvds1 = "/rkcif-mipi-lvds1";
		rkcif_mipi_lvds2 = "/rkcif-mipi-lvds2";
		rkcif_mipi_lvds3 = "/rkcif-mipi-lvds3";
		serial0 = "/serial@ff210000";
		serial1 = "/serial@ff670000";
		serial2 = "/serial@ff680000";
		serial3 = "/serial@ff690000";
		serial4 = "/serial@ff6a0000";
		serial5 = "/serial@ff6b0000";
		serial6 = "/serial@ff6c0000";
		serial7 = "/serial@ff6d0000";
		serial8 = "/serial@ff6e0000";
		serial9 = "/serial@ff6f0000";
		spi0 = "/spi@ff220000";
		spi1 = "/spi@ff640000";
		spi2 = "/spi@ff650000";
		spi3 = "/spi@ff860000";
		mmc0 = "/mmc@ff870000";
		mmc1 = "/mmc@ff880000";
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `rgb` (Zeile 1457-1490)
```dts
		rgb {
			compatible = "rockchip,rk3562-rgb";
			pinctrl-names = "default";
			pinctrl-0 = <0x3a>;
			status = "okay";
			phandle = <0x159>;

			ports {
				#address-cells = <0x01>;
				#size-cells = <0x00>;

				port@0 {
					reg = <0x00>;
					#address-cells = <0x01>;
					#size-cells = <0x00>;

					endpoint@0 {
						reg = <0x00>;
						remote-endpoint = <0x1d>;
						status = "okay";
						phandle = <0x7e>;
					};
				};

				port@1 {
					reg = <0x01>;

					endpoint {
						remote-endpoint = <0x3b>;
						phandle = <0xc4>;
					};
				};
			};
		};
```

### `pinctrl_rk8xx` (Zeile 1561-1601)
```dts
			pinctrl_rk8xx {
				gpio-controller;
				#gpio-cells = <0x02>;
				phandle = <0x15c>;

				rk817_slppin_null {
					pins = "gpio_slp";
					function = "pin_fun0";
					phandle = <0x15d>;
				};

				rk817_slppin_slp {
					pins = "gpio_slp";
					function = "pin_fun1";
					phandle = <0x40>;
				};

				rk817_slppin_pwrdn {
					pins = "gpio_slp";
					function = "pin_fun2";
					phandle = <0x42>;
				};

				rk817_slppin_rst {
					pins = "gpio_slp";
					function = "pin_fun3";
					phandle = <0x43>;
				};

				rk817_ts_gpio1 {
					pins = "gpio_ts";
					function = "pin_fun1";
					phandle = <0x15e>;
				};

				rk817_pin_ts {
					pins = "gpio_ts";
					function = "pin_fun0";
					phandle = <0x15f>;
				};
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `codec` (Zeile 1804-1822)
```dts
			codec {
				#sound-dai-cells = <0x00>;
				compatible = "rockchip,rk817-codec";
				clocks = <0x46>;
				clock-names = "mclk";
				assigned-clocks = <0x46>;
				assigned-clock-rates = <0xbb8000>;
				pinctrl-names = "default";
				pinctrl-0 = <0x47 0x48>;
				hp-volume = <0x3c>;
				spk-volume = <0x03>;
				mic-in-differential;
				status = "okay";
				use-ext-amplifier;
				hp2extamplifier;
				hp-mute-delay-ms = <0x64>;
				hp-ctl-gpios = <0x49 0x13 0x00>;
				phandle = <0xe4>;
			};
```

### `battery` (Zeile 1824-1846)
```dts
			battery {
				compatible = "rk817,battery";
				ocv_table = <0xdac 0xdc9 0xdf2 0xe15 0xe3c 0xe67 0xe9a 0xecd 0xeef 0xf07 0xf1f 0xf3f 0xf56 0xf75 0xf9f 0xfbb 0xfc4 0xfc9 0xfd6 0xffa 0x104f>;
				design_capacity = <0xb5a>;
				design_qmax = <0xc7d>;
				bat_res = <0x66>;
				sleep_enter_current = <0x12c>;
				sleep_exit_current = <0x12c>;
				sleep_filter_current = <0x64>;
				power_off_thresd = <0xdac>;
				zero_algorithm_vol = <0xf0a>;
				max_soc_offset = <0x3c>;
				monitor_sec = <0x05>;
				sample_res = <0x0a>;
				virtual_power = <0x00>;
				pinctrl-names = "default";
				pinctrl-0 = <0x4a>;
				charge_red_gpio = <0x49 0x01 0x00>;
				charge_green_gpio = <0x49 0x00 0x00>;
				moto_gpio = <0x49 0x07 0x00>;
				moto_r_gpio = <0x49 0x08 0x00>;
				phandle = <0x169>;
			};
```

### `spi@ff220000` (Zeile 1878-1893)
```dts
	spi@ff220000 {
		compatible = "rockchip,rk3066-spi";
		reg = <0x00 0xff220000 0x00 0x1000>;
		interrupts = <0x00 0x34 0x04>;
		#address-cells = <0x01>;
		#size-cells = <0x00>;
		clocks = <0x02 0x12d 0x02 0x12c 0x02 0x12e>;
		clock-names = "spiclk\0apb_pclk\0sclk_in";
		dmas = <0x4c 0x0d 0x4c 0x0c>;
		dma-names = "tx\0rx";
		pinctrl-names = "default";
		pinctrl-0 = <0x4d 0x4e 0x4f>;
		num-cs = <0x02>;
		status = "disabled";
		phandle = <0x16b>;
	};
```

### `pwm@ff230000` (Zeile 1895-1906)
```dts
	pwm@ff230000 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff230000 0x00 0x10>;
		interrupts = <0x00 0x14 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x50>;
		clocks = <0x02 0x130 0x02 0x12f>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x16c>;
	};
```

### `pwm@ff230010` (Zeile 1908-1919)
```dts
	pwm@ff230010 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff230010 0x00 0x10>;
		interrupts = <0x00 0x14 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x51>;
		clocks = <0x02 0x130 0x02 0x12f>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x16d>;
	};
```

### `pwm@ff230020` (Zeile 1921-1932)
```dts
	pwm@ff230020 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff230020 0x00 0x10>;
		interrupts = <0x00 0x14 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x52>;
		clocks = <0x02 0x130 0x02 0x12f>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x16e>;
	};
```

### `pwm@ff230030` (Zeile 1934-1945)
```dts
	pwm@ff230030 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff230030 0x00 0x10>;
		interrupts = <0x00 0x14 0x04 0x00 0x15 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x53>;
		clocks = <0x02 0x130 0x02 0x12f>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x16f>;
	};
```

### `spi@ff640000` (Zeile 2778-2793)
```dts
	spi@ff640000 {
		compatible = "rockchip,rk3066-spi";
		reg = <0x00 0xff640000 0x00 0x1000>;
		interrupts = <0x00 0x35 0x04>;
		#address-cells = <0x01>;
		#size-cells = <0x00>;
		clocks = <0x02 0xa1 0x02 0xa0 0x02 0xa2>;
		clock-names = "spiclk\0apb_pclk\0sclk_in";
		dmas = <0x4c 0x0f 0x4c 0x0e>;
		dma-names = "tx\0rx";
		pinctrl-names = "default";
		pinctrl-0 = <0x86 0x87 0x88>;
		num-cs = <0x02>;
		status = "disabled";
		phandle = <0x181>;
	};
```

### `spi@ff650000` (Zeile 2795-2810)
```dts
	spi@ff650000 {
		compatible = "rockchip,rk3066-spi";
		reg = <0x00 0xff650000 0x00 0x1000>;
		interrupts = <0x00 0x36 0x04>;
		#address-cells = <0x01>;
		#size-cells = <0x00>;
		clocks = <0x02 0xa4 0x02 0xa3 0x02 0xa5>;
		clock-names = "spiclk\0apb_pclk\0sclk_in";
		dmas = <0x4c 0x11 0x4c 0x10>;
		dma-names = "tx\0rx";
		pinctrl-names = "default";
		pinctrl-0 = <0x89 0x8a 0x8b>;
		num-cs = <0x02>;
		status = "disabled";
		phandle = <0x182>;
	};
```

### `serial@ff670000` (Zeile 2812-2825)
```dts
	serial@ff670000 {
		compatible = "rockchip,rk3562-uart\0snps,dw-apb-uart";
		reg = <0x00 0xff670000 0x00 0x100>;
		interrupts = <0x00 0x1f 0x04>;
		clocks = <0x02 0xb2 0x02 0xa6>;
		clock-names = "baudclk\0apb_pclk";
		reg-shift = <0x02>;
		reg-io-width = <0x04>;
		dmas = <0x4c 0x0a 0x4c 0x01>;
		status = "okay";
		pinctrl-names = "default";
		pinctrl-0 = <0x8c>;
		phandle = <0x183>;
	};
```

### `pwm@ff700000` (Zeile 2931-2942)
```dts
	pwm@ff700000 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff700000 0x00 0x10>;
		interrupts = <0x00 0x16 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x8d>;
		clocks = <0x02 0xd4 0x02 0xd3>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x18c>;
	};
```

### `pwm@ff700010` (Zeile 2944-2955)
```dts
	pwm@ff700010 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff700010 0x00 0x10>;
		interrupts = <0x00 0x16 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x8e>;
		clocks = <0x02 0xd4 0x02 0xd3>;
		clock-names = "pwm\0pclk";
		status = "okay";
		phandle = <0xde>;
	};
```

### `pwm@ff700020` (Zeile 2957-2968)
```dts
	pwm@ff700020 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff700020 0x00 0x10>;
		interrupts = <0x00 0x16 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x8f>;
		clocks = <0x02 0xd4 0x02 0xd3>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0xec>;
	};
```

### `pwm@ff700030` (Zeile 2970-2981)
```dts
	pwm@ff700030 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff700030 0x00 0x10>;
		interrupts = <0x00 0x16 0x04 0x00 0x17 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x90>;
		clocks = <0x02 0xd4 0x02 0xd3>;
		clock-names = "pwm\0pclk";
		status = "okay";
		phandle = <0xeb>;
	};
```

### `pwm@ff710000` (Zeile 2983-2994)
```dts
	pwm@ff710000 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff710000 0x00 0x10>;
		interrupts = <0x00 0x18 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x91>;
		clocks = <0x02 0xd7 0x02 0xd6>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x18d>;
	};
```

### `pwm@ff710010` (Zeile 2996-3007)
```dts
	pwm@ff710010 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff710010 0x00 0x10>;
		interrupts = <0x00 0x18 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x92>;
		clocks = <0x02 0xd7 0x02 0xd6>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x18e>;
	};
```

### `pwm@ff710020` (Zeile 3009-3020)
```dts
	pwm@ff710020 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff710020 0x00 0x10>;
		interrupts = <0x00 0x18 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x93>;
		clocks = <0x02 0xd7 0x02 0xd6>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x18f>;
	};
```

### `pwm@ff710030` (Zeile 3022-3033)
```dts
	pwm@ff710030 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff710030 0x00 0x10>;
		interrupts = <0x00 0x18 0x04 0x00 0x19 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x94>;
		clocks = <0x02 0xd7 0x02 0xd6>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x190>;
	};
```

### `pwm@ff720000` (Zeile 3035-3046)
```dts
	pwm@ff720000 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff720000 0x00 0x10>;
		interrupts = <0x00 0x1a 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x95>;
		clocks = <0x02 0xda 0x02 0xd9>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x191>;
	};
```

### `pwm@ff720010` (Zeile 3048-3059)
```dts
	pwm@ff720010 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff720010 0x00 0x10>;
		interrupts = <0x00 0x1a 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x96>;
		clocks = <0x02 0xda 0x02 0xd9>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x192>;
	};
```

### `pwm@ff720020` (Zeile 3061-3072)
```dts
	pwm@ff720020 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff720020 0x00 0x10>;
		interrupts = <0x00 0x1a 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x97>;
		clocks = <0x02 0xda 0x02 0xd9>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x193>;
	};
```

### `pwm@ff720030` (Zeile 3074-3085)
```dts
	pwm@ff720030 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff720030 0x00 0x10>;
		interrupts = <0x00 0x1a 0x04 0x00 0x1b 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x98>;
		clocks = <0x02 0xda 0x02 0xd9>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x194>;
	};
```

### `sai@ff800000` (Zeile 3146-3164)
```dts
	sai@ff800000 {
		compatible = "rockchip,rk3562-sai\0rockchip,sai-v1";
		reg = <0x00 0xff800000 0x00 0x1000>;
		interrupts = <0x00 0x4e 0x04>;
		clocks = <0x02 0x78 0x02 0x74>;
		clock-names = "mclk\0hclk";
		assigned-clocks = <0x02 0x75>;
		assigned-clock-parents = <0x02 0x04>;
		dmas = <0x4c 0x13 0x4c 0x12>;
		dma-names = "tx\0rx";
		resets = <0x02 0xc0023 0x02 0xc0020>;
		reset-names = "m\0h";
		pinctrl-names = "default";
		pinctrl-0 = <0x9d 0x9e 0x9f 0xa0>;
		#sound-dai-cells = <0x00>;
		sound-name-prefix = "SAI0";
		status = "okay";
		phandle = <0xe3>;
	};
```

### `sai@ff810000` (Zeile 3166-3184)
```dts
	sai@ff810000 {
		compatible = "rockchip,rk3562-sai\0rockchip,sai-v1";
		reg = <0x00 0xff810000 0x00 0x1000>;
		interrupts = <0x00 0x4f 0x04>;
		clocks = <0x02 0x7e 0x02 0x7a>;
		clock-names = "mclk\0hclk";
		assigned-clocks = <0x02 0x7b>;
		assigned-clock-parents = <0x02 0x04>;
		dmas = <0x4c 0x15 0x4c 0x14>;
		dma-names = "tx\0rx";
		resets = <0x02 0xc0028 0x02 0xc0025>;
		reset-names = "m\0h";
		pinctrl-names = "default";
		pinctrl-0 = <0xa1 0xa2 0xa3 0xa4>;
		#sound-dai-cells = <0x00>;
		sound-name-prefix = "SAI1";
		status = "okay";
		phandle = <0xe6>;
	};
```

### `sai@ff820000` (Zeile 3186-3204)
```dts
	sai@ff820000 {
		compatible = "rockchip,rk3562-sai\0rockchip,sai-v1";
		reg = <0x00 0xff820000 0x00 0x1000>;
		interrupts = <0x00 0x50 0x04>;
		clocks = <0x02 0x84 0x02 0x80>;
		clock-names = "mclk\0hclk";
		assigned-clocks = <0x02 0x81>;
		assigned-clock-parents = <0x02 0x04>;
		dmas = <0x4c 0x17 0x4c 0x16>;
		dma-names = "tx\0rx";
		resets = <0x02 0xc002d 0x02 0xc002a>;
		reset-names = "m\0h";
		pinctrl-names = "default";
		pinctrl-0 = <0xa5 0xa6 0xa7 0xa8>;
		#sound-dai-cells = <0x00>;
		sound-name-prefix = "SAI2";
		status = "disabled";
		phandle = <0x195>;
	};
```

### `pdm@ff830000` (Zeile 3206-3220)
```dts
	pdm@ff830000 {
		compatible = "rockchip,rk3562-pdm\0rockchip,rv1126-pdm";
		reg = <0x00 0xff830000 0x00 0x1000>;
		clocks = <0x02 0x89 0x02 0x88>;
		clock-names = "pdm_clk\0pdm_hclk";
		assigned-clocks = <0x02 0x89>;
		assigned-clock-parents = <0x02 0x04>;
		dmas = <0x4c 0x1f>;
		dma-names = "rx";
		pinctrl-names = "default";
		pinctrl-0 = <0xa9 0xaa 0xab 0xac 0xad 0xae>;
		#sound-dai-cells = <0x00>;
		status = "disabled";
		phandle = <0xdf>;
	};
```

### `spdif@ff840000` (Zeile 3222-3237)
```dts
	spdif@ff840000 {
		compatible = "rockchip,rk3562-spdif\0rockchip,rk3568-spdif";
		reg = <0x00 0xff840000 0x00 0x1000>;
		interrupts = <0x00 0x7f 0x04>;
		dmas = <0x4c 0x1e>;
		dma-names = "tx";
		clock-names = "mclk\0hclk";
		clocks = <0x02 0x8e 0x02 0x8a>;
		assigned-clocks = <0x02 0x8b>;
		assigned-clock-parents = <0x02 0x04>;
		#sound-dai-cells = <0x00>;
		pinctrl-names = "default";
		pinctrl-0 = <0xaf>;
		status = "disabled";
		phandle = <0xe1>;
	};
```

### `dsm@ff850000` (Zeile 3239-3252)
```dts
	dsm@ff850000 {
		compatible = "rockchip,rk3562-dsm";
		reg = <0x00 0xff850000 0x00 0x1000>;
		clocks = <0x02 0x87 0x02 0x86>;
		clock-names = "dac\0pclk";
		resets = <0x02 0xc0032>;
		reset-names = "reset";
		rockchip,grf = <0x9b>;
		pinctrl-names = "default";
		pinctrl-0 = <0xb0>;
		#sound-dai-cells = <0x00>;
		status = "disabled";
		phandle = <0x196>;
	};
```

### `mmc@ff880000` (Zeile 3288-3311)
```dts
	mmc@ff880000 {
		compatible = "rockchip,rk3562-dw-mshc\0rockchip,rk3288-dw-mshc";
		reg = <0x00 0xff880000 0x00 0x10000>;
		interrupts = <0x00 0x38 0x04>;
		max-frequency = <0xbebc200>;
		clocks = <0x02 0x8f 0x02 0x90 0x02 0x93 0x02 0x94>;
		clock-names = "biu\0ciu\0ciu-drive\0ciu-sample";
		resets = <0x02 0xc0040>;
		reset-names = "reset";
		fifo-depth = <0x100>;
		status = "okay";
		no-sdio;
		no-mmc;
		bus-width = <0x04>;
		cap-mmc-highspeed;
		cap-sd-highspeed;
		disable-wp;
		sd-uhs-sdr104;
		vmmc-supply = <0xb1>;
		vqmmc-supply = <0xb2>;
		pinctrl-names = "default";
		pinctrl-0 = <0xb3 0xb4 0xb5 0xb6>;
		phandle = <0x199>;
	};
```

### `mmc@ff890000` (Zeile 3313-3339)
```dts
	mmc@ff890000 {
		compatible = "rockchip,rk3562-dw-mshc\0rockchip,rk3288-dw-mshc";
		reg = <0x00 0xff890000 0x00 0x10000>;
		interrupts = <0x00 0x39 0x04>;
		max-frequency = <0xbebc200>;
		clocks = <0x02 0x91 0x02 0x92 0x02 0x95 0x02 0x96>;
		clock-names = "biu\0ciu\0ciu-drive\0ciu-sample";
		resets = <0x02 0xc0042>;
		reset-names = "reset";
		fifo-depth = <0x100>;
		status = "okay";
		no-sd;
		no-mmc;
		supports-sdio;
		bus-width = <0x04>;
		disable-wp;
		cap-sd-highspeed;
		cap-sdio-irq;
		keep-power-in-suspend;
		supports-aic8800DL;
		mmc-pwrseq = <0xb7>;
		broken-cd;
		pinctrl-names = "default";
		pinctrl-0 = <0xb8 0xb9 0xba>;
		sd-uhs-sdr104;
		phandle = <0x19a>;
	};
```

### `i2c@ffa00000` (Zeile 3521-3533)
```dts
	i2c@ffa00000 {
		compatible = "rockchip,rk3562-i2c\0rockchip,rk3399-i2c";
		reg = <0x00 0xffa00000 0x00 0x1000>;
		clocks = <0x02 0x20 0x02 0x1a>;
		clock-names = "i2c\0pclk";
		interrupts = <0x00 0x0d 0x04>;
		pinctrl-names = "default";
		pinctrl-0 = <0xbb>;
		#address-cells = <0x01>;
		#size-cells = <0x00>;
		status = "disabled";
		phandle = <0x1a0>;
	};
```

### `husb311@4e` (Zeile 3548-3584)
```dts
		husb311@4e {
			compatible = "hynetek,husb311";
			reg = <0x4e>;
			interrupt-parent = <0x3d>;
			interrupts = <0x0f 0x08>;
			pinctrl-names = "default";
			pinctrl-0 = <0xbd>;
			vbus-supply = <0xbe>;
			status = "okay";
			phandle = <0x4b>;

			ports {
				#address-cells = <0x01>;
				#size-cells = <0x00>;

				port@0 {
					reg = <0x00>;

					endpoint@0 {
						remote-endpoint = <0xbf>;
						phandle = <0x36>;
					};
				};
			};

			connector {
				compatible = "usb-c-connector";
				label = "USB-C";
				data-role = "dual";
				power-role = "dual";
				try-power-role = "sink";
				op-sink-microwatt = <0xf4240>;
				sink-pdos = <0x401912c>;
				source-pdos = <0x260190c8>;
				phandle = <0x1a2>;
			};
		};
```

### `i2c@ffa20000` (Zeile 3587-3599)
```dts
	i2c@ffa20000 {
		compatible = "rockchip,rk3562-i2c\0rockchip,rk3399-i2c";
		reg = <0x00 0xffa20000 0x00 0x1000>;
		clocks = <0x02 0x22 0x02 0x1c>;
		clock-names = "i2c\0pclk";
		interrupts = <0x00 0x0f 0x04>;
		pinctrl-names = "default";
		pinctrl-0 = <0xc0>;
		#address-cells = <0x01>;
		#size-cells = <0x00>;
		status = "disabled";
		phandle = <0x1a3>;
	};
```

### `rk628@50` (Zeile 3615-3641)
```dts
		rk628@50 {
			status = "okay";
			compatible = "rockchip,rk628";
			reg = <0x50>;
			#sound-dai-cells = <0x00>;
			interrupt-parent = <0x49>;
			interrupts = <0x12 0x04>;
			enable-gpios = <0x49 0x10 0x00>;
			reset-gpios = <0x49 0x11 0x01>;
			pinctrl-names = "default";
			pinctrl-0 = <0xc2 0xc3>;
			assigned-clocks = <0x02 0x132>;
			assigned-clock-rates = <0x16e3600>;
			clocks = <0x02 0x132>;
			clock-names = "soc_24M";
			rk628-rgb-in;
			rk628-hdmi-out;
			phandle = <0xe7>;

			port {

				endpoint {
					remote-endpoint = <0xc4>;
					phandle = <0x3b>;
				};
			};
		};
```

### `i2c@ffa40000` (Zeile 3644-3656)
```dts
	i2c@ffa40000 {
		compatible = "rockchip,rk3562-i2c\0rockchip,rk3399-i2c";
		reg = <0x00 0xffa40000 0x00 0x1000>;
		clocks = <0x02 0x24 0x02 0x1e>;
		clock-names = "i2c\0pclk";
		interrupts = <0x00 0x11 0x04>;
		pinctrl-names = "default";
		pinctrl-0 = <0xc5>;
		#address-cells = <0x01>;
		#size-cells = <0x00>;
		status = "disabled";
		phandle = <0x1a5>;
	};
```

### `panel@0` (Zeile 3819-3878)
```dts
		panel@0 {
			status = "okay";
			compatible = "simple-panel-dsi";
			reg = <0x00>;
			backlight = <0xce>;
			reset-delay-ms = <0x14>;
			enable-delay-ms = <0x78>;
			prepare-delay-ms = <0x14>;
			unprepare-delay-ms = <0x14>;
			disable-delay-ms = <0x14>;
			width-mm = <0x44>;
			height-mm = <0x79>;
			dsi,flags = <0xa03>;
			dsi,format = <0x00>;
			dsi,lanes = <0x04>;
			panel-init-sequence = [15 00 02 ee 01 15 00 02 ea 07 15 00 02 eb 12 15 00 02 0a 5e 15 00 02 13 14 15 00 02 17 35 15 00 02 1d 33 15 00 02 21 01 15 00 02 28 28 15 00 02 29 18 15 00 02 2a 63 15 00 02 2f f3 15 00 02 ee 02 15 00 02 39 a9 15 00 02 00 00 15 00 02 01 0d 15 00 02 02 12 15 00 02 03 08 15 00 02 04 0e 15 00 02 05 30 15 00 02 06 0b 15 00 02 07 0e 15 00 02 08 0f 15 00 02 09 0e 15 00 02 0a 11 15 00 02 0b 4e 15 00 02 0c 14 15 00 02 0d 1a 15 00 02 0e 2f 15 00 02 0f 36 15 00 02 10 3f 15 00 02 20 00 15 00 02 21 0d 15 00 02 22 12 15 00 02 23 08 15 00 02 24 0e 15 00 02 25 30 15 00 02 26 0b 15 00 02 27 0e 15 00 02 28 0f 15 00 02 29 0e 15 00 02 2a 11 15 00 02 2b 4e 15 00 02 2c 14 15 00 02 2d 1a 15 00 02 2e 2f 15 00 02 2f 36 15 00 02 30 3f 15 00 02 ee 04 15 00 02 00 05 15 00 02 01 01 15 00 02 02 80 15 00 02 03 04 15 00 02 04 00 15 00 02 06 06 15 00 02 07 05 15 00 02 08 1a 15 00 02 09 20 15 00 02 0a 0e 15 00 02 0b 00 15 00 02 20 40 15 00 02 24 08 15 00 02 ee 05 15 00 02 00 01 15 00 02 01 09 15 00 02 02 05 15 00 02 03 05 15 00 02 07 05 15 00 02 08 0d 15 00 02 09 00 15 00 02 0a 12 15 00 02 0b 14 15 00 02 0c 66 15 00 02 10 03 15 00 02 11 07 15 00 02 12 05 15 00 02 13 05 15 00 02 19 12 15 00 02 1a f6 15 00 02 40 55 15 00 02 41 00 15 00 02 43 03 15 00 02 44 01 15 00 02 45 81 15 00 02 46 06 15 00 02 47 00 15 00 02 ee 06 15 00 02 00 45 15 00 02 02 01 15 00 02 04 88 15 00 02 06 cd 15 00 02 08 ef 15 00 02 09 cd 15 00 02 0a ab 15 00 02 0b 89 15 00 02 0c 67 15 00 02 0d 45 15 00 02 0e 23 15 00 02 0f 01 15 00 02 ee 07 15 00 02 00 3c 15 00 02 01 3c 15 00 02 02 3c 15 00 02 03 3c 15 00 02 04 0d 15 00 02 05 3c 15 00 02 06 3c 15 00 02 07 3c 15 00 02 08 08 15 00 02 09 10 15 00 02 0a 12 15 00 02 0b 14 15 00 02 0c 16 15 00 02 0d 18 15 00 02 0e 1a 15 00 02 0f 1c 15 00 02 10 1e 15 00 02 11 04 15 00 02 12 00 15 00 02 13 3c 15 00 02 14 0c 15 00 02 15 3c 15 00 02 20 3c 15 00 02 21 3c 15 00 02 22 3c 15 00 02 23 3c 15 00 02 24 0d 15 00 02 25 3c 15 00 02 26 3c 15 00 02 27 3c 15 00 02 28 08 15 00 02 29 11 15 00 02 2a 13 15 00 02 2b 15 15 00 02 2c 17 15 00 02 2d 19 15 00 02 2e 1b 15 00 02 2f 1d 15 00 02 30 1f 15 00 02 31 05 15 00 02 32 01 15 00 02 33 3c 15 00 02 34 0c 15 00 02 35 3c 15 00 02 ee 08 15 00 02 10 00 15 00 02 12 dc 15 00 02 13 1c 15 00 02 17 23 15 00 02 18 20 15 00 02 20 80 15 00 02 ee 0f 15 00 02 00 01 15 00 02 01 00 15 00 02 ee 00 15 00 02 ea 00 15 00 02 eb 00 15 00 02 36 00 05 c8 01 11 05 14 01 29];
			panel-exit-sequence = <0x5000128 0x5000110>;
			enable-gpios = <0x3d 0x08 0x00>;
			reset-gpios = <0x3d 0x14 0x01>;
			pinctrl-names = "default";
			pinctrl-0 = <0xcf 0xd0>;
			init-delay-ms = <0x14>;
			phandle = <0x1ad>;

			display-timings {
				native-mode = <0xd1>;
				phandle = <0x1ae>;

				timing0 {
					clock-frequency = <0x3a2c940>;
					hactive = <0x400>;
					vactive = <0x300>;
					hfront-porch = <0x5a>;
					hsync-len = <0x50>;
					hback-porch = <0x50>;
					vfront-porch = <0x10>;
					vsync-len = <0x08>;
					vback-porch = <0x08>;
					hsync-active = <0x00>;
					vsync-active = <0x00>;
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `pinctrl` (Zeile 3919-6002)
```dts
	pinctrl {
		compatible = "rockchip,rk3562-pinctrl";
		rockchip,grf = <0x7d>;
		#address-cells = <0x02>;
		#size-cells = <0x02>;
		ranges;
		phandle = <0xd3>;

		gpio@ff260000 {
			compatible = "rockchip,gpio-bank";
			reg = <0x00 0xff260000 0x00 0x100>;
			interrupts = <0x00 0x00 0x04>;
			clocks = <0x02 0x11d 0x02 0x11e>;
			gpio-controller;
			#gpio-cells = <0x02>;
			gpio-ranges = <0xd3 0x00 0x00 0x20>;
			interrupt-controller;
			#interrupt-cells = <0x02>;
			phandle = <0x3d>;
		};

		gpio@ff620000 {
			compatible = "rockchip,gpio-bank";
			reg = <0x00 0xff620000 0x00 0x100>;
			interrupts = <0x00 0x02 0x04>;
			clocks = <0x02 0x100 0x02 0x103>;
			gpio-controller;
			#gpio-cells = <0x02>;
			gpio-ranges = <0xd3 0x00 0x20 0x20>;
			interrupt-controller;
			#interrupt-cells = <0x02>;
			phandle = <0xf4>;
		};

		gpio@ff630000 {
			compatible = "rockchip,gpio-bank";
			reg = <0x00 0xff630000 0x00 0x100>;
			interrupts = <0x00 0x04 0x04>;
			clocks = <0x02 0x101 0x02 0x104>;
			gpio-controller;
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `rk817-sound` (Zeile 6102-6124)
```dts
	rk817-sound {
		status = "okay";
		compatible = "rockchip,multicodecs-card";
		rockchip,card-name = "rockchip-rk817";
		hp-det-gpio = <0x3d 0x07 0x00>;
		io-channels = <0xdd 0x04>;
		io-channel-names = "adc-detect";
		keyup-threshold-microvolt = <0x1b7740>;
		poll-interval = <0x64>;
		rockchip,format = "i2s";
		rockchip,mclk-fs = <0x100>;
		rockchip,cpu = <0xe3>;
		rockchip,codec = <0xe4>;
		pinctrl-names = "default";
		pinctrl-0 = <0xe5>;
		phandle = <0x2b4>;

		play-pause-key {
			label = "playpause";
			linux,code = <0xa4>;
			press-threshold-microvolt = <0x7d0>;
		};
	};
```

### `sdio-pwrseq` (Zeile 6143-6152)
```dts
	sdio-pwrseq {
		compatible = "mmc-pwrseq-simple";
		clocks = <0xe8 0x01>;
		clock-names = "ext_clock";
		pinctrl-names = "default";
		pinctrl-0 = <0xe9>;
		post-power-on-delay-ms = <0xc8>;
		reset-gpios = <0x3d 0x0b 0x01>;
		phandle = <0xb7>;
	};
```

### `vcc-sd` (Zeile 6164-6176)
```dts
	vcc-sd {
		compatible = "regulator-gpio";
		enable-active-low;
		regulator-boot-on;
		gpios = <0x3d 0x05 0x01>;
		regulator-min-microvolt = <0x325aa0>;
		regulator-max-microvolt = <0x325aa0>;
		pinctrl-names = "default";
		pinctrl-0 = <0xea>;
		regulator-name = "vcc_sd";
		states = <0x00 0x00 0x325aa0 0x01>;
		phandle = <0xb1>;
	};
```

### `led-vcc` (Zeile 6218-6226)
```dts
	led-vcc {
		compatible = "regulator-fixed";
		regulator-name = "vcc-led";
		pinctrl-0 = <0xed>;
		pinctrl-names = "default";
		gpios = <0x3d 0x17 0x00>;
		enable-active-high;
		phandle = <0x2b7>;
	};
```

### `wireless-wlan` (Zeile 6228-6238)
```dts
	wireless-wlan {
		compatible = "wlan-platdata";
		rockchip,grf = <0x0e>;
		wifi_chip_type = "aic8800DL";
		pinctrl-names = "default";
		pinctrl-0 = <0xee 0xef>;
		WIFI,host_wake_irq = <0x3d 0x0c 0x00>;
		WIFI,poweren_gpio = <0x3d 0x06 0x01>;
		sdio_vref = <0x708>;
		status = "okay";
	};
```

### `fiq-debugger` (Zeile 6274-6284)
```dts
	fiq-debugger {
		compatible = "rockchip,fiq-debugger";
		rockchip,serial-id = <0x00>;
		rockchip,wake-irq = <0x00>;
		rockchip,irq-mode-enable = <0x01>;
		rockchip,baudrate = <0x16e360>;
		interrupts = <0x00 0xf2 0x04>;
		pinctrl-names = "default";
		pinctrl-0 = <0xf0>;
		status = "okay";
	};
```

### `play_joystick` (Zeile 6286-6354)
```dts
	play_joystick {
		compatible = "play_joystick";
		io-channels = <0xdd 0x02 0xdd 0x03 0xdd 0x05 0xdd 0x06 0xf1 0x01 0xf1 0x04 0xf1 0x00 0xf1 0x02 0xf1 0x03 0xf1 0x05 0xf1 0x06 0xf1 0x07>;
		io-channel-names = "button0\0button1\0button2\0button3\0l2-abs\0r2-abs\0left-key\0right-key\0down-key\0b-key\0x-key\0y-key";
		joysticks_numbers = <0x02>;
		l_x_swap;
		l_y_swap;
		axis-min-value-mv = <0xfa>;
		axis-max-value-mv = <0x60e>;
		axis-dead-zone-l = <0x316>;
		axis-dead-zone-h = <0x3f2>;
		axis-division-value = <0x3c>;
		keyup-threshold-microvolt = <0x1b7740>;
		poll-interval = <0x10>;
		debounce-interval = <0x64>;
		pinctrl-names = "default";
		pinctrl-0 = <0xf2 0xf3>;
		moto-gpio = <0x49 0x07 0x00>;
		moto-r-gpio = <0x49 0x08 0x00>;
		gpio-key-num = <0x0a>;
		key-gpios = <0xf4 0x17 0x01 0xf4 0x18 0x01 0xf4 0x1d 0x01 0xf4 0x1e 0x01 0xf4 0x1b 0x01 0xf4 0x1f 0x01 0xf4 0x1c 0x01 0x3d 0x15 0x01 0x3d 0x16 0x01>;
		key-gpios-map = <0x136 0x220 0x137 0x131 0x13a 0x13b 0x1d0 0x13d 0x13e>;
		l2-r2-min-value-mv = <0x32>;
		l2-r2-max-value-mv = <0x320>;
		l2-r2-division-value-mv = <0x4b>;
		l2_r2_abs;

		left-key {
			label = "left-key";
			adc-chan = <0x00>;
			linux,code = <0x222>;
			press-threshold-microvolt = <0x927c0>;
		};

		right-key {
			label = "right-key";
			adc-chan = <0x02>;
			linux,code = <0x223>;
			press-threshold-microvolt = <0x927c0>;
		};
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `__symbols__` (Zeile 6356-7054)
```dts
	__symbols__ {
		xin32k = "/clocks/xin32k";
		xin24m = "/clocks/xin24m";
		hclk_vepu = "/clocks/hclk_vepu@ff100324";
		aclk_vdpu = "/clocks/aclk_vdpu@ff100328";
		aclk_vi_isp = "/clocks/aclk_vi_isp@ff10032c";
		aclk_vo = "/clocks/aclk_vo@ff100334";
		aclk_vepu = "/clocks/aclk_vepu@ff100324";
		aclk_rga_jdec = "/clocks/aclk_rga_jdec@ff100338";
		mclkin_sai0 = "/clocks/mclkin-sai0";
		mclkin_sai1 = "/clocks/mclkin-sai1";
		mclkin_sai2 = "/clocks/mclkin-sai2";
		mclkout_sai0 = "/clocks/mclkout-sai0@ff040070";
		mclkout_sai1 = "/clocks/mclkout-sai1@ff040070";
		mclkout_sai2 = "/clocks/mclkout-sai2@ff040070";
		cpu0 = "/cpus/cpu@0";
		cpu1 = "/cpus/cpu@1";
		cpu2 = "/cpus/cpu@2";
		cpu3 = "/cpus/cpu@3";
		CPU_SLEEP = "/cpus/idle-states/cpu-sleep";
		cpu0_opp_table = "/cpu0-opp-table";
		cpu_opp_j_od_1416000000 = "/cpu0-opp-table/opp-j-od-1416000000";
		cpu_opp_j_od_1608000000 = "/cpu0-opp-table/opp-j-od-1608000000";
		cpu_opp_j_od_1800000000 = "/cpu0-opp-table/opp-j-od-1800000000";
		arm_pmu = "/arm-pmu";
		csi2_dphy0 = "/csi2-dphy0";
		csi2_dphy1 = "/csi2-dphy1";
		csi2_dphy2 = "/csi2-dphy2";
		csi2_dphy3 = "/csi2-dphy3";
		csi2_dphy4 = "/csi2-dphy4";
		csi2_dphy5 = "/csi2-dphy5";
		csu = "/csu";
		display_subsystem = "/display-subsystem";
		route_dsi = "/display-subsystem/route/route-dsi";
		route_lvds = "/display-subsystem/route/route-lvds";
		route_rgb = "/display-subsystem/route/route-rgb";
		dmc = "/dmc";
		dmc_opp_table = "/dmc-opp-table";
		scmi = "/firmware/scmi";
		scmi_clk = "/firmware/scmi/protocol@14";
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

## Kurze GPIO-Referenzliste (alle `&gpioX ...`)
_Keine gefunden._
