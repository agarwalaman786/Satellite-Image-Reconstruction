# Satellite-Image-Reconstruction
This Project is made during the Technoutsav Hackathon Organized by Deloitte. By using this application one can reconstruct the Images which are captured from the satellite and contains missing parts due to cloud and their shadows.

# Key Points about the software
1. This is the web app with the Interactive User Interface.
2. It contains the option to upload the Image.
3. One need to have patience because construction of the Image is time taking and highly dependent upon the number of pixels and number of distorted pixels.
4. Time taken to evaluate a high priority pixel is nearly 10-15 seconds.
5. The flow is when user uploads the Image first it is resized to the 256x256 (because system is designed for this size) after this the cloud and shadow detection algorithm runs and predict the mask for the Image and after this detected cloud and shadows are removed and new Image is generated one can save this Image.

