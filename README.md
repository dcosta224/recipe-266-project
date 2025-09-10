# recipe-266-project

Note for reviewer: Data folder "RecipeNLG" omitted. Primary coding files are 
- evaluate.ipynb
- inference.ipynb
- train.ipynb

## Abstract

LLM-generated recipe instructions have improved as larger models excel at reasoning tasks, yet even State-of-the-Art systems often fail to present steps in a logical sequence that reflects ingredient states. This limits their widespread adoption in culinary applications. This study compares a novel reference-based metric with an LLM-as-a-judge reference-free metric to assess the effects of Chain-ofThought prompting, retrieval-augmented fewshot learning, and fine-tuning on a 7B decoderonly model. Results show that CoT prompting consistently improves sequence preservation, with fine-tuning and few-shot prompting yielding gains primarily in reference-based evaluations.
