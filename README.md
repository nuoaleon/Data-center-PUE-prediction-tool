# Data Center PUE Prediction Tool

* A simple simulation tool for *world-wide analysis* of data centers energy performace (power usage effectiveness);
  
* A robust simulation tool for *large-scale global analysis*, low demanding on computational resource, without sacrificing prediction accuracy;

* Physics-based model supporting *national-level scenario analysis*;

* Support effective *PUE target-setting* according to Climate Zone

  
# PUE predition for hyperscale data centers

* Hyperscale data centers with airside economizer + adiabatic cooling: __PUE_AE_Chiller(w_aech,*data)__
* Hyperscale data centers utilizing evaporative cooling capability of cooling towers (waterside economizer): __PUE_WEC_Chiller(w_wech,*data)__
* Hyperscale data centers with seawater cooling (waterside economizer): __PUE_WES_Chiller(w_wech,*data)__

# Inputs

* Climate condition
* Hyperscale data center energy system parameters (equipment specifications, system operational efficiency metrics, and indoor environment set points)


# Under-development

* World-wide PUE analysis for non-hyperscale data centers
* World-wide analysis of water usage effectiveness (WUE)
* World-wide analysis of carbon usage effectiveness (CUE)

# Optimization method for PUE target-setting

We suggest using differential evolution for PUE optimization: http://www1.icsi.berkeley.edu/~storn/code.html

# Contact
Author: Nuoa Lei (nuoalei2021@u.northwestern.edu）

