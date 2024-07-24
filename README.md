# Image Generation with Pre-trained Models

## Stable Diffusion Image Generation

This script uses the Stable Diffusion model to generate images based on a text prompt. It utilizes the `diffusers` library and requires GPU support for efficient execution.

## Requirements

- Python 3.x
- PyTorch
- diffusers
- PIL (Python Imaging Library)
- IPython

## Installation

1. **Install PyTorch**: Follow the [official PyTorch installation guide](https://pytorch.org/get-started/locally/) to install PyTorch with GPU support.

2. **Install required packages**:
    ```bash
    pip install diffusers pillow ipython
    ```

## Usage

1. **Run the Script**: Execute the script in a Python environment with GPU support.

2. **Enter Text Prompt**: When prompted, enter a text description of the image you want to generate.

3. **View and Save Image**: The generated image will be displayed and saved as `generated_image.png` in the current directory.

## Notes

- Ensure that you have CUDA enabled and a compatible GPU to use this script effectively.
- If CUDA is not available, the script will notify you and require a GPU runtime to be enabled.

## Troubleshooting

- **CUDA Not Available**: Make sure your system has a compatible GPU and that CUDA is properly installed.

## License

This script is provided for educational purposes. The Stable Diffusion model is licensed under the [CompVis License](https://huggingface.co/CompVis/stable-diffusion-v-1-4-original/blob/main/LICENSE).

## Author

Rohit Kumar
