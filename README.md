# Fine-Tuning LLMs 

This repository demonstrates fine-tuning large language models (LLMs) using **parameter-efficient techniques**, with a focus on **LoRA** and **CLoRA**.  

We start with a **small sample dataset** (~1000 samples) to test and verify the fine-tuning process. Once verified, the approach can be scaled to **larger datasets** for more robust training.  

## Techniques Used

- **LoRA (Low-Rank Adaptation):** Efficiently fine-tunes pre-trained LLMs by injecting trainable low-rank matrices into select layers.  
- **CLoRA (Compressed LoRA):** An optimized version of LoRA for memory-constrained setups, combining low-rank adaptation with compression.  

## Notes

- The notebooks demonstrate loading a pre-trained LLM, applying LoRA/CLoRA, training, and evaluating on a sample dataset.  
- Training is configured for limited GPU resources (e.g., free Colab GPUs).  
- PEFT framework is used to simplify applying LoRA and CLoRA.  

## Future Work

- Extend to larger datasets and more complex tasks.  
- Include additional fine-tuning techniques like Adapters or Prefix Tuning.  
