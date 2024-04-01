
# Auto Speech Recognition with Whisper

## Description
This project leverages OpenAI's Whisper model for automatic speech recognition (ASR). It aims to convert speech to text accurately, showcasing the power of state-of-the-art machine learning models in processing and understanding audio data. This repository contains a Jupyter notebook that guides you through the process of data preparation, model invocation, and transcription of audio files into text.

## Installation

Ensure you have Python installed on your system. It's highly recommended to use a virtual environment for Python projects to manage dependencies efficiently.

Install the necessary packages using the following command:

\```bash
pip install transformers datasets soundfile librosa gradio
\```

These dependencies include libraries for machine learning models, data handling, audio file processing, and creating web interfaces for easy demonstration.

## Usage

To get started with this speech recognition project, follow these steps:

1. **Clone the repository** to your local machine.
2. **Navigate to the repository** directory and open the `Auto Speech Recognition (Whisper Speech to Text).ipynb` in Jupyter Lab or Jupyter Notebook.
3. **Follow the instructions** in the notebook, executing cells in order. The notebook will guide you through setting up your data, using the Whisper model for speech recognition, and optionally deploying a simple interface to test the model interactively.

## Features

- Data preparation and loading using the `datasets` library.
- Utilization of the Whisper model for speech-to-text conversion.
- Demonstration of results using `gradio` for interactive testing.

## Contributing

We welcome contributions and suggestions! If you have improvements or bug fixes, please feel free to fork the repository, make your changes, and submit a pull request. For significant changes or enhancements, please open an issue first to discuss what you'd like to change.

## License

This project is open-sourced under the MIT License. See the LICENSE file for more details.
