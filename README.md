[![DOI](https://zenodo.org/badge/1019784935.svg)](https://doi.org/10.5281/zenodo.15885589)
![Visitors Badge](https://visitor-badge.laobi.icu/badge?page_id=RuiGao9.LWP_Mapping_sUAS_California)<br>
# LWP_Mapping_sUAS_California
This repository and another one ([LWP_Vineyard_Features](https://github.com/RuiGao9/LWP_Vineyard_Features)) support a peer-reviewed journal paper (Integrating Time-Series Meteorological Data and sUAS Information into a Machine Learning Framework for California Vineyard Water Stress Monitoring) showing a simplified model for California vineyard leaf water potential mapping. A subtitle or the main title is below.<br>
In this repository, we provided:
1. `Input_data`, a folder contains demo data. `Demo_INput_TIR.tif` is the temperature image (in Celsius) obtained from the AggieAir sUAS. `Demo_Input_VNIR.tif` is the multi-spectral image (red, green, blue, and near-infrared).
2. `main_program.ipynb` is the main program, which is a simplifed model from the research **Integrating Time-Series Meteorological Data and sUAS Information into a Machine Learning Framework for California Vineyard Water Stress Monitoring**.
3. `xgb_tt.pkl` is the trained machine learning model (using the XGBoost approach). The required inputs are listed in the research paper, and we also list them below.
   - , air temperature in Celsius at 2 m above ground level.
   - , canopy temperature in Celsius.


## A Simplified Model for California Grapevine Leaf Water Potential Mapping at the Field Scale Based on a Machine Learning Approach

<p align="center">Rui Gao<sup>1,2,3</sup>, Alfonso Torres-Rua<sup>1</sup>, Maria Mar Alsina<sup>4</sup></p>
<sup>1</sup>Department of Civil and Environmental Engineering, Utah State University, Logan, UT 84321, USA<br>
<sup>2</sup>Department of Civil and Environmental Engineering, University of California, Merced, CA 95343, USA<br>
<sup>3</sup>Valley Institute for Sustainable Technology & Agriculture, University of California, Merced, CA 95343, USA<br>
<sup>4</sup>Institute of Research, Technology, Food & Agriculture (IRTA), Mas Badia. Tallada d’Empordà, 17134, Spain<br>

## Citation 
If you use this repository in your work, please consider following reference/DOIs:<br>
[![DOI](https://zenodo.org/badge/DOI/10.1007/s00271-026-01102-8.svg)](https://doi.org/10.1007/s00271-026-01102-8)<br>
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16730652.svg)](https://doi.org/10.5281/zenodo.16730652)<br>
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15885589.svg)](https://doi.org/10.5281/zenodo.15885589)<br>
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18305013.svg)](https://doi.org/10.5281/zenodo.18305013)

**BibTeX:**
```bibtex
@misc{gao2025lwpis,
  author       = {Rui Gao, Maria Mar Alsina, Alfonso Torres-Rua, Lawrence Hipps, William P. Kustas, Martha Anderson, Héctor Nieto, Andrew J. McElrone, Kyle Knipper, Nicolas Bambach Ortiz, Sebastian J. Castro, John H. Prueger, Joseph Alfieri, Lynn G McKee, William A. White, Feng Gao, Calvin Coopmans, Ian Gowing, Nurit Agam, Luis Sanchez, Nick Dokoozlian},
  title        = {A machine learning framework for California vineyard water status monitoring using sUAS imagery and short-term meteorological data},
  year         = {2026},
  publisher    = {Irrigation Science},
  doi          = {https://doi.org/10.1007/s00271-026-01102-8},
  url          = {https://link.springer.com/article/10.1007/s00271-026-01102-8#citeas}
}
```
```bibtex
@misc{gao2025lwpfeature,
  author       = {Rui Gao, Alfonso Torres-Rua},
  title        = {Feature Extraction From the High-resolution AggieAir Images for Leaf Water Potential Estimation in California Vineyards},
  year         = {2025},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.16730652},
  url          = {https://doi.org/10.5281/zenodo.16730652}
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
```bibtex
@misc{gao2026windex,
  author       = {Rui Gao, Alfonso Torres-Rua, Mohammad Safeeq, and Joshua H. Viers},
  title        = {A Python Tool for Winkler Index Calculation based on Hourly Air Temperature Records},
  year         = {2026},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.18305013},
  url          = {https://doi.org/10.5281/zenodo.18305013}
}
```

## Contact info
Rui.Ray.Gao@Gmail.com<br>
RuiGao@USU.edu<br>
RuiGao@UCMerced.edu
