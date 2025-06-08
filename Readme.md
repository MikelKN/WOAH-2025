# Think Like a Person Before Responding: A Multi-Faceted Evaluation of Persona-Guided LLMs for Countering Hate Speech

This repository contains the code and data for our paper "Think Like a Person Before Responding: A Multi-Faceted Evaluation of Persona-Guided LLMs for Countering Hate Speech", accepted at ACL-WOAH 2025.


Read the full paper here >> https://arxiv.org/abs/2506.04043

## Overview

Our work presents a novel approach to assessing LLM counter-narrative generation across four key dimensions:

- Persona Framing (Vanilla, NGO Persona, Compassionate NGO Persona)
  
- Readability and Verbosity

- Affective Tone (Emotion and Sentiment Analysis)

- LLM Response Quality

    - Refusal Rates

    - Hatefulness Scores

### Model Used

We evaluate three state-of-the-art models: 

- OpenAI's GPT-4o-mini,

- Meta's Llama-70 B-Instruct, and 

- Cohere's Command-R-7 B.

### Datasets

Our experiments utilize two well-established hate speech datasets:

- CONAN -Counter Narratives through Nichesourcing (Fanton et al., 2021) [https://github.com/marcoguerini/conan] 
  
- HatEval - Multilingual Detection of Hate Speech Against Immigrants and Women (Basile et al., 2019)[https://github.com/cicl2018/HateEvalTeam]


## Repository Structure

Conan_WOAH_2025/: Core implementation and experiments for the CONAN dataset.

LLM_prompt_strategies/: Prompt templates used to query both open- and closed-source LLMs.

conan_prompt_and_analysis_outcomes/: Processed results and analyses of LLM outputs on the CONAN dataset, including all generated prompt responses, verbosity stats, affective metrics(emotion and sentiment analysis with RoBERTa and DistilBERT, respectively).

hateeval_prompt_and_analysis_outcomes/: Equivalent analysis results for the HatEval dataset.


If you use this code or data, please cite our paper

[APA] 

**Ngueajio, M. K., Plaza-del-Arco, F. M., Chung, Y. L., Rawat, D. B., & Curry, A. C. (2025). Think Like a Person Before Responding: A Multi-Faceted Evaluation of Persona-Guided LLMs for Countering Hate. arXiv preprint arXiv:2506.04043.**

[BibTex] 

@article{ngueajio2025think,
  
title={Think Like a Person Before Responding: A Multi-Faceted Evaluation of Persona-Guided LLMs for Countering Hate},
  
author={Ngueajio, Mikel K and Plaza-del-Arco, Flor Miriam and Chung, Yi-Ling and Rawat, Danda B and Curry, Amanda Cercas},
  
journal={arXiv preprint arXiv:2506.04043},
  
year={2025}
}



