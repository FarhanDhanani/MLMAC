# [![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger) **MLMAC**
# **FAST-MT TEAM SUBMISSION TO [MLMAC-CONTEST](https://mlmac.io/)**
The repository contains our submission to the MLMAC CONTEST. Overall our submission got fourth-ranked of the competition.

[![N|Solid](https://upload.wikimedia.org/wikipedia/en/e/e4/National_University_of_Computer_and_Emerging_Sciences_logo.png)](https://nodesource.com/products/nsolid)

# **OVERVIEW**
In 2019, the announcement of GPT-2, a language model that could generate text of "unprecedented quality," brought new concerns to the forefront of responsible AI. Enabled by increases in compute capacity, big tech companies can now train extremely large neural network models on web scale collections of text, creating models that produce text so fluent, humans cannot reliably detect when text is synthetic. When these base models are released publicly, they can be fine-tuned at a relatively low cost to produce text tailored to a specific domain, such as sports or politics. Large language models (LLMs) may enable the generation of misinformation at scale, especially when fine-tuned on malicious text. However, it is unclear how widely adversaries use LLMs to generate misinformation today, partly because no general technical method has been widely deployed to attribute a fine-tuned LLM to a base LLM.

The ML Model Attribution Challenge (MLMAC) challenges contestants to develop creative technical solutions for LLM attribution. Contestants will attribute synthetic text written by fine-tuned language models back to the base LLM, establishing new methods that may provide strong evidence of model provenance. Model attribution would allow regulatory bodies to trace intellectual property theft or influence campaigns back to the base model. This competition works toward AI assurance by developing forensic capabilities and establishing the difficulty of model attribution in natural language processing and could contribute to the maturation of AI forensics as a subfield of AI security.

This competition incentivizes open research in this area. Each winning contestant must publish their method, and after the competition concludes, we will release query logs for each fine-tuned model that can enable post-hoc analysis of blind attribution methods. We have planned subsequent activity in this area to institutionalize practical model attribution research.

# **CITE**

@misc{https://doi.org/10.48550/arxiv.2211.10877,
  doi = {10.48550/ARXIV.2211.10877},
  url = {https://arxiv.org/abs/2211.10877},
  author = {Dhanani, Farhan and Rafi, Muhammad},
  keywords = {Computation and Language (cs.CL), Artificial Intelligence (cs.AI), Machine Learning (cs.LG), FOS: Computer and information sciences, FOS: Computer and information sciences},
  title = {Artificial Interrogation for Attributing Language Models},
  publisher = {arXiv},
  year = {2022},
  copyright = {arXiv.org perpetual, non-exclusive license}
}
