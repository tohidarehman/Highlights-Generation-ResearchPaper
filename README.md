# Highlight Generation from Research Papers
We present a new multi-disciplinary data set named MixSub that contains research papers (with author-written highlights) from different subject domains. 
To prepare MixSub, we crawled the ScienceDirect website and curated articles published in various journals in year 2020. We removed the articles that did not contain research highlights. 
Each example in this data set is organized as (abstract,  author-written research highlights). 
We have also segmented the data set into training, validation and test subsets.
Our method automatically generates research highlights from a scientific research paper. 
We propose a technique to combine a SciBERT  pre-trained layer of word embeddings with a pointer-generator network that also uses a coverage mechanism. 




If you find our dataset / method useful, please cite our paper:
@article{rehman2023generation,
  title={Generation of Highlights from Research Papers Using Pointer-Generator Networks and SciBERT Embeddings},
  author={Rehman, Tohida and Sanyal, Debarshi Kumar and Chattopadhyay, Samiran and Bhowmick, Plaban Kumar and Das, Partha Pratim},
  journal={arXiv preprint arXiv:2302.07729},
  year={2023}
}
