# Towards-efficient-automatic-water-meter-reading-using-haar--like-features.
Water metering is the practice of measuring water use. The traditional way of measuring water usage is by taking manual water volume readings from a water meter. This technique can lead to possible errors in meter reading. Therefore, there is a need for an automatic capturing system for water meter reading that will reduce inefficiencies.  This solution proposes Automatic water meter reading using digital image features called haar-like features that are used for object recognition. This approach will train a dataset of water meter images to and their corresponding masks that will be used to find the region of interest which is the water meter reading. After the regions of interest have been detected the meter reading region can be broken down into segments to identify the individual digits. The digits can be recognised using haar-like features. This can be done using integral images, haar-classifier and the AdaBoost classifier to determine the digit in the image.  

This project uses the  'Water Meters Dataset, 1244 Photos & Masks' and is accessed in the notbook using the kaggle api.
The key is provided in 'kaggle.json' file and is required to be uploaded in the notbook.

To run the code:

1.Upload notebook "DigitRecognition.ipynb" to google colab

2.Upload roboflow folder to colab

3.Will be prompted to upload kaggle.json file

4.Adjust file paths accordingly for sections; 'Segmenting individual digits', 'Calculating integral images and haar features', 'Classification and evaluation' in the notebook.

#Aternative to accessing the notebook: https://colab.research.google.com/drive/1KbVha64zLvNhFh2WxtZut8kEnj9S5pYe?usp=sharing

#Google drive folder with all files: https://drive.google.com/file/d/1qtsCF_tc9fG2EbeSblGSALIhAB0ciVyX/view?usp=sharing

