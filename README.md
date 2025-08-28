# Cartoonify Image using OpenCV

This project is an **image processing application** that transforms standard photos into **cartoon-style images** using computer vision techniques.  

It provides a complete workflow for selecting an image, applying cartoonification filters, and saving the output image.

---

## Features
- Converts normal photos into cartoon-style images.
- Applies key image processing techniques:
  - **Grayscale conversion**
  - **Median blur**
  - **Adaptive thresholding** for edge detection
  - **Bilateral filtering** for noise reduction while preserving edges
- File upload and download support in **Google Colab** for easy usage.
- Simple GUI-based file selection (via EasyGUI for local execution).

---

## Technologies Used
- **Python**
- **OpenCV (cv2)** – image processing
- **NumPy (numpy)** – numerical operations
- **Matplotlib (matplotlib.pyplot)** – visualization
- **EasyGUI (easygui)** – file selection (for local use)
- **PIL (Pillow)** – image handling
- **Google Colab Libraries (google.colab.files)** – upload & download support in Colab

---

## How It Works
1. Upload/select an image.
2. Convert the image to **grayscale**.
3. Apply **median blur** for smoothing.
4. Detect edges using **adaptive thresholding**.
5. Reduce noise with **bilateral filtering**.
6. Combine results to create a **cartoonified image**.
7. Save or download the cartoon image.

---

## Usage
### Run in **Google Colab**
1. Open the project notebook in Google Colab.
2. Upload an image using `google.colab.files`.
3. Run all cells to cartoonify your photo.
4. Download the output image.

### Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/cartoonify-image.git
   cd cartoonify-image
