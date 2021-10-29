# Fine-tuning Pretrained Language Models for Biomedical Tasks
This thesis is part of my Master of Data Science Degree at Monash University<br>
Author : Jirarote Jirasirikul (https://www.linkedin.com/in/jirarotej/)<br>
Supervisors : Ehsan Sharegi, Reza Haffari<br>

Link to:
- <a href="https://drive.google.com/file/d/1SO6UG4-yudsEOm7-sRdDchyRMa8yit3y/view?usp=sharing">Full paper</a>
- <a href="https://drive.google.com/file/d/1tfIVghY_alwU3Kp9kNNtWzou8pPfKVzq/view?usp=sharing">Poster</a>
- <a href="https://github.com/blizrys/BioMed-BERT-Eval/blob/main/LiteratureReviewAndProjectProposal.pdf">Literature Review - NLP Language Model Basic </a>

## Abstract
Contextualized representation using pre-trained language models was able to encode high-quality semantics that offers good performance on downstream NLP tasks. The well-known BERT architecture achieved state-of-the-art results on various tasks and benchmarks. In the Biomedical domain, two prominent domain-specialised BERT variants  are BioBERT and PubMedBERT that have achieved state-of-the-art results on Biomedical Language Understanding and Reasoning Benchmark leaderboard (BLURB). While successful,  there are various ways to tailor these models for downstream tasks specifically. Our research explores further into the hallmark of cancer (HoC) and PubMedQA tasks to verify the quality of representation from these models. We fine-tune these language models via various strategies such as input preprocessing, ensembling, and adapter layers. The empirical results substantiate the necessity of using domain-specific language models when dealing with special domains, and show that fine-tuning the underlying language models can generate more vigorous outcomes with a trade-off. The ensembling technique builds a more robust model for dealing with precision in exchange for recall. The adapter adds downstream tuning parameters in between layers of the language model. This allows the parameter’s weight to be more effective, however, GPU is became mandatory for fine-tuning downstream tasks together with the language model. Moreover, our observations point out that, in contrast with general domain, in special domains including more context could confuse models during learning and prediction. 

## Acknowledgement
We would like to acknowledge <a href="huggingface.co">huggingface.co</a> and <a href="adapterhub.ml">adapterhub.ml</a> for contribution toward the NLP community and the source code of this paper experiment setup.

## Model available
- N/A


