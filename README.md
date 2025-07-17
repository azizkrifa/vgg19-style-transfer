# 🎨 VGG19 Style Transfer

This project implements Neural Style Transfer using a pre-trained **VGG19** model in TensorFlow. It allows you to blend the **content** of one image with the **style** of another, producing artistic and expressive results.

----

## 🧱 Project Structure

This Project follows the standard pipeline for Neural Style Transfer:

1. 📦 **Import Dependencies**  
   Load all required libraries including TensorFlow, NumPy, and image processing tools.

2. 🖼️ **Load and Preprocess Images**  
   Load the content and style images, resize them, and convert them to tensors.

3. 🔍 **VGG19 Feature Extraction**   
   Use a pre-trained VGG19 model to extract content and style features from intermediate layers.

4. 🎭 **Style and Content Representation**   
   Compute the **Gram matrix** for style representation and directly use activations for content.

5. ⚖️ **Loss Functions**   
   Define the **style loss** and **content loss**, and combine them for the final optimization target.

6. 🚀 **Optimization Process**   
   Start from the content image and iteratively update it to minimize the total loss using gradient descent.

7. 🖼️ **Display Results**   
   Visualize the stylized image after each epoch.

---


