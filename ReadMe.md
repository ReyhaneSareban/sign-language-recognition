# Sign Language Alphabet Recognition

A real-time sign language alphabet recognition system built with Python, OpenCV, MediaPipe, and Machine Learning.

The project uses hand landmarks to recognize ASL alphabet letters (A–Z) with a Random Forest classifier.

## Project Structure

- `sign_language_recognition.ipynb` – Main Jupyter Notebook.
- `sign_language_model.pkl` – Trained Random Forest model.
- `requirements.txt` – Required Python libraries.

## Dataset

The dataset is not included in this repository.

Download **SignAlphaSet** from Mendeley Data:

https://data.mendeley.com/datasets/8fmvr9m98w/3

## How to Run

1. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

2. Download and extract the dataset.
3. Open `sign_language_recognition.ipynb` in Jupyter Notebook.

4. Run the dataset preparation cells to extract hand landmarks and generate the CSV file.

5. Starting from the model training section, run the remaining cells to train and test the model.

The trained model can also be loaded separately for real-time webcam recognition.

## Technologies

- Python
- OpenCV
- MediaPipe
- NumPy
- Pandas
- Scikit-learn
- Random Forest