# AI Disaster Response Coordinator

A multimodal AI prototype designed to analyse emergency incident information from text, images and audio and produce a structured incident assessment to support emergency prioritisation.

## Project Overview

The AI Disaster Response Coordinator processes multimodal emergency information from text, image and audio inputs. Information extracted from these different modalities is combined and analysed to produce a structured incident assessment.

The prototype was developed and evaluated using Flood, Fire and Earthquake emergency scenarios.

## Main Features

- Text, image and audio input processing
- Audio transcription using Whisper
- Image caption generation using BLIP
- Multimodal information fusion
- LLM-based incident analysis
- Severity and priority assessment
- Output validation and safety checks
- Gradio web interface
- Evaluation across Flood, Fire and Earthquake scenarios
- Missing-modality testing

## Repository Contents

- `AI_Disaster_Response_Coordinator.ipynb` – complete project implementation and evaluation notebook
- `sample_data/` – sample image and audio files used for testing
- `sample_data/README.md` – description of the supplied sample data

## Running the Project

The project was developed and tested using Google Colab.

1. Open `AI_Disaster_Response_Coordinator.ipynb` in Google Colab.
2. Upload the required image and audio test files to the Colab session **before running the cells that reference them**. Files are provided in the `sample_data` folder of this repository.
3. Run the notebook cells in order from top to bottom.
4. Allow the required dependencies and AI models to install and initialise.
5. The notebook processes the uploaded text, image and audio inputs through the multimodal pipeline.
6. Run the Gradio interface section to launch the interactive prototype.
7. The Gradio interface can then be used to provide multimodal incident inputs and generate an incident assessment.

## Sample Data

Representative image and audio inputs for Flood, Fire and Earthquake scenarios are included in the `sample_data` folder.

These files are provided so that example scenarios from the project can be reproduced when running the notebook in Google Colab.

## Technologies

- Python
- Google Colab
- Gradio
- OpenAI Whisper
- BLIP
- Hugging Face Transformers
- PyTorch

## Important Note

This system is an academic prototype developed as part of a final-year university project. It is intended for research, evaluation and demonstration purposes and is not designed for operational use in real-world emergency response.
