# ML-Projects
cat <<EOT >> README.md

This project aims to classify images of various animals using a pre-trained model. It utilizes a webcam to capture images, classify them, and announce the identified animal.

### Setup Instructions:

Follow these steps to set up the project:

1. **Download Files:**
   - Download the `animal_prediction.ipynb` file from [this repository](your_repository_link).
   - Download the `models` folder from the Google Drive link provided [here]([your_drive_link](https://drive.google.com/drive/folders/1QOqIhNx8FrsbUpqBvTgTZ7DpM_180-JI?usp=sharing)).
   - Place both the `animal_prediction.ipynb` file and the `models` folder in a single directory.

2. **Install Requirements:**
   - Download the project's requirements from `requirements.txt`.
   - Run the following command to install the necessary packages:
     ```bash
     pip install -r requirements.txt
     ```

### How to Run:

1. **Open Jupyter Notebook:**
   - Launch Jupyter Notebook by running:
     ```bash
     jupyter notebook
     ```
   - Open the `animal_prediction.ipynb` notebook.

2. **Execute the Code:**
   - Follow the instructions within the notebook to execute the code cells.
   - Ensure your webcam is accessible and functional.
   - Display an object to the webcam and press 'p' to capture and classify the image.

3. **Expected Output:**
   - The model will classify the image and announce the identified animal.
   - The range of animals the model can identify is listed below.

### Animal Range:
The model can classify the following animals:

{0: 'antelope', 1: 'badger', 2: 'bat', ... (and so on for all animals)}

EOT
