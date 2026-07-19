Brynn Dafoe brynndafoe02 3109669210

DSCI 552 Final Project

Files:

- notebook/Dafoe_Brynn_Project.ipynb
- requirements.txt
- data/defungi -> all data files 

Requirements:

- Install requirements.txt
- Open and run Dafoe_Brynn_Project.ipynb

Note:
- I began developing this project in Jupyter Notebook
- I switched to Google Colab and finished developing and ran this notebook in Google Colab in order to use the T4 GPU
- Because I switched to Google Colab I had to change the data paths accordingly to access the "defungi" data folder I uploaded to Google Drive (mounted in Colab)
- If running the notebook locally in Jupyter, updata the dataset path to point to the local location of the "defungi" dataset
- - can remove lines:
- - - from google.colab import drive
- - - drive.mount('/content/drive')
- - - data_path = "/content/drive/MyDrive/defungi"
- - can replace lines:
- - - defungi_path = Path(data_path)
- - with:
- - - defungi_path = Path("../data/defungi")
