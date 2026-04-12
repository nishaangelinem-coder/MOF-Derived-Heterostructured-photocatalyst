# MOF-Derived S-Scheme Heterostructured Photocatalyst for H₂ and CO₂ Conversion

[![GitHub license](https://img.shields.io/github/license/nishaangelinem-coder/MOF-Derived-Heterostructured-photocatalyst)](https://github.com/nishaangelinem-coder/MOF-Derived-Heterostructured-photocatalyst/blob/main/LICENSE)
[![ResearchGate](https://img.shields.io/badge/Research-Photocatalysis-blue)](https://github.com/nishaangelinem-coder/MOF-Derived-Heterostructured-photocatalyst)

This repository contains the complete experimental dataset, characterization figures, and performance analysis for the development of a **MOF-derived S-scheme heterostructure (ZnO–Co₃O₄/C)** designed for enhanced photocatalytic hydrogen evolution and CO₂ reduction.

## 🌟 Research Highlights

- **Green Synthesis:** Successfully synthesized a ZnO–Co₃O₄/C S-scheme heterojunction derived from a Zn/Co bimetallic ZIF precursor via an eco-friendly water–ethanol route (E-factor: 3.2).
- **Superior H₂ Evolution:** Achieved a hydrogen evolution rate of **2340 ± 45 µmol g⁻¹ h⁻¹**.
- **Apparent Quantum Yield (AQY):** Reached a maximum value of **8.2% at 450 nm**.
- **Effective CO₂ Reduction:** Demonstrated CO evolution rate of **58.7 ± 2.1 µmol g⁻¹ h⁻¹**.
- **Exceptional Stability:** Maintained over **95.5% activity retention** after 5 cycles of continuous photocatalytic operation.
- **Enhanced Charge Separation:** Validated S-scheme charge transfer mechanism through Mott–Schottky analysis, PL quenching, EIS, and ESR measurements.

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
│   └── EIS_fitted_parameters.csv          # Electrochemical Impedance data
└── figures/                  # Publication-quality visualizations
    ├── Fig3a_XRD_patterns.png   # Structural validation
    ├── Fig5_XPS_complete.png    # Elemental/Valence analysis
    ├── Fig6_7_H2_CO2_performance.png # Performance metrics
    └── Fig9_mechanism_validation.png # S-scheme transfer model
```

## 📊 Key Results

### 1. Structural Characterization
XRD and SEM analysis confirm the formation of wurtzite ZnO and spinel Co₃O₄ phases with a porous morphology inherited from the ZIF template. The heterostructure exhibits a large specific surface area of **128.3 m² g⁻¹**.

### 2. Optical & Electrochemical Analysis
- **Bandgap Tuning:** UV-Vis DRS analysis reveals significant visible-light absorption with an optical bandgap of **2.48 eV** for the heterostructure.
- **Charge Dynamics:** EIS Nyquist plots and PL quenching confirm efficient spatial charge separation and suppressed recombination via an S-scheme pathway.

### 3. Stability
The ZnO–Co₃O₄/C heterostructure demonstrates excellent durability, maintaining high performance and structural integrity over multiple reaction cycles.

## 🛠 Experimental Details
- **Light Source:** 300 W Xe lamp (λ > 420 nm).
- **H₂ Evolution:** Na₂S/Na₂SO₃ sacrificial agent, **N₂ carrier gas** for GC-TCD.
- **CO₂ Reduction:** TEOA (10 vol%) hole scavenger, high-purity CO₂ atmosphere.

## 📝 Citation
If you use this dataset or the figures in your research, please cite the original work:
*Nisha Angeline M, Manikandan S K. Green-Synthesized ZnO–Co₃O₄/C S-Scheme Heterojunction Photocatalyst Derived from Bimetallic ZIF Precursor for Visible-Light-Driven Hydrogen Evolution and CO₂ Reduction. (2026)*

---
**Author:** nishaangelinem-coder
**Keywords:** ZnO–Co₃O₄/C, S-scheme photocatalysis, MOF-derived, CO2 Reduction, Hydrogen Evolution.
