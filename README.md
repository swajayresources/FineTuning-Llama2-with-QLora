# FineTuning-Llama2-with-QLora


* We will leverage PEFT library from Hugging Face ecosystem, as well as QLoRA for more memory efficient finetuning

## Setup
* For our experiment we will need accelerate, peft, transformers, datasets and TRL to leverage the recent SFTTrainer. We will use bitsandbytes to quantize the base model into 4bit. We will also install einops as it is a requirement to load Falcon models
