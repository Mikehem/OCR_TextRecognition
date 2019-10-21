# OCR_TextRecognition
# Menu Extractor

Project holder for Eats Menu Extractor

## Steps To Setup Environment
1. Create a virtualenvironment
    `virtualenv -p python3.6 env`

2. Activate environment
    `cd env`
    `source bin/activate`

3. Add global variables
4. Add pip packages using requirements.txt
    `pip install -r requirements.txt`


## Solution Details
### 1. CRNN
This notebook cantains code to train a CRNN model using open sourced data from the Computer Vision Group. This implementation is done in tensorflow 1.12

### 2. CRNN RecogniseText TF
This makes use of the CRNN tensorflow model trained in the above notebook to make predictions.

### 3. CRNN RecogniseText PP
This makes use of the pre-built model in pytorch to make predictions.

### 4. CTPN TextRecognition
This is the CTPN implementation for recognising text in an image. This has been implemented in Tensorflow and makes use of a pre-built model.
