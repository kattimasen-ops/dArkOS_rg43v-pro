# Porting-Notizen: sig_offset_8456742
Quelle: `sig_offset_8456742.dts`  
Gefundene Knoten insgesamt: 882

## SoC / Board (Root-Eigenschaften)
- **compatible** = "rockchip,rk3562-evb1-lp4x-v10\0rockchip,rk3562"
- **model** = "Rockchip RK3562 EVB1 LP4X V10 Board"

## Speicher (memory-Knoten)
_Nichts gefunden._

## CPU / OPP-Tabelle (Taktstufen)
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
			phandle = <0xfb>;
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
			phandle = <0xfc>;
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
			phandle = <0xfd>;
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

### `opp-300000000` (Zeile 2053-2057)
```dts
		opp-300000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x11e1a300>;
			opp-microvolt = <0xc96a8 0xc96a8 0xf4240>;
		};
```

### `opp-400000000` (Zeile 2059-2063)
```dts
		opp-400000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x17d78400>;
			opp-microvolt = <0xc96a8 0xc96a8 0xf4240>;
		};
```

### `opp-500000000` (Zeile 2065-2069)
```dts
		opp-500000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x1dcd6500>;
			opp-microvolt = <0xc96a8 0xc96a8 0xf4240>;
		};
```

### `opp-600000000` (Zeile 2071-2080)
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

### `opp-700000000` (Zeile 2082-2091)
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

### `opp-800000000` (Zeile 2093-2102)
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

### `opp-900000000` (Zeile 2104-2113)
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

### `opp-1000000000` (Zeile 2115-2124)
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

### `opp-j-300000000` (Zeile 2126-2130)
```dts
		opp-j-300000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x11e1a300>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
		};
```

### `opp-j-400000000` (Zeile 2132-2136)
```dts
		opp-j-400000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x17d78400>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
		};
```

### `opp-j-500000000` (Zeile 2138-2142)
```dts
		opp-j-500000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x1dcd6500>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
		};
```

### `opp-j-600000000` (Zeile 2144-2148)
```dts
		opp-j-600000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x23c34600>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
		};
```

### `opp-j-700000000` (Zeile 2150-2155)
```dts
		opp-j-700000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x29b92700>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
			opp-microvolt-L0 = <0xe1d48 0xe1d48 0xf4240>;
		};
```

### `opp-j-od-800000000` (Zeile 2157-2168)
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
			phandle = <0x16f>;
		};
```

### `opp-j-od-900000000` (Zeile 2170-2181)
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
			phandle = <0x170>;
		};
```

### `opp-j-od-1000000000` (Zeile 2183-2194)
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
			phandle = <0x171>;
		};
```

### `opp-300000000` (Zeile 2249-2253)
```dts
		opp-300000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x11e1a300>;
			opp-microvolt = <0xc96a8 0xc96a8 0xf4240>;
		};
```

### `opp-400000000` (Zeile 2255-2259)
```dts
		opp-400000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x17d78400>;
			opp-microvolt = <0xc96a8 0xc96a8 0xf4240>;
		};
```

### `opp-500000000` (Zeile 2261-2265)
```dts
		opp-500000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x1dcd6500>;
			opp-microvolt = <0xc96a8 0xc96a8 0xf4240>;
		};
```

### `opp-600000000` (Zeile 2267-2271)
```dts
		opp-600000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x23c34600>;
			opp-microvolt = <0xc96a8 0xc96a8 0xf4240>;
		};
```

### `opp-700000000` (Zeile 2273-2282)
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

### `opp-800000000` (Zeile 2284-2293)
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

### `opp-900000000` (Zeile 2295-2304)
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

### `opp-j-300000000` (Zeile 2306-2310)
```dts
		opp-j-300000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x11e1a300>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
		};
```

### `opp-j-400000000` (Zeile 2312-2316)
```dts
		opp-j-400000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x17d78400>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
		};
```

### `opp-j-500000000` (Zeile 2318-2322)
```dts
		opp-j-500000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x1dcd6500>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
		};
```

### `opp-j-600000000` (Zeile 2324-2328)
```dts
		opp-j-600000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x23c34600>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
		};
```

### `opp-j-700000000` (Zeile 2330-2334)
```dts
		opp-j-700000000 {
			opp-supported-hw = <0x04 0xffff>;
			opp-hz = <0x00 0x29b92700>;
			opp-microvolt = <0xdbba0 0xdbba0 0xf4240>;
		};
```

### `opp-j-od-800000000` (Zeile 2336-2347)
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
			phandle = <0x172>;
		};
```

### `opp-j-od-900000000` (Zeile 2349-2360)
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
			phandle = <0x173>;
		};
```

### `__symbols__` (Zeile 6275-6966)
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

## Rockchip System-Controller (GRF/PMU)
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
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `arm-pmu` (Zeile 457-462)
```dts
	arm-pmu {
		compatible = "arm,cortex-a53-pmu";
		interrupts = <0x00 0xe4 0x04 0x00 0xe5 0x04 0x00 0xe6 0x04 0x00 0xe7 0x04>;
		interrupt-affinity = <0x0f 0x10 0x11 0x12>;
		phandle = <0xfe>;
	};
```

### `qos@fee03800` (Zeile 1038-1042)
```dts
	qos@fee03800 {
		compatible = "syscon";
		reg = <0x00 0xfee03800 0x00 0x20>;
		phandle = <0x131>;
	};
```

### `shaping@fee03888` (Zeile 1044-1048)
```dts
	shaping@fee03888 {
		compatible = "syscon";
		reg = <0x00 0xfee03888 0x00 0x04>;
		phandle = <0x132>;
	};
```

### `qos@fee10000` (Zeile 1050-1054)
```dts
	qos@fee10000 {
		compatible = "syscon";
		reg = <0x00 0xfee10000 0x00 0x20>;
		phandle = <0x133>;
	};
```

### `shaping@fee10088` (Zeile 1056-1060)
```dts
	shaping@fee10088 {
		compatible = "syscon";
		reg = <0x00 0xfee10088 0x00 0x04>;
		phandle = <0x134>;
	};
```

### `qos@fee10100` (Zeile 1062-1066)
```dts
	qos@fee10100 {
		compatible = "syscon";
		reg = <0x00 0xfee10100 0x00 0x20>;
		phandle = <0x135>;
	};
```

### `shaping@fee10188` (Zeile 1068-1072)
```dts
	shaping@fee10188 {
		compatible = "syscon";
		reg = <0x00 0xfee10188 0x00 0x04>;
		phandle = <0x136>;
	};
```

### `qos@fee10200` (Zeile 1074-1078)
```dts
	qos@fee10200 {
		compatible = "syscon";
		reg = <0x00 0xfee10200 0x00 0x20>;
		phandle = <0x137>;
	};
```

### `shaping@fee10288` (Zeile 1080-1084)
```dts
	shaping@fee10288 {
		compatible = "syscon";
		reg = <0x00 0xfee10288 0x00 0x04>;
		phandle = <0x138>;
	};
```

### `qos@fee10300` (Zeile 1086-1090)
```dts
	qos@fee10300 {
		compatible = "syscon";
		reg = <0x00 0xfee10300 0x00 0x20>;
		phandle = <0x139>;
	};
```

### `shaping@fee10388` (Zeile 1092-1096)
```dts
	shaping@fee10388 {
		compatible = "syscon";
		reg = <0x00 0xfee10388 0x00 0x04>;
		phandle = <0x13a>;
	};
```

### `qos@fee10400` (Zeile 1098-1102)
```dts
	qos@fee10400 {
		compatible = "syscon";
		reg = <0x00 0xfee10400 0x00 0x20>;
		phandle = <0x13b>;
	};
```

### `qos@fee20000` (Zeile 1104-1108)
```dts
	qos@fee20000 {
		compatible = "syscon";
		reg = <0x00 0xfee20000 0x00 0x20>;
		phandle = <0x13c>;
	};
```

### `shaping@fee20088` (Zeile 1110-1114)
```dts
	shaping@fee20088 {
		compatible = "syscon";
		reg = <0x00 0xfee20088 0x00 0x04>;
		phandle = <0x13d>;
	};
```

### `qos@fee20100` (Zeile 1116-1120)
```dts
	qos@fee20100 {
		compatible = "syscon";
		reg = <0x00 0xfee20100 0x00 0x20>;
		phandle = <0x13e>;
	};
```

### `shaping@fee20188` (Zeile 1122-1126)
```dts
	shaping@fee20188 {
		compatible = "syscon";
		reg = <0x00 0xfee20188 0x00 0x04>;
		phandle = <0x13f>;
	};
```

### `qos@fee30000` (Zeile 1128-1133)
```dts
	qos@fee30000 {
		compatible = "syscon";
		reg = <0x00 0xfee30000 0x00 0x20>;
		priority-init = <0x202>;
		phandle = <0x52>;
	};
```

### `shaping@fee30088` (Zeile 1135-1139)
```dts
	shaping@fee30088 {
		compatible = "syscon";
		reg = <0x00 0xfee30088 0x00 0x04>;
		phandle = <0x53>;
	};
```

### `qos@fee40000` (Zeile 1141-1145)
```dts
	qos@fee40000 {
		compatible = "syscon";
		reg = <0x00 0xfee40000 0x00 0x20>;
		phandle = <0x54>;
	};
```

### `shaping@fee40088` (Zeile 1147-1151)
```dts
	shaping@fee40088 {
		compatible = "syscon";
		reg = <0x00 0xfee40088 0x00 0x04>;
		phandle = <0x55>;
	};
```

### `qos@fee50000` (Zeile 1153-1157)
```dts
	qos@fee50000 {
		compatible = "syscon";
		reg = <0x00 0xfee50000 0x00 0x20>;
		phandle = <0x56>;
	};
```

### `shaping@fee50088` (Zeile 1159-1163)
```dts
	shaping@fee50088 {
		compatible = "syscon";
		reg = <0x00 0xfee50088 0x00 0x04>;
		phandle = <0x57>;
	};
```

### `qos@fee60000` (Zeile 1165-1169)
```dts
	qos@fee60000 {
		compatible = "syscon";
		reg = <0x00 0xfee60000 0x00 0x20>;
		phandle = <0x5c>;
	};
```

### `shaping@fee60088` (Zeile 1171-1175)
```dts
	shaping@fee60088 {
		compatible = "syscon";
		reg = <0x00 0xfee60088 0x00 0x04>;
		phandle = <0x5d>;
	};
```

### `qos@fee70000` (Zeile 1177-1181)
```dts
	qos@fee70000 {
		compatible = "syscon";
		reg = <0x00 0xfee70000 0x00 0x20>;
		phandle = <0x58>;
	};
```

### `shaping@fee70088` (Zeile 1183-1187)
```dts
	shaping@fee70088 {
		compatible = "syscon";
		reg = <0x00 0xfee70088 0x00 0x04>;
		phandle = <0x5a>;
	};
```

### `qos@fee70100` (Zeile 1189-1193)
```dts
	qos@fee70100 {
		compatible = "syscon";
		reg = <0x00 0xfee70100 0x00 0x20>;
		phandle = <0x59>;
	};
```

### `shaping@fee70188` (Zeile 1195-1199)
```dts
	shaping@fee70188 {
		compatible = "syscon";
		reg = <0x00 0xfee70188 0x00 0x04>;
		phandle = <0x5b>;
	};
```

### `qos@fee80000` (Zeile 1201-1205)
```dts
	qos@fee80000 {
		compatible = "syscon";
		reg = <0x00 0xfee80000 0x00 0x20>;
		phandle = <0x5e>;
	};
```

### `shaping@fee80088` (Zeile 1207-1211)
```dts
	shaping@fee80088 {
		compatible = "syscon";
		reg = <0x00 0xfee80088 0x00 0x04>;
		phandle = <0x5f>;
	};
```

### `qos@fee90000` (Zeile 1213-1217)
```dts
	qos@fee90000 {
		compatible = "syscon";
		reg = <0x00 0xfee90000 0x00 0x20>;
		phandle = <0x62>;
	};
```

### `shaping@fee90088` (Zeile 1219-1223)
```dts
	shaping@fee90088 {
		compatible = "syscon";
		reg = <0x00 0xfee90088 0x00 0x04>;
		phandle = <0x65>;
	};
```

### `qos@fee90100` (Zeile 1225-1229)
```dts
	qos@fee90100 {
		compatible = "syscon";
		reg = <0x00 0xfee90100 0x00 0x20>;
		phandle = <0x60>;
	};
```

### `shaping@fee90188` (Zeile 1231-1235)
```dts
	shaping@fee90188 {
		compatible = "syscon";
		reg = <0x00 0xfee90188 0x00 0x04>;
		phandle = <0x63>;
	};
```

### `qos@fee90200` (Zeile 1237-1241)
```dts
	qos@fee90200 {
		compatible = "syscon";
		reg = <0x00 0xfee90200 0x00 0x20>;
		phandle = <0x61>;
	};
```

### `shaping@fee90288` (Zeile 1243-1247)
```dts
	shaping@fee90288 {
		compatible = "syscon";
		reg = <0x00 0xfee90288 0x00 0x04>;
		phandle = <0x64>;
	};
```

### `qos@feea0000` (Zeile 1249-1253)
```dts
	qos@feea0000 {
		compatible = "syscon";
		reg = <0x00 0xfeea0000 0x00 0x20>;
		phandle = <0x66>;
	};
```

### `shaping@feea0088` (Zeile 1255-1260)
```dts
	shaping@feea0088 {
		compatible = "syscon";
		reg = <0x00 0xfeea0088 0x00 0x04>;
		shaping-init = <0x05>;
		phandle = <0x68>;
	};
```

### `qos@feea0100` (Zeile 1262-1266)
```dts
	qos@feea0100 {
		compatible = "syscon";
		reg = <0x00 0xfeea0100 0x00 0x20>;
		phandle = <0x67>;
	};
```

### `shaping@feea0188` (Zeile 1268-1272)
```dts
	shaping@feea0188 {
		compatible = "syscon";
		reg = <0x00 0xfeea0188 0x00 0x04>;
		phandle = <0x69>;
	};
```

### `qos@feeb0000` (Zeile 1274-1278)
```dts
	qos@feeb0000 {
		compatible = "syscon";
		reg = <0x00 0xfeeb0000 0x00 0x20>;
		phandle = <0x140>;
	};
```

### `shaping@feeb0088` (Zeile 1280-1284)
```dts
	shaping@feeb0088 {
		compatible = "syscon";
		reg = <0x00 0xfeeb0088 0x00 0x04>;
		phandle = <0x141>;
	};
```

### `qos@feeb0100` (Zeile 1286-1290)
```dts
	qos@feeb0100 {
		compatible = "syscon";
		reg = <0x00 0xfeeb0100 0x00 0x20>;
		phandle = <0x142>;
	};
```

### `shaping@feeb0188` (Zeile 1292-1296)
```dts
	shaping@feeb0188 {
		compatible = "syscon";
		reg = <0x00 0xfeeb0188 0x00 0x04>;
		phandle = <0x143>;
	};
```

### `qos@feeb0200` (Zeile 1298-1302)
```dts
	qos@feeb0200 {
		compatible = "syscon";
		reg = <0x00 0xfeeb0200 0x00 0x20>;
		phandle = <0x144>;
	};
```

### `shaping@feeb0288` (Zeile 1304-1308)
```dts
	shaping@feeb0288 {
		compatible = "syscon";
		reg = <0x00 0xfeeb0288 0x00 0x04>;
		phandle = <0x145>;
	};
```

### `qos@feeb0300` (Zeile 1310-1314)
```dts
	qos@feeb0300 {
		compatible = "syscon";
		reg = <0x00 0xfeeb0300 0x00 0x20>;
		phandle = <0x146>;
	};
```

### `shaping@feeb0388` (Zeile 1316-1320)
```dts
	shaping@feeb0388 {
		compatible = "syscon";
		reg = <0x00 0xfeeb0388 0x00 0x04>;
		phandle = <0x147>;
	};
```

### `qos@feeb0400` (Zeile 1322-1326)
```dts
	qos@feeb0400 {
		compatible = "syscon";
		reg = <0x00 0xfeeb0400 0x00 0x20>;
		phandle = <0x148>;
	};
```

### `shaping@feeb0488` (Zeile 1328-1332)
```dts
	shaping@feeb0488 {
		compatible = "syscon";
		reg = <0x00 0xfeeb0488 0x00 0x04>;
		phandle = <0x149>;
	};
```

### `qos@feeb0500` (Zeile 1334-1338)
```dts
	qos@feeb0500 {
		compatible = "syscon";
		reg = <0x00 0xfeeb0500 0x00 0x20>;
		phandle = <0x14a>;
	};
```

### `shaping@feeb0588` (Zeile 1340-1344)
```dts
	shaping@feeb0588 {
		compatible = "syscon";
		reg = <0x00 0xfeeb0588 0x00 0x04>;
		phandle = <0x14b>;
	};
```

### `qos@feeb0600` (Zeile 1346-1350)
```dts
	qos@feeb0600 {
		compatible = "syscon";
		reg = <0x00 0xfeeb0600 0x00 0x20>;
		phandle = <0x14c>;
	};
```

### `shaping@feeb0688` (Zeile 1352-1356)
```dts
	shaping@feeb0688 {
		compatible = "syscon";
		reg = <0x00 0xfeeb0688 0x00 0x04>;
		phandle = <0x14d>;
	};
```

### `qos@feeb0700` (Zeile 1358-1362)
```dts
	qos@feeb0700 {
		compatible = "syscon";
		reg = <0x00 0xfeeb0700 0x00 0x20>;
		phandle = <0x14e>;
	};
```

### `shaping@feeb0788` (Zeile 1364-1368)
```dts
	shaping@feeb0788 {
		compatible = "syscon";
		reg = <0x00 0xfeeb0788 0x00 0x04>;
		phandle = <0x14f>;
	};
```

### `qos@feeb0800` (Zeile 1370-1374)
```dts
	qos@feeb0800 {
		compatible = "syscon";
		reg = <0x00 0xfeeb0800 0x00 0x20>;
		phandle = <0x150>;
	};
```

### `shaping@feeb0888` (Zeile 1376-1380)
```dts
	shaping@feeb0888 {
		compatible = "syscon";
		reg = <0x00 0xfeeb0888 0x00 0x04>;
		phandle = <0x151>;
	};
