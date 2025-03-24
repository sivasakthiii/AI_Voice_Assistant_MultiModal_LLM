Multimodal RAG

Overview

This project integrates OpenAI Whisper, LLaVA (Large Language and Vision Assistant), and Gradio to build a multimodal retrieval-augmented generation (RAG) system. The system processes speech and image inputs to generate detailed textual descriptions and responses.

Features

Speech-to-Text: Uses OpenAI's Whisper model to transcribe audio input.

Image Analysis: Employs LLaVA for detailed image descriptions and contextual analysis.

Text-to-Speech: Converts the generated text into speech using gTTS (Google Text-to-Speech).

Interactive Interface: Built using Gradio, allowing easy interaction with audio and image inputs.

Installation

Before running the project, install the necessary dependencies:
pip install -q -U transformers==4.37.2
pip install -q bitsandbytes==0.41.3 accelerate==0.25.0
pip install -q git+https://github.com/openai/whisper.git
pip install -q gradio
git clone https://github.com/openai/whisper.git
pip install -q gTTS
