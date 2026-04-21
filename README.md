# VLM Radiology Report Generation

This project focuses on chest X-ray report generation using a vision-language model.

We start with a baseline encoder-decoder model and improve it by adding a cross-attention mechanism to better align image features with generated text.

## Goal
To improve clinical grounding and reduce hallucinations in generated radiology reports.

## Current Work
- Baseline model setup
- Data preprocessing (IU X-ray dataset)
- Initial training pipeline

## Next Steps
- Add cross-attention layer
- Run experiments (baseline vs improved model)
- Evaluate using BLEU, ROUGE, METEOR, and BERTScore

