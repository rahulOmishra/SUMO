# SUMO
Dataset for Rahul Mishra, Dhruv Gupta, Markus Leippold ["Generating Fact Checking Summaries forWeb Claims"](https://www.aclweb.org/anthology/2020.wnut-1.12.pdf). WNUT@EMNLP2020.  
## References
Please cite the following paper:
~~~~
@inproceedings{mishra-etal-2020-generating,
    title = "Generating Fact Checking Summaries for Web Claims",
    author = "Mishra, Rahul  and
      Gupta, Dhruv  and
      Leippold, Markus",
    booktitle = "Proceedings of the Sixth Workshop on Noisy User-generated Text (W-NUT 2020)",
    month = nov,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.wnut-1.12",
    doi = "10.18653/v1/2020.wnut-1.12",
    pages = "81--90",
    abstract = "We present SUMO, a neural attention-based approach that learns to establish correctness of textual claims based on evidence in the form of text documents (e.g., news articles or web documents). SUMO further generates an extractive summary by presenting a diversified set of sentences from the documents that explain its decision on the correctness of the textual claim. Prior approaches to address the problem of fact checking and evidence extraction have relied on simple concatenation of claim and document word embeddings as an input to claim driven attention weight computation. This is done so as to extract salient words and sentences from the documents that help establish the correctness of the claim. However this design of claim-driven attention fails to capture the contextual information in documents properly. We improve on the prior art by using improved claim and title guided hierarchical attention to model effective contextual cues. We show the efficacy of our approach on political, healthcare, and environmental datasets.",
}
~~~~
