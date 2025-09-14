# Lingatoanki - Contextual Word Definitions and Anki Flashcards Generator

## Overview

This project uses the LLaMA 2 7B Chat language model to generate detailed word definitions based on contextual sentences. It processes input data from a CSV file from Linga app, generates explanations, and creates Anki flashcards for efficient vocabulary learning.

## Features

- Load and run LLaMA 2 7B Chat with Transformers and PyTorch
- Generate word meanings based on the context in which they were used in the sentence
- Create Anki decks (.apkg) with questions and answers including source citations

## Requirements

- Python 3.10+
- Libraries: transformers, torch, pandas, genanki
- Local access to LLaMA 2 7B Chat HF model files
- Input CSV with columns: word, sentence, source_author, source_title

## Usage

1. Prepare the input CSV with the required columns (csv. file from the Linga app).
2. Load the model and tokenizer.
3. Run the pipeline to generate definitions.
4. Export results to Anki flashcards:
