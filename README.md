Paper Title: "Generation of Highlights from Research Papers Using Pointer-Generator Networks and SciBERT Embeddings"
Author Written Research Highlights: 
1. A new multi-disciplinary dataset called MixSub is also presented. It contains URIs of papers from different domains. Each paper contains research highlights in addition to the abstract. The performance of the proposed method on MixSub is also described.
2. Conducted crawling and publishing activities to compile the CSPubSum dataset, comprising 10,147 computer science publications sourced from ScienceDirect.
3. An approach for extracting research highlights from scientific papers is proposed.
4. The proposed approach combines SciBERT pre-trained word embeddings with a pointer-generator network that also uses a coverage mechanism.
5. The proposed approach outperforms existing methods on CSPubSum dataset in terms of ROUGH, METEOR , and BERTScore metrics.


MixSub Dataset:
We propose a new dataset called MixSub that contains research articles from multiple domains.
To prepare MixSub, we crawled the ScienceDirect website and curated articles published in various journals in year 2020. 
We removed the articles that did not contain research highlights. 
Finally, we got 19785 articles with author-written research highlights as shown in Table \ref{Table:MixSub Dataset}. 
Each example in this dataset is organized as \textit{(abstract,  author-written research highlights)}. We have also segmented the dataset into training, validation and test subsets.


CSPubSum Dataset:
Conducted crawling and publishing activities to compile the CSPubSum dataset, comprising 10,147 computer science publications sourced from ScienceDirect. The URLs for the dataset were extracted based on the work by Collins et al. \cite{collins2017supervised}
