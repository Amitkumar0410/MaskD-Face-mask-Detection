# MaskD-Face-mask-Detection
Effective strategies to restrain COVID-19 pandemic need high attention to mitigate negatively
impacted communal health and global economy,with the brim-full horizon yet to unfold.In the 
absence of effective antiviral and limited medical resources,wearing a mask has become the
non-pharmaceutical intervention measures that can be used to cut the primary source of SARS-
CoV2 droplets expelled by infected individual.To contribute towards communal health, we have 
made a deep learning based model which we have named as MaskD-Face-mask-Detection.
        This project aims towards detecting masks over faces in public places to curtail 
community spread of Coronavirus.Our model can effeciently handle varying kinds of occulsions in 
dense situation by making use of ensemble of single and two stage detectors.The ensemble approach
not only helps in achieving high accuracy but also improves detection speed considerably.The model is 
98.2% accurate at mask detection.The high accuracy of model is due to highly balanced face mask centric 
dataset.The other factor that contributed towards achievement of our highly effecient model is the 
usage of transfer learning.Transfer learning leads to good results by enabling use of powerful 
pre-trained model model such as MobileNet which we have used in our model.We have used MobileNet to 
achieve highly accurate results in less inference time.Our whole model is coded in phyton language.  

Followings are the main applications which we have used in our model:
tensorflow/keras-it has been used to allow data augmentation,loading MobileNet classifier,pre-processing
and loading image data.
imutils-it helps us to find and list images in our dataset. 
numpy
opencv-python
matplotlib-it is used in order to plot our taining curves.
scipy

Following is the explanations of the files in project:
Dataset folder(data.zip, data.z01, data.z02, data.z03, data.z04, data.z05, data.z06)-contains all data that is used.
   training.py is the file where code is written to train the machine to perform the necessary task.
 video_stream.py is the file which contains codes which will eventually help in running our  task.
