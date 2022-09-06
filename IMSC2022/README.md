# IMSC2022 NVMS Maastricht, the Netherlands 

## [Slides for: Naïve Bayes classification model for isotopologue detection in LC-HRMS data](Probabilistic%20classification%20ER%20model%20for%20isotope%20detection_IMSC.pdf)

### Presenter: Denice van Herwerden

### Abstract

Isotopologue identification or removal is a necessary step to reduce the number of features that need to be identified in samples analyzed with non-targeted analysis. Currently available approaches rely on either predicted isotopic patterns or an arbitrary mass tolerance, requiring information on the molecular formula or instrumental error, respectively. Therefore, a Naive Bayes isotopologue classification model was developed that does not depend on any thresholds or molecular formula information. This classification model uses the elemental mass defects of six elemental ratios and successfully identified isotopologues for both theoretical isotopic patterns and wastewater influent samples, outperforming one of the most commonly used approaches (i.e., 1.0033 ​Da mass difference method - CAMERA). For the theoretical isotopologues, the classification model outperformed an “in-house” mass difference method with a true positive rate (TPr) of 99.0% and false positive rate (FPr) of 1.8% compared to a TPr of 16.2% and an FPr of 0.02%, assuming no error. As for the wastewater influent samples, the classification model, with a TPr of 99.8% and false detection rate (FDr) of 0.5%, again performed better than the mass difference method, with a TPr of 96.3% and FDr of 4.8%. Therefore, it can be concluded that the classification model can be used for isotopologue identification, requiring no thresholds or information on the molecular formula.

### Citation

[DOI manuscript](https://www.sciencedirect.com/science/article/pii/S0169743922000260)

@article{van2022naive,
  title={Naive Bayes classification model for isotopologue detection in LC-HRMS data},
  author={van Herwerden, Denice and O'Brien, Jake W and Choi, Phil M and Thomas, Kevin V and Schoenmakers, Peter J and Samanipour, Saer},
  journal={Chemometrics and Intelligent Laboratory Systems},
  volume={223},
  pages={104515},
  year={2022},
  publisher={Elsevier}
}


## [Slides for: InSpectra – A Global Platform for Identifying Emerging Chemical Threats](IMSC2022.pdf)

### Presenter: Saer Samanipour

### Abstract

Non-target analysis (NTA) combined with high resolution mass spectrometry (HRMS) is considered the most comprehensive monitoring approach for characterization of the chemical exposome. NTA has thus far not fulfilled its promise of comprehensive analysis and been adopted as a routine approach due to the richness of HRMS data, sample complexity, and the challenges faced by the analysts to perform NTA. NTA data are typically very large (3-4 GB per sample), noisy, and complex so analysts must perform multiple data pre-processing steps to be able to identify features in a sample. These steps may include feature detection, feature prioritization, and database matching. Due to the complexity of these datasets, each step taken in an NTA workflow is prone to error and thus false detection. Here we present a collection of open source/access tools that we have developed to specifically improve and simplify the NTA workflow from feature detection to identification, while maintaining maximum transparency. These tools have been tested on complex environmental samples such as wastewater influent and wastewater sludge and have outperformed commonly used methodologies. Additionally, we present the implementation of these tools within the framework of an open access web platform. This cloud-based web platform will provide both a hub for data processing and a repository for data.  The repository facilitates future analysis (i.e. retrospective NTA and/or suspect screening). We envisage that the platform will be a focal point for future developments in NTA.  