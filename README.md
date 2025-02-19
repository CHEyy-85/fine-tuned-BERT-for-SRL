# Semantic Role Labeling with BERT

## Overview
This project focuses on implementing a **Semantic Role Labeling (SRL)** system using **BERT**. The system follows the PropBank-style SRL framework, treating the task as a sequence-labeling problem. Each token in a sentence is assigned a **B-I-O** tag, representing its semantic role in relation to a predicate.

## Features
- Fine-tuning **BERT** for SRL using **Huggingface Transformers**.
- **PyTorch-based implementation** for training and evaluation.
- Utilizes **OntoNotes 5.0** dataset for training.