```

### `reboot-mode` (Zeile 1387-1400)
```dts
		reboot-mode {
			compatible = "syscon-reboot-mode";
			offset = <0x220>;
			mode-bootloader = <0x5242c301>;
			mode-charge = <0x5242c30b>;
			mode-fastboot = <0x5242c309>;
			mode-loader = <0x5242c301>;
			mode-normal = <0x5242c300>;
			mode-recovery = <0x5242c303>;
			mode-ums = <0x5242c30c>;
			mode-panic = <0x5242c307>;
			mode-watchdog = <0x5242c308>;
			phandle = <0x152>;
		};
```

### `syscon@ff030000` (Zeile 1403-1433)
```dts
	syscon@ff030000 {
		compatible = "rockchip,rk3562-sys-grf\0syscon\0simple-mfd";
		reg = <0x00 0xff030000 0x00 0x10000>;
		phandle = <0x0e>;

		lvds {
			compatible = "rockchip,rk3562-lvds";
			phys = <0x38>;
			phy-names = "phy";
			status = "disabled";
			phandle = <0x153>;

			ports {
				#address-cells = <0x01>;
				#size-cells = <0x00>;

				port@0 {
					reg = <0x00>;
					#address-cells = <0x01>;
					#size-cells = <0x00>;

					endpoint@0 {
						reg = <0x00>;
						remote-endpoint = <0x1c>;
						status = "disabled";
						phandle = <0x7e>;
					};
				};
			};
		};
	};
```

### `syscon@ff040000` (Zeile 1435-1439)
```dts
	syscon@ff040000 {
		compatible = "rockchip,rk3562-peri-grf\0syscon";
		reg = <0x00 0xff040000 0x00 0x10000>;
		phandle = <0x99>;
	};
```

### `syscon@ff060000` (Zeile 1441-1480)
```dts
	syscon@ff060000 {
		compatible = "rockchip,rk3562-ioc-grf\0syscon\0simple-mfd";
		reg = <0x00 0xff060000 0x00 0x30000>;
		phandle = <0x7b>;

		rgb {
			compatible = "rockchip,rk3562-rgb";
			pinctrl-names = "default";
			pinctrl-0 = <0x39>;
			status = "okay";
			phandle = <0x154>;

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
						phandle = <0x7c>;
					};
				};

				port@1 {
					reg = <0x01>;

					endpoint {
						remote-endpoint = <0x3a>;
						phandle = <0xbf>;
					};
				};
			};
		};
	};
```

### `syscon@ff090000` (Zeile 1482-1486)
```dts
	syscon@ff090000 {
		compatible = "rockchip,rk3562-usbphy-grf\0syscon";
		reg = <0x00 0xff090000 0x00 0x8000>;
		phandle = <0x98>;
	};
```

### `syscon@ff098000` (Zeile 1488-1492)
```dts
	syscon@ff098000 {
		compatible = "rockchip,rk3562-pipephy-grf\0syscon";
		reg = <0x00 0xff098000 0x00 0x8000>;
		phandle = <0x9a>;
	};
```

### `clock-controller@ff100000` (Zeile 1494-1503)
```dts
	clock-controller@ff100000 {
		compatible = "rockchip,rk3562-cru";
		reg = <0x00 0xff100000 0x00 0x40000>;
		rockchip,grf = <0x0e>;
		#clock-cells = <0x01>;
		#reset-cells = <0x01>;
		assigned-clocks = <0x02 0x02 0x02 0x05 0x02 0x04>;
		assigned-clock-rates = <0x46cf7100 0x3b9aca00 0x3a980000>;
		phandle = <0x02>;
	};
```

### `LDO_REG1` (Zeile 1654-1666)
```dts
				LDO_REG1 {
					regulator-always-on;
					regulator-boot-on;
					regulator-min-microvolt = <0x1b7740>;
					regulator-max-microvolt = <0x1b7740>;
					regulator-name = "vcca1v8_pmu";
					phandle = <0x15d>;

					regulator-state-mem {
						regulator-on-in-suspend;
						regulator-suspend-microvolt = <0x1b7740>;
					};
				};
```

### `LDO_REG3` (Zeile 1681-1693)
```dts
				LDO_REG3 {
					regulator-always-on;
					regulator-boot-on;
					regulator-min-microvolt = <0xdbba0>;
					regulator-max-microvolt = <0xdbba0>;
					regulator-name = "vdda0v9_pmu";
					phandle = <0x15f>;

					regulator-state-mem {
						regulator-on-in-suspend;
						regulator-suspend-microvolt = <0xdbba0>;
					};
				};
```

### `LDO_REG6` (Zeile 1721-1733)
```dts
				LDO_REG6 {
					regulator-always-on;
					regulator-boot-on;
					regulator-min-microvolt = <0x325aa0>;
					regulator-max-microvolt = <0x325aa0>;
					regulator-name = "vcc3v3_pmu";
					phandle = <0x161>;

					regulator-state-mem {
						regulator-on-in-suspend;
						regulator-suspend-microvolt = <0x2dc6c0>;
					};
				};
