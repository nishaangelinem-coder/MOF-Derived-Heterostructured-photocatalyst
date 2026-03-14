# Green-Synthesized S-Scheme MOF-Derived Heterostructured Photocatalyst for Visible-Light-Driven Hydrogen Evolution and CO₂ Reduction


---

## Authors

**Nisha Angeline M¹\***, **Manikandan S K²**

¹ Professor, Department of ECE, Velalar College of Engineering and Technology, Erode, Tamil Nadu, India  
² Professor, Department of BME, Velalar College of Engineering and Technology, Erode, Tamil Nadu, India

\* Corresponding author

---

## Overview

This repository contains the complete experimental characterization data supporting our work on a green-synthesized MOF-derived S-scheme heterojunction photocatalyst for dual solar fuel production — visible-light-driven hydrogen evolution reaction (HER) and photocatalytic CO₂ reduction. The optimal S-scheme heterostructure achieved an H₂ evolution rate of **2340 ± 45 μmol g⁻¹ h⁻¹** with an apparent quantum yield of **8.2% at 420 nm**, and a CO₂-to-CO reduction rate of **58.7 ± 2.1 μmol g⁻¹ h⁻¹**, retaining over 95% photocatalytic activity after five consecutive cycles. All characterization data were acquired from laboratory-grade analytical instruments and are provided in both raw and processed formats.

---

## Repository Structure

```
MOF-Derived-Heterostructured-photocatalyst/
│
├── README.md
│
├── figures/                              # Publication-quality figures (600 DPI)
│   ├── Fig3a_XRD_patterns.png
│   ├── Fig3a_XRD_patterns.tiff
│   ├── Fig4ab_UVVis_DRS_Tauc.png
│   ├── Fig4c_PL_spectra.png
│   ├── Fig4d_EIS_Nyquist.png
│   ├── Fig5a_BET_BJH_analysis.png
│   ├── Fig5_XPS_complete.png
│   ├── Fig6_7_H2_CO2_performance.png
│   ├── Fig9_mechanism_validation.png
│   ├── Fig10_stability.png
│   └── Fig_GC_analysis.png
│
├── raw_data/                             # Raw instrument output data
│   ├── XRD_raw_counts.csv
│   ├── UV_Vis_DRS_raw.csv
│   ├── PL_raw_data.csv
│   ├── GC_TCD_H2_raw.csv
│   ├── GC_FID_CO2products_raw.csv
│   └── H2_evolution_triplicate.csv
│
└── processed_data/                       # Processed, fitted, and tabulated data
    ├── MOF_SScheme_Complete_Dataset.xlsx
    ├── Scherrer_analysis.csv
    ├── EIS_fitted_parameters.csv
    └── Table8_stability.csv
```

---

## Experimental Instruments and Measurement Conditions

### Structural Characterization

| Technique | Instrument | Conditions |
|-----------|-----------|------------|
| Powder XRD | Rigaku MiniFlex 600 | Cu Kα radiation (λ = 1.5406 Å), 40 kV / 15 mA, 2θ = 10–80°, step size 0.02°, scan speed 2° min⁻¹ |
| FESEM | JEOL JSM-7600F | Accelerating voltage 5–15 kV, working distance 8 mm, Pt-coated specimens |
| TEM / HRTEM | JEOL JEM-2100Plus | 200 kV, point resolution 0.23 nm, specimens on Cu grid with holey carbon |
| SAED | JEOL JEM-2100Plus | Camera length 25 cm |
| EDS Mapping | Oxford Instruments X-MaxN 80 | Attached to FESEM, Si(Li) detector |

### Surface and Pore Analysis

| Technique | Instrument | Conditions |
|-----------|-----------|------------|
| N₂ Adsorption–Desorption (BET/BJH) | Micromeritics ASAP 2020 Plus | 77 K, degassed at 150 °C for 12 h under vacuum, BET range P/P₀ = 0.05–0.30 |
| XPS | PHI 5000 VersaProbe III | Al Kα monochromatic source (1486.6 eV), pass energy 23.5 eV (high-res), charge referenced to C 1s at 284.8 eV, Shirley background subtraction |

### Optical and Electronic Characterization

