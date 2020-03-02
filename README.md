# OCR with PyTesseract and OpenCV

## Getting started (on Windows)
Feel free to clone this repository and make a pull request with instructions for other OS's

### 1. Install Tesseract
  1. [Download link for v4.00.00](http://digi.bib.uni-mannheim.de/tesseract/tesseract-ocr-setup-4.00.00dev.exe)
  2. Add Tesseract root folder to PATH  
  Root folder can be found at either  
    - `C:\Program Files\Tesseract-OCR` (if installed for all users)  
    OR  
    - `C:\Users\<username>\AppData\Local\Tesseract-OCR` (if installed just for one user)

### 2. Install pytesseract
[PyPi link](https://pypi.org/project/pytesseract/)
```python
pip install pytesseract
```

### 3. Install OpenCV
[PyPi link](https://pypi.org/project/opencv-python/)
```python
pip install opencv-python
```