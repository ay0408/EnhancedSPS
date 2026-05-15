# Differentially Private Selection using Enhanced Sensitivity Concepts

We propose novel differentially private selection mechanisms using enhanced sensitivity concepts. In the paper, we first enhance concepts of global and smooth sensitivity to simultaneously handle changes in the scores of both the target and the other candidates. We then propose direction-aware concepts that consider the direction of changes as well. We further present enhanced concepts that can be employed when using a one-sided distribution. The proposed concepts are stricter than existing ones, leading to lower amount of noise and higher output accuracy.

In "beta_evaluation" folder, we pre-evaluated the value of $l$ for the proposed mechanisms.

In "Accuracy" folder, we compared the accuracy of our mechanisms with existing mechanisms, using simulation data for TDT statistics. The results show that our mechanisms can provide the highest accuracy.

In "distribution_evaluation" folder, we investigated suitable values of $\gamma$ and $\zeta$ in the probability distributions.

Supplements.pdf provides the proofs and omitted definitions in the main paper. 


## Note

For details of our methods and discussion, please see our paper entitled "Differentially Private Selection using Enhanced Sensitivity Concepts".

### Contact
Akito Yamamoto

Division of Medical Data Informatics, Human Genome Center,

the Institute of Medical Science, the University of Tokyo

a-ymmt@ims.u-tokyo.ac.jp
