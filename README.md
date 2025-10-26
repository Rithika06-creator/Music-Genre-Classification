# Music Genre Classification Project

**Objective:** To build and train a Convolutional Neural Network (CNN) to classify music files into 10 different genres using MFCC features.

**Author:** [Your Name Here]
**Course:** [Your Course Name Here]

---

## Deliverables

This project includes:

* **`Music_Genre_Classification.ipynb`**: The main Google Colab notebook containing all code for data preprocessing, model building, training, and the final prediction demo.
* **`genre_classifier.h5`**: The trained and saved Keras model file.
* **`README.md`**: This file, explaining the project.

---

## How to Run the Demo

The audio prediction demo is located at the end of the Colab notebook (`.ipynb` file).

1.  **Upload Project:** Upload both `Music_Genre_Classification.ipynb` and `genre_classifier.h5` to a folder in your Google Drive (e.g., "My Drive/Colab Projects").
2.  **Open in Colab:** Open the `.ipynb` notebook in Google Colab.
3.  **Run Setup:** Run the first few cells to mount your Google Drive and install `librosa`.
4.  **Run the Demo:** Scroll down to **"Step 4: Create the Prediction Demo"** (Cell 10).
    * Run the cell that loads the model and defines the `predict_genre` function. Make sure to update the `MODEL_PATH` variable to point to where you saved `genre_classifier.h5` in your Drive.
5.  **Test:** Run the final cell (Cell 11) to activate the "Choose Files" button and upload your own `.mp3` or `.wav` file for classification. The prediction will be printed in the output.
