# Computer-Vision-Assignment-2

 Hand Gesture Recognition with SOTA Explainability
 About the Project
This repository contains the implementation for **Assignment 2** of the Computer Vision course. The project upgrades a baseline CNN for hand gesture recognition (classes: `peace`, `stop`, `thumbs_up`) by integrating State-of-the-Art (SOTA) computer vision components for explainability and robustness.
Key Features
* **Improved CNN Architecture:** Upgraded baseline model with Batch Normalization and Dropout for better generalization.
* **SOTA Explainability (Grad-CAM):** Generates heatmaps to visualize the exact spatial features (e.g., fingertips) the network relies on to make predictions.
* **Robustness Stress-Testing:** Simulates low exposure and noise to demonstrate vulnerabilities in standard CNNs and justify the need for image enhancement methods like **ArtAug**.
* **Interactive Web UI:** A real-time web application built with Gradio that supports both image upload and live webcam inference.
  
 Repository Contents
* `assik_2_CV.ipynb`: The main Jupyter Notebook containing the full pipeline (dataset downloading, model training, evaluation, and Gradio app deployment).
* `improved_cnn.pth`: Pre-trained weights for the Improved CNN model.

 How to Run
1. Open `assik_2_CV.ipynb` in Google Colab.
2. Choose **Runtime -> Run all** to execute the pipeline.
3. Scroll to the last cell and click the generated `gradio.live` link to interact with the web application.
