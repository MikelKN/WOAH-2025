# Think Like a Person Before Responding: A Multi-Faceted Evaluation of Persona-Guided LLMs for Countering Hate Speech

This repository contains the code and data for our paper "Think Like a Person Before Responding: A Multi-Faceted Evaluation of Persona-Guided LLMs for Countering Hate Speech", accepted at ACL-WOAH 2025.

## Overview

Our work presents a novel approach to assessing LLM counter-narrative generation across four key dimensions:

- Persona Framing (Vanilla, NGO Persona, Compassionatye NGO persona)
  
- Readability and Verbosity

- Affective Tone (Emotion and Sentiment Analysis)

- LLM Response Quality

    - Refusal Rates

    - Hatefulness Scores

### Model Used

We evaluate three state-of-the-art models: 

- OpenAI's GPT-4o-mini,

- Meta's Llama-70B-Instruct, and 

- Cohere's Command-R-7B.

### Datasets

Our experiments utilize two well-established hate speech datasets:

- CONAN -Counter Narratives through Nichesourcing (Fanton et al., 2021) [https://github.com/marcoguerini/conan] 
  
- HatEval - Multilingual Detection of Hate Speech Against Immigrants and Women (Basile et al., 2019)[https://github.com/cicl2018/HateEvalTeam]


## Repository Structure

Conan_WOAH_2025/: Core implementation and experiments for the CONAN dataset.

LLM_prompt_strategies/: Prompt templates used to query both open- and closed-source LLMs.

conan_prompt_and_analysis_outcomes/: Processed results and analyses of LLM outputs on the CONAN dataset, including all generated prompt responses, verbosity stats, affective metrics(emotion and sentiment analysis with RoBERTa abd DistilBERT respectively) .

hateeval_prompt_and_analysis_outcomes/: Equivalent analysis results for the HatEval dataset.


Read the full paper here

If you use this code or data, please cite our paper



