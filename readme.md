# Pan Card Tampering Flask App

Detect Tampering of PAN Card using Computer Vision

This project is aimed at using computer vision techniques to detect tampering of PAN cards, which is a prevalent issue in India. The system uses image processing and analysis techniques to identify any modifications made to the PAN card, including changes to the text, image, or background.

## Prerequisites

* Python 3.6 or higher
* OpenCV
* NumPy
* Pandas

## Installation

1. Clone the repository
2. Install the required packages using the following command:

#pip install -r requirements.txt

## Usage

1. Open a terminal window and navigate to the project directory.
2. Run the following command to detect tampering in a PAN card image:

#python detect_tampering.py --image path/to/image


## Results

The system uses advanced image processing algorithms to analyze the input PAN card image and identify any modifications made to it. The output of the system is a binary classification of whether or not the PAN card has been tampered with.

## Limitations

The system relies heavily on the quality of the input image, and may not be able to detect subtle changes made to the PAN card if the input image is of poor quality.

## Future Work

Future work on this project could include improving the accuracy of the system by using deep learning techniques, or expanding the scope of the system to detect tampering in other types of identification documents.

