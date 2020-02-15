#Run the following on Google Colab

- from google.colab import files

- files.upload()
- !pip install -q kaggle
- !mkdir -p ~/.kaggle
- !cp kaggle.json ~/.kaggle/
- !kaggle datasets list