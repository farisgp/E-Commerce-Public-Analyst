## Setup Environment Miniconda
- curl https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe -o .\miniconda.exe
- start /wait "" .\miniconda.exe /S
- del .\miniconda.exe
- conda create --name main-ds python=3.9
- conda activate main-ds

## Setup Environment
- mkdir data_analyst
- cd data_analyst
- pip install pipreqs
- pipreqs /home/project/location

Run steamlit app
streamlit run dashboard.py
