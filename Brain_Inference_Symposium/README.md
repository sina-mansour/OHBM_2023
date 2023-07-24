# Inference on the Brain
## Advances and practices in brain activity inference

### Organizers: [Sina Mansour L.](https://sina-mansour.github.io/) & [Andrew Zalesky](https://findanexpert.unimelb.edu.au/profile/24599-andrew-zalesky)

### Speakers: [Sara Larivière](https://saratheriver.github.io/), [Sina Mansour L.](https://sina-mansour.github.io/), [Stephanie Noble](https://sneuroble.github.io/), & [Paul Taylor](https://www.nimh.nih.gov/research/research-conducted-at-nimh/principal-investigators/paul-taylor-phd)

#### *OHBM 2023* (Symposium: Tuesday, Jul 25, 2:45 PM - 4:00 PM)

Here you may find relevant content to the OHBM 2023 symposium on brain inference:

#### Abstract:

This symposium presents novel statistical advances in current neuroimaging inference techniques. Inference from MRI statistical parametric maps remains a fundamental analytical tool in the cognitive neuroscientist’s toolbox. Researchers commonly use inference techniques to assess the statistical validity of observed effects (e.g. changes in brain activity, connectivity, or structure) on a wide range of study designs. However, the most widely used inference approaches are known to have critical limitations (insufficient power, reliability, replicability, and interpretability) that hinder optimal inference when applied to high-dimensional neuroimaging data. An increasing number of studies are thus deeloping solutions to improve inference quality. This symposium includes four presentations from researchers from three countries (namely Australia, Canada, and the United States) at various career stages (PhD Candidate, Early Career Researcher, Senior Researcher, and Professor).

The symposium will showcase different approaches that provide solutions to improve current methods of inference on the brain, namely our symposium will present: 
1. A toolbox that facilitates statistical analyses of neuroimaging data and the cross-associations with patterns of histological, cognitive, and genetic brain-wide phenotypes,
2. An anatomically informed inference method that links changes in brain activity with underlying white matter connectivity patterns from tractography,
3. An overview for effect-size guidelines in typical fMRI studies and how they may be used to create an empirical power calculator, and
4. Limitations of current inference methods when dealing with asymmetric effects commonly observed in neuroimaging datasets and solutions to address this issue.
By bringing together the distributed knowledge of inference techniques across multiple research groups this symposium serves to promote best practices in state-of-the-art statistical analysis of neuroimaging data in the human brain mapping community.

---
---

### Presentations:

---

#### BrainStat: A toolbox for statistical analysis of neuroimaging data

Analysis and interpretation of neuroimaging datasets has become a multidisciplinary endeavor, relying not only on statistical methods, but increasingly on associations with respect to other brain-derived features such as gene expression, histological data, and functional as well as cognitive architectures. This talk introduces BrainStat—a toolbox for (i) univariate and multivariate linear models in volumetric and surface-based brain imaging datasets, and (ii) multidomain feature association of results with respect to spatial maps of post-mortem gene expression and histology, task-based fMRI meta-analysis, as well as resting-state fMRI motifs across several common surface templates. By being the only tool that combines statistical analysis and contextualization in two widely used programming languages (Python and Matlab), BrainStat facilitates and consolidates analytical workflows as a fully open-access tool.

##### Presenter: [Sara Larivière](https://saratheriver.github.io/)

---

#### Topological Cluster Statistic (TCS): Linking tractography and brain activation to make anatomically-informed inference

Functional magnetic resonance imaging (fMRI) studies use cluster-based inference to detect local changes in brain activity. Insufficient statistical power and disproportionate false-positive rates reportedly hinder optimal inference. In this talk, we present a structural-connectivity-guided clustering framework that enhances sensitivity by leveraging white matter anatomical connectivity information. TCS harnesses multimodal information from diffusion tractography and functional imaging to improve task fMRI activation inference. Compared to conventional approaches, TCS consistently improves statistical power with a widespread 10%-50% increase in local sensitivity. We will additionally showcase how TCS enables inspection of underlying anatomical networks uncovering knowledge regarding the anatomical underpinnings of brain activation. This novel approach is made available in FSL PALM software to facilitate future usability. Given the increasing recognition that activation reflects widespread, coordinated processes, TCS provides a way to integrate the known structure underlying widespread activations into neuroimaging analyses moving forward.

##### Presenter: [Sina Mansour L.](https://sina-mansour.github.io/)

---

#### Towards a large data-driven power calculator for fMRI: preliminary effect size guidelines

Recent work has exposed an endemic lack of statistical power (i.e., ability to detect effects of interest) in fMRI studies, leading to findings that do not replicate or only uncover a small “tip of the iceberg” of true effects. This is partly because it can be challenging to plan well-powered fMRI studies. Existing databases and tools fill a critical need but still require the user to specify the range/distribution of effects to expect a priori or do not provide power estimates for more complex, often nonparametric inferential procedures. Here, we provide a preliminary, interpretable overview regarding the range of effect sizes that may be expected for typical fMRI studies, and outline next steps and plans to build a resolutely empirical power calculator based on this work. Altogether, effects are generally expected to be small across typical study types, and it may be advisable to plan accordingly. We hope this empirical evidence helps not only inform study planning, but also ignites motivation for multivariate methods that capture effects occurring across the image or connectome.

##### Presenter: [Stephanie Noble](https://sneuroble.github.io/)

---

#### Limitations in detecting asymmetric effects using two-tailed inference methods

Traditional analyses of brain images apply a mass univariate approach, independently computing a statistical estimate for each and every voxel. Such approaches require the provision of appropriate familywise error correction strategies to control the number of false positives due to multiple testing. Permutation Thresholding (PT) and false discovery rate (FDR) control reportedly provide higher power compared to traditional Bonferroni correction by assessing the variability in the observed data. However, for two-tailed tests, the resulting thresholds from either PT or FDR are often asymmetric. Existing tools for threshold estimates and visualization often assume or enforce symmetric thresholds and pose limitations in assessing asymmetric effects. In this talk, we describe methods to accurately model these effects.

##### Presenter: [Paul Taylor](https://www.nimh.nih.gov/research/research-conducted-at-nimh/principal-investigators/paul-taylor-phd)

---