```

### `power-management@ff258000` (Zeile 1936-2001)
```dts
	power-management@ff258000 {
		compatible = "rockchip,rk3562-pmu\0syscon\0simple-mfd";
		reg = <0x00 0xff258000 0x00 0x1000>;
		phandle = <0x16c>;

		power-controller {
			compatible = "rockchip,rk3562-power-controller";
			#power-domain-cells = <0x01>;
			#address-cells = <0x01>;
			#size-cells = <0x00>;
			status = "okay";
			phandle = <0x35>;

			pd_gpu@8 {
				reg = <0x08>;
				pm_qos = <0x52>;
				pm_shaping = <0x53>;
			};

			pd_npu@7 {
				reg = <0x07>;
				pm_qos = <0x54>;
				pm_shaping = <0x55>;
			};

			pd_vdpu@11 {
				reg = <0x0b>;
				pm_qos = <0x56>;
				pm_shaping = <0x57>;
			};

			pd_vi@12 {
				reg = <0x0c>;
				#address-cells = <0x01>;
				#size-cells = <0x00>;
				pm_qos = <0x58 0x59>;
				pm_shaping = <0x5a 0x5b>;

				pd_vepu@10 {
					reg = <0x0a>;
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `npu-opp-table` (Zeile 2032-2195)
```dts
	npu-opp-table {
		compatible = "operating-points-v2";
		mbist-vmin = <0xc96a8 0xdbba0 0xee098>;
		nvmem-cells = <0x6d 0x6e 0x0b 0x6f 0x0d>;
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
		phandle = <0x6a>;

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
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `gpu-opp-table` (Zeile 2228-2361)
```dts
	gpu-opp-table {
		compatible = "operating-points-v2";
		mbist-vmin = <0xc96a8 0xdbba0 0xee098>;
		nvmem-cells = <0x72 0x73 0x0b 0x74 0x0d>;
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
		phandle = <0x70>;

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
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `csi2-dphy0-hw@ff3c0000` (Zeile 2491-2501)
```dts
	csi2-dphy0-hw@ff3c0000 {
		compatible = "rockchip,rk3562-csi2-dphy-hw";
		reg = <0x00 0xff3c0000 0x00 0x10000>;
		clocks = <0x02 0x162>;
		clock-names = "pclk";
		resets = <0x02 0xc4>;
		reset-names = "srst_p_csiphy0";
		rockchip,grf = <0x0e>;
		status = "okay";
		phandle = <0x16>;
	};
```

### `csi2-dphy1-hw@ff3d0000` (Zeile 2503-2513)
```dts
	csi2-dphy1-hw@ff3d0000 {
		compatible = "rockchip,rk3562-csi2-dphy-hw";
		reg = <0x00 0xff3d0000 0x00 0x10000>;
		clocks = <0x02 0x163>;
		clock-names = "pclk";
		resets = <0x02 0xc5>;
		reset-names = "srst_p_csiphy1";
		rockchip,grf = <0x0e>;
		status = "okay";
		phandle = <0x17>;
	};
```

### `rkcif@ff3e0000` (Zeile 2515-2530)
```dts
	rkcif@ff3e0000 {
		compatible = "rockchip,rk3562-cif";
		reg = <0x00 0xff3e0000 0x00 0x800>;
		reg-names = "cif_regs";
		interrupts = <0x00 0x63 0x04>;
		interrupt-names = "cif-intr";
		clocks = <0x02 0x157 0x02 0x158 0x02 0x159 0x02 0x15a 0x02 0x15b 0x02 0x15c 0x02 0x15d>;
		clock-names = "aclk_cif\0hclk_cif\0dclk_cif\0csirx0_data\0csirx1_data\0csirx2_data\0csirx3_data";
		resets = <0x02 0xb9 0x02 0xba 0x02 0xbb 0x02 0xbc 0x02 0xbd 0x02 0xbe 0x02 0xbf>;
		reset-names = "rst_cif_a\0rst_cif_h\0rst_cif_d\0rst_cif_i0\0rst_cif_i1\0rst_cif_i2\0rst_cif_i3";
		power-domains = <0x35 0x0c>;
		rockchip,grf = <0x0e>;
		iommus = <0x2a>;
		status = "disabled";
		phandle = <0x29>;
	};
```

### `vop@ff400000` (Zeile 2573-2622)
```dts
	vop@ff400000 {
		compatible = "rockchip,rk3562-vop";
		reg = <0x00 0xff400000 0x00 0x2000 0x00 0xff405000 0x00 0x1000>;
		reg-names = "regs\0gamma_lut";
		interrupts = <0x00 0x87 0x04>;
		clocks = <0x02 0x166 0x02 0x167 0x02 0x168>;
		clock-names = "aclk_vop\0hclk_vop\0dclk_vp0";
		resets = <0x02 0xd6 0x02 0xd7 0x02 0xd8>;
		reset-names = "axi\0ahb\0dclk_vp0";
		rockchip,csu = <0x79 0x02>;
		rockchip,csu-names = "aclk";
		iommus = <0x7a>;
		power-domains = <0x35 0x0d>;
		rockchip,grf = <0x7b>;
		assigned-clocks = <0x02 0x168>;
		assigned-clock-parents = <0x02 0x03>;
		status = "okay";
		phandle = <0x176>;

		ports {
			#address-cells = <0x01>;
			#size-cells = <0x00>;
			phandle = <0x18>;

			port@0 {
				#address-cells = <0x01>;
				#size-cells = <0x00>;
				reg = <0x00>;
				phandle = <0x177>;

				endpoint@0 {
					reg = <0x00>;
					remote-endpoint = <0x7c>;
					phandle = <0x1d>;
				};

				endpoint@1 {
					reg = <0x01>;
					remote-endpoint = <0x7d>;
					phandle = <0x1b>;
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `dfi@ff4c0000` (Zeile 2696-2702)
```dts
	dfi@ff4c0000 {
		reg = <0x00 0xff4c0000 0x00 0x400>;
		compatible = "rockchip,rk3562-dfi";
		rockchip,pmugrf = <0x81>;
		status = "okay";
		phandle = <0x1e>;
	};
```

### `usb2-phy@ff740000` (Zeile 3090-3116)
```dts
	usb2-phy@ff740000 {
		compatible = "rockchip,rk3562-usb2phy";
		reg = <0x00 0xff740000 0x00 0x10000>;
		clocks = <0x02 0x13d 0x02 0xfb>;
		clock-names = "phyclk\0pclk";
		#clock-cells = <0x00>;
		clock-output-names = "usb480m_phy";
		rockchip,usbgrf = <0x98>;
		status = "okay";
		phandle = <0x36>;

		otg-port {
			#phy-cells = <0x00>;
			interrupts = <0x00 0x99 0x04 0x00 0x9a 0x04 0x00 0x9b 0x04>;
			interrupt-names = "otg-bvalid\0otg-id\0linestate";
			status = "okay";
			phandle = <0x34>;
		};

		host-port {
			#phy-cells = <0x00>;
			interrupts = <0x00 0x9c 0x04>;
			interrupt-names = "linestate";
			status = "disabled";
			phandle = <0x37>;
		};
	};
```

### `phy@ff750000` (Zeile 3118-3132)
```dts
	phy@ff750000 {
		compatible = "rockchip,rk3562-naneng-combphy";
		reg = <0x00 0xff750000 0x00 0x100>;
		#phy-cells = <0x01>;
		clocks = <0x02 0x13a 0x02 0xfc 0x02 0x106>;
		clock-names = "refclk\0apbclk\0pipe_clk";
		assigned-clocks = <0x02 0x13a>;
		assigned-clock-rates = <0x5f5e100>;
		resets = <0x02 0xc00f7 0x02 0x113>;
		reset-names = "combphy-apb\0combphy";
		rockchip,pipe-grf = <0x99>;
		rockchip,pipe-phy-grf = <0x9a>;
		status = "okay";
		phandle = <0x83>;
	};
```

### `dsm@ff850000` (Zeile 3227-3240)
```dts
	dsm@ff850000 {
		compatible = "rockchip,rk3562-dsm";
		reg = <0x00 0xff850000 0x00 0x1000>;
		clocks = <0x02 0x87 0x02 0x86>;
		clock-names = "dac\0pclk";
		resets = <0x02 0xc0032>;
		reset-names = "reset";
		rockchip,grf = <0x99>;
		pinctrl-names = "default";
		pinctrl-0 = <0xae>;
		#sound-dai-cells = <0x00>;
		status = "disabled";
		phandle = <0x192>;
	};
```

### `dma-controller@ff9a0000` (Zeile 3488-3499)
```dts
	dma-controller@ff9a0000 {
		compatible = "rockchip,rk3562-dma\0rockchip,dma-v1";
		reg = <0x00 0xff9a0000 0x00 0x4000>;
		interrupts = <0x00 0x70 0x04>;
		clocks = <0x02 0xf2>;
		clock-names = "aclk";
		#dma-cells = <0x01>;
		dma-channels = <0x2a>;
		dma-requests = <0x2a>;
		rockchip,grf = <0x99>;
		phandle = <0x19a>;
	};
```

### `tsadc@ffa70000` (Zeile 3627-3646)
```dts
	tsadc@ffa70000 {
		compatible = "rockchip,rk3562-tsadc";
		reg = <0x00 0xffa70000 0x00 0x400>;
		rockchip,grf = <0x0e>;
		interrupts = <0x00 0x7d 0x04>;
		clocks = <0x02 0x41 0x02 0x42 0x02 0x40>;
		clock-names = "tsadc\0tsadc_tsen\0apb_pclk";
		assigned-clocks = <0x02 0x41 0x02 0x42>;
		assigned-clock-rates = <0x124f80 0xb71b00>;
		resets = <0x02 0x181 0x02 0x180 0x02 0x182>;
		reset-names = "tsadc\0tsadc-apb\0tsadc-phy";
		#thermal-sensor-cells = <0x01>;
		rockchip,hw-tshut-temp = <0x1d4c0>;
		rockchip,hw-tshut-mode = <0x00>;
		rockchip,hw-tshut-polarity = <0x00>;
		nvmem-cells = <0xc1 0xc2 0xc3 0xc4>;
		nvmem-cell-names = "trim_l\0trim_h\0trim_base\0trim_base_frac";
		status = "okay";
		phandle = <0x30>;
	};
```

### `ethernet@ffa80000` (Zeile 3648-3698)
```dts
	ethernet@ffa80000 {
		compatible = "rockchip,rk3562-gmac\0snps,dwmac-4.20a";
		reg = <0x00 0xffa80000 0x00 0x10000>;
		interrupts = <0x00 0x49 0x04 0x00 0x46 0x04>;
		interrupt-names = "macirq\0eth_wake_irq";
		rockchip,grf = <0x0e>;
		rockchip,php_grf = <0x7b>;
		clocks = <0x02 0x47 0x02 0x48 0x02 0x45 0x02 0x46>;
		clock-names = "stmmaceth\0clk_mac_ref\0pclk_mac\0aclk_mac";
		resets = <0x02 0x191>;
		reset-names = "stmmaceth";
		rockchip,csu = <0x79 0x00 0x79 0x01>;
		rockchip,csu-names = "aclk\0pclk";
		snps,mixed-burst;
		snps,tso;
		snps,axi-config = <0xc5>;
		snps,mtl-rx-config = <0xc6>;
		snps,mtl-tx-config = <0xc7>;
		status = "disabled";
		phandle = <0x1a3>;

		mdio {
			compatible = "snps,dwmac-mdio";
			#address-cells = <0x01>;
			#size-cells = <0x00>;
			phandle = <0x1a4>;
		};

		stmmac-axi-config {
			snps,wr_osr_lmt = <0x04>;
			snps,rd_osr_lmt = <0x08>;
			snps,blen = <0x00 0x00 0x00 0x00 0x10 0x08 0x04>;
			phandle = <0xc5>;
		};

		rx-queues-config {
			snps,rx-queues-to-use = <0x01>;
			phandle = <0xc6>;

			queue0 {
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `dsi@ffb10000` (Zeile 3725-3829)
```dts
	dsi@ffb10000 {
		compatible = "rockchip,rk3562-mipi-dsi";
		reg = <0x00 0xffb10000 0x00 0x10000>;
		interrupts = <0x00 0x84 0x04>;
		clocks = <0x02 0x4e>;
		clock-names = "pclk";
		resets = <0x02 0x199>;
		reset-names = "apb";
		phys = <0x38>;
		phy-names = "dphy";
		rockchip,grf = <0x0e>;
		#address-cells = <0x01>;
		#size-cells = <0x00>;
		status = "okay";
		phandle = <0x1a6>;

		ports {
			#address-cells = <0x01>;
			#size-cells = <0x00>;

			port@0 {
				reg = <0x00>;
				#address-cells = <0x01>;
				#size-cells = <0x00>;
				phandle = <0x1a7>;

				endpoint@0 {
					reg = <0x00>;
					remote-endpoint = <0x1b>;
					status = "okay";
					phandle = <0x7d>;
				};
			};

			port@1 {
				reg = <0x01>;

				endpoint {
					remote-endpoint = <0xc8>;
					phandle = <0xcd>;
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `ethernet@ffb30000` (Zeile 3845-3867)
```dts
	ethernet@ffb30000 {
		compatible = "rockchip,rk3562-gmac";
		reg = <0x00 0xffb30000 0x00 0x10000>;
		interrupts = <0x00 0x43 0x04 0x00 0x44 0x04>;
		interrupt-names = "macirq\0eth_wake_irq";
		rockchip,grf = <0x0e>;
		rockchip,php_grf = <0x7b>;
		clocks = <0x02 0x5a 0x02 0x5a 0x02 0x57 0x02 0x59>;
		clock-names = "stmmaceth\0clk_mac_ref\0pclk_mac\0aclk_mac";
		resets = <0x02 0x1b1>;
		reset-names = "stmmaceth";
		rockchip,csu = <0x79 0x00 0x79 0x01>;
		rockchip,csu-names = "aclk\0pclk";
		status = "disabled";
		phandle = <0x1aa>;

		mdio {
			compatible = "snps,dwmac-mdio";
			#address-cells = <0x01>;
			#size-cells = <0x00>;
			phandle = <0x1ab>;
		};
	};
```

### `pmu-pins` (Zeile 4999-5002)
```dts
			pmu-pins {
				rockchip,pins = <0x00 0x05 0x03 0xcf>;
				phandle = <0x23d>;
			};
```

### `wireless-wlan` (Zeile 6162-6172)
```dts
	wireless-wlan {
		compatible = "wlan-platdata";
		rockchip,grf = <0x0e>;
		wifi_chip_type = "rk915";
		pinctrl-names = "default";
		pinctrl-0 = <0xe9 0xea>;
		WIFI,host_wake_irq = <0x3c 0x0c 0x00>;
		WIFI,poweren_gpio = <0x3c 0x06 0x01>;
		sdio_vref = <0x708>;
		status = "okay";
	};
```

### `__symbols__` (Zeile 6275-6966)
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

## Buttons (gpio-keys / adc-keys)
### `adc-keys` (Zeile 5947-5966)
```dts
	adc-keys {
		compatible = "adc-keys";
		io-channels = <0xd8 0x01>;
		io-channel-names = "buttons";
		keyup-threshold-microvolt = <0x1b7740>;
		poll-interval = <0x64>;
		phandle = <0x2aa>;

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

### `__symbols__` (Zeile 6275-6966)
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
		shaping_jpeg = "/shaping@fee90088";
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

## Analog-Sticks / Joystick
### `play_joystick` (Zeile 6205-6273)
```dts
	play_joystick {
		compatible = "play_joystick";
		io-channels = <0xd8 0x02 0xd8 0x03 0xd8 0x05 0xd8 0x06 0xec 0x01 0xec 0x04 0xec 0x00 0xec 0x02 0xec 0x03 0xec 0x05 0xec 0x06 0xec 0x07>;
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
		pinctrl-0 = <0xed 0xee>;
		moto-gpio = <0x48 0x07 0x00>;
		moto-r-gpio = <0x48 0x08 0x00>;
		gpio-key-num = <0x0a>;
		key-gpios = <0xef 0x17 0x01 0xef 0x18 0x01 0xef 0x1d 0x01 0xef 0x1e 0x01 0xef 0x1b 0x01 0xef 0x1f 0x01 0xef 0x1c 0x01 0x3c 0x15 0x01 0x3c 0x16 0x01>;
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

## Akku / Ladeschaltung / PMIC
### `rk817_slppin_null` (Zeile 1555-1559)
```dts
				rk817_slppin_null {
					pins = "gpio_slp";
					function = "pin_fun0";
					phandle = <0x158>;
				};
```

### `rk817_slppin_slp` (Zeile 1561-1565)
```dts
				rk817_slppin_slp {
					pins = "gpio_slp";
					function = "pin_fun1";
					phandle = <0x3f>;
				};
```

### `rk817_slppin_pwrdn` (Zeile 1567-1571)
```dts
				rk817_slppin_pwrdn {
					pins = "gpio_slp";
					function = "pin_fun2";
					phandle = <0x41>;
				};
```

### `rk817_slppin_rst` (Zeile 1573-1577)
```dts
				rk817_slppin_rst {
					pins = "gpio_slp";
					function = "pin_fun3";
					phandle = <0x42>;
				};
```

### `rk817_ts_gpio1` (Zeile 1579-1583)
```dts
				rk817_ts_gpio1 {
					pins = "gpio_ts";
					function = "pin_fun1";
					phandle = <0x159>;
				};
```

### `rk817_pin_ts` (Zeile 1585-1589)
```dts
				rk817_pin_ts {
					pins = "gpio_ts";
					function = "pin_fun0";
					phandle = <0x15a>;
				};
```

### `codec` (Zeile 1793-1811)
```dts
			codec {
				#sound-dai-cells = <0x00>;
				compatible = "rockchip,rk817-codec";
				clocks = <0x45>;
				clock-names = "mclk";
				assigned-clocks = <0x45>;
				assigned-clock-rates = <0xbb8000>;
				pinctrl-names = "default";
				pinctrl-0 = <0x46 0x47>;
				hp-volume = <0x3c>;
				spk-volume = <0x03>;
				mic-in-differential;
				status = "okay";
				use-ext-amplifier;
				hp2extamplifier;
				hp-mute-delay-ms = <0x64>;
				hp-ctl-gpios = <0x48 0x13 0x00>;
				phandle = <0xdf>;
			};
```

### `battery` (Zeile 1813-1835)
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
				pinctrl-0 = <0x49>;
				charge_red_gpio = <0x48 0x01 0x00>;
				charge_green_gpio = <0x48 0x00 0x00>;
				moto_gpio = <0x48 0x07 0x00>;
				moto_r_gpio = <0x48 0x08 0x00>;
				phandle = <0x165>;
			};
```

### `charger` (Zeile 1837-1850)
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
				extcon = <0x36>;
				gate_function_disable = <0x01>;
			};
```

### `rk817-sound` (Zeile 6036-6058)
```dts
	rk817-sound {
		status = "okay";
		compatible = "rockchip,multicodecs-card";
		rockchip,card-name = "rockchip-rk817";
		hp-det-gpio = <0x3c 0x07 0x00>;
		io-channels = <0xd8 0x04>;
		io-channel-names = "adc-detect";
		keyup-threshold-microvolt = <0x1b7740>;
		poll-interval = <0x64>;
		rockchip,format = "i2s";
		rockchip,mclk-fs = <0x100>;
		rockchip,cpu = <0xde>;
		rockchip,codec = <0xdf>;
		pinctrl-names = "default";
		pinctrl-0 = <0xe0>;
		phandle = <0x2ae>;

		play-pause-key {
			label = "playpause";
			linux,code = <0xa4>;
			press-threshold-microvolt = <0x7d0>;
		};
	};
```

### `__symbols__` (Zeile 6275-6966)
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
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

## WiFi / Bluetooth / SDIO
### `mmc@ff870000` (Zeile 3254-3274)
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
		phandle = <0x194>;
	};
```

### `mmc@ff880000` (Zeile 3276-3299)
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
		vmmc-supply = <0xaf>;
		vqmmc-supply = <0xb0>;
		pinctrl-names = "default";
		pinctrl-0 = <0xb1 0xb2 0xb3 0xb4>;
		phandle = <0x195>;
	};
```

### `mmc@ff890000` (Zeile 3301-3327)
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
		supports-rk912;
		mmc-pwrseq = <0xb5>;
		broken-cd;
		pinctrl-names = "default";
		pinctrl-0 = <0xb6 0xb7 0xb8>;
		sd-uhs-sdr104;
		phandle = <0x196>;
	};
```

### `wifi-enable-h` (Zeile 5868-5871)
```dts
			wifi-enable-h {
				rockchip,pins = <0x00 0x0b 0x00 0xcf>;
				phandle = <0xe4>;
			};
```

### `wifi-host-wake-irq` (Zeile 5884-5887)
```dts
			wifi-host-wake-irq {
				rockchip,pins = <0x00 0x0c 0x00 0xd7>;
				phandle = <0xe9>;
			};
```

### `wifi-poweren-gpio` (Zeile 5889-5892)
```dts
			wifi-poweren-gpio {
				rockchip,pins = <0x00 0x06 0x00 0xd2>;
				phandle = <0xea>;
			};
```

### `sdio-pwrseq` (Zeile 6077-6086)
```dts
	sdio-pwrseq {
		compatible = "mmc-pwrseq-simple";
		clocks = <0xe3 0x01>;
		clock-names = "ext_clock";
		pinctrl-names = "default";
		pinctrl-0 = <0xe4>;
		post-power-on-delay-ms = <0xc8>;
		reset-gpios = <0x3c 0x0b 0x01>;
		phandle = <0xb5>;
	};
```

### `wireless-wlan` (Zeile 6162-6172)
```dts
	wireless-wlan {
		compatible = "wlan-platdata";
		rockchip,grf = <0x0e>;
		wifi_chip_type = "rk915";
		pinctrl-names = "default";
		pinctrl-0 = <0xe9 0xea>;
		WIFI,host_wake_irq = <0x3c 0x0c 0x00>;
		WIFI,poweren_gpio = <0x3c 0x06 0x01>;
		sdio_vref = <0x708>;
		status = "okay";
	};
```

### `wireless-bluetooth` (Zeile 6174-6177)
```dts
	wireless-bluetooth {
		compatible = "bluetooth-platdata";
		status = "disabled";
	};
```

### `__symbols__` (Zeile 6275-6966)
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

## Audio (Codec / I2S / Sound)
### `LDO_REG4` (Zeile 1695-1706)
```dts
				LDO_REG4 {
					regulator-always-on;
					regulator-boot-on;
					regulator-min-microvolt = <0x2dc6c0>;
					regulator-max-microvolt = <0x2dc6c0>;
					regulator-name = "vccio_acodec";
					phandle = <0x160>;

					regulator-state-mem {
						regulator-off-in-suspend;
					};
				};
```

### `codec` (Zeile 1793-1811)
```dts
			codec {
				#sound-dai-cells = <0x00>;
				compatible = "rockchip,rk817-codec";
				clocks = <0x45>;
				clock-names = "mclk";
				assigned-clocks = <0x45>;
				assigned-clock-rates = <0xbb8000>;
				pinctrl-names = "default";
				pinctrl-0 = <0x46 0x47>;
				hp-volume = <0x3c>;
				spk-volume = <0x03>;
				mic-in-differential;
				status = "okay";
				use-ext-amplifier;
				hp2extamplifier;
				hp-mute-delay-ms = <0x64>;
				hp-ctl-gpios = <0x48 0x13 0x00>;
				phandle = <0xdf>;
			};
```

### `rkvdec@ff340100` (Zeile 2363-2384)
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
		iommus = <0x75>;
		rockchip,srv = <0x76>;
		rockchip,taskqueue-node = <0x00>;
		rockchip,resetgroup-node = <0x00>;
		rockchip,task-capacity = <0x10>;
		status = "okay";
		phandle = <0x174>;
	};
```

### `rkvenc@ff360000` (Zeile 2400-2419)
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
		iommus = <0x77>;
		rockchip,srv = <0x76>;
		rockchip,taskqueue-node = <0x01>;
		rockchip,resetgroup-node = <0x01>;
		status = "okay";
		phandle = <0x175>;
	};
```

### `jpegd@ff450000` (Zeile 2664-2680)
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
		iommus = <0x80>;
		rockchip,srv = <0x76>;
		rockchip,taskqueue-node = <0x02>;
		rockchip,resetgroup-node = <0x02>;
		status = "okay";
		phandle = <0x179>;
	};
```

### `sai@ff800000` (Zeile 3134-3152)
```dts
	sai@ff800000 {
		compatible = "rockchip,rk3562-sai\0rockchip,sai-v1";
		reg = <0x00 0xff800000 0x00 0x1000>;
		interrupts = <0x00 0x4e 0x04>;
		clocks = <0x02 0x78 0x02 0x74>;
		clock-names = "mclk\0hclk";
		assigned-clocks = <0x02 0x75>;
		assigned-clock-parents = <0x02 0x04>;
		dmas = <0x4a 0x13 0x4a 0x12>;
		dma-names = "tx\0rx";
		resets = <0x02 0xc0023 0x02 0xc0020>;
		reset-names = "m\0h";
		pinctrl-names = "default";
		pinctrl-0 = <0x9b 0x9c 0x9d 0x9e>;
		#sound-dai-cells = <0x00>;
		sound-name-prefix = "SAI0";
		status = "okay";
		phandle = <0xde>;
	};
```

### `sai@ff810000` (Zeile 3154-3172)
```dts
	sai@ff810000 {
		compatible = "rockchip,rk3562-sai\0rockchip,sai-v1";
		reg = <0x00 0xff810000 0x00 0x1000>;
		interrupts = <0x00 0x4f 0x04>;
		clocks = <0x02 0x7e 0x02 0x7a>;
		clock-names = "mclk\0hclk";
		assigned-clocks = <0x02 0x7b>;
		assigned-clock-parents = <0x02 0x04>;
		dmas = <0x4a 0x15 0x4a 0x14>;
		dma-names = "tx\0rx";
		resets = <0x02 0xc0028 0x02 0xc0025>;
		reset-names = "m\0h";
		pinctrl-names = "default";
		pinctrl-0 = <0x9f 0xa0 0xa1 0xa2>;
		#sound-dai-cells = <0x00>;
		sound-name-prefix = "SAI1";
		status = "okay";
		phandle = <0xe1>;
	};
```

### `sai@ff820000` (Zeile 3174-3192)
```dts
	sai@ff820000 {
		compatible = "rockchip,rk3562-sai\0rockchip,sai-v1";
		reg = <0x00 0xff820000 0x00 0x1000>;
		interrupts = <0x00 0x50 0x04>;
		clocks = <0x02 0x84 0x02 0x80>;
		clock-names = "mclk\0hclk";
		assigned-clocks = <0x02 0x81>;
		assigned-clock-parents = <0x02 0x04>;
		dmas = <0x4a 0x17 0x4a 0x16>;
		dma-names = "tx\0rx";
		resets = <0x02 0xc002d 0x02 0xc002a>;
		reset-names = "m\0h";
		pinctrl-names = "default";
		pinctrl-0 = <0xa3 0xa4 0xa5 0xa6>;
		#sound-dai-cells = <0x00>;
		sound-name-prefix = "SAI2";
		status = "disabled";
		phandle = <0x191>;
	};
```

### `pdm@ff830000` (Zeile 3194-3208)
```dts
	pdm@ff830000 {
		compatible = "rockchip,rk3562-pdm\0rockchip,rv1126-pdm";
		reg = <0x00 0xff830000 0x00 0x1000>;
		clocks = <0x02 0x89 0x02 0x88>;
		clock-names = "pdm_clk\0pdm_hclk";
		assigned-clocks = <0x02 0x89>;
		assigned-clock-parents = <0x02 0x04>;
		dmas = <0x4a 0x1f>;
		dma-names = "rx";
		pinctrl-names = "default";
		pinctrl-0 = <0xa7 0xa8 0xa9 0xaa 0xab 0xac>;
		#sound-dai-cells = <0x00>;
		status = "disabled";
		phandle = <0xda>;
	};
```

### `spdif@ff840000` (Zeile 3210-3225)
```dts
	spdif@ff840000 {
		compatible = "rockchip,rk3562-spdif\0rockchip,rk3568-spdif";
		reg = <0x00 0xff840000 0x00 0x1000>;
		interrupts = <0x00 0x7f 0x04>;
		dmas = <0x4a 0x1e>;
		dma-names = "tx";
		clock-names = "mclk\0hclk";
		clocks = <0x02 0x8e 0x02 0x8a>;
		assigned-clocks = <0x02 0x8b>;
		assigned-clock-parents = <0x02 0x04>;
		#sound-dai-cells = <0x00>;
		pinctrl-names = "default";
		pinctrl-0 = <0xad>;
		status = "disabled";
		phandle = <0xdc>;
	};
```

### `dsm@ff850000` (Zeile 3227-3240)
```dts
	dsm@ff850000 {
		compatible = "rockchip,rk3562-dsm";
		reg = <0x00 0xff850000 0x00 0x1000>;
		clocks = <0x02 0x87 0x02 0x86>;
		clock-names = "dac\0pclk";
		resets = <0x02 0xc0032>;
		reset-names = "reset";
		rockchip,grf = <0x99>;
		pinctrl-names = "default";
		pinctrl-0 = <0xae>;
		#sound-dai-cells = <0x00>;
		status = "disabled";
		phandle = <0x192>;
	};
```

### `rk628@50` (Zeile 3565-3591)
```dts
		rk628@50 {
			status = "okay";
			compatible = "rockchip,rk628";
			reg = <0x50>;
			#sound-dai-cells = <0x00>;
			interrupt-parent = <0x48>;
			interrupts = <0x12 0x04>;
			enable-gpios = <0x48 0x10 0x00>;
			reset-gpios = <0x48 0x11 0x01>;
			pinctrl-names = "default";
			pinctrl-0 = <0xbd 0xbe>;
			assigned-clocks = <0x02 0x132>;
			assigned-clock-rates = <0x16e3600>;
			clocks = <0x02 0x132>;
			clock-names = "soc_24M";
			rk628-rgb-in;
			rk628-hdmi-out;
			phandle = <0xe2>;

			port {

				endpoint {
					remote-endpoint = <0xbf>;
					phandle = <0x3a>;
				};
			};
		};
```

### `i2s0m0-lrck` (Zeile 4592-4595)
```dts
			i2s0m0-lrck {
				rockchip,pins = <0x03 0x04 0x01 0xd1>;
				phandle = <0x9b>;
			};
```

### `i2s0m0-mclk` (Zeile 4597-4600)
```dts
			i2s0m0-mclk {
				rockchip,pins = <0x03 0x02 0x01 0xd1>;
				phandle = <0x46>;
			};
```

### `i2s0m0-sclk` (Zeile 4602-4605)
```dts
			i2s0m0-sclk {
				rockchip,pins = <0x03 0x03 0x01 0xd1>;
				phandle = <0x9c>;
			};
```

### `i2s0m0-sdi0` (Zeile 4607-4610)
```dts
			i2s0m0-sdi0 {
				rockchip,pins = <0x03 0x09 0x01 0xcf>;
				phandle = <0x9d>;
			};
```

### `i2s0m0-sdi1` (Zeile 4612-4615)
```dts
			i2s0m0-sdi1 {
				rockchip,pins = <0x03 0x08 0x02 0xcf>;
				phandle = <0x207>;
			};
```

### `i2s0m0-sdi2` (Zeile 4617-4620)
```dts
			i2s0m0-sdi2 {
				rockchip,pins = <0x03 0x07 0x02 0xcf>;
				phandle = <0x208>;
			};
```

### `i2s0m0-sdi3` (Zeile 4622-4625)
```dts
			i2s0m0-sdi3 {
				rockchip,pins = <0x03 0x06 0x02 0xcf>;
				phandle = <0x209>;
			};
```

### `i2s0m0-sdo0` (Zeile 4627-4630)
```dts
			i2s0m0-sdo0 {
				rockchip,pins = <0x03 0x05 0x01 0xcf>;
				phandle = <0x9e>;
			};
```

### `i2s0m0-sdo1` (Zeile 4632-4635)
```dts
			i2s0m0-sdo1 {
				rockchip,pins = <0x03 0x06 0x01 0xcf>;
				phandle = <0x20a>;
			};
```

### `i2s0m0-sdo2` (Zeile 4637-4640)
```dts
			i2s0m0-sdo2 {
				rockchip,pins = <0x03 0x07 0x01 0xcf>;
				phandle = <0x20b>;
			};
```

### `i2s0m0-sdo3` (Zeile 4642-4645)
```dts
			i2s0m0-sdo3 {
				rockchip,pins = <0x03 0x08 0x01 0xcf>;
				phandle = <0x20c>;
			};
```

### `i2s0m1-lrck` (Zeile 4647-4650)
```dts
			i2s0m1-lrck {
				rockchip,pins = <0x01 0x14 0x03 0xd1>;
				phandle = <0x20d>;
			};
```

### `i2s0m1-mclk` (Zeile 4652-4655)
```dts
			i2s0m1-mclk {
				rockchip,pins = <0x01 0x16 0x03 0xd1>;
				phandle = <0x20e>;
			};
```

### `i2s0m1-sclk` (Zeile 4657-4660)
```dts
			i2s0m1-sclk {
				rockchip,pins = <0x01 0x15 0x03 0xd1>;
				phandle = <0x20f>;
			};
```

### `i2s0m1-sdi0` (Zeile 4662-4665)
```dts
			i2s0m1-sdi0 {
				rockchip,pins = <0x01 0x11 0x03 0xcf>;
				phandle = <0x210>;
			};
```

### `i2s0m1-sdi1` (Zeile 4667-4670)
```dts
			i2s0m1-sdi1 {
				rockchip,pins = <0x01 0x12 0x03 0xcf>;
				phandle = <0x211>;
			};
```

### `i2s0m1-sdi2` (Zeile 4672-4675)
```dts
			i2s0m1-sdi2 {
				rockchip,pins = <0x01 0x1b 0x03 0xcf>;
				phandle = <0x212>;
			};
```

### `i2s0m1-sdi3` (Zeile 4677-4680)
```dts
			i2s0m1-sdi3 {
				rockchip,pins = <0x01 0x1c 0x03 0xcf>;
				phandle = <0x213>;
			};
```

### `i2s0m1-sdo0` (Zeile 4682-4685)
```dts
			i2s0m1-sdo0 {
				rockchip,pins = <0x01 0x13 0x03 0xcf>;
				phandle = <0x214>;
			};
```

### `i2s0m1-sdo1` (Zeile 4687-4690)
```dts
			i2s0m1-sdo1 {
				rockchip,pins = <0x01 0x19 0x03 0xcf>;
				phandle = <0x215>;
			};
```

### `i2s0m1-sdo2` (Zeile 4692-4695)
```dts
			i2s0m1-sdo2 {
				rockchip,pins = <0x01 0x1a 0x03 0xcf>;
				phandle = <0x216>;
			};
```

### `i2s0m1-sdo3` (Zeile 4697-4700)
```dts
			i2s0m1-sdo3 {
				rockchip,pins = <0x02 0x01 0x05 0xcf>;
				phandle = <0x217>;
			};
```

### `i2s1m0-lrck` (Zeile 4705-4708)
```dts
			i2s1m0-lrck {
				rockchip,pins = <0x03 0x16 0x02 0xd1>;
				phandle = <0x218>;
			};
```

### `i2s1m0-mclk` (Zeile 4710-4713)
```dts
			i2s1m0-mclk {
				rockchip,pins = <0x03 0x14 0x02 0xd1>;
				phandle = <0x219>;
			};
```

### `i2s1m0-sclk` (Zeile 4715-4718)
```dts
			i2s1m0-sclk {
				rockchip,pins = <0x03 0x15 0x02 0xd1>;
				phandle = <0x21a>;
			};
```

### `i2s1m0-sdi0` (Zeile 4720-4723)
```dts
			i2s1m0-sdi0 {
				rockchip,pins = <0x03 0x18 0x02 0xcf>;
				phandle = <0x21b>;
			};
```

### `i2s1m0-sdi1` (Zeile 4725-4728)
```dts
			i2s1m0-sdi1 {
				rockchip,pins = <0x03 0x19 0x02 0xcf>;
				phandle = <0x21c>;
			};
```

### `i2s1m0-sdi2` (Zeile 4730-4733)
```dts
			i2s1m0-sdi2 {
				rockchip,pins = <0x03 0x1a 0x02 0xcf>;
				phandle = <0x21d>;
			};
```

### `i2s1m0-sdi3` (Zeile 4735-4738)
```dts
			i2s1m0-sdi3 {
				rockchip,pins = <0x03 0x1b 0x02 0xcf>;
				phandle = <0x21e>;
			};
```

### `i2s1m0-sdo0` (Zeile 4740-4743)
```dts
			i2s1m0-sdo0 {
				rockchip,pins = <0x03 0x17 0x02 0xcf>;
				phandle = <0x21f>;
			};
```

### `i2s1m0-sdo1` (Zeile 4745-4748)
```dts
			i2s1m0-sdo1 {
				rockchip,pins = <0x04 0x0c 0x02 0xcf>;
				phandle = <0x220>;
			};
```

### `i2s1m0-sdo2` (Zeile 4750-4753)
```dts
			i2s1m0-sdo2 {
				rockchip,pins = <0x04 0x0d 0x02 0xcf>;
				phandle = <0x221>;
			};
```

### `i2s1m0-sdo3` (Zeile 4755-4758)
```dts
			i2s1m0-sdo3 {
				rockchip,pins = <0x04 0x0e 0x02 0xcf>;
				phandle = <0x222>;
			};
```

### `i2s1m1-lrck` (Zeile 4760-4763)
```dts
			i2s1m1-lrck {
				rockchip,pins = <0x03 0x0c 0x01 0xd1>;
				phandle = <0xa1>;
			};
```

### `i2s1m1-mclk` (Zeile 4765-4768)
```dts
			i2s1m1-mclk {
				rockchip,pins = <0x03 0x0a 0x01 0xd1>;
				phandle = <0x9f>;
			};
```

### `i2s1m1-sclk` (Zeile 4770-4773)
```dts
			i2s1m1-sclk {
				rockchip,pins = <0x03 0x0b 0x01 0xd1>;
				phandle = <0xa0>;
			};
```

### `i2s1m1-sdi0` (Zeile 4775-4778)
```dts
			i2s1m1-sdi0 {
				rockchip,pins = <0x03 0x11 0x01 0xcf>;
				phandle = <0x223>;
			};
```

### `i2s1m1-sdi1` (Zeile 4780-4783)
```dts
			i2s1m1-sdi1 {
				rockchip,pins = <0x03 0x10 0x02 0xcf>;
				phandle = <0x224>;
			};
```

### `i2s1m1-sdi2` (Zeile 4785-4788)
```dts
			i2s1m1-sdi2 {
				rockchip,pins = <0x03 0x0f 0x02 0xcf>;
				phandle = <0x225>;
			};
```

### `i2s1m1-sdi3` (Zeile 4790-4793)
```dts
			i2s1m1-sdi3 {
				rockchip,pins = <0x03 0x0e 0x02 0xcf>;
				phandle = <0x226>;
			};
```

### `i2s1m1-sdo0` (Zeile 4795-4798)
```dts
			i2s1m1-sdo0 {
				rockchip,pins = <0x03 0x0d 0x01 0xcf>;
				phandle = <0xa2>;
			};
```

### `i2s1m1-sdo1` (Zeile 4800-4803)
```dts
			i2s1m1-sdo1 {
				rockchip,pins = <0x03 0x0e 0x01 0xcf>;
				phandle = <0x227>;
			};
```

### `i2s1m1-sdo2` (Zeile 4805-4808)
```dts
			i2s1m1-sdo2 {
				rockchip,pins = <0x03 0x0f 0x01 0xcf>;
				phandle = <0x228>;
			};
```

### `i2s1m1-sdo3` (Zeile 4810-4813)
```dts
			i2s1m1-sdo3 {
				rockchip,pins = <0x03 0x10 0x01 0xcf>;
				phandle = <0x229>;
			};
```

### `i2s2m0-lrck` (Zeile 4818-4821)
```dts
			i2s2m0-lrck {
				rockchip,pins = <0x01 0x1e 0x01 0xd1>;
				phandle = <0xa3>;
			};
```

### `i2s2m0-mclk` (Zeile 4823-4826)
```dts
			i2s2m0-mclk {
				rockchip,pins = <0x02 0x01 0x01 0xd1>;
				phandle = <0x22a>;
			};
```

### `i2s2m0-sclk` (Zeile 4828-4831)
```dts
			i2s2m0-sclk {
				rockchip,pins = <0x01 0x1d 0x01 0xd1>;
				phandle = <0xa4>;
			};
```

### `i2s2m0-sdi` (Zeile 4833-4836)
```dts
			i2s2m0-sdi {
				rockchip,pins = <0x02 0x00 0x01 0xcf>;
				phandle = <0xa5>;
			};
```

### `i2s2m0-sdo` (Zeile 4838-4841)
```dts
			i2s2m0-sdo {
				rockchip,pins = <0x01 0x1f 0x01 0xcf>;
				phandle = <0xa6>;
			};
```

### `i2s2m1-lrck` (Zeile 4843-4846)
```dts
			i2s2m1-lrck {
				rockchip,pins = <0x04 0x01 0x03 0xd1>;
				phandle = <0x22b>;
			};
```

### `i2s2m1-mclk` (Zeile 4848-4851)
```dts
			i2s2m1-mclk {
				rockchip,pins = <0x03 0x1e 0x03 0xd1>;
				phandle = <0x22c>;
			};
```

### `i2s2m1-sclk` (Zeile 4853-4856)
```dts
			i2s2m1-sclk {
				rockchip,pins = <0x04 0x09 0x04 0xd1>;
				phandle = <0x22d>;
			};
```

### `i2s2m1-sdi` (Zeile 4858-4861)
```dts
			i2s2m1-sdi {
				rockchip,pins = <0x03 0x1c 0x04 0xcf>;
				phandle = <0x22e>;
			};
```

### `i2s2m1-sdo` (Zeile 4863-4866)
```dts
			i2s2m1-sdo {
				rockchip,pins = <0x03 0x1d 0x04 0xcf>;
				phandle = <0x22f>;
			};
```

### `dummy-codec` (Zeile 5976-5981)
```dts
	dummy-codec {
		status = "okay";
		compatible = "rockchip,dummy-codec";
		#sound-dai-cells = <0x00>;
		phandle = <0xdb>;
	};
```

### `simple-audio-card,cpu` (Zeile 5989-5991)
```dts
		simple-audio-card,cpu {
			sound-dai = <0xda>;
		};
```

### `simple-audio-card,codec` (Zeile 5993-5995)
```dts
		simple-audio-card,codec {
			sound-dai = <0xdb>;
		};
```

### `spdif-out` (Zeile 5998-6003)
```dts
	spdif-out {
		status = "disabled";
		compatible = "linux,spdif-dit";
		#sound-dai-cells = <0x00>;
		phandle = <0xdd>;
	};
```

### `simple-audio-card,cpu` (Zeile 6012-6014)
```dts
		simple-audio-card,cpu {
			sound-dai = <0xdc>;
		};
```

### `simple-audio-card,codec` (Zeile 6016-6018)
```dts
		simple-audio-card,codec {
			sound-dai = <0xdd>;
		};
```

### `rk817-sound` (Zeile 6036-6058)
```dts
	rk817-sound {
		status = "okay";
		compatible = "rockchip,multicodecs-card";
		rockchip,card-name = "rockchip-rk817";
		hp-det-gpio = <0x3c 0x07 0x00>;
		io-channels = <0xd8 0x04>;
		io-channel-names = "adc-detect";
		keyup-threshold-microvolt = <0x1b7740>;
		poll-interval = <0x64>;
		rockchip,format = "i2s";
		rockchip,mclk-fs = <0x100>;
		rockchip,cpu = <0xde>;
		rockchip,codec = <0xdf>;
		pinctrl-names = "default";
		pinctrl-0 = <0xe0>;
		phandle = <0x2ae>;

		play-pause-key {
			label = "playpause";
			linux,code = <0xa4>;
			press-threshold-microvolt = <0x7d0>;
		};
	};
```

### `simple-audio-card,cpu` (Zeile 6068-6070)
```dts
		simple-audio-card,cpu {
			sound-dai = <0xe1>;
		};
```

### `simple-audio-card,codec` (Zeile 6072-6074)
```dts
		simple-audio-card,codec {
			sound-dai = <0xe2>;
		};
```

### `__symbols__` (Zeile 6275-6966)
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

## Display / Panel / VOP / DSI
### `route-dsi` (Zeile 529-537)
```dts
			route-dsi {
				status = "okay";
				logo,uboot = "logo.bmp";
				logo,kernel = "logo_kernel.bmp";
				logo,mode = "center";
				charge_logo,mode = "center";
				connect = <0x1b>;
				phandle = <0x106>;
			};
```

### `route-lvds` (Zeile 539-547)
```dts
			route-lvds {
				status = "disabled";
				logo,uboot = "logo.bmp";
				logo,kernel = "logo_kernel.bmp";
				logo,mode = "center";
				charge_logo,mode = "center";
				connect = <0x1c>;
				phandle = <0x107>;
			};
```

### `route-rgb` (Zeile 549-557)
```dts
			route-rgb {
				status = "okay";
				logo,uboot = "logo.bmp";
				logo,kernel = "logo_kernel.bmp";
				logo,mode = "center";
				charge_logo,mode = "center";
				connect = <0x1d>;
				phandle = <0x108>;
			};
```

### `rgb` (Zeile 1446-1479)
```dts
		rgb {
			compatible = "rockchip,rk3562-rgb";
			pinctrl-names = "default";
			pinctrl-0 = <0x39>;
			status = "okay";
			phandle = <0x154>;

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
						phandle = <0x7c>;
					};
				};

				port@1 {
					reg = <0x01>;

					endpoint {
						remote-endpoint = <0x3a>;
						phandle = <0xbf>;
					};
				};
			};
		};
```

### `vop@ff400000` (Zeile 2573-2622)
```dts
	vop@ff400000 {
		compatible = "rockchip,rk3562-vop";
		reg = <0x00 0xff400000 0x00 0x2000 0x00 0xff405000 0x00 0x1000>;
		reg-names = "regs\0gamma_lut";
		interrupts = <0x00 0x87 0x04>;
		clocks = <0x02 0x166 0x02 0x167 0x02 0x168>;
		clock-names = "aclk_vop\0hclk_vop\0dclk_vp0";
		resets = <0x02 0xd6 0x02 0xd7 0x02 0xd8>;
		reset-names = "axi\0ahb\0dclk_vp0";
		rockchip,csu = <0x79 0x02>;
		rockchip,csu-names = "aclk";
		iommus = <0x7a>;
		power-domains = <0x35 0x0d>;
		rockchip,grf = <0x7b>;
		assigned-clocks = <0x02 0x168>;
		assigned-clock-parents = <0x02 0x03>;
		status = "okay";
		phandle = <0x176>;

		ports {
			#address-cells = <0x01>;
			#size-cells = <0x00>;
			phandle = <0x18>;

			port@0 {
				#address-cells = <0x01>;
				#size-cells = <0x00>;
				reg = <0x00>;
				phandle = <0x177>;

				endpoint@0 {
					reg = <0x00>;
					remote-endpoint = <0x7c>;
					phandle = <0x1d>;
				};

				endpoint@1 {
					reg = <0x01>;
					remote-endpoint = <0x7d>;
					phandle = <0x1b>;
				};

				endpoint@2 {
					reg = <0x02>;
					remote-endpoint = <0x7e>;
					phandle = <0x1c>;
				};
			};
		};
	};
```

### `iommu@ff407e00` (Zeile 2624-2636)
```dts
	iommu@ff407e00 {
		compatible = "rockchip,iommu-v2";
		reg = <0x00 0xff407e00 0x00 0x100>;
		interrupts = <0x00 0x87 0x04>;
		interrupt-names = "vop_mmu";
		clocks = <0x02 0x166 0x02 0x167>;
		clock-names = "aclk\0iface";
		#iommu-cells = <0x00>;
		rockchip,disable-device-link-resume;
		rockchip,shootdown-entire;
		status = "okay";
		phandle = <0x7a>;
	};
```

### `rk628@50` (Zeile 3565-3591)
```dts
		rk628@50 {
			status = "okay";
			compatible = "rockchip,rk628";
			reg = <0x50>;
			#sound-dai-cells = <0x00>;
			interrupt-parent = <0x48>;
			interrupts = <0x12 0x04>;
			enable-gpios = <0x48 0x10 0x00>;
			reset-gpios = <0x48 0x11 0x01>;
			pinctrl-names = "default";
			pinctrl-0 = <0xbd 0xbe>;
			assigned-clocks = <0x02 0x132>;
			assigned-clock-rates = <0x16e3600>;
			clocks = <0x02 0x132>;
			clock-names = "soc_24M";
			rk628-rgb-in;
			rk628-hdmi-out;
			phandle = <0xe2>;

			port {

				endpoint {
					remote-endpoint = <0xbf>;
					phandle = <0x3a>;
				};
			};
		};
```

### `panel@0` (Zeile 3769-3828)
```dts
		panel@0 {
			status = "okay";
			compatible = "simple-panel-dsi";
			reg = <0x00>;
			backlight = <0xc9>;
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
			enable-gpios = <0x3c 0x08 0x00>;
			reset-gpios = <0x3c 0x14 0x01>;
			pinctrl-names = "default";
			pinctrl-0 = <0xca 0xcb>;
			init-delay-ms = <0x14>;
			phandle = <0x1a8>;

			display-timings {
				native-mode = <0xcc>;
				phandle = <0x1a9>;

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
					phandle = <0xcc>;
				};
			};

			ports {
				#address-cells = <0x01>;
				#size-cells = <0x00>;

				port@0 {
					reg = <0x00>;

					endpoint {
						remote-endpoint = <0xcd>;
						phandle = <0xc8>;
					};
				};
			};
		};
```

### `phy@ffb20000` (Zeile 3831-3843)
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
		phandle = <0x38>;
	};
```

### `rgb3x8-pins-m0` (Zeile 5808-5811)
```dts
			rgb3x8-pins-m0 {
				rockchip,pins = <0x04 0x0f 0x01 0xd6 0x03 0x14 0x01 0xd5 0x03 0x15 0x01 0xd5 0x03 0x16 0x01 0xd5 0x03 0x17 0x01 0xd5 0x03 0x18 0x01 0xd5 0x03 0x19 0x01 0xd5 0x03 0x1a 0x01 0xd5 0x03 0x1b 0x01 0xd5 0x04 0x0e 0x01 0xd5 0x04 0x0c 0x01 0xd5 0x04 0x0d 0x01 0xd5>;
				phandle = <0x2a4>;
			};
```

### `rgb3x8-pins-m1` (Zeile 5813-5816)
```dts
			rgb3x8-pins-m1 {
				rockchip,pins = <0x04 0x0f 0x01 0xd6 0x03 0x1c 0x01 0xd5 0x03 0x1d 0x01 0xd5 0x03 0x1e 0x01 0xd5 0x03 0x1f 0x01 0xd5 0x04 0x00 0x01 0xd5 0x04 0x01 0x01 0xd5 0x04 0x02 0x01 0xd5 0x04 0x03 0x01 0xd5 0x04 0x0e 0x01 0xd5 0x04 0x0c 0x01 0xd5 0x04 0x0d 0x01 0xd5>;
				phandle = <0x2a5>;
			};
```

### `rgb565-pins` (Zeile 5818-5821)
```dts
			rgb565-pins {
				rockchip,pins = <0x04 0x0f 0x01 0xd6 0x03 0x14 0x01 0xd5 0x03 0x15 0x01 0xd5 0x03 0x16 0x01 0xd5 0x03 0x17 0x01 0xd5 0x03 0x18 0x01 0xd5 0x03 0x19 0x01 0xd5 0x03 0x1a 0x01 0xd5 0x03 0x1b 0x01 0xd5 0x03 0x1c 0x01 0xd5 0x03 0x1d 0x01 0xd5 0x03 0x1e 0x01 0xd5 0x03 0x1f 0x01 0xd5 0x04 0x00 0x01 0xd5 0x04 0x01 0x01 0xd5 0x04 0x02 0x01 0xd5 0x04 0x03 0x01 0xd5 0x04 0x0e 0x01 0xd5 0x04 0x0c 0x01 0xd5 0x04 0x0d 0x01 0xd5>;
				phandle = <0x2a6>;
			};
```

### `rgb666-pins` (Zeile 5823-5826)
```dts
			rgb666-pins {
				rockchip,pins = <0x04 0x0f 0x01 0xd6 0x04 0x0a 0x01 0xd5 0x03 0x14 0x01 0xd5 0x03 0x15 0x01 0xd5 0x03 0x16 0x01 0xd5 0x03 0x17 0x01 0xd5 0x03 0x18 0x01 0xd5 0x03 0x19 0x01 0xd5 0x03 0x1a 0x01 0xd5 0x03 0x1b 0x01 0xd5 0x03 0x1c 0x01 0xd5 0x03 0x1d 0x01 0xd5 0x03 0x1e 0x01 0xd5 0x04 0x0b 0x01 0xd5 0x03 0x1f 0x01 0xd5 0x04 0x00 0x01 0xd5 0x04 0x01 0x01 0xd5 0x04 0x02 0x01 0xd5 0x04 0x03 0x01 0xd5 0x04 0x0e 0x01 0xd5 0x04 0x0c 0x01 0xd5 0x04 0x0d 0x01 0xd5>;
				phandle = <0x2a7>;
			};
```

### `lcd-rst-gpio` (Zeile 5855-5858)
```dts
			lcd-rst-gpio {
				rockchip,pins = <0x00 0x14 0x00 0xcf>;
				phandle = <0xca>;
			};
```

### `lcd-powerctrl-gpio` (Zeile 5860-5863)
```dts
			lcd-powerctrl-gpio {
				rockchip,pins = <0x00 0x08 0x00 0xcf>;
				phandle = <0xcb>;
			};
```

### `backlight` (Zeile 5968-5974)
```dts
	backlight {
		compatible = "pwm-backlight";
		pwms = <0xd9 0x00 0x61a8 0x00>;
		brightness-levels = <0x00 0x14 0x14 0x15 0x15 0x16 0x16 0x17 0x17 0x18 0x18 0x19 0x19 0x1a 0x1a 0x1b 0x1b 0x1c 0x1c 0x1d 0x1d 0x1e 0x1e 0x1f 0x1f 0x20 0x20 0x21 0x21 0x22 0x22 0x23 0x23 0x24 0x24 0x25 0x25 0x26 0x26 0x27 0x28 0x29 0x2a 0x2b 0x2c 0x2d 0x2e 0x2f 0x30 0x31 0x32 0x33 0x34 0x35 0x36 0x37 0x38 0x39 0x3a 0x3b 0x3c 0x3d 0x3e 0x3f 0x40 0x41 0x42 0x43 0x44 0x45 0x46 0x47 0x48 0x49 0x4a 0x4b 0x4c 0x4d 0x4e 0x4f 0x50 0x51 0x52 0x53 0x54 0x55 0x56 0x57 0x58 0x59 0x5a 0x5b 0x5c 0x5d 0x5e 0x5f 0x60 0x61 0x62 0x63 0x64 0x65 0x66 0x67 0x68 0x69 0x6a 0x6b 0x6c 0x6d 0x6e 0x6f 0x70 0x71 0x72 0x73 0x74 0x75 0x76 0x77 0x78 0x79 0x7a 0x7b 0x7c 0x7d 0x7e 0x7f 0x80 0x81 0x82 0x83 0x84 0x85 0x86 0x87 0x88 0x89 0x8a 0x8b 0x8c 0x8d 0x8e 0x8f 0x90 0x91 0x92 0x93 0x94 0x95 0x96 0x97 0x98 0x99 0x9a 0x9b 0x9c 0x9d 0x9e 0x9f 0xa0 0xa1 0xa2 0xa3 0xa4 0xa5 0xa6 0xa7 0xa8 0xa9 0xaa 0xab 0xac 0xad 0xae 0xaf 0xb0 0xb1 0xb2 0xb3 0xb4 0xb5 0xb6 0xb7 0xb8 0xb9 0xba 0xbb 0xbc 0xbd 0xbe 0xbf 0xc0 0xc1 0xc2 0xc3 0xc4 0xc5 0xc6 0xc7 0xc8 0xc9 0xca 0xcb 0xcc 0xcd 0xce 0xcf 0xd0 0xd1 0xd2 0xd3 0xd4 0xd5 0xd6 0xd7 0xd8 0xd9 0xda 0xdb 0xdc 0xdd 0xde 0xdf 0xe0 0xe1 0xe2 0xe3 0xe4 0xe5 0xe6 0xe7 0xe8 0xe9 0xea 0xeb 0xec 0xed 0xee 0xef 0xf0 0xf1 0xf2 0xf3 0xf4 0xf5 0xf6 0xf7 0xf8 0xf9 0xfa 0xfb 0xfc 0xfd 0xfe 0xff>;
		default-brightness-level = <0xc8>;
		phandle = <0xc9>;
	};
```

### `vcc3v3-lcd0-n` (Zeile 6025-6034)
```dts
	vcc3v3-lcd0-n {
		compatible = "regulator-fixed";
		regulator-name = "vcc3v3_lcd_n";
		regulator-boot-on;
		phandle = <0x2ad>;

		regulator-state-mem {
			regulator-off-in-suspend;
		};
	};
```

### `rk628-sound` (Zeile 6060-6075)
```dts
	rk628-sound {
		compatible = "simple-audio-card";
		simple-audio-card,format = "i2s";
		simple-audio-card,mclk-fs = <0x80>;
		simple-audio-card,name = "rockchip,hdmi-rk628";
		status = "okay";
		phandle = <0x2af>;

		simple-audio-card,cpu {
			sound-dai = <0xe1>;
		};

		simple-audio-card,codec {
			sound-dai = <0xe2>;
		};
	};
```

### `__symbols__` (Zeile 6275-6966)
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
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

## Touchscreen
_Nichts gefunden._

## USB / OTG / PHY
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
		mmc2 = "/mmc@ff890000";
	};
