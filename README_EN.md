# Bio-Guard 16.5 | Building Physics Diagnostic Platform

> 🚀 **[Launch Diagnostic Dashboard](https://goati01.github.io/bio-guard/)**
> 
> 📖 **[README (繁中)](./README.md)** | **[Manual (繁中)](./MANUAL.md)** | **[Technical Manual (EN)](./MANUAL_EN.md)**

Professional-grade diagnostic tool for 2026 building inspections. This platform integrates the **VTT Mold Growth Model** with deep calibration for subtropical humidity and material sensitivity.

## 🧬 Academic Logic

$$
MGI = \text{round}( (RH - 55)^{1.28} \times C_{reg} \times C_{mat} \times \text{NDWI} \times \text{Vent} \times 0.25 )
$$

> **Mobile Fallback:** `MGI = round( (RH - 55)^1.28 * C_reg * C_mat * NDWI * Vent * 0.25 )`

### Key Coefficients
- **Geographic Correction (`C_reg`)**: Adjusted weighting for high wind-pressure zones.
- **Material Sensitivity (`C_mat`)**: Weighted for moisture equilibrium capacities (EMC).
- **Ground Water (NDWI)**: Simulates upward **Capillary Pressure** from the foundation.

---
*Engineered for data-driven building management and proactive moisture control.*