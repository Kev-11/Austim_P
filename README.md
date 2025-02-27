Austim_P

A machine learning model deployed using Streamlit to predict whether a person has autism based on given input features.

Features

Uses a trained ML model (best_model.pkl) for prediction.

Encodes categorical features using encoders.pkl.

Includes a Jupyter Notebook (model.ipynb) for model training and evaluation.

Web-based interface built with Streamlit (streamlit_app.py).

Dataset files (datasets/) for training and testing.

Installation

Clone the repository:

git clone https://github.com/Kev-11/Austim_P.git
cd Austim_P

Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

Install dependencies:

pip install -r requirements.txt

Usage

Run the Streamlit App

streamlit run streamlit_app.py

This will open the web interface where users can input data and get autism predictions.

Model Training

To retrain the model or modify it, open model.ipynb in Jupyter Notebook and follow the steps inside.

Dataset

The project includes a dataset in the datasets/ directory:

train.csv - Training data.

test.csv - Testing data.

sample_submission.csv - Example of expected output format.

Dependencies

All required Python packages are listed in requirements.txt. The key dependencies include:

scikit-learn

pandas

numpy

streamlit

Contributing

Feel free to fork this repository, create a branch, and submit a pull request for improvements.

License

This project is under the MIT License.
