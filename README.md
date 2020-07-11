# Data Center PUE Prediction Tool

* A simple simulation tool for *world-wide analysis* of data center infrastructure energy efficiency (power usage effectiveness);
  
* A robust simulation tool for *large-scale global analysis*, low demanding on computational resource, without sacrificing prediction accuracy;

* Physics-based model supporting *national-level scenario analysis*;

* Support effective *PUE target-setting* according to Climate Zone.

  
# PUE predition for hyperscale data centers

* Hyperscale data centers with airside economizer + adiabatic cooling: __PUE_AE_Chiller(w_aech,*data)__
* Hyperscale data centers utilizing evaporative cooling capability of cooling towers (waterside economizer): __PUE_WEC_Chiller(w_wech,*data)__
* Hyperscale data centers with seawater cooling (waterside economizer): __PUE_WES_Chiller(w_wech,*data)__

# Inputs

* Climate condition
* Hyperscale data center energy system parameters (equipment specifications, system operational efficiency metrics, and indoor environment set points)
* Inputs for sensitivity analysis: please refer to __Table A.1. Model input values and ranges__ in the __Energy paper__
* Inputs for uncertainty quantification: based on location-specific climate data and calibriated system parameters described in the __Energy paper__

# Implementation of Sobol Sensitivity Analysis

* Hyperscale data centers with airside economizer + adiabatic cooling: __F.1.1_AE_sensitivity analysis.ipynb__
* Hyperscale data centers utilizing evaporative cooling capability of cooling towers (waterside economizer): __F.1.2_WEC_sensitivity analysis.ipynb__
* Hyperscale data centers with seawater cooling (waterside economizer): __F.1.3_WES_sensitivity analysis.ipynb__


# Reference

* Lei, Nuoa, and Eric Masanet. "Statistical analysis for predicting location-specific data center PUE and its improvement potential." Energy (2020): 117556. https://doi.org/10.1016/j.energy.2020.117556

# Contact
Author: Nuoa Lei (nuoalei2021@u.northwestern.edu）

