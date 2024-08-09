# AAI-511-Neural Networks and Deep Learning-final-project
The primary objective of this project is to develop a deep learning model that can predict the composer of a given musical score accurately. The project aims to accomplish this objective by using two deep learning techniques: Long Short-Term Memory (LSTM) and Convolutional Neural Network (CNN).

### Requirements

- Python 3.x
- [pip](https://pip.pypa.io/en/stable/)

## Installation

1. Create a virtual environment (optional but recommended):

    ```bash
    python -m venv final_project_venv
    ```

2. Activate the virtual environment:

    - **On Windows**:

    ```bash
    final_project_venv\Scripts\activate
    ```

    - **On macOS/Linux**:

    ```bash
    source final_project_venv/bin/activate
    ```

3. Install dependencies using `requirements.txt`:

    ```bash
    pip install -r requirements.txt
    ```

## Running the Notebooks

### Option 1: Running Locally in a Jupyter Notebook

1. Install Jupyter Notebook (if not already installed):

   ```bash
   pip install jupyterlab
   ```

3. Start the Jupyter Notebook server:

- **On Windows**:

  ```bash
  final_project_venv\Scripts\activate
  jupyter notebook
  ```

- **On macOS/Linux**:

  ```bash
  source final_project_venv/bin/activate
  jupyter notebook
  ```

3. Navigate to your project directory and open the notebook where you want to run the code.

4. Ensure that your virtual environment is being used in the Jupyter notebook by selecting the appropriate kernel:

- Click on the Kernel menu.
    - Choose Change kernel.
    - Select your environment (final_project_venv).

### Option 2: Running in Google Colab

1. Upload your project files to Google Drive or directly to Google Colab.

2. Install the required dependencies in the Colab environment by adding the following code at the beginning of your notebook:

   ```bash
   pip install -r Requirements.txt
   ```

4. Mount your Google Drive to access project files (if necessary):

    ```bash
    from google.colab import drive
    drive.mount('/content/drive')
    ```
    
6. Run your code cells as you normally would in a Jupyter notebook.
