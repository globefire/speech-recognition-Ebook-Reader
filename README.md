<h3>Implementing speech synthesis(📖 to 🗣) on eBooks</h3>

Bored of writing notes in a lecture? How about we convert the notes dictated by the lecturer into text?
Use the **speechtotext.py** script to get the text format of spoken notes, which saves the text in a .txt file.
<br>
Too lazy to read a novel? Get an Ebook version of the novel and run the **finalAudioBookGenerator.py** script. It will generate an mp3(audio) format of the book. Enjoy book listening :)
<br>
You can also convert your single images using **singleImageReader.py** script
<br><br>
An **example** of each of the script is shown, the text from **_spoken text.PNG_** was delivered by me, observe the **s2txt.txt** it is the output (accurate to a great extent if you have a decent english speaking accent)<br>
Listen to the **read.mp3** and observe the page numbers which are spoken from the pdf file. (eg of ebook reader) 

### Prerequisite

**For Windows Users**
- Install tesseract from [here](https://github.com/UB-Mannheim/tesseract/wiki).
- Add tesseract to your environment variable. (Add this path C:\Program Files (x86)\Tesseract-OCR)
- Type 'tesseract' in cmd you will get a lot of options like [this](https://github.com/globefire/speech-recognition-Ebook-Reader/blob/master/tesseractCMDScreenshot.PNG). 
- (**_Optional:_ This step should be done only if you get an error which gives the below error** )Add a new variable in environment variable **TESSDATA_PREFIX** and give it _C:\Program Files (x86)\Tesseract-OCR\tessdata_ this value.

```
Please make sure the TESSDATA_PREFIX environment variable is set to the parent directory of your "tessdata" directory.
```

**For Linux Users**
- Install Tesseract with this [tutorial](https://www.linux.com/tutorials/using-tesseract-ubuntu/). After installation jump to how to run.
- Refer this [https://github.com/sladyn98/AudioBookGenarator-CLI](https://github.com/sladyn98/AudioBookGenarator-CLI) It is a CLI of this project developed by @sladyn98. 

### How to run:
__NOTE: You need to complete the steps mentioned in Prerequisite.__

Run these commands in cmd/terminal of a directory

```git
git clone https://github.com/globefire/Audio-book-generator.git
cd speech-recognition-Ebook-Reader
pip install -r requirements.txt
python speechtotext.py
python finalAudioBookGenerator.py
```


### Watch the demonstration
- [Press Me :)](https://youtu.be/xhMvGg1dAsg)


### Support Me
If you liked this Repository, then please leave a star on this repository. It motivates me to contribute more in such Open Source projects in the future.
### Happy Coding =)
