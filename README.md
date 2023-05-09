
<!-- README.md is generated from README.Rmd. Please edit that file -->

# SAS Group Comparison Macros: %DSTMAC, %UNI_CAT, %ggBaseline

<!-- badges: start -->
<!-- badges: end -->

**Purpose**  
Introduce different summary tables under group stratification

**Description**  
The SAS file walks through data analysis for a demonstration dataset
using three SAS macros: %DSTMAC (Fenchel, McPhail, and VanDyke 2011),
%UNI_CAT (Liu et al. 2019), and %ggBaseline (Gu et al. 2018). Two
variables (“trt” and “sex”) are used as stratification variables. In
summary statistics, means ± standard deviations are calculated for
continuous variables and N (%) are produced for categorical variables.
Statistical tests include:

- Parametric Test: T-Test/ANOVA for continuous variables
- Parametric Test: Likelihood Ratio Chi-Square Test for categorical
  variables
- Non-parametric Test: Kruskal-Wallis Test for continuous variables
- Non-parametric Test: Fisher’s Exact Test for categorical variables

**Dataset**  
PBC

**Date**  
09/24/2019

**Demonstrated SAS Version**  
SAS 9.4

**Authors**  
Pei-Shan Yen, Nairita Ghosal, Yi-Fan Chen  
Biostatistics Core, Center for Clinical and Translational Science  
University of Illinois at Chicago

## References

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-Fenchel2011" class="csl-entry">

Fenchel, Matthew C., Gary L. McPhail, and Rhonda D. VanDyke. 2011. “A
Lazy Programmer’s Macro for Descriptive Statistics’ Tables.” In *MidWest
SAS Users Group*.
<https://www.mwsug.org/proceedings/2011/stats/MWSUG-2011-SA19.pdf>.

</div>

<div id="ref-Gu2018" class="csl-entry">

Gu, Hong-Qiu, Dao-Ji Li, Chelsea Liu, and Zhen-Zhen Rao. 2018. “<span
class="nocase">%ggBaseline: a SAS macro for analyzing and reporting
baseline characteristics automatically in medical research</span>.”
*Annals of Translational Medicine* 6 (August): 326–26.
<https://doi.org/10.21037/atm.2018.08.13>.

</div>

<div id="ref-Liu2019" class="csl-entry">

Liu, Yuan, Dana C. Nickleach, Chao Zhang, Jeffrey M. Switchenko, and
Jeanne Kowalski. 2019. “Carrying Out Streamlined Routine Data Analyses
with Reports for Observational Studies: Introduction to a Series of
Generic SAS ®Macros.” *F1000Research* 7.
<https://doi.org/10.12688/f1000research.16866.2>.

</div>

</div>
