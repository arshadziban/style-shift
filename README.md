# StyleShift

A fine-tuned LLM adapter for converting informal text to formal English using QLoRA.

## Features
- Lightweight fine-tuning with QLoRA adapters
- Based on TinyLlama-1.1B-Chat
- 4-bit quantization for efficient inference

## Setup
```bash
pip install -r requirements.txt
```

## Usage
Run the inference notebook:
```bash
jupyter notebook infer.ipynb
```

## Training
Modify and run the training notebook:
```bash
jupyter notebook train.ipynb
```

## Model
- **Base Model**: TinyLlama/TinyLlama-1.1B-Chat-v1.0
- **Adapters**: LoRA adapters in `adapters/` folder
