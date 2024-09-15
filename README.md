<div align='center'>
  
# Finetune Llama 2 - MiniGuanaco
  
*Fine-Tune Your Own Llama 2 Model* 

![image](https://github.com/user-attachments/assets/66af9f68-e837-4d90-9937-3d98992243cc)

</div>


---

## Abstract

Llama 2 is a state-of-the-art large language model (LLM) developed by Meta AI, designed for a variety of natural language processing (NLP) tasks. Its architecture builds upon transformer-based models, leveraging massive text corpora during pretraining to develop rich language understanding capabilities. Fine-tuning Llama 2 can be customized to a specific task by using a smaller, task-specific dataset, often resulting in a specialized model that outperforms the general-purpose base model on that task. In this project, we fine-tune the Llama-2-7b-hf model using a subset of the Guanaco dataset, focusing on developing a highly efficient model called "MiniGuanaco."

:link: Notebook on kaggle [`finetune-llama2`](https://www.kaggle.com/zeyadusf/finetune-llama2)

## Project Overview

This repository demonstrates the steps and code required to fine-tune Llama 2 for specific tasks. Using the Hugging Face model **NousResearch/Llama-2-7b-hf** as the base, the model is fine-tuned with the dataset **mlabonne/guanaco-llama2-1k**. The fine-tuned model is saved under the name **llama2-miniguanaco**.

### Model Details

- **Base Model**: `NousResearch/Llama-2-7b-hf`
- **Fine-tuned Model**: [`llama2-miniguanaco`](https://huggingface.co/zeyadusf/llama2-miniguanaco)
- **Dataset**: `mlabonne/guanaco-llama2-1k`


## Fine-Tuning Process

Fine-tuning a large language model like Llama 2 involves adjusting the weights of the base model using a smaller and more task-specific dataset. The **guanaco-llama2-1k** dataset used here consists of high-quality instruction-following samples designed to help the model perform well in conversational and chat tasks.

In this project, we focus on:

1. **Supervised Fine-Tuning (SFT)**: This initial step adapts the base Llama 2 model to better handle specific instructions from the target dataset.
2. **Model Optimization**: Multiple epochs were used to improve the model's performance on the dataset.
3. **Metrics**: The main metric observed was the training loss, which was reduced to 1.3477 after 625 training steps. Other performance metrics such as runtime, FLOPs, and sample processing speed are also noted.

<!--Social Media-->
<hr>

# :email: Contact #

<p align="center">
 <a href="https://www.facebook.com/ziayd.yosif" target="_blank">
  <img src="https://img.shields.io/badge/-Zeyad Usf-1877F2?style=flat&logo=facebook&logoColor=white" alt="Facebook" />
</a>

<a href="https://www.instagram.com/zeyadusf/" target="_blank">
  <img src="https://img.shields.io/badge/-zeyadusf-white?style=flat&logo=instagram&logoColor=#E65468" alt="Instagram" />
</a>



<a href="https://www.linkedin.com/in/zeyadusf/" target="_blank">
  <img src="https://img.shields.io/badge/-Zeyad Usf-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>

<a href="https://github.com/zeyadusf" target="_blank">
  <img src="https://img.shields.io/badge/-@zeyadusf-181717?style=flat&logo=github&logoColo

