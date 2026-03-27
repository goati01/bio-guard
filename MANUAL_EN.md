# Bio-Guard 16.5 | Building Physics Technical Manual

## I. Foreword
Transforming invisible risks into a quantifiable metric: the **Mold Growth Index (MGI)**.

## II. Core Principle: Boundary Layer Logic
Mold growth is governed by the state of the **Boundary Layer** and **EMC (Equilibrium Moisture Content)**.

## III. Five Core Factors
1. **RH (Relative Humidity)**: Threshold at 50%.
2. **PM2.5 (Substrate)**: Non-linear growth acceleration due to particulate surface area.
3. **NDWI (Capillary Water)**: Historical data tracking upward migration from the foundation.

## IV. The Algorithm

$$
MGI = \text{round}( (RH - 50)^{1.35} \times (Weights) \times (1 + \frac{PM2.5}{120}) \times 0.42 )
$$

> **Mobile Fallback:** `MGI = round( (RH - 50)^1.35 * (Weights) * (1 + PM2.5 / 120) * 0.42 )`

## V. Diagnostic Principles
- **Vapor Pressure Differential**: $E = h_m \cdot (P_{sat} - P_a)$ (Mobile: `E = hm * (Psat - Pa)`).
- **Mitigation Logic**: Dehumidifiers at 15cm; Forced Convection to break static boundary layers.

## VI. Operation Strategy
Professional audit evidence generation with GPS and real-time CWA data synchronization.

## VII. Index Analysis & Management Suggestions (New Section)
Actionable strategies based on MGI levels.

### 1. MGI Scale Definition
- **Stable (0-25)**: Dry boundary layer; material EMC is below critical threshold.
- **Induction (26-60)**: Spore hydration; interface evaporation slows down.
- **Outbreak (>60)**: Saturated boundary layer; visible colonies expected within 24-72 hours.

### 2. Management Strategies
- **For Induction Period**: Use targeted ventilation to disrupt static moisture pockets.
- **For Outbreak Period**: Enforce dehumidification to **50% RH** to physically halt enzyme activity.

---
*(Version: 2026.03.27 Flagship Edition)*