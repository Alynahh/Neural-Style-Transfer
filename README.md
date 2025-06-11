# Neural Style Transfer with TensorFlow 

This project uses **Neural Style Transfer** to blend a **content image** (like your dog) with the **style of another image** (like a painting or pattern). It's built with TensorFlow and a pre-trained **VGG19** model.

## Features
- Load & preprocess images
- Extract style/content features from a pre-trained CNN
- Calculate Gram matrices for style representation
- Minimize combined style & content loss
- Output a new stylized image

## Tech Stack
- TensorFlow 2.x
- NumPy
- Matplotlib
- Google Colab

## How It Works
1. Upload your content + style images
2. The model extracts content from the content image & style from the style image
3. Using backpropagation, it adjusts a target image to minimize both losses
4. Voila! AI-generated art 😎

## Example
Content Image: 🐶  
Style Image: 🎨  
Result: ✨Magic✨

## Try it yourself
Run it on **Google Colab** or locally with:
```bash
pip install tensorflow matplotlib