```

### `csi2-dphy0` (Zeile 470-475)
```dts
	csi2-dphy0 {
		compatible = "rockchip,rk3562-csi2-dphy";
		rockchip,hw = <0x16 0x17>;
		status = "disabled";
		phandle = <0xff>;
	};
```

### `csi2-dphy1` (Zeile 477-482)
```dts
	csi2-dphy1 {
		compatible = "rockchip,rk3562-csi2-dphy";
		rockchip,hw = <0x16 0x17>;
		status = "disabled";
		phandle = <0x100>;
	};
```

### `csi2-dphy2` (Zeile 484-489)
```dts
	csi2-dphy2 {
		compatible = "rockchip,rk3562-csi2-dphy";
		rockchip,hw = <0x16 0x17>;
		status = "disabled";
		phandle = <0x101>;
	};
```

### `csi2-dphy3` (Zeile 491-496)
```dts
	csi2-dphy3 {
		compatible = "rockchip,rk3562-csi2-dphy";
		rockchip,hw = <0x16 0x17>;
		status = "disabled";
		phandle = <0x102>;
	};
```

### `csi2-dphy4` (Zeile 498-503)
```dts
	csi2-dphy4 {
		compatible = "rockchip,rk3562-csi2-dphy";
		rockchip,hw = <0x16 0x17>;
		status = "disabled";
		phandle = <0x103>;
	};
