# AutoLoRA: AutoGuidance Meets Low-Rank Adaptation for Diffusion Models

Artur Kasymov, Marcin Sendera, Michał Stypułkowski, Maciej Zieba, Przemysław Spurek

## Abstract
Low-rank adaptation (LoRA) is a fine-tuning technique that can be applied to conditional generative diffusion models. 
LoRA utilizes a small number of context examples to adapt the model to a specific domain, character, style, or concept. 
However, due to the limited data utilized during training, the fine-tuned model performance is often characterized by 
strong context bias and a low degree of variability in the generated images. To solve this issue, we introduce AutoLoRA, 
a novel guidance technique for diffusion models fine-tuned with the LoRA approach. Inspired by other guidance techniques, 
AutoLoRA searches for a trade-off between consistency in the domain represented by LoRA weights and sample diversity from 
the base conditional diffusion model. Moreover, we show that incorporating classifier-free guidance for both LoRA fine-tuned 
and base models leads to generating samples with higher diversity and better quality. The experimental results for several 
fine-tuned LoRA domains show superiority over existing guidance techniques on selected metrics.

## Update

* [October 2024] Repository creation. The source code will be available soon!
