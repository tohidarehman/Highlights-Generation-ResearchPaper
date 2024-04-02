**Paper Title:** "Generation of Highlights from Research Papers Using Pointer-Generator Networks and SciBERT Embeddings" authored by Tohida Rehman, Debarshi Kumar Sanyal, Samiran Chattopadhyay, Plaban Kumar Bhowmick, Partha Pratim Das.
**Author Written Research Highlights:** 
1. A new multi-disciplinary dataset called MixSub is also presented. It contains URIs of papers from different domains. Each paper contains research highlights in addition to the abstract. The performance of the proposed method on MixSub is also described.
2. Conducted crawling and publishing activities to compile the CSPubSum dataset, comprising 10,147 computer science publications sourced from ScienceDirect.
3. An approach for extracting research highlights from scientific papers is proposed.
4. The proposed approach combines SciBERT pre-trained word embeddings with a pointer-generator network that also uses a coverage mechanism.
5. The proposed approach outperforms existing methods on CSPubSum dataset in terms of ROUGH, METEOR , and BERTScore metrics.

**MixSub Dataset:**
1. We propose a new dataset called MixSub that contains research articles from multiple domains.
2. To prepare MixSub, we crawled the ScienceDirect website and curated articles published in various journals in year 2020.
3. We removed the articles that did not contain research highlights.
4. Finally, we got 19785 articles with author-written research highlights as shown in Table given below.
5. Each example in this dataset is organized as **(abstract,  author-written research highlights)**.
6. We have also segmented the dataset into **training, validation and test** subsets in the ratio of **80:10:10**.

**Subject-wise URL/data contents count in MixSub dataset**

| ----------- | ----------------------------------------------    | ------ | ------ | ---- | ----- |
| Domain Name | Subject Name                                      | #Total | #Train | #Val | #Test |
|-------------|---------------------------------------------------|--------|--------|------|-------|
| Biological  | Agricultural and Biological Sciences              | 2156   | 1726   | 216  | 214   |
|             | Biochemistry, Genetics and Molecular Biology      | 976    | 806    | 71   | 99    |
|             | Immunology and Microbiology                       | 233    | 195    | 24   | 14    |
|             | Neuroscience                                      | 962    | 771    | 96   | 95    |
| ----------- | ----------------------------------------------    | ------ | ------ | ---- | ----- |
| Chemistry   | Chemical Engineering                              | 2140   | 1713   | 214  | 213   |
|             | Chemistry                                         | 2282   | 1919   | 240  | 123   |
|             | Materials Science                                 | 735    | 572    | 82   | 81    |
| ----------- | ----------------------------------------------    | ------ | ------ | ---- | ----- |
| Energy      | Energy                                            | 1313   | 1025   | 145  | 143   |
|             | Environmental Science                             | 677    | 517    | 81   | 79    |
| ----------- | ----------------------------------------------    | ------ | ------ | ---- | ----- |
| Management  | Business, Management and Accounting               | 698    | 560    | 70   | 68    |
|             | Decision Sciences                                 | 947    | 759    | 95   | 93    |
|             | Economics, Econometrics and Finance               | 421    | 324    | 56   | 41    |
| ----------- | ----------------------------------------------    | ------ | ------ | ---- | ----- |
| Nursing     | Health Sciences                                   | 823    | 796    | 12   | 15    |
|             | Nursing and Health Professions                    | 61     | 47     | 8    | 6     |
|             | Pharmacology, Toxicology, Pharmaceutical Science  | 1184   | 949    | 118  | 117   |
|             | Psychology                                        | 28     | 24     | 3    | 1     |
|             | Veterinary Science and Veterinary Medicine        | 186    | 156    | 19   | 11    |
| ----------- | ----------------------------------------------    | ------ | ------ | ---- | ----- |
| Physics     | Earth and Planetary Sciences                      | 1354   | 1038   | 159  | 157   |
|             | Mathematics                                       | 288    | 232    | 29   | 27    |
|             | Physics and Astronomy                             | 1469   | 1177   | 147  | 145   |
| ----------- | ----------------------------------------------    | ------ | ------ | ---- | ----- |
| Social Science | Social Sciences                                | 852    | 654    | 100  | 98    |
| ----------- | ----------------------------------------------    | ------ | ------ | ---- | ----- |

**CSPubSum Dataset:**
1. Conducted crawling and publishing activities to compile the **CSPubSum dataset, comprising 10,147 computer science publications sourced from ScienceDirect**.
2. The URLs for the dataset were extracted based on the work by Collins et al. \cite{collins2017supervised}.
3. Each document in the dataset is meticulously structured, featuring essential components such as **abstracts and author-provided research highlights**, ensuring comprehensive coverage and accessibility for researchers and enthusiasts.
4. We have also segmented the dataset into **training, validation and test** subsets in the ratio of **80:10:10**.

**Our paper is available on [IEEE Xplore](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10172215) and [arXiv](https://arxiv.org/abs/2302.07729).**

**If you find our dataset/method useful, please cite our paper:**
1. IEEE Access: Rehman, T., Sanyal, D. K., Chattopadhyay, S., Bhowmick, P. K., & Das, P. P. (2023). "Generation of Highlights From Research Papers Using Pointer-Generator Networks and SciBERT Embeddings." IEEE Access, 11, 91358-91374.
2. arXiv: Rehman, T. et al. (2023). "Generation of Highlights from Research Papers Using Pointer-Generator Networks and SciBERT Embeddings." arXiv preprint arXiv:2302.07729."

**All rights reserved to the author.**
