
# PDF to Audio Book Converter 

# How it works

We are extracting the text from the pdf document and later we are cleaning the text to align it in proper formate. This converted text in string format is being passed on to **Google Computer Vision** API to convert it to speech in real-time.

# How to use?

- Download the repository
- Open a new terminal
- Create a new conda environment for the project </br>
  ```conda create -n pdf-to-audio python=3.6``` </br>
  ```conda activate pdf-to-audio```
- Create a Google cloud account for free and get your Privat key API for text-to-speech and store in the **PDF-to-audoibook-converter** directory.
  - For reference take a look at this [Google Cloud Text-to-speech](https://cloud.google.com/text-to-speech/docs/libraries)
  - Open you **pdf_to_audio.py** file and in **line no. 68** replace and add your Private API key location (which is your local directory).
- Go to the **PDF-to-audoibook-converter** repository in termial and do, </br>
  ```pip install -r requirements.txt```
- Run ```python pdf_to_audio.py``` and a gui will open to select the PDF file which you wanted to be converted to audio.
- Select the pdf file which you want to convert to audio.
- Then you will get your pdf file converted to a audio book.

# Note

If you find difficult to use google computer vision or you want to make it simple you can use **gTTS** library to convert the text(string) to audio. </br></br>
To install the library use the follwing command, </br> 
- ```pip install gTTS``` 
- Refer this [gTTS](https://gtts.readthedocs.io/en/latest/) documentation for implementing string to speech conversion. 

</br> 
<ins>Disclaimer:</ins> Convertion of text to string will take more time with this tool.


### ENJOY LISTENING TO YOUR BOOKS!! 

<p align="center">Thank you for scrolling all the way!</p>
<p align="center"><a href="#top"><img src="https://img.shields.io/badge/-Back%20to%20Top-teal?style=for-the-badge" /></a></p>
