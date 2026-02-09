# ROS3

This repository contains code for training and using speech-to-text models based on Hugging Face Transformers.

## Files Overview

- **Model usage.ipynb**  
  Demonstrates how to load and use pre-trained models (e.g., Wav2Vec2 or Whisper) from the Hugging Face Hub for inference.

- **Train wav2vec models.ipynb**  
  Notebook for fine-tuning Wav2Vec2 models on custom datasets.

- **Train whisper small.ipynb**  
  Notebook for training or fine-tuning the small version of the Whisper model.

- **Train whisper large.ipynb**  
  Notebook for training or fine-tuning the large version of the Whisper model.

- **requirements.txt**  
  List of dependencies required to run the notebooks.

## Pre-trained Models

| Model Type      | Dataset / Notes                  | Hugging Face Link |
|-----------------|---------------------------------|-----------------|
| **Wav2Vec2**    | RO All 34                        | [Link](https://huggingface.co/alexandradiaconu/wav2vec2-ft-ro-all-34) |
| **Wav2Vec2**    | RO ProTV 17                      | [Link](https://huggingface.co/alexandradiaconu/wav2vec2-ft-ro-protv-17) |
| **Wav2Vec2**    | RO Observator 17                 | [Link](https://huggingface.co/alexandradiaconu/wav2vec2-ft-ro-observator-17) |
| **Whisper Small** | 34 All2                         | [Link](https://huggingface.co/alexandradiaconu/whisper-small-34-all2) |
| **Whisper Small** | ProTV 17                        | [Link](https://huggingface.co/alexandradiaconu/whisper-protv-17) |
| **Whisper Small** | Observator 17                   | [Link](https://huggingface.co/alexandradiaconu/whisper-observator-17) |
| **Whisper Small** | 34 Echo                         | [Link](https://huggingface.co/alexandradiaconu/whisper-small-echo-34) |
| **Whisper Small** | 34 Mix                          | [Link](https://huggingface.co/alexandradiaconu/whisper-small-34-mix) |
| **Whisper Small** | 17 ProTV Mix                     | [Link](https://huggingface.co/alexandradiaconu/whisper-small-17-protv-mix) |
| **Whisper Small** | 17 ProTV ElevenLabs              | [Link](https://huggingface.co/alexandradiaconu/whisper-small-17-protv-elevenlabs) |
| **Whisper Large** | 34 All New3                      | [Link](https://huggingface.co/alexandradiaconu/whisper-large-all-34-new3) |

## Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
