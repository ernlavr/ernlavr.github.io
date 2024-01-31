---
title: "Llama-2 for Abstractive Text Summarization and its Factuality"
excerpt: "MSc thesis conducted during Spring 2023 semester. <br/><img src=\"/images/portfolio/adv_nlp/llama2.jpg\" width=\"500\" >"
collection: portfolio
---
![adAttack](/images/portfolio/adv_nlp/llama2.jpg)
*Conducted as part of a group with Bence Zoltan Balazs*

[Download the Full Paper](/files/portfolio/fullPapers/advanced_nlp_abstractive_summary.pdf)

Relevant Links:
- [Github](https://github.com/ernlavr/llamarizer)
- [HuggingFace Model 🤗](https://huggingface.co/ernlavr/llama-2-7bn-xsum-lora-adapter)
- [Weights & Biases](https://wandb.ai/ernlavr/adv_nlp2023/sweeps)


# Abstract
Text summarization proves to be an effective
and efficient method for swiftly conveying
crucial information. Large Language Models
(LLM) hold immense potential in simplifying
this task for a diverse audience. However, existing research reveals a challenge — many LLMs
exhibit factual inconsistencies when generating
summary texts. In this project, we embark on
fine-tuning a Llama2-7bn text summarization adapter
model. Our focus is on evaluating the performance of a fine-tuned model and investigating
how integration of Natural Language Inference
(NLI) into the cost function can enhance factuality performance. We conduct training and
evaluation on the XSum news summary dataset
and employ multiple factuality consistency metrics on our final results. We find that in the
current iteration of our models, there is no substantial difference between the base model and
the NLI enhanced version. We propose to use
better NLI model in the cost function and to
train our model longer to mitigate this issue.
Furthermore, we notice that the fine-tuned tend
to predict parts from the source text, which is
likely to be the reason that our model performs
worse than the state-of-the-art models. Thus we
propose an extra penalty term on taking entire
sentences from the source document.
