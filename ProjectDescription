LoRA on an 8GB GPU — Thesis Study

MS thesis project on parameter-efficient fine-tuning (LoRA) under strict 8 GB GPU constraints.

Study Focus
_________________________ _________________________ _________________________
The core study evaluates how LoRA behaves when training and serving models on an 8 GB GPU. It examines three experimental tracks described in the plans:
  1.	Text model adaptation — small LLMs fine-tuned with LoRA/QLoRA, measuring accuracy, throughput, and memory behavior.
  2.	Vision model adaptation — ViT-tiny–scale models trained with LoRA/DoRA to examine rank/placement tradeoffs.
  3.	Multi-adapter serving — performance of merged vs unmerged adapters when many task-specific LoRAs share a single base model.
  
  These tracks collectively test what is realistically possible on a constrained consumer GPU and provide a baseline for comparing local vs cloud execution.
_________________________ _________________________ _________________________
4th Track: Workflow, Cost, and Training Process
  A fourth component extends the study to evaluate the training workflow itself. 
  This includes:
  •	Comparing local 8 GB GPU runs to cloud runs funded by credits
  •	Tracking time, energy use, cost per 10k tokens, and cost per 1% accuracy gain
  •	Treating the entire LoRA lifecycle—local experiment → cloud execution → deployment (e.g., HF/Gradio)—as an object of study
_________________________ _________________________ _________________________
This track connects directly to the real-world constraints most practitioners face.
  Funding and Compute Credits
  The project currently includes $150 of Tinker compute credits, which serve as seed funding for remote experiments. 
  These credits will either be consumed in a focused set of comparative LoRA trials or serve as the starting point for extended workflow and cost analyses, depending on experimental outcomes.
