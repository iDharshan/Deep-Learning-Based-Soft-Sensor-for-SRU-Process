# Efficient SRU Optimization via Deep Learning-driven LSTM Dynamical Models

## Project Overview:
This project utilizes Long Short-Term Memory (LSTM) networks to estimate key variables in a sulfur recovery unit (SRU) of a refinery plant. The goal is to achieve accurate predictions for process optimization, even in offline analyzer scenarios.

## Files Included:
- `IN_Table.csv`: Input dataset containing essential measurement series for predicting SO2 and H2S concentrations.
- `OUT_Table.csv`: Output dataset containing target variables Out1 and Out2.
- `H2S_Model.ipynb`: Jupyter Notebook containing the code for the H2S concentration prediction model.
- `SO2_Model.ipynb`: Jupyter Notebook containing the code for the SO2 concentration prediction model.
- `H2S_GUI.ipynb`: Jupyter Notebook containing the Streamlit code for the H2S concentration prediction GUI.

## Instructions for Running:
1. Ensure you have Python and Jupyter Notebook installed on your system.
2. Clone this repository to your local machine using `git clone <repository-url>`.
3. Navigate to the project directory.
4. Place the `IN_Table.csv` and `OUT_Table.csv` datasets in the same directory.
5. Open the desired Jupyter Notebook (`H2S_Model.ipynb` or `SO2_Model.ipynb`) in Jupyter Notebook.
6. Follow the instructions provided in the notebook to run the code and train the LSTM model.
7. For the GUI application, open `H2S_GUI.ipynb` and follow the instructions to run the Streamlit app.

## Dependencies:
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- TensorFlow
- Streamlit (for GUI)

