---
base_model: /root/autodl-fs/llama3-8b/Meta-Llama-3-8B
library_name: peft
license: other
tags:
- llama-factory
- lora
- generated_from_trainer
model-index:
- name: train_act_content1
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# train_act_content1

This model is a fine-tuned version of [/root/autodl-fs/llama3-8b/Meta-Llama-3-8B](https://huggingface.co//root/autodl-fs/llama3-8b/Meta-Llama-3-8B) on the act_train_modified dataset.

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 0.0002
- train_batch_size: 2
- eval_batch_size: 8
- seed: 42
- gradient_accumulation_steps: 8
- total_train_batch_size: 16
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: cosine
- num_epochs: 10.0
- mixed_precision_training: Native AMP

### Training results



### Framework versions

- PEFT 0.11.1
- Transformers 4.42.3
- Pytorch 2.3.1+cu121
- Datasets 2.20.0
- Tokenizers 0.19.1