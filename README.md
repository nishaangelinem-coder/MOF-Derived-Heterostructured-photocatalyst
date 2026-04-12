# Green-Synthesized ZnO–Co₃O₄/C S-Scheme Heterojunction Photocatalyst

[![GitHub license](https://img.shields.io/github/license/nishaangelinem-coder/MOF-Derived-Heterostructured-photocatalyst)](https://github.com/nishaangelinem-coder/MOF-Derived-Heterostructured-photocatalyst/blob/main/LICENSE)
[![ResearchGate](https://img.shields.io/badge/Research-Photocatalysis-blue)](https://github.com/nishaangelinem-coder/MOF-Derived-Heterostructured-photocatalyst)

This repository contains the complete experimental dataset, characterization figures, and performance analysis for the **ZnO–Co₃O₄/C S-scheme heterojunction photocatalyst** derived from a bimetallic ZIF precursor. This work focuses on visible-light-driven hydrogen evolution and CO₂ reduction.

## 🌟 Research Highlights

Green Synthesis: Water–ethanol solvothermal synthesis (E-factor: 3.2) followed by thermal conversion at 600 °C under nitrogen (N₂).
High H₂ Evolution: 2340 ± 45 µmol g⁻¹ h⁻¹ under visible light irradiation.
Apparent Quantum Yield (AQY): 8.2% at 450 nm.
CO₂ Reduction Performance: CO production rate of 58.7 ± 2.1 µmol g⁻¹ h⁻¹.
CO Selectivity: ~83–84% (calculated from CO/(CO+CH₄)).
S-Scheme Charge Transfer: Supported by PL quenching, EIS, Mott–Schottky, and ESR analyses.
Stability: 95.5% activity retention after five cycles.

## 📁 Repository Structure

```
├── raw_data/                 # Raw experimental results (CSV)
│   ├── GC_FID_CO2products_raw.csv # CO2 reduction product data (FID)
│   ├── GC_TCD_H2_raw.csv          # H2 evolution data (TCD, N2 carrier gas)
│   ├── XRD_raw_counts.csv         # Raw X-Ray Diffraction counts
│   ├── UV_Vis_DRS_raw.csv         # UV-Vis Diffuse Reflectance data
│   ├── PL_raw_data.csv            # Photoluminescence spectra
│   └── H2_evolution_triplicate.csv # H2 evolution reproducibility data
├── processed_data/           # Cleaned and analyzed datasets
│   ├── MOF_SScheme_Complete_Dataset.xlsx # Master dataset
│   ├── Scherrer_analysis.csv             # Crystallite size calculations
│   ├── EIS_fitted_parameters.csv          # Electrochemical Impedance data
│   └── Table8_stability.csv              # Recycling performance metrics
└── figures/                  # Publication-quality visualizations
    ├── Fig3a_XRD_patterns.png   # Structural validation (ZnO, Co3O4/C, Heterostructure)
    ├── Fig5_XPS_complete.png    # Elemental and Valence state analysis
    ├── Fig6_7_H2_CO2_performance.png # Photocatalytic rate comparisons
    └── Fig9_mechanism_validation.png # S-scheme charge transfer model
```

## 📊 Key Experimental Parameters

| Parameter | Hydrogen Evolution | CO₂ Reduction |
| :--- | :--- | :--- |
| **Catalyst Loading** | 50 mg (1.0 g L⁻¹) | 50 mg (1.0 g L⁻¹) |
| **Light Source** | 300 W Xe lamp, λ > 420 nm | 300 W Xe lamp, λ > 420 nm |
| **Carrier Gas (GC)** | **Nitrogen (N₂)** | **Nitrogen (N₂)** / CO₂ |
| **Sacrificial Agent** | Na₂S/Na₂SO₃ | TEOA (10 vol%) |
| **AQY** | **8.2% @ 450 nm** | - |

## 🛠 Data Usage
The data files provided are standardized for direct use in analytical software (OriginPro, Python, MATLAB). 
- All samples are labeled consistently: **ZnO**, **Co3O4/C**, and **ZnO–Co3O4/C**.
- Raw data includes baseline corrections where applicable.


**Keywords:** S-scheme photocatalysis, MOF-derived, CO2 Reduction, Hydrogen Evolution, Green Synthesis.
