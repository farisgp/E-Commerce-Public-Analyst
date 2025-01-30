Setup Environment Miniconda
curl https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe -o .\miniconda.exe
start /wait "" .\miniconda.exe /S
del .\miniconda.exe
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt

Setup Environment
mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pip install -r requirements.txt

Run steamlit app
streamlit run dashboard.py