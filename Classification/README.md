# Classification

For classification, we compared the performance of supervised and self-supervised (DINO and CASS) on different label fractions.

We used the following implementations:

-  [ CASS ](https://github.com/pranavsinghps1/CASS)
- [ DINO ](https://github.com/lucidrains/vit-pytorch)
- [ Supervised ](https://github.com/pranavsinghps1/DEDL/tree/main/Classification)

# Datasets

We used three datasets for classification: The ISIC-2017, Dermofit, and the dermatomyositis dataset.
- The ISIC-2017 dataset is open-sourced and available [at this link.](https://challenge.isic-archive.com/data/#2017)
- The Dermofit dataset comes from the Dermofit project of the University of Edinburgh and can be accessed for a small fee from [this link](https://homepages.inf.ed.ac.uk/rbf/DERMOFIT/datasets.htm).
- The Dermatomyositis dataset used in our study is not open-sourced and originates from the work of Van Buren et al. [1]. Kindly contact the corresponding author for more information.

# References

[1] Van Buren, K., Li, Y., Zhong, F., Ding, Y., Puranik, A., Loomis, C. A., ... & Niewold, T. B. (2022). Artificial intelligence and deep learning to map immune cell types in inflamed human tissue. _Journal of Immunological Methods_, _505_, 113233.