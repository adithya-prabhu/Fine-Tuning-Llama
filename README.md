# Fine-Tuning-Llama

Llama model is mainly fine tuned by using Ludwig framework. It is a low code framework through which we can finetune LLm models through just a YAML config files.

Here the Llama 7b model is finetuned specifically for "alpaca-code-20k" datatset on a T4 GPU. This dataset is a code generation dataset. 

To run on a single GPU various strategies were used to navigate memory bottlenecks.

The Strategies are :
  1) Quantisaton
  2) LoRA
  3) QLoRA

By emplying these startegies, we can overcome memory bottlenecks of training 7b model. 
