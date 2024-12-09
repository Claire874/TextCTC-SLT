# TextCTC-SLT (COLING2025)

Implementation of paper "Improvement in Sign Language Translation Using Text CTC Alignment"

## Paper Highlights
Unlike other sign language translation(SLT) technique which limits the Connectionist Temporal Classification (CTC) for sign langauge translation (SLT). Our work, however, fully explores CTC capacity for non-monotic alignment between sign language and spoken text for SLT.
 
 Briefly,
- We propose leveraging a **joint CTC/Attention framework** combined with **transfer learning** to address the unique challenges of SLT, particularly the modality gap between visual sign language and spoken text. Compared with speech and text translation, SLT requires handling more complex spatial-temporal representations and addressing non-monotonic alignments to grasp the linguistic feature embedded in sign language.
- The proposed method achieves results comparable to state-of-the-art, outperforming the pure-attention baseline on widely adopted benchmarks, RWTH-PHOENIX-Weather 2014 T and CSL-Daily.
- We offer a promising direction for future research by exploring the potential of **text CTC alignment for gloss-free SLT**.

## Proposed Method Overview
![Overview](Overview.png)


## Sign Embeddings

Please follow the intructions of [SMKD](https://github.com/VIPL-SLP/VAC_CSLR/tree/main) and [Corrent](https://github.com/hulianyuyy/CorrNet/tree/main) to extract sign features.


## Data Augmentation

The Augmented PHOENIX14T is based on [Text2Gloss](https://github.com/DFKI-SignLanguage/text-to-gloss-sign-language-translation) Machine Translation task.
We use back translation to obtain the paraphased CLS-Daily spoken text.



## Citation 

If you get any inspriation from this paper, please consider to cite it!
