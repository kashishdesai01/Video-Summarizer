# Video-Summarizer

This project uses OpenAI's Whisper and a BART model to generate concise and humanised summaries from any YouTube video with spoken audio. It can fetch official transcripts or perform its own transcription if none are available.

## Features
- **Accurate Transcription**: Utilizes OpenAI's Whisper for robust speech-to-text.
- **Local Summarization**: Employs a local Hugging Face BART model, requiring no API keys for summarization.
- **Transcript Fallback**: If a video lacks an official transcript, the tool automatically downloads the audio and transcribes it.

## Setup and Installation

To run this project, clone the repository and install the required dependencies.

```bash
git clone [https://github.com/kashishdesai01/Video-Summarizer.git]
cd Video-Summarizer
pip install -r requirements.txt
```

## How to Use
1.  Open the `.ipynb` file in a Jupyter Notebook or Google Colab.
2.  Run the cells in order from top to bottom.
3.  In the final cell, an interactive widget will appear.
4.  Paste a YouTube URL into the text box and click "Summarize Video".

## Technology Stack
- **Python**
- **PyTorch**
- **OpenAI Whisper**
- **Hugging Face Transformers**
- **Jupyter / Google Colab**
