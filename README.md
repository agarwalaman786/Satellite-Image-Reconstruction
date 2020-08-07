# Satellite-Image-Reconstruction
This Project is made during the Technoutsav Hackathon Organized by Deloitte. By using this application one can reconstruct the Images which are captured from the satellite and contains missing parts due to cloud and their shadows.

# Key Points about the software
1. This is the web app with the Interactive User Interface (Created using flask).
2. It contains the option to upload the Image.
3. One need to have patience because construction of the Image is time taking and highly dependent upon the number of pixels and number of distorted pixels.
4. Time taken to evaluate a high priority pixel is nearly 10-15 seconds.
5. The flow is when user uploads the Image first it is resized to the 256x256 (because system is designed for this size) after this the cloud and shadow detection algorithm runs and predict the mask for the Image and after this detected cloud and shadows are removed and new Image is generated one can save this Image.

# How to run the project
1. One need to have the python 3.5.2 in the system and better GPU support with cuda enabled and minimum of 4GB Ram.
2.One need to install the required libraries to run this software and tensorflow is required and rest libraries are mentioned in the requirements.txt file.
pip install -r requirements.txt
3. Pre trained models are given for the convinence and if one need of the training data contact at (agarwalaman860@gmail.com).
4. Download all the files and run the project by using command python app.py

After running the above command one need to paste the URL (0.0.0.0:8080) into the browser. This is the localhost address at which the application is running currently.

## Below is the home page of the application
![Screenshot from 2020-06-26 14-30-39](https://user-images.githubusercontent.com/39858354/89435311-53bec700-d762-11ea-996d-191c59f9f21d.png)

## One should read the Instructions before using the software.. for this click on the click here button
![Screenshot from 2020-06-26 14-30-56](https://user-images.githubusercontent.com/39858354/89607960-6552bc80-d891-11ea-80bc-ebcc60c07204.png)






