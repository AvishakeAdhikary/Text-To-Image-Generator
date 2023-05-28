# Text-To-Image-Generator

![image](https://github.com/AvishakeAdhikary/Text-To-Image-Generator/assets/32614982/1fa835b0-f8e0-4900-a696-57fea1196573)

> This project uses the Stable Diffusion Pipeline to generate images from text prompts. The Stable Diffusion Pipeline is a machine learning model that uses a diffusion process to generate images from text prompts.
> This is a simple GUI application for generating images based on user prompts using the StableDiffusionPipeline model from the diffusers module. The application allows users to enter a prompt, click a button to generate an image based on the prompt, and view the generated image in the GUI window.

## Getting Started

To get started, you will need to have a GPU and install the following dependencies:

- PyTorch
- diffusers
- matplotlib

### Prerequisites

Before running this application, you will need to have the following installed:

- Python 3.6 or later
- tkinter module
- customtkinter module
- diffusers module
- torch module
- Pillow module

You can install these dependencies using pip. For example:

```
pip install tkinter
```
```
pip install customtkinter
```
```
pip install diffusers
```
```
pip install torch
```
```
pip install Pillow
```

To run this file you need a HuggingFace API Token.

1. Go to the Hugging Face website: https://huggingface.co/
2. Click on the "Sign In" button in the top-right corner of the page.
3. Sign in with your Hugging Face account or create a new account if you don't have one.
4. Once you are signed in, click on your profile picture in the top-right corner of the page and select "Account settings" from the dropdown menu.
5. On the account settings page, click on the "API token" tab.
6. Click on the "Generate new token" button to create a new authorization token.
7. Enter a name for your token in the "Token name" field (e.g. "Image Generator App").
8. Choose the permissions you want to grant to your token (e.g. "Read-only" or "Full access").
9. Click on the "Generate" button to create your token.
10. Copy the generated token and use it in your Python code where it says ```self.authorization_token = ""```.

Once you have installed the dependencies, you can run the code by running the following command:

```
python imagegenerator.py
```

## Usage

When you run the code, you will be prompted to enter a text prompt. Once you have entered a text prompt, the Stable Diffusion Pipeline will generate an image based on the text prompt. The generated image will be displayed using matplotlib.

![image](https://github.com/AvishakeAdhikary/Text-To-Image-Generator/assets/32614982/633c43f7-65b6-42f7-adee-7f1d206534d6)

## Contributing

We welcome contributions to this project! If you would like to contribute, please follow these steps:

1. Fork this repository to your own GitHub account.
2. Clone the forked repository to your local machine.
3. Make changes to the code as needed.
4. Test your changes to make sure they work as expected.
5. Commit your changes and push them to your forked repository.
6. Create a pull request on the original repository to submit your changes.

We will review your pull request and provide feedback as needed. Thank you for contributing to this project!

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
