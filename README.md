# Heart Sound Classification with Deep Learning

This project implements a deep learning model for the **classification of heart sounds**.  
The model is trained to distinguish between different heart conditions such as **Aortic Stenosis**, **Mitral Stenosis**, and **Normal** heart sounds.

---

## Project Files
- **BD24_2_Speech_Recog_Qualification.ipynb**  
  Contains the complete code for the project, including:
  - **Data Preparation**: Downloading and extracting the dataset.  
  - **Model Architecture**: Deep learning model using TensorFlow & Keras for audio classification.  
  - **Training & Evaluation**: Training the model and measuring performance.  
  - **Results**: Accuracy, correct predictions, and errors.

---

## Technologies Used
- **Python** – Main programming language  
- **TensorFlow & Keras** – Model building & training  
- **NumPy** – Numerical operations & data manipulation  
- **Matplotlib** – Data visualization  
- **SciPy** – Audio file processing (`.wav` files)  

---

## Results
The model achieved an accuracy of **81.25%**, correctly classifying **104 out of 128 samples**.  
The notebook provides a detailed breakdown of predictions for each data point.

---

## How to Run
1. Install Python and the required libraries (`TensorFlow`, `NumPy`, `Matplotlib`, `SciPy`).  
2. Open the notebook:  
   ```bash
   jupyter notebook BD24_2_Speech_Recog_Qualification.ipynb
