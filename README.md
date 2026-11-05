<div align="center">

# Esteban Cruz Isidro

**Physical oceanographer · Numerical ocean modeller**

*Simulating ocean dynamics, one MITgcm run at a time.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/esteban-cruz-isidro-1a6a421a3)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:estebanci96@gmail.com)

</div>

---

## About me

I'm a physical oceanographer from Mexico, finishing my M.Sc. in Earth Sciences (Meteorology & Physical Oceanography) at UNAM. I build and run numerical ocean models, from idealized process studies in MITgcm to an operational regional forecast with HYCOM.

**🔭 Seeking a PhD starting in 2027** in polar ocean modelling: ice–ocean interaction, internal waves and mixing in polar oceans, and machine learning for ocean models. I'd love the PhD to include Antarctic or Arctic fieldwork.

---

## Research

### 🌊 Internal waves radiated by a wind-forced bay — M.Sc. thesis (UNAM, 2026)
*Advisor: Dr. Ana Karina Ramos Musalem · Presented at EGU General Assembly 2025*

Idealized MITgcm experiments of a bay the size of Sebastián Vizcaíno Bay (Baja California), forced by a 2.8 h wind pulse, under linear, realistic and two-layer stratification, each with a no-bay control run.

- The 3.8 h seiche period does not depend on stratification, but its decay does (8.3, 9.0 and 9.9 h).
- Barotropic-to-baroclinic conversion at the mouth explains 18, 10 and 1 % of the seiche decay.
- **The seiche is not the main pathway:** most of the baroclinic energy leaving the bay is its near-inertial response (1.01–1.07 f), which exits as a sloping beam and as coastal internal Kelvin waves.

➡️ [Model configuration](https://github.com/Estebanovich/BayIW_Rectan) · [Analysis & figures](https://github.com/Estebanovich/-IWBayMITgcm-postprocessing)

### 🛰️ Operational ocean forecasting — UNAM / CENAPRED (2023–present)
- Built and operate a **1/25° HYCOM forecast for the Mexican Pacific** (1.8 M grid points, 36 hybrid layers), forced by WRF winds, rivers and 8-constituent TPXO10 tides with self-attraction and loading. It provides the total-water-level component of CENAPRED's early-warning system for storm surge and extreme events.
- Maintain the daily HYCOM forecast for the Gulf of Mexico on UNAM's HPC cluster, delivering SST, SSH and heat-content products to PEMEX, CONAGUA and civil-protection authorities.
- Operate a PyGNOME Lagrangian dispersal system for oil-spill response, and wrote a tested Python toolkit (265 tests) that compares HYCOM, ESPC and Copernicus Marine forecasts.
- Designing a two-way WRF–HYCOM coupled system (ESMF/NUOPC) for tropical cyclones in the eastern Pacific.

*(Operational code is private to the institution.)*

### 🏞️ Interaction between submarine canyons — B.Sc. thesis (UNAM, 2023)
MITgcm simulations of rotating-tank upwelling over two identical canyons. The upstream canyon always upwelled more than the downstream one, so the canyons interact dynamically; the difference shrinks as the Rossby and Burger numbers grow.

### 🚢 Fieldwork
Research cruise on R/V *Justo Sierra*, Gulf of Mexico (May 2024): hydrographic, biological and sediment sampling, data QC.

---

## Tools

**Ocean & climate models:** MITgcm · HYCOM · WRF forcing · PyGNOME · ESMF/NUOPC · TPXO10 · ERA5 · GEBCO
**Machine learning:** ECMWF Anemoi (graph neural networks on ERA5) · scikit-learn
**Programming & HPC:** Python · Fortran · Bash/C-shell · MATLAB · MPI · SLURM · Linux clusters
**Data:** xarray · NetCDF4 · Dask · NumPy · Matplotlib · Cartopy · Jupyter

---

## Outreach
🎙️ Creator and host of *Pronóstico*, a Spanish-language podcast on climate science.

🌎 Spanish (native) · English (professional) · French (basic)
