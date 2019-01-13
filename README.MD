Today’s blog post is part one in a two part series on installing and using the 

https://packaging.python.org/guides/installing-using-pip-and-virtualenv/
create virtualenv
python -m virtualenv env

activate virtualenv
source env/bin/activate

leave

deactivate


install tesseract
first step: https://www.pyimagesearch.com/2017/07/03/installing-tesseract-for-ocr/
brew install tesseract

Test on tesseract
tesseract example_01.png stdout
tesseract tesseract_inputs/example_03.png stdout digits 

sudo opt install tesseract-ocr
https://www.pyimagesearch.com/2017/07/10/using-tesseract-ocr-python/

1
2
$ pip install pillow
$ pip install pytesseract

pip install opencv-python



to run

python run.py --image example_01.png

or 
python ocr.py --image example_02.png --preprocess blur