| Technique | Instrument | Conditions |
|-----------|-----------|------------|
| UV–Vis DRS | Shimadzu UV-3600Plus | Wavelength range 200–800 nm, BaSO₄ as reference, scan speed 200 nm min⁻¹, bandwidth 2 nm |
| Photoluminescence (PL) | Horiba FluoroMax-4 | Excitation wavelength λex = 325 nm, emission scan 340–650 nm, slit widths 3 nm / 3 nm |

### Electrochemical Measurements

| Technique | Instrument | Conditions |
|-----------|-----------|------------|
| EIS | Metrohm Autolab PGSTAT302N + FRA32M | Three-electrode cell (Ag/AgCl reference, Pt counter), frequency range 0.01 Hz – 1 MHz, amplitude 10 mV, 0.1 M Na₂SO₄ electrolyte |
| Mott–Schottky | Metrohm Autolab PGSTAT302N | Frequencies 1, 2, 3 kHz, potential scan −1.5 to +0.8 V vs. Ag/AgCl |
| Transient Photocurrent | Metrohm Autolab PGSTAT302N | Chronoamperometry at 0 V vs. Ag/AgCl, on/off cycles (30 s each), 300 W Xe lamp (λ > 420 nm) |

### Photocatalytic Performance

| Technique | Instrument | Conditions |
|-----------|-----------|------------|
| H₂ Detection (GC-TCD) | Shimadzu GC-2014 | Molecular sieve 5A column, Ar carrier gas, TCD detector, column temp 80 °C |
| CO₂ Reduction Products (GC-FID/TCD) | Shimadzu GC-2014 | Porapak Q + molecular sieve columns, methanizer for FID, CO₂ products quantified against calibration standards |
| ¹³C Isotope Labeling | Shimadzu GCMS-QP2020 NX | ¹³CO₂ (99 atom% ¹³C) as feedstock, m/z shift verification |
| ESR Spin Trapping | Bruker EMXmicro | DMPO as spin trap, X-band (9.85 GHz), modulation amplitude 1 G, microwave power 6.3 mW |

### Photocatalytic Reaction Setup

| Parameter | Hydrogen Evolution | CO₂ Reduction |
|-----------|-------------------|---------------|
| Catalyst loading | 50 mg (1.0 g L⁻¹) | 50 mg (1.0 g L⁻¹) |
| Reaction volume | 50 mL | 50 mL |
| Light source | 300 W Xe lamp (Newport 66902), λ > 420 nm cutoff | 300 W Xe lamp (Newport 66902), λ > 420 nm cutoff |
| Light intensity | 100 mW cm⁻² (AM 1.5G) | 100 mW cm⁻² (AM 1.5G) |
| Temperature | 25 ± 2 °C (water-cooled) | 25 ± 2 °C (water-cooled) |
| Atmosphere | N₂ purge (30 min) | CO₂ bubbling (30 min, 40 mL min⁻¹) |
| Sacrificial agent | Na₂S (0.35 M) / Na₂SO₃ (0.25 M) | TEOA (10 vol%) |
| Duration | 5 h | 5 h |
| Replicates | n = 3 (independent experiments) | n = 3 (independent experiments) |

---

## Key Results

### Physicochemical Properties (Table 3)

| Sample | Crystal Phase | BET Surface Area (m² g⁻¹) | Bandgap (eV) | PL Intensity (a.u.) |
|--------|--------------|---------------------------|-------------|---------------------|
| Pristine A (α-Fe₂O₃) | Single phase oxide | 42.3 | 2.85 | 2850 |
| Pristine B (NiFe₂O₄) | Single phase oxide | 67.8 | 2.42 | 1920 |
| 10% Heterostructure | Mixed phases | 112.6 | 2.51 | 1120 |
| **Optimal Heterostructure** | **S-scheme interface** | **128.3** | **2.48** | **890** |

### H₂ Evolution Performance Comparison (Table 4)

| Photocatalyst | Light Source | Sacrificial Agent | H₂ Rate (μmol g⁻¹ h⁻¹) | AQY (%) |
|--------------|-------------|-------------------|------------------------|---------|
| TiO₂/g-C₃N₄ [3] | Xe, >420 nm | TEOA | 485 | 2.8 |
| ZIF-8-derived ZnO/CdS [26] | Visible | Na₂S/Na₂SO₃ | 1240 | 4.2 |
| UiO-66-derived TiO₂/CdS [26] | Xe, >420 nm | Lactic acid | 1567 | 5.1 |
| **This work (S-scheme)** | **Xe, >420 nm** | **Na₂S/Na₂SO₃** | **2340 ± 45** | **8.2** |

