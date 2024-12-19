# Sayiqa-Speech-App

  [title](mailto\:title): Voice Clone

  [emoji](mailto\:emoji): 🌍

  [color](mailto\:color): green

  [color](mailto\:colorTo): blue

  [SDK](mailto\:SDK): gradio

  [sdk_version](mailto\:sdk_version): 5.9.1

  [app_file](mailto\:app_file): app.py

  [pinned](mailto\:pinned): false

  [license](mailto\:license): mit

# Voice-to-Image and Speech-to-Text Application

This project is a Gradio-based web application that provides the following features:

1. **Speech-to-Text Transcription**: Transcribe audio files into text using OpenAI's Whisper model.
2. **Voice-to-Image Generation**: Generate high-definition images based on transcribed text from audio files using Stable Diffusion.

## Features

### Speech-to-Text/voice cloning Transcription

- Supports audio files longer than 20 minutes by chunking the audio into smaller parts for processing.
- Utilizes OpenAI's Whisper model for accurate transcription.

### Voice-to-Image Generation

- Converts transcribed text into high-quality (1024x1024 resolution) images using Stable Diffusion.
- Designed for generating creative visuals from voice inputs.

## Installation

To run this project locally, ensure you have Python 3.8 or higher installed, then follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/devartificizen/Sayiqa-Speech-App.git
   cd Sayiqa-Speech-App
   ```

2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Set your Hugging Face API token as an environment variable:

   ```bash
   export HF_TOKEN=your_huggingface_token
   ```

   Replace `your_huggingface_token` with your actual Hugging Face API token.

## Usage

1. Launch the application:

   ```bash
   python app.py
   ```

2. Open the Gradio interface in your browser. The application provides two tabs:

   - **Speech-to-Text**: Upload an audio file to transcribe it into text.
   - **Voice-to-Image**: Upload an audio file to generate an image based on its transcribed text.

3. Share your application by enabling public access using the `share` parameter.

## Dependencies

The project relies on the following Python libraries:

- `torch`
- `transformers`
- `diffusers`
- `librosa`
- `accelerate`
- `gradio`
- `huggingface_hub`

These dependencies are installed automatically when you run the provided installation script.

## Models Used

1. **Whisper**:

   - Model: `openai/whisper-tiny`
   - Task: Automatic speech recognition (ASR).

2. **Stable Diffusion**:

   - Model: `runwayml/stable-diffusion-v1-5`
   - Task: Text-to-image generation.

## Key Features and Implementation Details

1. **Audio Processing**:

   - Audio files are preprocessed into 16kHz for compatibility with the Whisper model.
   - Files longer than 20 minutes are chunked for seamless processing.

2. **Parallel Processing**:

   - Transcription and image generation are executed in parallel threads for improved performance.

3. **High-Definition Image Output**:

   - Images are generated at a resolution of 1024x1024 for clarity and detail.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- OpenAI for the Whisper model.
- Hugging Face for providing the transformers and diffusers libraries.
- Gradio for the user-friendly interface framework.

## Contact

For any questions or feedback, please contact # Voice-to-Image and Speech-to-Text Application

This project is a Gradio-based web application that provides the following features:

1. **Speech-to-Text Transcription**: Transcribe audio files into text using OpenAI's Whisper model.
2. **Voice-to-Image Generation**: Generate high-definition images based on transcribed text from audio files using Stable Diffusion.

## Features

### Speech-to-Text Transcription

- Supports audio files longer than 20 minutes by chunking the audio into smaller parts for processing.
- Utilizes OpenAI's Whisper model for accurate transcription.

### Voice-to-Image Generation

- Converts transcribed text into high-quality (1024x1024 resolution) images using Stable Diffusion.
- Designed for generating creative visuals from voice inputs.

## Installation

To run this project locally, ensure you have Python 3.8 or higher installed, then follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/devartificizen/Sayiqa-Speech-App.git
   cd Sayiqa-Speech-App
   ```

2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Set your Hugging Face API token as an environment variable:

   ```bash
   export HF_TOKEN=your_huggingface_token
   ```

   Replace `your_huggingface_token` with your actual Hugging Face API token.

## Usage

1. Launch the application:

   ```bash
   python app.py
   ```

2. Open the Gradio interface in your browser. The application provides two tabs:

   - **Speech-to-Text**: Upload an audio file to transcribe it into text.
   - **Voice-to-Image**: Upload an audio file to generate an image based on its transcribed text.

3. Share your application by enabling public access using the `share` parameter.

## Dependencies

The project relies on the following Python libraries:

- `torch`
- `transformers`
- `diffusers`
- `librosa`
- `accelerate`
- `gradio`
- `huggingface_hub`

These dependencies are installed automatically when you run the provided installation script.

## Models Used

1. **Whisper**:

   - Model: `openai/whisper-tiny`
   - Task: Automatic speech recognition (ASR).

2. **Stable Diffusion**:

   - Model: `runwayml/stable-diffusion-v1-5`
   - Task: Text-to-image generation.

## Key Features and Implementation Details

1. **Audio Processing**:

   - Audio files are preprocessed into 16kHz for compatibility with the Whisper model.
   - Files longer than 20 minutes are chunked for seamless processing.

2. **Parallel Processing**:

   - Transcription and image generation are executed in parallel threads for improved performance.

3. **High-Definition Image Output**:

   - Images are generated at a resolution of 1024x1024 for clarity and detail.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- OpenAI for the Whisper model.
- Hugging Face for providing the transformers and diffusers libraries.
- Gradio for the user-friendly interface framework.





