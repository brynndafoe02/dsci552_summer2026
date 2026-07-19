Brynn Dafoe brynndafoe02 3109669210

DSCI 552 Final Project

Files:
- notebook/Dafoe_Brynn_Project.ipynb
- requirements.txt
- data/defungi -> all data files (for Jupyter execution)

Requirements:
- Install requirements.txt
- Open and run Dafoe_Brynn_Project.ipynb

Note:
- I began developing this project first in Jupyter Notebook
- I switched to Google Colab in order to use the T4 GPU and finished developing and ran the notebook here
- Because I switched to Google Colab I had to change the data paths accordingly
- - To access the "defungi" data folder I uploaded to Google Drive (mounted in Colab)

IF RUNNING IN GOOGLE COLAB:
- The Colab notebook expects the data folder to be located at:
- - /content/drive/MyDrive/defungi
- Upload the "defungi" folder to the ROOT of your Google Drive (inside MyDrive, not inside another folder)
- - Then you can run this code as is

IF RUNNING IN JUPYTER NOTEBOOK:
- Update the dataset path to point to the local location of the "defungi" dataset
- - Can remove lines:
- - - from google.colab import drive
- - - drive.mount('/content/drive')
- - - data_path = "/content/drive/MyDrive/defungi"
- - Can replace lines:
- - - defungi_path = Path(data_path)
- - With:
- - - defungi_path = Path("../data/defungi")