```

### `csi2-dphy5` (Zeile 505-510)
```dts
	csi2-dphy5 {
		compatible = "rockchip,rk3562-csi2-dphy";
		rockchip,hw = <0x16 0x17>;
		status = "disabled";
		phandle = <0x104>;
	};
```

### `usb@fe500000` (Zeile 968-995)
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
			extcon = <0x36>;
			maximum-speed = "high-speed";
			snps,dis_u2_susphy_quirk;
			snps,usb2-lpm-disable;
			phandle = <0x12d>;
		};
```

### `usb@fed00000` (Zeile 1008-1018)
```dts
	usb@fed00000 {
		compatible = "generic-ehci";
		reg = <0x00 0xfed00000 0x00 0x40000>;
		interrupts = <0x00 0x96 0x04>;
		clocks = <0x02 0x9e 0x02 0x9f 0x36>;
		clock-names = "usbhost\0arbiter\0utmi";
		phys = <0x37>;
		phy-names = "usb2-phy";
		status = "disabled";
		phandle = <0x12e>;
	};
```

### `usb@fed40000` (Zeile 1020-1030)
```dts
	usb@fed40000 {
		compatible = "generic-ohci";
		reg = <0x00 0xfed40000 0x00 0x40000>;
		interrupts = <0x00 0x97 0x04>;
		clocks = <0x02 0x9e 0x02 0x9f 0x36>;
		clock-names = "usbhost\0arbiter\0utmi";
		phys = <0x37>;
		phy-names = "usb2-phy";
		status = "disabled";
		phandle = <0x12f>;
	};
```

### `lvds` (Zeile 1408-1432)
```dts
		lvds {
			compatible = "rockchip,rk3562-lvds";
			phys = <0x38>;
			phy-names = "phy";
			status = "disabled";
			phandle = <0x153>;

			ports {
				#address-cells = <0x01>;
				#size-cells = <0x00>;

				port@0 {
					reg = <0x00>;
					#address-cells = <0x01>;
					#size-cells = <0x00>;

					endpoint@0 {
						reg = <0x00>;
						remote-endpoint = <0x1c>;
						status = "disabled";
						phandle = <0x7e>;
					};
				};
			};
		};
```

### `syscon@ff090000` (Zeile 1482-1486)
```dts
	syscon@ff090000 {
		compatible = "rockchip,rk3562-usbphy-grf\0syscon";
		reg = <0x00 0xff090000 0x00 0x8000>;
		phandle = <0x98>;
	};
```

### `syscon@ff098000` (Zeile 1488-1492)
```dts
	syscon@ff098000 {
		compatible = "rockchip,rk3562-pipephy-grf\0syscon";
		reg = <0x00 0xff098000 0x00 0x8000>;
		phandle = <0x9a>;
	};
```

### `OTG_SWITCH` (Zeile 1783-1790)
```dts
				OTG_SWITCH {
					regulator-name = "otg_switch";
					phandle = <0x164>;

					regulator-state-mem {
						regulator-off-in-suspend;
					};
				};
```

### `charger` (Zeile 1837-1850)
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
				extcon = <0x36>;
				gate_function_disable = <0x01>;
			};
```

### `csi2-dphy0-hw@ff3c0000` (Zeile 2491-2501)
```dts
	csi2-dphy0-hw@ff3c0000 {
		compatible = "rockchip,rk3562-csi2-dphy-hw";
		reg = <0x00 0xff3c0000 0x00 0x10000>;
		clocks = <0x02 0x162>;
		clock-names = "pclk";
		resets = <0x02 0xc4>;
		reset-names = "srst_p_csiphy0";
		rockchip,grf = <0x0e>;
		status = "okay";
		phandle = <0x16>;
	};
```

### `csi2-dphy1-hw@ff3d0000` (Zeile 2503-2513)
```dts
	csi2-dphy1-hw@ff3d0000 {
		compatible = "rockchip,rk3562-csi2-dphy-hw";
		reg = <0x00 0xff3d0000 0x00 0x10000>;
		clocks = <0x02 0x163>;
		clock-names = "pclk";
		resets = <0x02 0xc5>;
		reset-names = "srst_p_csiphy1";
		rockchip,grf = <0x0e>;
		status = "okay";
		phandle = <0x17>;
	};
```

### `pcie@ff500000` (Zeile 2704-2741)
```dts
	pcie@ff500000 {
		compatible = "rockchip,rk3562-pcie\0snps,dw-pcie";
		#address-cells = <0x03>;
		#size-cells = <0x02>;
		bus-range = <0x00 0xff>;
		clocks = <0x02 0x107 0x02 0x108 0x02 0x109 0x02 0x10a 0x02 0x10b>;
		clock-names = "aclk_mst\0aclk_slv\0aclk_dbi\0pclk\0aux";
		device_type = "pci";
		interrupts = <0x00 0x92 0x04 0x00 0x91 0x04 0x00 0x90 0x04 0x00 0x8f 0x04 0x00 0x8e 0x04 0x00 0x8d 0x04>;
		interrupt-names = "msi\0pmc\0sys\0legacy\0msg\0err";
		#interrupt-cells = <0x01>;
		interrupt-map-mask = <0x00 0x00 0x00 0x07>;
		interrupt-map = <0x00 0x00 0x00 0x01 0x82 0x00 0x00 0x00 0x00 0x02 0x82 0x01 0x00 0x00 0x00 0x03 0x82 0x02 0x00 0x00 0x00 0x04 0x82 0x03>;
		linux,pci-domain = <0x00>;
		num-ib-windows = <0x08>;
		num-viewport = <0x08>;
		num-ob-windows = <0x02>;
		max-link-speed = <0x02>;
		num-lanes = <0x01>;
		phys = <0x83 0x02>;
		phy-names = "pcie-phy";
		power-domains = <0x35 0x0f>;
		ranges = <0x800 0x00 0xfc000000 0x00 0xfc000000 0x00 0x100000 0x81000000 0x00 0xfc100000 0x00 0xfc100000 0x00 0x100000 0x82000000 0x00 0xfc200000 0x00 0xfc200000 0x00 0x1e00000 0xc3000000 0x03 0x00 0x03 0x00 0x00 0x40000000>;
		reg = <0x00 0xfe000000 0x00 0x400000 0x00 0xff500000 0x00 0x10000>;
		reg-names = "pcie-dbi\0pcie-apb";
		resets = <0x02 0x108>;
		reset-names = "pipe";
		status = "disabled";
		phandle = <0x17a>;

		legacy-interrupt-controller {
			interrupt-controller;
			#address-cells = <0x00>;
			#interrupt-cells = <0x01>;
			interrupt-parent = <0x01>;
			phandle = <0x82>;
		};
	};
```

### `otg-port` (Zeile 3101-3107)
```dts
		otg-port {
			#phy-cells = <0x00>;
			interrupts = <0x00 0x99 0x04 0x00 0x9a 0x04 0x00 0x9b 0x04>;
			interrupt-names = "otg-bvalid\0otg-id\0linestate";
			status = "okay";
			phandle = <0x34>;
		};
```

### `host-port` (Zeile 3109-3115)
```dts
		host-port {
			#phy-cells = <0x00>;
			interrupts = <0x00 0x9c 0x04>;
			interrupt-names = "linestate";
			status = "disabled";
			phandle = <0x37>;
		};
```

### `phy@ff750000` (Zeile 3118-3132)
```dts
	phy@ff750000 {
		compatible = "rockchip,rk3562-naneng-combphy";
		reg = <0x00 0xff750000 0x00 0x100>;
		#phy-cells = <0x01>;
		clocks = <0x02 0x13a 0x02 0xfc 0x02 0x106>;
		clock-names = "refclk\0apbclk\0pipe_clk";
		assigned-clocks = <0x02 0x13a>;
		assigned-clock-rates = <0x5f5e100>;
		resets = <0x02 0xc00f7 0x02 0x113>;
		reset-names = "combphy-apb\0combphy";
		rockchip,pipe-grf = <0x99>;
		rockchip,pipe-phy-grf = <0x9a>;
		status = "okay";
		phandle = <0x83>;
	};
