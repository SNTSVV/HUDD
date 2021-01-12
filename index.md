

## Overview 

Deep neural networks (DNNs) are increasingly important in safety-critical systems, for example in their perception layer to analyze images. Unfortunately, there is a lack of methods to ensure the functional safety of DNN-based components. The machine learning literature suggests one should trust DNNs demonstrating high accuracy on test sets. In case of low accuracy, DNNs should be retrained using additional inputs similar to the error-inducing ones.

We observe three major challenges with existing practices regarding DNNs in safety-critical systems: (1) scenarios that are underrepresented in the test set may lead to serious safety violation risks, but may, however, remain unnoticed; (2) char- acterizing such high-risk scenarios is critical for safety analysis; (3) retraining DNNs to address these risks is poorly supported when causes of violations are difficult to determine.

To address these problems in the context of DNNs analyzing images, e.g., in the perception layers of cyber-physical systems, we propose HUDD, an approach that automatically supports the identification of root causes for DNN errors. We automatically group error-inducing images whose results are due to common subsets of DNN neurons. HUDD identifies root causes by applying a clustering algorithm to matrices (i.e., heatmaps) capturing the relevance of every DNN neuron on the DNN outcome. Also, HUDD retrains DNNs with images that are automatically selected based on their relatedness to the identified image clusters.

We have evaluated HUDD with DNNs from the automotive domain. The approach was able to automatically identify all the distinct root causes of DNN errors, thus supporting safety analysis. Also, our retraining approach has shown to be more effective at improving DNN accuracy than existing approaches.


## Replicability package

Our replicability package is available to reviewers at the following URL http://bit.ly/<ID> It will be made public after acceptance.
  
Please replace <ID> with the submission ID associated to the paper (TR-<Year>-<Num>)
