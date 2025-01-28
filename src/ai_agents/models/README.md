# AI Models Directory

This directory contains pre-trained AI models and training data for AI battle agents in AI Fantasy Battle Arena.

## Contents
- **Pre-Trained Models:**  
  Store the pre-trained AI models here. These models can be directly used in the game or further fine-tuned.
  
- **Training Data:**  
  Includes datasets used for training the AI agents. Ensure that all datasets are well-documented and appropriately licensed.

## File Naming Conventions
1. **Model Files:** Use `.h5`, `.pt`, or `.onnx` extensions for models (e.g., `battle_agent_v1.h5`).
2. **Datasets:** Use descriptive names with the `.csv` or `.json` extensions (e.g., `battle_data_v1.csv`).

## How to Use
1. Upload trained AI models to this directory.
2. Reference the models in `src/ai_agents/agent.py` for gameplay use.
3. If new models are added, update their documentation here.

## Contribution Guide
- Ensure models are well-tested before uploading.
- Use appropriate file naming conventions.
- Document the performance of each model in this file.
