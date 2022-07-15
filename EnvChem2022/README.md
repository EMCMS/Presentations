# EnvChem2022 RSC York, UK 

## Slides for: From descriptors to intrinsic fish toxicity of chemicals: an alternative approach to chemical prioritization

### Abstract

Most chemicals present in the human and environmental exposome are structurally unknown (i.e. ≤ 1%). The European Chemicals Agency (ECHA) and US Environmen- tal Protection Agency (EPA) have listed approximately 800k chemicals that must be further investigated for their potential environmental and/or human health risk. A sig- nificant number of these chemicals have large enough global volumes of consumption (e.g. industrial and agrochemical) to reach the limits of detection of our analytical chemistry methods and may be toxic. In this study we present a supervised classification model that directly connects the molecular descriptors of chemicals to their toxicity. As a proof of concept we used 907 experimentally defined LC50 values for acute fish toxicity. Our classification model explained ≈ 90% of variance in our data for the training set and ≈ 80% for the test set. Direct comparison of our classification model with the conventional strategy (i.e. QSAR regression models) resulted in a 5 fold decrease in the wrong chemical categorization for our model. This optimized model was employed to predict the toxicity categories of ≈ 32k chemicals (from the Norman SusDat). Finally, a comparison between the model based applicability domain (AD) vs the training set AD was performed, suggesting that the training set based AD is a more adequate way to avoid extrapolation when using such models. The better performance of our direct classification model compared to conventionally employed QSAR methods, makes this approach a viable tool for hazard identification and risk assessment of chemicals.

### Citation

[DOI Presentation: 10.13140/RG.2.2.14278.34881](https://github.com/EMCMS/Presentations/tree/main/EnvChem2022)

[DOI manuscript](https://chemrxiv.org/engage/chemrxiv/article-details/62ac9a8004a3a97dec4a2223)

@article{samanipour2022descriptors,
  title={From descriptors to intrinsic fish toxicity of chemicals: an alternative approach to chemical prioritization},
  author={Samanipour, Saer and O'Brien, Jake and Reid, Malcolm and Thomas, Kevin and Praetorius, Antonia},
  year={2022}
}

### Data and code 

[Code](https://bitbucket.org/SSamanipour/toxcatpred-jl/src/main/)


[Data](https://uvaauas.figshare.com/articles/dataset/FishTox_Data/20089751)

