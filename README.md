# Plant Predictor

The aim of this project was to design a system that predicts the health of he plant, give its information and suggest remedies for a disease free plant. 
-A system that can be made easily available at any time and at any place and provides more information than just prediction.

Training a deep network to identify distinct types of materials has received a lot of attention in recent years since the issue of localization and recognizing an object can be challenging when applied to real-world images. The approach in detecting plant diseases is using a deep cnvoltuional neural network which is trained and fine-tuned to fit accurately to the database of plant's leaves that was gathered independently for diverse plant disease. 

_Block Diagram_

![image](https://user-images.githubusercontent.com/56022804/142756406-4ce041e1-952e-412c-81a4-0ee6c9eeefdf.png)

_Flow Chart_

![image](https://user-images.githubusercontent.com/56022804/142756435-ab2032c3-caa7-4213-8b7b-3c1818930713.png)

The image taken from user is resized to 200*200*3 pixels and reshaped to grayscale. Features are extracted from this image like edges, vein lines, shape,etc. The extracted features are campared with the features of raining dataset and image is thus classified. The image classification is then campared with the database and relevant suggestions are given to the user as result. 

Results include:
  1. Plant Recognition
  2. Scientific Name 
  3. Health
  4. Medicinal and Non-medicinal uses
  5. Tips to protect plant
  6. Minimum span for the plant to blossom
  7. Season of flowering

## Setup:
1. Download the zip file or git clone.
2. Extract the zip file in your project folder.
3. Install pip and python version 3.7.
4. Navigate to the project folder (extracted zip folder) on the command line or the terminal.
5. Create a virtual environment using the command *python -m venv envname* for windows and *$ sudo apt install python3-venv* followed by *$ python3 -m venv envname* for linux system.
6. Activate the ennvironment by *.\envname\scripts\activate* for windows and *$ source envname/bin/activate* for linux system.
7. Install the requirements.txt file using the command *pip install -r requirements.txt* for windows and *$ pip3 install -r requirements.txt* for linux system.
8. After successful installaion run the command *python -m flask run* for windows and *$ flask run* for linux system.
9. Open the localhost server 5000 on the browser.
Enjoy Prediction😁🙌 
