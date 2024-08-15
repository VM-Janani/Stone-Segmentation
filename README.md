# Stone Segmentation Using U-Net

This project demonstrates stone segmentation using a U-Net model. The goal is to segment stones from images, including handling cases where stones are closely packed. The project is implemented in Google Colab.

## Project Overview

- **Dataset**: 20 diverse images of stones.
- **Approach**: U-Net model for image segmentation.
- **Techniques Used**:
  - Normalization and preprocessing
  - Data augmentation (horizontal/vertical flips, random brightness, Gaussian blurring, rotations)
  - Model training and fine-tuning
  - Evaluation using Intersection over Union (IoU) metrics

## Getting Started
To run this project, open the provided Google Colab notebook:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/stone-segmentation.git
   ```
   Navigate to the project directory:
   ```bash
   cd stone-segmentation
   ```

2. **Open Google Colab Notebook**:
   Upload the `stone_segmentation.ipynb` notebook to Google Colab.

3. **Setup and Dependencies**:
   In the Colab notebook, run the following cells to install necessary libraries and configure the environment:
   ```python
   !pip install tensorflow opencv-python-headless matplotlib
   ```

4. **Upload Dataset**:
   Upload your dataset images to Google Colab. Ensure the dataset is correctly referenced in the notebook.

5. **Run the Notebook**:
   Execute each cell in the notebook sequentially. The notebook contains code for:
   - Loading and preprocessing data
   - Building and training the U-Net model
   - Evaluating the model
   - Performing predictions and visualizing results

## Project Structure
- `stone_segmentation.ipynb`: The main notebook containing the entire workflow.

## Results

- **Input**: Stone images with various sizes and shapes.
- **Output**: Segmented images with stones identified and marked.

## Acknowledgements

- Inspired by Digital Sreeni’s YouTube channel for the U-Net architecture.
