# Trustworthy Online Conformal Prediction by Super Learner Ensembling

Reliable uncertainty quantification is essential in streaming and nonstationary settings. 
Online conformal prediction (OCP) guarantees distribution-free coverage, but its efficiency 
is limited when based on a single model. We extend OCP with the Super Learner (SL), a meta-learning ensemble that combines heterogeneous predictors under constrained weights. Compared with Conformal Online Model Aggregation (COMA), our approach consistently 
yields narrower confidence intervals while maintaining validity. Experiments on synthetic jump--diffusion data and the \texttt{ELEC2} dataset show that: (i) the Super Learner outperforms individual base learners and COMA, (ii) when included as an expert it 
dominates COMA ensembles, and (iii) all methods preserve coverage near the nominal level. 
These results highlight meta-learning as a practical strategy for improving efficiency 
in online conformal prediction.  
