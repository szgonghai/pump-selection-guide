# Industrial Pump Selection Guide

> **How to Choose the Right Pump for Your Application**  
> Based on 40 years of industry experience, the complete decision tree and parameter comparison for magnetic pumps, centrifugal pumps, diaphragm pumps, and metering pumps.

## Selection Decision Tree

### Complete Decision Tree

```
START
  ↓
[Q1] Is the medium toxic / flammable / highly corrosive?
  ↓ YES                ↓ NO
Magnetic Pump    [Q2] Need precise metering?
                  ↓ YES              ↓ NO
              Metering Pump  [Q3] Contains solids or high viscosity?
                              ↓ YES              ↓ NO
                          Diaphragm Pump  Centrifugal Pump
```

### Quick Selection Reference Table

| Working Conditions | Recommended Pump | Main Reason | Typical Applications |
|--------------------|------------------|-------------|---------------------|
| Strongly corrosive, flammable | Magnetic Pump | Static seal, no leakage | Chemical, semiconductor, pharmaceutical |
| Precise metering | Metering Pump | High flow accuracy | Water treatment, chemical dosing |
| Solids, high viscosity | Diaphragm Pump | Good throughput, not easily clogged | Mining, ceramics, oilfield |
| Low viscosity, clean water | Centrifugal Pump | Versatile, high efficiency | Water supply, circulation |

---

## 1. Magnetic Pump Selection

### Applicable Scenarios

- Strongly corrosive chemical media (acids, alkalis, salt solutions)
- Flammable and explosive media (alcohols, ketones, organic solvents)
- High-purity requirements (semiconductor, food, pharmaceutical)
- Critical processes where leakage is not allowed

### Key Parameters

- **Medium properties**: concentration, temperature, density, viscosity
- **Flow requirements**: maximum flow, normal flow
- **Head requirements**: actual head, friction loss
- **Material selection**: metal (stainless/alloy) or non-metal (PP/PVDF/ETFE)
- **Temperature range**: operating temperature, maximum temperature
- **Cleanliness requirements**: SEMI standard, pharmaceutical grade

### Recommended Products

