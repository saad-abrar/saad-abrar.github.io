---
title: "Learning Drug-Disease-Target Embedding (DDTE) from knowledge graphs to inform drug repurposing hypotheses"
collection: publications
category: manuscripts
permalink: https://www.sciencedirect.com/science/article/pii/S1532046421001672
excerpt: "We aimed to develop and validate a new graph embedding algorithm DDTE for embedding drug-disease-target networks to generate novel drug repurposing hypotheses."
date: 2021-07-01
venue: "Journal of Biomedical Informatics"
slidesurl: #'http://academicpages.github.io/files/slides1.pdf'
paperurl: "http://saad-abrar.github.io/files/paper1_1.pdf"
citation: "Moon, C., Jin, C., Dong, X., **Abrar, S.**, Zheng, W., Chirkova, R. Y., & Tropsha, A. (2021). Learning Drug-Disease-Target Embedding (DDTE) from knowledge graphs to inform drug repurposing hypotheses. Journal of biomedical informatics, 119, 103838."
---

We aimed to develop and validate a new graph embedding algorithm for embedding drug-disease-target networks to generate novel drug repurposing hypotheses. Our model denotes drugs, diseases and targets as subjects, predicates and objects, respectively. Each entity is represented by a multidimensional vector and the predicate is
regarded as a translation vector from a subject to an object vectors. These vectors are optimized so that when a subject-predicate-object triple represents a known drug-disease-target relationship, the summed vector between the subject and the predicate is to be close to that of the object; otherwise, the summed vector is distant from the
object. The DTINet dataset was utilized to test this algorithm and discover unknown links between drugs and diseases. In cross-validation experiments, this new algorithm outperformed the original DTINet model. The MRR (Mean Reciprocal Rank) values of our models were around 0.80 while those of the original model were about
0.70. In addition, we have identified and verified several pairs of new therapeutic relations as well as adverse effect relations that were not recorded in the original DTINet dataset. This approach showed excellent performance, and the predicted drug-disease and drug-side-effect relationships were found to be consistent with literature reports. This novel method can be used to analyze diverse types of emerging biomedical and healthcare-related knowledge graphs (KG).
