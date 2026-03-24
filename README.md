[![DOI](https://zenodo.org/badge/1019784935.svg)](https://doi.org/10.5281/zenodo.15885589)
![Visitors Badge](https://visitor-badge.laobi.icu/badge?page_id=RuiGao9.LWP_Mapping_sUAS_California)<br>

## A Simplified Model for California Grapevine Leaf Water Potential Mapping at the Field Scale Based on a Machine Learning Approach
This repository and another one ([LWP_Vineyard_Features](https://github.com/RuiGao9/LWP_Vineyard_Features)) support a peer-reviewed journal paper published in *Irrigation Science* ([A machine learning framework for California vineyard water status monitoring using sUAS Imagery and short-term meteorological data](https://link.springer.com/article/10.1007/s00271-026-01102-8#citeas)) showing a simplified model for California vineyard leaf water potential mapping. A subtitle or the main title is below.<br>
In this repository, we provided:
1. `Input_data`, a folder that contains demo data. `Demo_INput_TIR.tif` is the temperature image (in Celsius) obtained from the AggieAir sUAS. `Demo_Input_VNIR.tif` is the multi-spectral image (red, green, blue, and near-infrared).
2. `main_program.ipynb` is the main program, which is a simplified model from the research **A machine learning framework for California vineyard water status monitoring using sUAS Imagery and short-term meteorological data**.
3. `xgb_tt.pkl` is the trained machine learning model (using the XGBoost approach). The required inputs are listed in the research paper, and we also list them below.
   - $T_a$, air temperature in Celsius at 2 m above ground level.
   - $T_c$, canopy temperature in Celsius.


## Reference
Gao, R., Alsina, M. M., Torres-Rua, A. F., Hipps, L., Kustas, W. P., Anderson, M., ... & Dokoozlian, N. (2026). A machine learning framework for California vineyard water status monitoring using sUAS Imagery and short-term meteorological data. Irrigation Science, 44(3), 60. https://doi.org/10.1007/s00271-026-01102-8
Gao, R., Torres-Rua, A., & Alsina, M. M. (2025). A Simplified Model for California Grapevine Leaf Water Potential Mapping at the Field Scale Based on a Machine Learning Approach (v0.0.1). Zenodo. https://doi.org/10.5281/zenodo.15885590
Gao, R., & Torres-Rua, A. (2025). Feature Extraction from the High-resolution AggieAir Images for Leaf Water Potential Estimation in California Vineyards (Initial). Zenodo. https://doi.org/10.5281/zenodo.16730652

## Citation 
If you use this repository in your work, please consider following reference/DOIs:<br>

**BibTeX:**
```bibtex
@misc{gao2025lwpis,
  author       = {Rui Gao, Maria Mar Alsina, Alfonso Torres-Rua, Lawrence Hipps, William P. Kustas, Martha Anderson, Héctor Nieto, Andrew J. McElrone, Kyle Knipper, Nicolas Bambach Ortiz, Sebastian J. Castro, John H. Prueger, Joseph Alfieri, Lynn G McKee, William A. White, Feng Gao, Calvin Coopmans, Ian Gowing, Nurit Agam, Luis Sanchez, Nick Dokoozlian},
  title        = {A machine learning framework for California vineyard water status monitoring using sUAS imagery and short-term meteorological data},
  year         = {2026},
  publisher    = {Irrigation Science},
  doi          = {https://doi.org/10.1007/s00271-026-01102-8},
  url          = {https://link.springer.com/article/10.1007/s00271-026-01102-8}
}
```

```bibtex
@misc{gao2025lwpmap,
  author       = {Rui Gao, Alfonso Torres-Rua, Maria Mar Alsina},
  title        = {A Simplified Model for California Grapevine Leaf Water Potential Mapping at the Field Scale Based on a Machine Learning Approach},
  year         = {2025},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.15885589},
  url          = {https://doi.org/10.5281/zenodo.15885589}
}
```

## Contact info
Rui.Ray.Gao@Gmail.com<br>
RuiGao@USU.edu<br>
RuiGao@UCMerced.edu
