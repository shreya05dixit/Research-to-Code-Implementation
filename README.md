# 🎨 Neural Style Transfer with Keras

This repository implements **Neural Style Transfer** using Keras and VGG19, blending the **content** of one image with the **style** of another to create artistic images.

> Based on the paper: [A Neural Algorithm of Artistic Style](http://arxiv.org/abs/1508.06576)

---

## 🧠 What is Neural Style Transfer?

Neural Style Transfer (NST) generates an image that preserves the **content** of a base image while adopting the **style** of another image (typically an artwork). It works by optimizing a loss function that combines:

- 🎯 **Content Loss**: Ensures the output retains the structure and layout of the base image.
- 🖌️ **Style Loss**: Matches the textures, colors, and patterns from the style image using Gram matrices.
- 🌈 **Total Variation Loss**: Encourages local smoothness in the generated image for natural-looking results.

---

## 📁 File Structure

- `style_transfer.py`: The main script implementing the NST pipeline.
- `README.md`: Documentation for understanding and running the project.
- `img/`: Directory to store input images.
- `results/`: Output images will be saved here (create if not present).

---

## 📦 Requirements

Install dependencies via pip:

```bash
pip install tensorflow keras numpy scipy pillow