```

### `otp@ff930000` (Zeile 3355-3475)
```dts
	otp@ff930000 {
		compatible = "rockchip,rk3562-otp";
		reg = <0x00 0xff930000 0x00 0x4000>;
		#address-cells = <0x01>;
		#size-cells = <0x01>;
		clocks = <0x02 0xf5 0x02 0xf4 0x02 0xf3 0x02 0xfa>;
		clock-names = "usr\0sbpi\0apb\0phy";
		resets = <0x02 0xc00e2 0x02 0xc00e1 0x02 0xc00e0 0x02 0xc00e6 0x02 0xc00e7>;
		reset-names = "usr\0sbpi\0apb\0arb\0phy";
		phandle = <0x199>;

		cpu-code@2 {
			reg = <0x02 0x02>;
			phandle = <0x15>;
		};

		specification-serial-number@7 {
			reg = <0x07 0x01>;
			bits = <0x00 0x05>;
			phandle = <0x0d>;
		};

		cpu-version@8 {
			reg = <0x08 0x01>;
			bits = <0x03 0x03>;
			phandle = <0x14>;
		};

		mbist-vmin@9 {
			reg = <0x09 0x01>;
			bits = <0x00 0x02>;
			phandle = <0x0b>;
		};

		log-mbist-vmin@9 {
			reg = <0x09 0x01>;
			bits = <0x04 0x02>;
			phandle = <0x23>;
		};

		id@a {
			reg = <0x0a 0x10>;
			phandle = <0x13>;
		};

		cpu-leakage@1a {
			reg = <0x1a 0x01>;
			phandle = <0x09>;
		};

		log-leakage@1b {
			reg = <0x1b 0x01>;
			phandle = <0x21>;
		};

		npu-leakage@1c {
			reg = <0x1c 0x01>;
			phandle = <0x6d>;
		};

		gpu-leakage@1d {
			reg = <0x1d 0x01>;
			phandle = <0x72>;
		};

		cpu-tsadc-trim-l@2a {
			reg = <0x2a 0x01>;
			phandle = <0xc1>;
		};

		cpu-tsadc-trim-h@2b {
			reg = <0x2b 0x01>;
			phandle = <0xc2>;
		};

		tsadc-trim-base-frac@2c {
			reg = <0x2c 0x01>;
			bits = <0x04 0x04>;
			phandle = <0xc4>;
		};
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `tsadc@ffa70000` (Zeile 3627-3646)
```dts
	tsadc@ffa70000 {
		compatible = "rockchip,rk3562-tsadc";
		reg = <0x00 0xffa70000 0x00 0x400>;
		rockchip,grf = <0x0e>;
		interrupts = <0x00 0x7d 0x04>;
		clocks = <0x02 0x41 0x02 0x42 0x02 0x40>;
		clock-names = "tsadc\0tsadc_tsen\0apb_pclk";
		assigned-clocks = <0x02 0x41 0x02 0x42>;
		assigned-clock-rates = <0x124f80 0xb71b00>;
		resets = <0x02 0x181 0x02 0x180 0x02 0x182>;
		reset-names = "tsadc\0tsadc-apb\0tsadc-phy";
		#thermal-sensor-cells = <0x01>;
		rockchip,hw-tshut-temp = <0x1d4c0>;
		rockchip,hw-tshut-mode = <0x00>;
		rockchip,hw-tshut-polarity = <0x00>;
		nvmem-cells = <0xc1 0xc2 0xc3 0xc4>;
		nvmem-cell-names = "trim_l\0trim_h\0trim_base\0trim_base_frac";
		status = "okay";
		phandle = <0x30>;
	};
```

### `dsi@ffb10000` (Zeile 3725-3829)
```dts
	dsi@ffb10000 {
		compatible = "rockchip,rk3562-mipi-dsi";
		reg = <0x00 0xffb10000 0x00 0x10000>;
		interrupts = <0x00 0x84 0x04>;
		clocks = <0x02 0x4e>;
		clock-names = "pclk";
		resets = <0x02 0x199>;
		reset-names = "apb";
		phys = <0x38>;
		phy-names = "dphy";
		rockchip,grf = <0x0e>;
		#address-cells = <0x01>;
		#size-cells = <0x00>;
		status = "okay";
		phandle = <0x1a6>;

		ports {
			#address-cells = <0x01>;
			#size-cells = <0x00>;

			port@0 {
				reg = <0x00>;
				#address-cells = <0x01>;
				#size-cells = <0x00>;
				phandle = <0x1a7>;

				endpoint@0 {
					reg = <0x00>;
					remote-endpoint = <0x1b>;
					status = "okay";
					phandle = <0x7d>;
				};
			};

			port@1 {
				reg = <0x01>;

				endpoint {
					remote-endpoint = <0xc8>;
					phandle = <0xcd>;
				};
			};
		};

		panel@0 {
			status = "okay";
			compatible = "simple-panel-dsi";
			reg = <0x00>;
			backlight = <0xc9>;
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
			enable-gpios = <0x3c 0x08 0x00>;
			reset-gpios = <0x3c 0x14 0x01>;
			pinctrl-names = "default";
			pinctrl-0 = <0xca 0xcb>;
			init-delay-ms = <0x14>;
			phandle = <0x1a8>;

			display-timings {
				native-mode = <0xcc>;
				phandle = <0x1a9>;

				timing0 {
					clock-frequency = <0x3a2c940>;
					hactive = <0x400>;
					vactive = <0x300>;
					hfront-porch = <0x5a>;
					hsync-len = <0x50>;
					hback-porch = <0x50>;
					vfront-porch = <0x10>;
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `phy@ffb20000` (Zeile 3831-3843)
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
		phandle = <0x38>;
	};
```

### `__symbols__` (Zeile 6275-6966)
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

## LEDs / PWM
### `pwm@ff230000` (Zeile 1884-1895)
```dts
	pwm@ff230000 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff230000 0x00 0x10>;
		interrupts = <0x00 0x14 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x4e>;
		clocks = <0x02 0x130 0x02 0x12f>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x168>;
	};
```

### `pwm@ff230010` (Zeile 1897-1908)
```dts
	pwm@ff230010 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff230010 0x00 0x10>;
		interrupts = <0x00 0x14 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x4f>;
		clocks = <0x02 0x130 0x02 0x12f>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x169>;
	};
```

### `pwm@ff230020` (Zeile 1910-1921)
```dts
	pwm@ff230020 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff230020 0x00 0x10>;
		interrupts = <0x00 0x14 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x50>;
		clocks = <0x02 0x130 0x02 0x12f>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x16a>;
	};
```

### `pwm@ff230030` (Zeile 1923-1934)
```dts
	pwm@ff230030 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff230030 0x00 0x10>;
		interrupts = <0x00 0x14 0x04 0x00 0x15 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x51>;
		clocks = <0x02 0x130 0x02 0x12f>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x16b>;
	};
```

### `pwm@ff700000` (Zeile 2920-2931)
```dts
	pwm@ff700000 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff700000 0x00 0x10>;
		interrupts = <0x00 0x16 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x8b>;
		clocks = <0x02 0xd4 0x02 0xd3>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x188>;
	};
```

### `pwm@ff700010` (Zeile 2933-2944)
```dts
	pwm@ff700010 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff700010 0x00 0x10>;
		interrupts = <0x00 0x16 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x8c>;
		clocks = <0x02 0xd4 0x02 0xd3>;
		clock-names = "pwm\0pclk";
		status = "okay";
		phandle = <0xd9>;
	};
```

### `pwm@ff700020` (Zeile 2946-2957)
```dts
	pwm@ff700020 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff700020 0x00 0x10>;
		interrupts = <0x00 0x16 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x8d>;
		clocks = <0x02 0xd4 0x02 0xd3>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0xe7>;
	};
```

### `pwm@ff700030` (Zeile 2959-2970)
```dts
	pwm@ff700030 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff700030 0x00 0x10>;
		interrupts = <0x00 0x16 0x04 0x00 0x17 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x8e>;
		clocks = <0x02 0xd4 0x02 0xd3>;
		clock-names = "pwm\0pclk";
		status = "okay";
		phandle = <0xe6>;
	};
```

### `pwm@ff710000` (Zeile 2972-2983)
```dts
	pwm@ff710000 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff710000 0x00 0x10>;
		interrupts = <0x00 0x18 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x8f>;
		clocks = <0x02 0xd7 0x02 0xd6>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x189>;
	};
```

### `pwm@ff710010` (Zeile 2985-2996)
```dts
	pwm@ff710010 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff710010 0x00 0x10>;
		interrupts = <0x00 0x18 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x90>;
		clocks = <0x02 0xd7 0x02 0xd6>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x18a>;
	};
```

### `pwm@ff710020` (Zeile 2998-3009)
```dts
	pwm@ff710020 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff710020 0x00 0x10>;
		interrupts = <0x00 0x18 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x91>;
		clocks = <0x02 0xd7 0x02 0xd6>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x18b>;
	};
```

### `pwm@ff710030` (Zeile 3011-3022)
```dts
	pwm@ff710030 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff710030 0x00 0x10>;
		interrupts = <0x00 0x18 0x04 0x00 0x19 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x92>;
		clocks = <0x02 0xd7 0x02 0xd6>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x18c>;
	};
```

### `pwm@ff720000` (Zeile 3024-3035)
```dts
	pwm@ff720000 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff720000 0x00 0x10>;
		interrupts = <0x00 0x1a 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x93>;
		clocks = <0x02 0xda 0x02 0xd9>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x18d>;
	};
```

### `pwm@ff720010` (Zeile 3037-3048)
```dts
	pwm@ff720010 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff720010 0x00 0x10>;
		interrupts = <0x00 0x1a 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x94>;
		clocks = <0x02 0xda 0x02 0xd9>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x18e>;
	};
```

### `pwm@ff720020` (Zeile 3050-3061)
```dts
	pwm@ff720020 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff720020 0x00 0x10>;
		interrupts = <0x00 0x1a 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x95>;
		clocks = <0x02 0xda 0x02 0xd9>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x18f>;
	};
```

### `pwm@ff720030` (Zeile 3063-3074)
```dts
	pwm@ff720030 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff720030 0x00 0x10>;
		interrupts = <0x00 0x1a 0x04 0x00 0x1b 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x96>;
		clocks = <0x02 0xda 0x02 0xd9>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x190>;
	};
```

### `pwm0m0-pins` (Zeile 5007-5010)
```dts
			pwm0m0-pins {
				rockchip,pins = <0x00 0x13 0x02 0xd4>;
				phandle = <0x4e>;
			};
```

### `pwm0m1-pins` (Zeile 5012-5015)
```dts
			pwm0m1-pins {
				rockchip,pins = <0x01 0x15 0x04 0xd4>;
				phandle = <0x23e>;
			};
```

### `pwm1m0-pins` (Zeile 5020-5023)
```dts
			pwm1m0-pins {
				rockchip,pins = <0x00 0x14 0x02 0xd4>;
				phandle = <0x4f>;
			};
```

### `pwm1m1-pins` (Zeile 5025-5028)
```dts
			pwm1m1-pins {
				rockchip,pins = <0x01 0x16 0x04 0xd4>;
				phandle = <0x23f>;
			};
```

### `pwm2m0-pins` (Zeile 5033-5036)
```dts
			pwm2m0-pins {
				rockchip,pins = <0x00 0x15 0x02 0xd4>;
				phandle = <0x50>;
			};
```

### `pwm2m1-pins` (Zeile 5038-5041)
```dts
			pwm2m1-pins {
				rockchip,pins = <0x01 0x17 0x03 0xd4>;
				phandle = <0x240>;
			};
```

### `pwm3m0-pins` (Zeile 5046-5049)
```dts
			pwm3m0-pins {
				rockchip,pins = <0x00 0x07 0x01 0xd4>;
				phandle = <0x51>;
			};
```

### `pwm3m1-pins` (Zeile 5051-5054)
```dts
			pwm3m1-pins {
				rockchip,pins = <0x01 0x18 0x03 0xd4>;
				phandle = <0x241>;
			};
```

### `pwm4m0-pins` (Zeile 5059-5062)
```dts
			pwm4m0-pins {
				rockchip,pins = <0x00 0x0f 0x02 0xd4>;
				phandle = <0x8b>;
			};
```

### `pwm4m1-pins` (Zeile 5064-5067)
```dts
			pwm4m1-pins {
				rockchip,pins = <0x01 0x19 0x04 0xd4>;
				phandle = <0x242>;
			};
```

### `pwm5m0-pins` (Zeile 5072-5075)
```dts
			pwm5m0-pins {
				rockchip,pins = <0x00 0x12 0x02 0xd4>;
				phandle = <0x8c>;
			};
```

### `pwm5m1-pins` (Zeile 5077-5080)
```dts
			pwm5m1-pins {
				rockchip,pins = <0x01 0x1a 0x04 0xd4>;
				phandle = <0x243>;
			};
```

### `pwm6m0-pins` (Zeile 5085-5088)
```dts
			pwm6m0-pins {
				rockchip,pins = <0x00 0x11 0x02 0xd4>;
				phandle = <0x8d>;
			};
```

### `pwm6m1-pins` (Zeile 5090-5093)
```dts
			pwm6m1-pins {
				rockchip,pins = <0x01 0x1b 0x04 0xd4>;
				phandle = <0x244>;
			};
```

### `pwm7m0-pins` (Zeile 5098-5101)
```dts
			pwm7m0-pins {
				rockchip,pins = <0x00 0x10 0x02 0xd4>;
				phandle = <0x8e>;
			};
```

### `pwm7m1-pins` (Zeile 5103-5106)
```dts
			pwm7m1-pins {
				rockchip,pins = <0x01 0x1c 0x04 0xd4>;
				phandle = <0x245>;
			};
```

### `pwm8m0-pins` (Zeile 5111-5114)
```dts
			pwm8m0-pins {
				rockchip,pins = <0x03 0x04 0x02 0xd4>;
				phandle = <0x8f>;
			};
```

### `pwm8m1-pins` (Zeile 5116-5119)
```dts
			pwm8m1-pins {
				rockchip,pins = <0x01 0x11 0x04 0xd4>;
				phandle = <0x246>;
			};
```

### `pwm9m0-pins` (Zeile 5124-5127)
```dts
			pwm9m0-pins {
				rockchip,pins = <0x03 0x05 0x02 0xd4>;
				phandle = <0x90>;
			};
```

### `pwm9m1-pins` (Zeile 5129-5132)
```dts
			pwm9m1-pins {
				rockchip,pins = <0x01 0x12 0x04 0xd4>;
				phandle = <0x247>;
			};
```

### `pwm10m0-pins` (Zeile 5137-5140)
```dts
			pwm10m0-pins {
				rockchip,pins = <0x01 0x0d 0x05 0xd4>;
				phandle = <0x91>;
			};
```

### `pwm10m1-pins` (Zeile 5142-5145)
```dts
			pwm10m1-pins {
				rockchip,pins = <0x01 0x13 0x04 0xd4>;
				phandle = <0x248>;
			};
```

### `pwm11m0-pins` (Zeile 5150-5153)
```dts
			pwm11m0-pins {
				rockchip,pins = <0x01 0x0e 0x05 0xd4>;
				phandle = <0x92>;
			};
```

### `pwm11m1-pins` (Zeile 5155-5158)
```dts
			pwm11m1-pins {
				rockchip,pins = <0x01 0x14 0x04 0xd4>;
				phandle = <0x249>;
			};
```

### `pwm12m0-pins` (Zeile 5163-5166)
```dts
			pwm12m0-pins {
				rockchip,pins = <0x04 0x01 0x04 0xd4>;
				phandle = <0x93>;
			};
```

### `pwm12m1-pins` (Zeile 5168-5171)
```dts
			pwm12m1-pins {
				rockchip,pins = <0x03 0x0c 0x05 0xd4>;
				phandle = <0x24a>;
			};
```

### `pwm13m0-pins` (Zeile 5176-5179)
```dts
			pwm13m0-pins {
				rockchip,pins = <0x04 0x04 0x03 0xd4>;
				phandle = <0x94>;
			};
```

### `pwm13m1-pins` (Zeile 5181-5184)
```dts
			pwm13m1-pins {
				rockchip,pins = <0x03 0x0d 0x05 0xd4>;
				phandle = <0x24b>;
			};
```

### `pwm14m0-pins` (Zeile 5189-5192)
```dts
			pwm14m0-pins {
				rockchip,pins = <0x03 0x15 0x04 0xd4>;
				phandle = <0x95>;
			};
```

### `pwm14m1-pins` (Zeile 5194-5197)
```dts
			pwm14m1-pins {
				rockchip,pins = <0x01 0x1f 0x05 0xd4>;
				phandle = <0x24c>;
			};
```

### `pwm15m0-pins` (Zeile 5202-5205)
```dts
			pwm15m0-pins {
				rockchip,pins = <0x03 0x16 0x04 0xd4>;
				phandle = <0x96>;
			};
```

### `pwm15m1-pins` (Zeile 5207-5210)
```dts
			pwm15m1-pins {
				rockchip,pins = <0x02 0x00 0x05 0xd4>;
				phandle = <0x24d>;
			};
```

### `backlight` (Zeile 5968-5974)
```dts
	backlight {
		compatible = "pwm-backlight";
		pwms = <0xd9 0x00 0x61a8 0x00>;
		brightness-levels = <0x00 0x14 0x14 0x15 0x15 0x16 0x16 0x17 0x17 0x18 0x18 0x19 0x19 0x1a 0x1a 0x1b 0x1b 0x1c 0x1c 0x1d 0x1d 0x1e 0x1e 0x1f 0x1f 0x20 0x20 0x21 0x21 0x22 0x22 0x23 0x23 0x24 0x24 0x25 0x25 0x26 0x26 0x27 0x28 0x29 0x2a 0x2b 0x2c 0x2d 0x2e 0x2f 0x30 0x31 0x32 0x33 0x34 0x35 0x36 0x37 0x38 0x39 0x3a 0x3b 0x3c 0x3d 0x3e 0x3f 0x40 0x41 0x42 0x43 0x44 0x45 0x46 0x47 0x48 0x49 0x4a 0x4b 0x4c 0x4d 0x4e 0x4f 0x50 0x51 0x52 0x53 0x54 0x55 0x56 0x57 0x58 0x59 0x5a 0x5b 0x5c 0x5d 0x5e 0x5f 0x60 0x61 0x62 0x63 0x64 0x65 0x66 0x67 0x68 0x69 0x6a 0x6b 0x6c 0x6d 0x6e 0x6f 0x70 0x71 0x72 0x73 0x74 0x75 0x76 0x77 0x78 0x79 0x7a 0x7b 0x7c 0x7d 0x7e 0x7f 0x80 0x81 0x82 0x83 0x84 0x85 0x86 0x87 0x88 0x89 0x8a 0x8b 0x8c 0x8d 0x8e 0x8f 0x90 0x91 0x92 0x93 0x94 0x95 0x96 0x97 0x98 0x99 0x9a 0x9b 0x9c 0x9d 0x9e 0x9f 0xa0 0xa1 0xa2 0xa3 0xa4 0xa5 0xa6 0xa7 0xa8 0xa9 0xaa 0xab 0xac 0xad 0xae 0xaf 0xb0 0xb1 0xb2 0xb3 0xb4 0xb5 0xb6 0xb7 0xb8 0xb9 0xba 0xbb 0xbc 0xbd 0xbe 0xbf 0xc0 0xc1 0xc2 0xc3 0xc4 0xc5 0xc6 0xc7 0xc8 0xc9 0xca 0xcb 0xcc 0xcd 0xce 0xcf 0xd0 0xd1 0xd2 0xd3 0xd4 0xd5 0xd6 0xd7 0xd8 0xd9 0xda 0xdb 0xdc 0xdd 0xde 0xdf 0xe0 0xe1 0xe2 0xe3 0xe4 0xe5 0xe6 0xe7 0xe8 0xe9 0xea 0xeb 0xec 0xed 0xee 0xef 0xf0 0xf1 0xf2 0xf3 0xf4 0xf5 0xf6 0xf7 0xf8 0xf9 0xfa 0xfb 0xfc 0xfd 0xfe 0xff>;
		default-brightness-level = <0xc8>;
		phandle = <0xc9>;
	};
```

### `vdd-gpu` (Zeile 6122-6135)
```dts
	vdd-gpu {
		compatible = "pwm-regulator";
		pwms = <0xe6 0x00 0x1388 0x01>;
		regulator-name = "vdd_gpu";
		regulator-min-microvolt = "\0\f5";
		regulator-max-microvolt = <0x10c8e0>;
		regulator-init-microvolt = <0xdbba0>;
		regulator-always-on;
		regulator-boot-on;
		regulator-settling-time-up-us = <0xfa>;
		pwm-supply = <0x43>;
		status = "okay";
		phandle = <0x71>;
	};
```

### `vdd-npu` (Zeile 6137-6150)
```dts
	vdd-npu {
		compatible = "pwm-regulator";
		pwms = <0xe7 0x00 0x1388 0x01>;
		regulator-name = "vdd_npu";
		regulator-min-microvolt = "\0\f5";
		regulator-max-microvolt = <0x10c8e0>;
		regulator-init-microvolt = <0xdbba0>;
		regulator-always-on;
		regulator-boot-on;
		regulator-settling-time-up-us = <0xfa>;
		pwm-supply = <0x43>;
		status = "disabled";
		phandle = <0x6c>;
	};
```

### `__symbols__` (Zeile 6275-6966)
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

## Thermal-Zonen & Kühlung
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
			opp-microvolt-L0 = <0xe1d48 0xe1d48 0x118c30>;
			opp-microvolt-L1 = <0xdbba0 0xdbba0 0x118c30>;
			opp-microvolt-L2 = <0xd59f8 0xd59f8 0x118c30>;
			opp-microvolt-L3 = <0xcf850 0xcf850 0x118c30>;
			opp-microvolt-L4 = <0xc96a8 0xc96a8 0x118c30>;
			clock-latency-ns = <0x9c40>;
		};

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

    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `rockchip-system-monitor` (Zeile 883-887)