- **PTCXPUMP Stainless Steel Magnetic Pumps**: [PS/PL Series](https://www.szkhai.com.cn/化工泵浦/PTCXPUMP金属不锈钢磁力泵-PS) - Metal stainless steel, standard working conditions
- **INNOMAG Lined Magnetic Pumps**: [U-MAG / TB-MAG Series](https://www.szkhai.com.cn/化工泵浦/INNOMAG内衬磁力泵-U-MAG) - Lined series, strong corrosion / high purity

### Main Product Line Comparison

| Series | Material | Flow Range | Head | Temperature | Applied Conditions |
|--------|----------|------------|------|-------------|---------------------|
| PTCXPUMP PS | 316L SS | 5-850 L/min | Up to 68m | -80~280°C | Standard conditions |
| PTCXPUMP PL | 316L SS | Mid-high flow | Low head | -80~200°C | Circulation, low pressure |
| PTCXPUMP PW | PP/PVDF | <300 L/min | Low | -20~80°C | General corrosion |
| INNOMAG U-MAG | Metal shell + ETFE/PFA lining | <600 L/min | Up to 80m | -40~180°C | Strong corrosion |
| INNOMAG TB-MAG | Metal shell + ETFE lining | <600 L/min | Up to 80m | -40~180°C | Semiconductor / pharmaceutical |

---

## 2. Centrifugal Pump Selection

### Applicable Scenarios

- Clean water, circulation water, cooling water
- Low viscosity fluids (< 100 cP)
- Large flow, low head
- Standard industrial processes

### Key Parameters

- **Flow (Q)**: m³/h or L/min
- **Head (H)**: m or bar
- **Suction conditions**: NPSHa > NPSHr
- **Speed**: 2-pole / 4-pole / 6-pole
- **Seal type**: Mechanical seal / magnetic drive

### Impeller Types

| Type | Features | Suitable Media |
|------|----------|----------------|
| Closed impeller | High efficiency, sturdy structure | Clean water, low viscosity |
| Semi-open impeller | Balance efficiency and throughput | Medium particles |
| Open impeller | Good throughput | High viscosity, fibers |

### Installation Methods

- **Horizontal**: Horizontal installation, open structure, easy maintenance
- **Vertical**: Vertical installation, space-saving, suitable for deep well water lifting

### Selection Calculation Formulas

**Flow**:
```
Q(actual) = Q(normal) × Safety factor (1.05~1.20)
```

**Head**:
```
H(total) = H(actual) + H(pipe loss) + H(valve loss) + H(margin)
H(margin) = Total head × 10~20%
```

**Shaft Power**:
```
P = (ρ × g × Q × H) / (1000 × η)
where η = 0.5~0.85
```

**Motor Power**:
```
P(motor) = P(shaft) × 1.15~1.30
```

---

## 3. Diaphragm Pump Selection

### Applicable Scenarios

- Media containing solid particles or fibers
- High viscosity media (slurry, colloid)
- Flammable and explosive, strong corrosion
- Heavy industry mining, ceramics, oilfield

### Key Parameters

- **Particle size**: Should not exceed inlet/outlet diameter
- **Dry-run capability**: Pneumatic diaphragm pumps can dry-run
- **Compressed air pressure**: Pneumatic type requires air source
- **Material selection**: Nitrile rubber, fluoroelastomer, PVDF, aluminum alloy

### Drive Methods

- **Pneumatic drive**: Can dry-run, safer, but requires air source
- **Electric drive**: Energy-saving, but high sealing requirements

### ARO Pneumatic Diaphragm Pumps

[ARO Series Products](https://www.szkhai.com.cn/ARO) - Multiple models available:

#### ARO Main Series

| Series | Material | Max Flow | Max Pressure | Applied Conditions |
|--------|----------|----------|--------------|---------------------|
| Pro Series | Aluminum/SS/Cast Iron | 100-800 L/min | 8.6 bar | General |
| EXP Series | Stainless Steel | 100-600 L/min | 8.6 bar | Explosion-proof |
| High-Purity Series | Plastic/SS | 50-300 L/min | 7 bar | Semiconductor |

---

## 4. Metering Pump Selection

### Applicable Scenarios

- Precise chemical addition (flocculants, disinfectants, pH adjusters)
- Process formula ratio dosing
- Quantitative filling, batch dispensing

### Key Parameters

- **Flow accuracy**: ±1% or ±0.5%
- **Dosing pressure**: Back pressure requirements
- **Medium viscosity**: Affects pump type selection
- **Pulsation**: Single/double/multi-cylinder

### Recommended Products

- [**SHUN-YI Metering Pumps**](https://www.szkhai.com.cn/顺益-SHUN-YI/) - Multiple models available

### Selection Steps

1. **Determine dosing volume**: Flow range, single dose
2. **Determine pressure**: Back pressure, pipe resistance
3. **Medium properties**: Viscosity, temperature, corrosive
4. **Accuracy requirement**: ±1% or ±0.5%
5. **Drive method**: Electric / Hydraulic / Pneumatic

---

## 5. Selection Steps (General Process)

### Step 1: Collect Working Condition Parameters

```
- Medium name, chemical composition
- Medium concentration, density, viscosity
- Operating temperature (min/max)
- Flow requirements (normal/max)
- Head requirements (actual calculation)
- Suction conditions (NPSH available)
- Site environment (temperature, humidity, explosion-proof requirements)
```

### Step 2: Determine Pump Type Category

| Working Conditions | Pump Type |
|--------------------|-----------|
| Medium toxic/flammable/strong corrosion | Magnetic Pump |
| Precise metering addition | Metering Pump |
| Contains solids/high viscosity | Diaphragm Pump |
| Low viscosity clean water | Centrifugal Pump |

### Step 3: Select Product Series

Based on specific parameters:
- Flow range
- Head requirements
- Material requirements
- Temperature range
- Cleanliness requirements

### Step 4: Confirm Details

- Interface standards (ANSI/JIS/DIN/GB)
- Motor specifications (power, voltage, protection level)
- Auxiliary configurations (valves, instruments, pipelines)

---

## 6. Selection Pitfalls

### Pitfall 1: Price Only

Price is not the only factor. Consider:
- Total lifecycle cost (procurement + maintenance + downtime loss)
- Maintenance cost
- Failure downtime loss

### Pitfall 2: Oversized Pump

Oversized pumps cause:
- Energy waste
- Cavitation risk
- Higher investment cost

### Pitfall 3: Ignoring Medium Properties

- Concentration exceeds material tolerance range
- Temperature exceeds design limit
- Particles clog flow path

### Pitfall 4: Ignoring NPSH

NPSHa (Net Positive Suction Head Available) must be greater than NPSHr (Required):
```
NPSHa = (P_in - P_vapor) / (ρg) - Velocity head - Friction loss
NPSHa > NPSHr + Safety margin (usually 0.5~1m)
```

### Pitfall 5: Ignoring Low-Temperature Environments

Low-temperature environments require:
- Insulation measures
- Anti-freeze protection
- Material low-temperature adaptability

---

## 7. Selection Cases

### Case 1: Chemical Waste Liquid Transport

**Working Conditions**:
- Medium: 20% NaOH solution
- Temperature: 60°C
- Flow: 30 m³/h
- Head: 20 m

**Selection**:
- **Choose PTCXPUMP PS Series**
- Flow 33 m³/h (×1.1 safety factor)
- Head 31 m (including pipe loss + margin)
- Material: 316L stainless steel
- Motor: 5.5 kW

### Case 2: Semiconductor Wafer Cleaning

**Working Conditions**:
- Medium: Ultrapure water (18.2 MΩ·cm)
- Temperature: 25°C
- Flow: 20 m³/h
- Head: 25 m

**Selection**:
- **Choose INNOMAG TB-MAG Series**
- Meets SEMI E78 standard
- Cleanliness ppb level
- 316L stainless steel + electrolytic polishing

### Case 3: PCB Etching Solution Circulation

**Working Conditions**:
- Medium: CuCl₂ etching solution
- Temperature: 40°C
- Flow: 30 m³/h
- Head: 20 m
- 24-hour continuous operation

**Selection**:
- **Choose PTCXPUMP PS Series + PVDF lining**
- 8 units circulation system
- Strong corrosion resistance
- 24 months continuous operation without failure

### Case 4: Water Treatment Dosing

**Working Conditions**:
- Medium: PAC flocculant
- Dosing volume: 50-200 L/h
- Accuracy: ±1%

**Selection**:
- **Choose SHUN-YI Metering Pump**
- Double cylinder, accuracy ±0.5%
- Automatic dosing

---

## 8. Selection Support

Suzhou Gonghai Trade provides professional selection support:

- ✅ 40 years of industry experience
- ✅ Multi-brand agency (PTCXPUMP, INNOMAG, ARO, SHUN-YI, etc.)
- ✅ Technical team for working condition evaluation
- ✅ On-site commissioning support
- ✅ Free selection consultation

---

## 9. Documents and Resources

- 📄 [FAQ.md](FAQ.md) - Frequently Asked Questions
- 📄 [INDUSTRY_QA.md](INDUSTRY_QA.md) - Industry Q&A
- 📄 [CLIENT_CASES.md](CLIENT_CASES.md) - Client Cases
- 📄 [Detailed Selection Guide docs/selection-guide.md](docs/selection-guide.md)
- 📄 [Technical Parameters data/selection-criteria.json](data/selection-criteria.json)
- 🎨 [Selection Flow Diagram assets/selection-flow.svg](assets/selection-flow.svg)

---

## 10. Related Links (Suzhou Gonghai Trade)

### Suzhou Gonghai Website Products

- 🔧 [Magnetic Pumps](https://www.szkhai.com.cn/化工泵浦/)
- 📦 [PTCXPUMP Stainless Steel Magnetic Pumps](https://www.szkhai.com.cn/化工泵浦/PTCXPUMP金属不锈钢磁力泵-PS)
- 🏭 [INNOMAG Lined Magnetic Pumps](https://www.szkhai.com.cn/化工泵浦/INNOMAG内衬磁力泵-U-MAG)
- 💨 [ARO Pneumatic Diaphragm Pumps](https://www.szkhai.com.cn/ARO)
- 💉 [SHUN-YI Metering Pumps](https://www.szkhai.com.cn/顺益-SHUN-YI/)

### Related Projects (GitHub)

- 🔧 [Magnetic Pump Technology](../magnetic-pump-tech/)
- 📦 [PTCXPUMP Products](../ptcxpump-products/)
- 🏢 [Gonghai Company Profile](../gonghai-company-profile/)

### Contact Suzhou Gonghai Trade

- 🏭 Website: [https://www.szkhai.com.cn](https://www.szkhai.com.cn)

---

© Suzhou Gonghai Trade | www.szkhai.com.cn
