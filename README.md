
### Setting Up
It is generally encouraged that you always use Python virtuan environment to have isolated Python installations per project. In this guide, I suggest you do the same. So 'cd' into the 'invictus' directory that you've cloned onto your computer and perform the following actions to run the notebooks in a separate virtual environment.

1. ```python3 -m venv env```
2. ```source /env/bin/activate```
3. ```pip3 install -r requirements.txt```
4. ```jupyter notebook```

### Tesseract-OCR
Click [here](https://sourceforge.net/projects/tesseract-ocr-alt/files/tesseract-ocr-setup-3.02.02.exe/download) to download Tesseract-OCR, which is used for number plate recognition.

download and install the above software in: C:\Program Files (x86)\Tesseract-OCR

### Opening Notebooks
In invictus, every notebook is self-contained and demonstrates end-to-end flow of actions that must be taken to accomplish a given task. The name of a notebook file suggests its purpose.

Once you've started jupyter notebooks with the command ```jupyter notebook``` you must open http://localhost:8888/ in your browser to see the tree of files and directories in invictus.

Click on the ```notebooks``` folder and select your notebook of choice to see the code demonstration.

