Download tesseract exe from https://github.com/UB-Mannheim/tesseract/wiki. <br />
Install this exe in C:\Program Files (x86)\Tesseract-OCR
Open virtual machine command prompt in windows or anaconda prompt.
Run pip install pytesseract

You will need to add the following line in your code in order to be able to call pytesseract on your machine: pytesseract.pytesseract.tesseract_cmd = 'C:\\Program Files\\Tesseract-OCR\\tesseract.exe'
