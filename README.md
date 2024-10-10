# ProyekAnalisis_Data

## Setup Environment
```
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt
conda install ipykernel
python -m ipykernel install --user --name=main-ds
```

## Setup Environment - Shell/Terminal
```
mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt
```

## Run Streamlit app
```
streamlit run dashboard.py
```
