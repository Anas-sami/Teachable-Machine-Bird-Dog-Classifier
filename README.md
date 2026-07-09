# Teachable-Machine-Bird-Dog-Classifier
An image classification project to identify birds and dogs using a custom trained model and Python script for the Smart Methods training task.


# Image Classification Project (Bird & Dog Classifier) - Teachable Machine

This is a practical project to deploy an AI model that recognizes images of birds and dogs. It predicts the correct class and displays the confidence score using Python.

## Tools and Libraries Used:
- **Teachable Machine (Google):** Used for collecting data and training the model.
- **Jupyter Notebook:** Used to write and execute the Python workflow.
- **Python Libraries:** `numpy`, `Pillow` (PIL), and `tf_keras` (to ensure version compatibility).

## Workflow Steps:
1. **Model Training:** Created two classes (`bird` and `dog`), collected sample images, trained the model on Teachable Machine, and exported the weights in Keras format.
2. **Environment Setup:** Downloaded the model files into the workspace and imported `tf_keras` explicitly to handle compatibility issues with newer Keras versions (such as the `DepthwiseConv2D` error).
3. **Testing:** Ran the full script in a Jupyter Notebook cell to load a local test image. The model successfully identified the target with 100% confidence.

## Repository Files:
- `tm_project.ipynb`: The main Jupyter Notebook script containing the execution code.
- `keras_model.h5`: The trained model file containing the weights.
- `labels.txt`: The text file containing the class indices and labels.
- `output_screenshot.png`: A screenshot showing the successful script output in Jupyter Notebook.
