# Dialogue-Summarization-using-FLAN-T5
Adapted a large language model for producing summaries that closely resemble human-generated content for a conversation
• Employed the FLAN-T5 base model through In-context Learning (ICL) techniques such as zero-shot, one-shot, and few-shot inferences
• Fine-tuned base model on DialogSum dataset using Instruction Fine-tuning (IFT), resulting in a 56% improvement in the ROUGE-L score
• Implemented PEFT by leveraging Low Rank Adaption (LoRA) technique with rank r = 8, leading to a 43% boost in the ROUGE-L score
