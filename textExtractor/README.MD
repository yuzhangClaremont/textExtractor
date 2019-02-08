
# install tesseract, OpenCV
first step: https://www.pyimagesearch.com/2017/07/03/installing-tesseract-for-ocr/
"brew install tesseract"

Test on tesseract
tesseract example_01.png stdout
tesseract tesseract_inputs/example_03.png stdout digits 

"sudo opt install tesseract-ocr"
https://www.pyimagesearch.com/2017/07/10/using-tesseract-ocr-python/

$ pip3 install pillow
$ pip3 install pytesseract

$ pip3 install opencv-python



## to run

python3 run.py --image images/example_01.jpg

or 
python3 run.py --image images/example_02.jpg --preprocess blur


# run2
pip3 install imutils

python3 run2.py --east frozen_east_text_detection.pb --image images/example_01.png

Download pb file

<!-- python3 text_recognition.py --east frozen_east_text_detection.pb --image images/example_05.jpg --padding 0.25

python3 text_recognition.py --east frozen_east_text_detection.pb --image images/10.png --padding 0.15 -c 0.1 -w 160 

python3 extractor.py --east frozen_east_text_detection.pb --image images/example_02.jpg --padding 0.25 -d labels.txt

python3 extractor.py --east frozen_east_text_detection.pb -i images --padding 0.25 --dictionary labels.txt

python3 extractor.py --east frozen_east_text_detection.pb -i images --padding 0.05 --dictionary labels.txt

python3 extractor.py --east frozen_east_text_detection.pb -i images --padding 0.15 --dictionary labels.txt -->

python3 extractor.py --east frozen_east_text_detection.pb -i images --padding 0.15 --dictionary labels.txt -c 0.1