```dts
	rockchip-system-monitor {
		compatible = "rockchip,system-monitor";
		rockchip,thermal-zone = "soc-thermal";
		phandle = <0x126>;
	};
```

### `cooling-maps` (Zeile 923-936)
```dts
			cooling-maps {

				map0 {
					trip = <0x31>;
					cooling-device = <0x0f 0xffffffff 0xffffffff>;
					contribution = <0x400>;
				};

				map1 {
					trip = <0x31>;
					cooling-device = <0x32 0xffffffff 0xffffffff>;
					contribution = <0x400>;
				};
			};
```

### `npu-opp-table` (Zeile 2032-2195)
```dts
	npu-opp-table {
		compatible = "operating-points-v2";
		mbist-vmin = <0xc96a8 0xdbba0 0xee098>;
		nvmem-cells = <0x6d 0x6e 0x0b 0x6f 0x0d>;
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
		phandle = <0x6a>;

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

		opp-900000000 {
			opp-supported-hw = <0xf9 0xffff>;
			opp-hz = <0x00 0x35a4e900>;
			opp-microvolt = <0xf4240 0xf4240 0xf4240>;
			opp-microvolt-L0 = <0xf4240 0xf4240 0xf4240>;
			opp-microvolt-L1 = <0xf4240 0xf4240 0xf4240>;
			opp-microvolt-L2 = <0xee098 0xee098 0xf4240>;
			opp-microvolt-L3 = <0xe7ef0 0xe7ef0 0xf4240>;
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `gpu-opp-table` (Zeile 2228-2361)
```dts
	gpu-opp-table {
		compatible = "operating-points-v2";
		mbist-vmin = <0xc96a8 0xdbba0 0xee098>;
		nvmem-cells = <0x72 0x73 0x0b 0x74 0x0d>;
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
		phandle = <0x70>;

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
			opp-microvolt-L0 = <0xe7ef0 0xe7ef0 0xf4240>;
			opp-microvolt-L1 = <0xe1d48 0xe1d48 0xf4240>;
			opp-microvolt-L2 = <0xdbba0 0xdbba0 0xf4240>;
			opp-microvolt-L3 = <0xd59f8 0xd59f8 0xf4240>;
			opp-microvolt-L4 = <0xcf850 0xcf850 0xf4240>;
		};

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

		opp-j-300000000 {
			opp-supported-hw = <0x04 0xffff>;
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `__symbols__` (Zeile 6275-6966)
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

## Pinctrl (Pin-Multiplexing - Auszüge)
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
		mmc2 = "/mmc@ff890000";
	};
```

### `rgb` (Zeile 1446-1479)
```dts
		rgb {
			compatible = "rockchip,rk3562-rgb";
			pinctrl-names = "default";
			pinctrl-0 = <0x39>;
			status = "okay";
			phandle = <0x154>;

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
						phandle = <0x7c>;
					};
				};

				port@1 {
					reg = <0x01>;

					endpoint {
						remote-endpoint = <0x3a>;
						phandle = <0xbf>;
					};
				};
			};
		};
```

### `pinctrl_rk8xx` (Zeile 1550-1590)
```dts
			pinctrl_rk8xx {
				gpio-controller;
				#gpio-cells = <0x02>;
				phandle = <0x157>;

				rk817_slppin_null {
					pins = "gpio_slp";
					function = "pin_fun0";
					phandle = <0x158>;
				};

				rk817_slppin_slp {
					pins = "gpio_slp";
					function = "pin_fun1";
					phandle = <0x3f>;
				};

				rk817_slppin_pwrdn {
					pins = "gpio_slp";
					function = "pin_fun2";
					phandle = <0x41>;
				};

				rk817_slppin_rst {
					pins = "gpio_slp";
					function = "pin_fun3";
					phandle = <0x42>;
				};

				rk817_ts_gpio1 {
					pins = "gpio_ts";
					function = "pin_fun1";
					phandle = <0x159>;
				};

				rk817_pin_ts {
					pins = "gpio_ts";
					function = "pin_fun0";
					phandle = <0x15a>;
				};
			};
```

### `codec` (Zeile 1793-1811)
```dts
			codec {
				#sound-dai-cells = <0x00>;
				compatible = "rockchip,rk817-codec";
				clocks = <0x45>;
				clock-names = "mclk";
				assigned-clocks = <0x45>;
				assigned-clock-rates = <0xbb8000>;
				pinctrl-names = "default";
				pinctrl-0 = <0x46 0x47>;
				hp-volume = <0x3c>;
				spk-volume = <0x03>;
				mic-in-differential;
				status = "okay";
				use-ext-amplifier;
				hp2extamplifier;
				hp-mute-delay-ms = <0x64>;
				hp-ctl-gpios = <0x48 0x13 0x00>;
				phandle = <0xdf>;
			};
```

### `battery` (Zeile 1813-1835)
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
				pinctrl-0 = <0x49>;
				charge_red_gpio = <0x48 0x01 0x00>;
				charge_green_gpio = <0x48 0x00 0x00>;
				moto_gpio = <0x48 0x07 0x00>;
				moto_r_gpio = <0x48 0x08 0x00>;
				phandle = <0x165>;
			};
```

### `spi@ff220000` (Zeile 1867-1882)
```dts
	spi@ff220000 {
		compatible = "rockchip,rk3066-spi";
		reg = <0x00 0xff220000 0x00 0x1000>;
		interrupts = <0x00 0x34 0x04>;
		#address-cells = <0x01>;
		#size-cells = <0x00>;
		clocks = <0x02 0x12d 0x02 0x12c 0x02 0x12e>;
		clock-names = "spiclk\0apb_pclk\0sclk_in";
		dmas = <0x4a 0x0d 0x4a 0x0c>;
		dma-names = "tx\0rx";
		pinctrl-names = "default";
		pinctrl-0 = <0x4b 0x4c 0x4d>;
		num-cs = <0x02>;
		status = "disabled";
		phandle = <0x167>;
	};
```

### `pwm@ff230000` (Zeile 1884-1895)
```dts
	pwm@ff230000 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff230000 0x00 0x10>;
		interrupts = <0x00 0x14 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x4e>;
		clocks = <0x02 0x130 0x02 0x12f>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x168>;
	};
```

### `pwm@ff230010` (Zeile 1897-1908)
```dts
	pwm@ff230010 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff230010 0x00 0x10>;
		interrupts = <0x00 0x14 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x4f>;
		clocks = <0x02 0x130 0x02 0x12f>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x169>;
	};
```

### `pwm@ff230020` (Zeile 1910-1921)
```dts
	pwm@ff230020 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff230020 0x00 0x10>;
		interrupts = <0x00 0x14 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x50>;
		clocks = <0x02 0x130 0x02 0x12f>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x16a>;
	};
```

### `pwm@ff230030` (Zeile 1923-1934)
```dts
	pwm@ff230030 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff230030 0x00 0x10>;
		interrupts = <0x00 0x14 0x04 0x00 0x15 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x51>;
		clocks = <0x02 0x130 0x02 0x12f>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x16b>;
	};
```

### `spi@ff640000` (Zeile 2767-2782)
```dts
	spi@ff640000 {
		compatible = "rockchip,rk3066-spi";
		reg = <0x00 0xff640000 0x00 0x1000>;
		interrupts = <0x00 0x35 0x04>;
		#address-cells = <0x01>;
		#size-cells = <0x00>;
		clocks = <0x02 0xa1 0x02 0xa0 0x02 0xa2>;
		clock-names = "spiclk\0apb_pclk\0sclk_in";
		dmas = <0x4a 0x0f 0x4a 0x0e>;
		dma-names = "tx\0rx";
		pinctrl-names = "default";
		pinctrl-0 = <0x84 0x85 0x86>;
		num-cs = <0x02>;
		status = "disabled";
		phandle = <0x17d>;
	};
```

### `spi@ff650000` (Zeile 2784-2799)
```dts
	spi@ff650000 {
		compatible = "rockchip,rk3066-spi";
		reg = <0x00 0xff650000 0x00 0x1000>;
		interrupts = <0x00 0x36 0x04>;
		#address-cells = <0x01>;
		#size-cells = <0x00>;
		clocks = <0x02 0xa4 0x02 0xa3 0x02 0xa5>;
		clock-names = "spiclk\0apb_pclk\0sclk_in";
		dmas = <0x4a 0x11 0x4a 0x10>;
		dma-names = "tx\0rx";
		pinctrl-names = "default";
		pinctrl-0 = <0x87 0x88 0x89>;
		num-cs = <0x02>;
		status = "disabled";
		phandle = <0x17e>;
	};
```

### `serial@ff670000` (Zeile 2801-2814)
```dts
	serial@ff670000 {
		compatible = "rockchip,rk3562-uart\0snps,dw-apb-uart";
		reg = <0x00 0xff670000 0x00 0x100>;
		interrupts = <0x00 0x1f 0x04>;
		clocks = <0x02 0xb2 0x02 0xa6>;
		clock-names = "baudclk\0apb_pclk";
		reg-shift = <0x02>;
		reg-io-width = <0x04>;
		dmas = <0x4a 0x0a 0x4a 0x01>;
		status = "okay";
		pinctrl-names = "default";
		pinctrl-0 = <0x8a>;
		phandle = <0x17f>;
	};
```

### `pwm@ff700000` (Zeile 2920-2931)
```dts
	pwm@ff700000 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff700000 0x00 0x10>;
		interrupts = <0x00 0x16 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x8b>;
		clocks = <0x02 0xd4 0x02 0xd3>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x188>;
	};
```

### `pwm@ff700010` (Zeile 2933-2944)
```dts
	pwm@ff700010 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff700010 0x00 0x10>;
		interrupts = <0x00 0x16 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x8c>;
		clocks = <0x02 0xd4 0x02 0xd3>;
		clock-names = "pwm\0pclk";
		status = "okay";
		phandle = <0xd9>;
	};
```

### `pwm@ff700020` (Zeile 2946-2957)
```dts
	pwm@ff700020 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff700020 0x00 0x10>;
		interrupts = <0x00 0x16 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x8d>;
		clocks = <0x02 0xd4 0x02 0xd3>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0xe7>;
	};
```

### `pwm@ff700030` (Zeile 2959-2970)
```dts
	pwm@ff700030 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff700030 0x00 0x10>;
		interrupts = <0x00 0x16 0x04 0x00 0x17 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x8e>;
		clocks = <0x02 0xd4 0x02 0xd3>;
		clock-names = "pwm\0pclk";
		status = "okay";
		phandle = <0xe6>;
	};
```

### `pwm@ff710000` (Zeile 2972-2983)
```dts
	pwm@ff710000 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff710000 0x00 0x10>;
		interrupts = <0x00 0x18 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x8f>;
		clocks = <0x02 0xd7 0x02 0xd6>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x189>;
	};
```

### `pwm@ff710010` (Zeile 2985-2996)
```dts
	pwm@ff710010 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff710010 0x00 0x10>;
		interrupts = <0x00 0x18 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x90>;
		clocks = <0x02 0xd7 0x02 0xd6>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x18a>;
	};
```

### `pwm@ff710020` (Zeile 2998-3009)
```dts
	pwm@ff710020 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff710020 0x00 0x10>;
		interrupts = <0x00 0x18 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x91>;
		clocks = <0x02 0xd7 0x02 0xd6>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x18b>;
	};
```

### `pwm@ff710030` (Zeile 3011-3022)
```dts
	pwm@ff710030 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff710030 0x00 0x10>;
		interrupts = <0x00 0x18 0x04 0x00 0x19 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x92>;
		clocks = <0x02 0xd7 0x02 0xd6>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x18c>;
	};
```

### `pwm@ff720000` (Zeile 3024-3035)
```dts
	pwm@ff720000 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff720000 0x00 0x10>;
		interrupts = <0x00 0x1a 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x93>;
		clocks = <0x02 0xda 0x02 0xd9>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x18d>;
	};
```

### `pwm@ff720010` (Zeile 3037-3048)
```dts
	pwm@ff720010 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff720010 0x00 0x10>;
		interrupts = <0x00 0x1a 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x94>;
		clocks = <0x02 0xda 0x02 0xd9>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x18e>;
	};
```

### `pwm@ff720020` (Zeile 3050-3061)
```dts
	pwm@ff720020 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff720020 0x00 0x10>;
		interrupts = <0x00 0x1a 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x95>;
		clocks = <0x02 0xda 0x02 0xd9>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x18f>;
	};
```

### `pwm@ff720030` (Zeile 3063-3074)
```dts
	pwm@ff720030 {
		compatible = "rockchip,rk3562-pwm\0rockchip,rk3328-pwm";
		reg = <0x00 0xff720030 0x00 0x10>;
		interrupts = <0x00 0x1a 0x04 0x00 0x1b 0x04>;
		#pwm-cells = <0x03>;
		pinctrl-names = "active";
		pinctrl-0 = <0x96>;
		clocks = <0x02 0xda 0x02 0xd9>;
		clock-names = "pwm\0pclk";
		status = "disabled";
		phandle = <0x190>;
	};
```

### `sai@ff800000` (Zeile 3134-3152)
```dts
	sai@ff800000 {
		compatible = "rockchip,rk3562-sai\0rockchip,sai-v1";
		reg = <0x00 0xff800000 0x00 0x1000>;
		interrupts = <0x00 0x4e 0x04>;
		clocks = <0x02 0x78 0x02 0x74>;
		clock-names = "mclk\0hclk";
		assigned-clocks = <0x02 0x75>;
		assigned-clock-parents = <0x02 0x04>;
		dmas = <0x4a 0x13 0x4a 0x12>;
		dma-names = "tx\0rx";
		resets = <0x02 0xc0023 0x02 0xc0020>;
		reset-names = "m\0h";
		pinctrl-names = "default";
		pinctrl-0 = <0x9b 0x9c 0x9d 0x9e>;
		#sound-dai-cells = <0x00>;
		sound-name-prefix = "SAI0";
		status = "okay";
		phandle = <0xde>;
	};
```

### `sai@ff810000` (Zeile 3154-3172)
```dts
	sai@ff810000 {
		compatible = "rockchip,rk3562-sai\0rockchip,sai-v1";
		reg = <0x00 0xff810000 0x00 0x1000>;
		interrupts = <0x00 0x4f 0x04>;
		clocks = <0x02 0x7e 0x02 0x7a>;
		clock-names = "mclk\0hclk";
		assigned-clocks = <0x02 0x7b>;
		assigned-clock-parents = <0x02 0x04>;
		dmas = <0x4a 0x15 0x4a 0x14>;
		dma-names = "tx\0rx";
		resets = <0x02 0xc0028 0x02 0xc0025>;
		reset-names = "m\0h";
		pinctrl-names = "default";
		pinctrl-0 = <0x9f 0xa0 0xa1 0xa2>;
		#sound-dai-cells = <0x00>;
		sound-name-prefix = "SAI1";
		status = "okay";
		phandle = <0xe1>;
	};
```

