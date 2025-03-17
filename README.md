# AstroAI: An AI-Powered Astrophysics Chatbot with Image Generation

## Overview
AstroAI is an AI-powered chatbot designed to answer astrophysics-related questions using Google Gemini AI and generate space-themed images with Stable Diffusion.

## Features
- **Astrophysics Chatbot**: Provides expert answers to astrophysics and cosmology questions.
- **Image Generation**: Creates space-related images (galaxies, black holes, nebulae, etc.) using Stable Diffusion.
- **GPU Support**: Utilizes GPU acceleration when available for faster processing.

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Pip
- PyTorch with CUDA support (optional, for GPU acceleration)

### Install Dependencies
Run the following command:
```sh
pip install diffusers torch google-generativeai pillow
```

## Usage
1. Replace `YOUR_API_KEY` in the script with your Google Gemini API key.
2. Run the script:
```sh
python astroai.py
```
3. Ask questions about space and receive expert responses.
4. If your question includes space-related terms (e.g., "black hole", "nebula"), the script generates an image.

## Example
```
Ask your question about space (or type 'exit' to quit): What is a black hole?
🤖 AI Response:
A black hole is a region of spacetime where gravity is so strong that nothing, not even light, can escape...

🖼 Generating image...
Image saved as 'generated_image.jpg'
```

## Contributing
Feel free to submit pull requests or report issues on GitHub.

## License
This project is licensed under the MIT License.

## Author
[Your Name]

