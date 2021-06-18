# OCRtoSpeech
This project is developed with the help of Tesseract, Google APIs for translate and text to speech recognition.

### OCR and text to speech [english] Translate in Native languages

1. To recognise texts in English which is in the form of images, Tesseract is used here. 
2. The image is fed as input with the help of opencv package.
![readme](https://user-images.githubusercontent.com/58415948/122537423-2bbb1800-d043-11eb-9af8-1d96fe18b549.PNG)
3. Then the text is extracted from it an then fed as an input for gTTS, which is a python library and a CLI tool to interface with Google API. (for english version of the text, refer repository English.mp3)
4. The text obtained from the image is given as an input to the googletrans,which is also a python library that implements Google translate API.
5. The text can be converted to the set of native languages that are being offered by googletrans.
6. Again the gTTS is being used to read out the text aloud in specified languages (for native version of the text, refer repository Native.mp3)  


https://user-images.githubusercontent.com/58415948/122542349-388e3a80-d048-11eb-8d4d-4f51d4f4b706.mp4