### `sai@ff820000` (Zeile 3174-3192)
```dts
	sai@ff820000 {
		compatible = "rockchip,rk3562-sai\0rockchip,sai-v1";
		reg = <0x00 0xff820000 0x00 0x1000>;
		interrupts = <0x00 0x50 0x04>;
		clocks = <0x02 0x84 0x02 0x80>;
		clock-names = "mclk\0hclk";
		assigned-clocks = <0x02 0x81>;
		assigned-clock-parents = <0x02 0x04>;
		dmas = <0x4a 0x17 0x4a 0x16>;
		dma-names = "tx\0rx";
		resets = <0x02 0xc002d 0x02 0xc002a>;
		reset-names = "m\0h";
		pinctrl-names = "default";
		pinctrl-0 = <0xa3 0xa4 0xa5 0xa6>;
		#sound-dai-cells = <0x00>;
		sound-name-prefix = "SAI2";
		status = "disabled";
		phandle = <0x191>;
	};
```

### `pdm@ff830000` (Zeile 3194-3208)
```dts
	pdm@ff830000 {
		compatible = "rockchip,rk3562-pdm\0rockchip,rv1126-pdm";
		reg = <0x00 0xff830000 0x00 0x1000>;
		clocks = <0x02 0x89 0x02 0x88>;
		clock-names = "pdm_clk\0pdm_hclk";
		assigned-clocks = <0x02 0x89>;
		assigned-clock-parents = <0x02 0x04>;
		dmas = <0x4a 0x1f>;
		dma-names = "rx";
		pinctrl-names = "default";
		pinctrl-0 = <0xa7 0xa8 0xa9 0xaa 0xab 0xac>;
		#sound-dai-cells = <0x00>;
		status = "disabled";
		phandle = <0xda>;
	};
```

### `spdif@ff840000` (Zeile 3210-3225)
```dts
	spdif@ff840000 {
		compatible = "rockchip,rk3562-spdif\0rockchip,rk3568-spdif";
		reg = <0x00 0xff840000 0x00 0x1000>;
		interrupts = <0x00 0x7f 0x04>;
		dmas = <0x4a 0x1e>;
		dma-names = "tx";
		clock-names = "mclk\0hclk";
		clocks = <0x02 0x8e 0x02 0x8a>;
		assigned-clocks = <0x02 0x8b>;
		assigned-clock-parents = <0x02 0x04>;
		#sound-dai-cells = <0x00>;
		pinctrl-names = "default";
		pinctrl-0 = <0xad>;
		status = "disabled";
		phandle = <0xdc>;
	};
```

### `dsm@ff850000` (Zeile 3227-3240)
```dts
	dsm@ff850000 {
		compatible = "rockchip,rk3562-dsm";
		reg = <0x00 0xff850000 0x00 0x1000>;
		clocks = <0x02 0x87 0x02 0x86>;
		clock-names = "dac\0pclk";
		resets = <0x02 0xc0032>;
		reset-names = "reset";
		rockchip,grf = <0x99>;
		pinctrl-names = "default";
		pinctrl-0 = <0xae>;
		#sound-dai-cells = <0x00>;
		status = "disabled";
		phandle = <0x192>;
	};
```

### `mmc@ff880000` (Zeile 3276-3299)
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
		vmmc-supply = <0xaf>;
		vqmmc-supply = <0xb0>;
		pinctrl-names = "default";
		pinctrl-0 = <0xb1 0xb2 0xb3 0xb4>;
		phandle = <0x195>;
	};
```

### `mmc@ff890000` (Zeile 3301-3327)
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
		supports-rk912;
		mmc-pwrseq = <0xb5>;
		broken-cd;
		pinctrl-names = "default";
		pinctrl-0 = <0xb6 0xb7 0xb8>;
		sd-uhs-sdr104;
		phandle = <0x196>;
	};
```

### `i2c@ffa00000` (Zeile 3509-3521)
```dts
	i2c@ffa00000 {
		compatible = "rockchip,rk3562-i2c\0rockchip,rk3399-i2c";
		reg = <0x00 0xffa00000 0x00 0x1000>;
		clocks = <0x02 0x20 0x02 0x1a>;
		clock-names = "i2c\0pclk";
		interrupts = <0x00 0x0d 0x04>;
		pinctrl-names = "default";
		pinctrl-0 = <0xb9>;
		#address-cells = <0x01>;
		#size-cells = <0x00>;
		status = "disabled";
		phandle = <0x19c>;
	};
```

### `i2c@ffa10000` (Zeile 3523-3535)
```dts
	i2c@ffa10000 {
		compatible = "rockchip,rk3562-i2c\0rockchip,rk3399-i2c";
		reg = <0x00 0xffa10000 0x00 0x1000>;
		clocks = <0x02 0x21 0x02 0x1b>;
		clock-names = "i2c\0pclk";
		interrupts = <0x00 0x0e 0x04>;
		pinctrl-names = "default";
		pinctrl-0 = <0xba>;
		#address-cells = <0x01>;
		#size-cells = <0x00>;
		status = "okay";
		phandle = <0x19d>;
	};
```

### `i2c@ffa20000` (Zeile 3537-3549)
```dts
	i2c@ffa20000 {
		compatible = "rockchip,rk3562-i2c\0rockchip,rk3399-i2c";
		reg = <0x00 0xffa20000 0x00 0x1000>;
		clocks = <0x02 0x22 0x02 0x1c>;
		clock-names = "i2c\0pclk";
		interrupts = <0x00 0x0f 0x04>;
		pinctrl-names = "default";
		pinctrl-0 = <0xbb>;
		#address-cells = <0x01>;
		#size-cells = <0x00>;
		status = "disabled";
		phandle = <0x19e>;
	};
```

### `rk628@50` (Zeile 3565-3591)
```dts
		rk628@50 {
			status = "okay";
			compatible = "rockchip,rk628";
			reg = <0x50>;
			#sound-dai-cells = <0x00>;
			interrupt-parent = <0x48>;
			interrupts = <0x12 0x04>;
			enable-gpios = <0x48 0x10 0x00>;
			reset-gpios = <0x48 0x11 0x01>;
			pinctrl-names = "default";
			pinctrl-0 = <0xbd 0xbe>;
			assigned-clocks = <0x02 0x132>;
			assigned-clock-rates = <0x16e3600>;
			clocks = <0x02 0x132>;
			clock-names = "soc_24M";
			rk628-rgb-in;
			rk628-hdmi-out;
			phandle = <0xe2>;

			port {

				endpoint {
					remote-endpoint = <0xbf>;
					phandle = <0x3a>;
				};
			};
		};
```

### `i2c@ffa40000` (Zeile 3594-3606)
```dts
	i2c@ffa40000 {
		compatible = "rockchip,rk3562-i2c\0rockchip,rk3399-i2c";
		reg = <0x00 0xffa40000 0x00 0x1000>;
		clocks = <0x02 0x24 0x02 0x1e>;
		clock-names = "i2c\0pclk";
		interrupts = <0x00 0x11 0x04>;
		pinctrl-names = "default";
		pinctrl-0 = <0xc0>;
		#address-cells = <0x01>;
		#size-cells = <0x00>;
		status = "disabled";
		phandle = <0x1a0>;
	};
```

### `panel@0` (Zeile 3769-3828)
```dts
		panel@0 {
			status = "okay";
			compatible = "simple-panel-dsi";
			reg = <0x00>;
			backlight = <0xc9>;
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
			enable-gpios = <0x3c 0x08 0x00>;
			reset-gpios = <0x3c 0x14 0x01>;
			pinctrl-names = "default";
			pinctrl-0 = <0xca 0xcb>;
			init-delay-ms = <0x14>;
			phandle = <0x1a8>;

			display-timings {
				native-mode = <0xcc>;
				phandle = <0x1a9>;

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
					phandle = <0xcc>;
				};
			};

			ports {
				#address-cells = <0x01>;
				#size-cells = <0x00>;

				port@0 {
					reg = <0x00>;

					endpoint {
						remote-endpoint = <0xcd>;
						phandle = <0xc8>;
					};
				};
			};
		};
```

### `pinctrl` (Zeile 3869-5936)
```dts
	pinctrl {
		compatible = "rockchip,rk3562-pinctrl";
		rockchip,grf = <0x7b>;
		#address-cells = <0x02>;
		#size-cells = <0x02>;
		ranges;
		phandle = <0xce>;

		gpio@ff260000 {
			compatible = "rockchip,gpio-bank";
			reg = <0x00 0xff260000 0x00 0x100>;
			interrupts = <0x00 0x00 0x04>;
			clocks = <0x02 0x11d 0x02 0x11e>;
			gpio-controller;
			#gpio-cells = <0x02>;
			gpio-ranges = <0xce 0x00 0x00 0x20>;
			interrupt-controller;
			#interrupt-cells = <0x02>;
			phandle = <0x3c>;
		};

		gpio@ff620000 {
			compatible = "rockchip,gpio-bank";
			reg = <0x00 0xff620000 0x00 0x100>;
			interrupts = <0x00 0x02 0x04>;
			clocks = <0x02 0x100 0x02 0x103>;
			gpio-controller;
			#gpio-cells = <0x02>;
			gpio-ranges = <0xce 0x00 0x20 0x20>;
			interrupt-controller;
			#interrupt-cells = <0x02>;
			phandle = <0xef>;
		};

		gpio@ff630000 {
			compatible = "rockchip,gpio-bank";
			reg = <0x00 0xff630000 0x00 0x100>;
			interrupts = <0x00 0x04 0x04>;
			clocks = <0x02 0x101 0x02 0x104>;
			gpio-controller;
			#gpio-cells = <0x02>;
			gpio-ranges = <0xce 0x00 0x40 0x20>;
			interrupt-controller;
			#interrupt-cells = <0x02>;
			phandle = <0x1ac>;
		};

		gpio@ffac0000 {
			compatible = "rockchip,gpio-bank";
			reg = <0x00 0xffac0000 0x00 0x100>;
			interrupts = <0x00 0x06 0x04>;
			clocks = <0x02 0x54 0x02 0x26>;
			gpio-controller;
			#gpio-cells = <0x02>;
			gpio-ranges = <0xce 0x00 0x60 0x20>;
			interrupt-controller;
			#interrupt-cells = <0x02>;
			phandle = <0x48>;
		};

		gpio@ffad0000 {
			compatible = "rockchip,gpio-bank";
			reg = <0x00 0xffad0000 0x00 0x100>;
			interrupts = <0x00 0x08 0x04>;
			clocks = <0x02 0x55 0x02 0x27>;
			gpio-controller;
			#gpio-cells = <0x02>;
			gpio-ranges = <0xce 0x00 0x80 0x20>;
			interrupt-controller;
			#interrupt-cells = <0x02>;
			phandle = <0x1ad>;
		};

		pcfg-pull-up {
			bias-pull-up;
			phandle = <0xd2>;
		};

		pcfg-pull-down {
			bias-pull-down;
			phandle = <0xd7>;
		};

		pcfg-pull-none {
			bias-disable;
			phandle = <0xcf>;
		};

		pcfg-pull-none-drv-level-0 {
			bias-disable;
			drive-strength = <0x00>;
			phandle = <0x1ae>;
		};

		pcfg-pull-none-drv-level-1 {
			bias-disable;
			drive-strength = <0x01>;
			phandle = <0xd4>;
		};

		pcfg-pull-none-drv-level-2 {
			bias-disable;
			drive-strength = <0x02>;
			phandle = <0x1af>;
		};

		pcfg-pull-none-drv-level-3 {
			bias-disable;
			drive-strength = <0x03>;
			phandle = <0xd5>;
		};

		pcfg-pull-none-drv-level-4 {
			bias-disable;
			drive-strength = <0x04>;
			phandle = <0xd6>;
		};

		pcfg-pull-none-drv-level-5 {
			bias-disable;
			drive-strength = <0x05>;
			phandle = <0x1b0>;
		};

		pcfg-pull-none-drv-level-6 {
			bias-disable;
			drive-strength = <0x06>;
			phandle = <0x1b1>;
		};

		pcfg-pull-none-drv-level-7 {
			bias-disable;
			drive-strength = <0x07>;
			phandle = <0x1b2>;
		};

		pcfg-pull-none-drv-level-8 {
			bias-disable;
			drive-strength = <0x08>;
			phandle = <0x1b3>;
		};

		pcfg-pull-none-drv-level-9 {
			bias-disable;
			drive-strength = <0x09>;
			phandle = <0x1b4>;
		};

		pcfg-pull-none-drv-level-10 {
			bias-disable;
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

### `rk817-sound` (Zeile 6036-6058)
```dts
	rk817-sound {
		status = "okay";
		compatible = "rockchip,multicodecs-card";
		rockchip,card-name = "rockchip-rk817";
		hp-det-gpio = <0x3c 0x07 0x00>;
		io-channels = <0xd8 0x04>;
		io-channel-names = "adc-detect";
		keyup-threshold-microvolt = <0x1b7740>;
		poll-interval = <0x64>;
		rockchip,format = "i2s";
		rockchip,mclk-fs = <0x100>;
		rockchip,cpu = <0xde>;
		rockchip,codec = <0xdf>;
		pinctrl-names = "default";
		pinctrl-0 = <0xe0>;
		phandle = <0x2ae>;

		play-pause-key {
			label = "playpause";
			linux,code = <0xa4>;
			press-threshold-microvolt = <0x7d0>;
		};
	};
```

### `sdio-pwrseq` (Zeile 6077-6086)
```dts
	sdio-pwrseq {
		compatible = "mmc-pwrseq-simple";
		clocks = <0xe3 0x01>;
		clock-names = "ext_clock";
		pinctrl-names = "default";
		pinctrl-0 = <0xe4>;
		post-power-on-delay-ms = <0xc8>;
		reset-gpios = <0x3c 0x0b 0x01>;
		phandle = <0xb5>;
	};
```

### `vcc-sd` (Zeile 6098-6110)
```dts
	vcc-sd {
		compatible = "regulator-gpio";
		enable-active-low;
		regulator-boot-on;
		gpios = <0x3c 0x05 0x01>;
		regulator-min-microvolt = <0x325aa0>;
		regulator-max-microvolt = <0x325aa0>;
		pinctrl-names = "default";
		pinctrl-0 = <0xe5>;
		regulator-name = "vcc_sd";
		states = <0x00 0x00 0x325aa0 0x01>;
		phandle = <0xaf>;
	};
```

### `led-vcc` (Zeile 6152-6160)
```dts
	led-vcc {
		compatible = "regulator-fixed";
		regulator-name = "vcc-led";
		pinctrl-0 = <0xe8>;
		pinctrl-names = "default";
		gpios = <0x3c 0x17 0x00>;
		enable-active-high;
		phandle = <0x2b1>;
	};
```

### `wireless-wlan` (Zeile 6162-6172)
```dts
	wireless-wlan {
		compatible = "wlan-platdata";
		rockchip,grf = <0x0e>;
		wifi_chip_type = "rk915";
		pinctrl-names = "default";
		pinctrl-0 = <0xe9 0xea>;
		WIFI,host_wake_irq = <0x3c 0x0c 0x00>;
		WIFI,poweren_gpio = <0x3c 0x06 0x01>;
		sdio_vref = <0x708>;
		status = "okay";
	};
```

### `fiq-debugger` (Zeile 6193-6203)
```dts
	fiq-debugger {
		compatible = "rockchip,fiq-debugger";
		rockchip,serial-id = <0x00>;
		rockchip,wake-irq = <0x00>;
		rockchip,irq-mode-enable = <0x01>;
		rockchip,baudrate = <0x16e360>;
		interrupts = <0x00 0xf2 0x04>;
		pinctrl-names = "default";
		pinctrl-0 = <0xeb>;
		status = "okay";
	};
```

### `play_joystick` (Zeile 6205-6273)
```dts
	play_joystick {
		compatible = "play_joystick";
		io-channels = <0xd8 0x02 0xd8 0x03 0xd8 0x05 0xd8 0x06 0xec 0x01 0xec 0x04 0xec 0x00 0xec 0x02 0xec 0x03 0xec 0x05 0xec 0x06 0xec 0x07>;
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
		pinctrl-0 = <0xed 0xee>;
		moto-gpio = <0x48 0x07 0x00>;
		moto-r-gpio = <0x48 0x08 0x00>;
		gpio-key-num = <0x0a>;
		key-gpios = <0xef 0x17 0x01 0xef 0x18 0x01 0xef 0x1d 0x01 0xef 0x1e 0x01 0xef 0x1b 0x01 0xef 0x1f 0x01 0xef 0x1c 0x01 0x3c 0x15 0x01 0x3c 0x16 0x01>;
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

### `__symbols__` (Zeile 6275-6966)
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
		shaping_jpeg = "/shaping@fee90088";
		qos_rga_rd = "/qos@fee90100";
		shaping_rga_rd = "/shaping@fee90188";
		qos_rga_wr = "/qos@fee90200";
		shaping_rga_wr = "/shaping@fee90288";
		qos_pcie = "/qos@feea0000";
		shaping_pcie = "/shaping@feea0088";
		qos_usb3 = "/qos@feea0100";
		shaping_usb3 = "/shaping@feea0188";
		qos_crypto_apb = "/qos@feeb0000";
		shaping_crypto_apb = "/shaping@feeb0088";
		qos_crypto = "/qos@feeb0100";
		shaping_crypto = "/shaping@feeb0188";
		qos_dmac = "/qos@feeb0200";
		shaping_dmac = "/shaping@feeb0288";
		qos_emmc = "/qos@feeb0300";
		shaping_emmc = "/shaping@feeb0388";
		qos_fspi = "/qos@feeb0400";
		shaping_fspi = "/shaping@feeb0488";
		qos_rkdma = "/qos@feeb0500";
		shaping_rkdma = "/shaping@feeb0588";
		qos_sdmmc0 = "/qos@feeb0600";
		shaping_sdmmc0 = "/shaping@feeb0688";
		qos_sdmmc1 = "/qos@feeb0700";
		shaping_sdmmc1 = "/shaping@feeb0788";
		qos_usb2 = "/qos@feeb0800";
		shaping_usb2 = "/shaping@feeb0888";
		pmu_grf = "/syscon@ff010000";
		reboot_mode = "/syscon@ff010000/reboot-mode";
		sys_grf = "/syscon@ff030000";
		lvds = "/syscon@ff030000/lvds";
    // ... (gekuerzt, siehe volle .dts-Datei fuer Rest) ...
```