### CO₂ Photoreduction Comparison (Table 6)

| Photocatalyst | Heterojunction Type | Main Product | Rate (μmol g⁻¹ h⁻¹) |
|--------------|--------------------|--------------|--------------------|
| g-C₃N₄/NiO [3] | Type-II | CO | 32.5 |
| BiOBr/Bi₂WO₆ [4] | Z-scheme | CO | 41.2 |
| CdS/WO₃ [2] | S-scheme | CO | 52.3 |
| **This work** | **S-scheme** | **CO** | **58.7 ± 2.1** |

### Active Species Trapping (Table 7)

| Scavenger | Target Species | H₂ Rate Inhibition (%) | CO Rate Inhibition (%) |
|-----------|---------------|------------------------|----------------------|
| EDTA | h⁺ | 51.9 | 51.6 |
| AgNO₃ | e⁻ | 80.5 | 79.4 |
| BQ | •O₂⁻ | 19.0 | 16.2 |
| TBA | •OH | 6.5 | 4.9 |

### Cycling Stability (Table 8)

| Cycle | H₂ Rate Retention (%) | CO Rate Retention (%) | Structural Change |
|-------|----------------------|----------------------|-------------------|
| 1 | 100.0 | 100.0 | None |
| 2 | 99.2 | 98.8 | None |
| 3 | 98.5 | 97.5 | None |
| 4 | 97.7 | 96.2 | None |
| 5 | 95.5 | 93.5 | None |

---

## Raw Data Description

### `raw_data/XRD_raw_counts.csv`
Powder X-ray diffraction intensity data (counts) as a function of 2θ angle for five samples: Pristine MOF precursor, Intermediate (300 °C treated), Component A (α-Fe₂O₃), Component B (NiFe₂O₄), and S-scheme Heterostructure. Acquired with 0.02° step size across 2θ = 10–80° (3501 data points per pattern).

### `raw_data/UV_Vis_DRS_raw.csv`
UV–Vis diffuse reflectance spectroscopy absorbance data for six compositions (Pristine A, Pristine B, 5%, 10%, 15%, and 20% heterostructures) recorded from 200–800 nm at 0.5 nm resolution (1200 data points per spectrum).

### `raw_data/PL_raw_data.csv`
Photoluminescence emission spectra (λex = 325 nm) for Pristine A, Pristine B, and S-scheme Heterostructure, recorded from 340–650 nm at 0.5 nm steps.

### `raw_data/GC_TCD_H2_raw.csv`
Gas chromatograph–thermal conductivity detector raw chromatogram for H₂ quantification. Retention time (min) versus TCD response (mV). H₂ retention time: 2.8 min.

### `raw_data/GC_FID_CO2products_raw.csv`
GC-FID chromatogram for CO₂ reduction gaseous products. Identified peaks: CO (tR = 3.5 min), CH₄ (tR = 5.2 min), CH₃OH (tR = 8.8 min), HCOOH (tR = 10.5 min).

### `raw_data/H2_evolution_triplicate.csv`
Time-dependent H₂ evolution data from triplicate independent experiments (n = 3) for all photocatalyst compositions. Includes mean, standard deviation, and individual run data at 0.5 h intervals over 5 h irradiation.

---

## Processed Data Description

### `processed_data/MOF_SScheme_Complete_Dataset.xlsx`

Master Excel workbook containing all processed characterization data organized across the following sheets:

| Sheet | Content |
|-------|---------|
| `XRD_Raw_Counts` | XRD diffraction patterns (all samples) |
| `Scherrer_Analysis` | Crystallite size from Scherrer equation |
| `UV_Vis_DRS` | UV–Vis DRS absorbance spectra |
| `PL_Spectra` | Photoluminescence emission data |
| `EIS_Fitted_Params` | EIS equivalent circuit fitting (Rs, Rct, CPE-Q, α, σ-Warburg, χ²) |
| `H2_Triplicate` | Triplicate H₂ evolution kinetics |
| `AQY` | Wavelength-dependent apparent quantum yield (420–600 nm) |
| `CO2_Products` | CO₂ reduction product evolution (CO, CH₄, CH₃OH, HCOOH) |
| `Stability` | Five-cycle retention data |
| `Table4_H2_Comparison` | Literature benchmark — H₂ evolution |
| `Table6_CO2_Comparison` | Literature benchmark — CO₂ reduction |
| `Table7_Scavenger` | Active species trapping results |
| `Band_Positions` | S-scheme band edge positions (ECB, EVB vs. NHE, work functions) |

