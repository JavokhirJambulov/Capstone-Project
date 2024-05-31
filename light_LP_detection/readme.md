KoreanLpDetector

Korean License Plate detection

Algorithm
Start -> Turn on Camera -> Detect Cars -> Detect Korean License Plate in Car -> OCR -> 

Requirements
This project uses the following libraries: yolov5, easyocr, pytorch, opencv, numpy.

You can install all the required libraries using pip. If you encounter any issues, try reinstalling the libraries using pip.

All necessary weights are included in the repository, making its size approximately 50 MB. You don't need to download anything extra.

Trained On
The model is trained on the AIHUB dataset.
OCR is trained on a set of 80,000 license plate characters.


Advantages
This project outperforms other open-source projects on GitHub.
It features the simplest code among similar projects on GitHub.
Performance can be improved with further training.

Limitations
The training is not fully optimized; the original yolov5 model is used for car detection, so it may not perform well when a car is close to the camera.
Older license plates may be hard to recognize, whereas newer ones are more easily detected.

References
YOLOv5 Repository
EasyOCR Repository