### `processed_data/EIS_fitted_parameters.csv`

Randles equivalent circuit fitting results from Nyquist plots:

| Sample | Rs (Ω) | Rct (Ω) | CPE-Q (F s^(α−1)) | α | σ-Warburg (Ω s⁻⁰·⁵) | χ² |
|--------|--------|---------|-------------------|---|--------------------|-----|
| Pristine A | 14.2 | 342 | 2.1 × 10⁻⁵ | 0.84 | 8.0 | 0.0042 |
| Pristine B | 11.8 | 245 | 3.2 × 10⁻⁵ | 0.86 | 6.5 | 0.0035 |
| 5% Heterostructure | 10.5 | 178 | 4.1 × 10⁻⁵ | 0.87 | 5.0 | 0.0028 |
| 10% Heterostructure | 9.3 | 128 | 5.3 × 10⁻⁵ | 0.88 | 4.2 | 0.0031 |
| **15% Heterostructure (Optimal)** | **8.1** | **82** | **7.2 × 10⁻⁵** | **0.90** | **3.0** | **0.0024** |
| 20% Heterostructure | 8.8 | 108 | 5.8 × 10⁻⁵ | 0.89 | 3.8 | 0.0029 |

### `processed_data/Scherrer_analysis.csv`

Average crystallite size determined from XRD peak broadening using the Scherrer equation (D = Kλ / β cos θ, K = 0.9):

| Sample | Peak 2θ (°) | FWHM (°) | Crystallite Size (nm) |
|--------|------------|----------|----------------------|
| Pristine MOF | 12.72 | 0.20 | 45.0 |
| Component A (α-Fe₂O₃) | 33.15 | 0.20 | 18.0 |
| Component B (NiFe₂O₄) | 35.44 | 0.22 | 12.0 |
| S-scheme Heterostructure | 35.44 | 0.32 | 5.5 |

---

## S-Scheme Band Alignment

Band edge positions determined from UV–Vis DRS (Tauc plot) and Mott–Schottky analysis:

| Component | Role | Bandgap (eV) | ECB (V vs. NHE) | EVB (V vs. NHE) | Work Function (eV) |
|-----------|------|-------------|-----------------|-----------------|-------------------|
| Component A (α-Fe₂O₃) | Oxidation Photocatalyst | 2.85 | −0.603 | +2.247 | 5.3 |
| Component B (NiFe₂O₄) | Reduction Photocatalyst | 2.42 | −0.203 | +2.217 | 4.8 |

The work function difference (ΔΦ = 0.5 eV) drives the internal electric field at the heterointerface, facilitating S-scheme charge transfer where low-energy carriers recombine at the interface while high-energy electrons (RP conduction band) and holes (OP valence band) are retained for H₂ evolution and CO₂ reduction, respectively.

---

## Data Availability

All data generated and analysed during the current study are included in this published article and its supplementary information files. The complete datasets are publicly available at:

**https://github.com/nishaangelinem-coder/MOF-Derived-Heterostructured-photocatalyst**

---

## Citation

If you use this data in your research, please cite:

```bibtex
@article{angeline2025mof_sscheme,
  title     = {Green-Synthesized S-Scheme MOF-Derived Heterostructured Photocatalyst 
               for Visible-Light-Driven Hydrogen Evolution and CO₂ Reduction},
  author    = {Angeline M, Nisha and Manikandan, S K},
  journal   = {},
  year      = {2025},
  doi       = {},
  url       = {https://github.com/nishaangelinem-coder/MOF-Derived-Heterostructured-photocatalyst}
}
```

---



## Contact

**Dr. M. Nisha Angeline**  
Department of Electronics and Communication Engineering  
Velalar College of Engineering and Technology  
Erode, Tamil Nadu 638012, India

---

*Repository last updated: March 2026*
