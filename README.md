# Gesture Recognition Project
Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions. You want to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote. 

The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

    Thumbs up:  Increase the volume
    Thumbs down: Decrease the volume
    Left swipe: 'Jump' backwards 10 seconds
    Right swipe: 'Jump' forward 10 seconds  
    Stop: Pause the movie
    
## Understanding the Dataset

Testing the optimum value for batch size: Initially, we experimented with various batch sizes. A batch size of 128 caused an error, so our testing was conducted exclusively with batch sizes of 32 and 64.
For image resolution, we tested the models with an 80*80 resolution and also tried a 120*120 resolution. However, we did not observe a significant improvement in accuracy with the higher resolution image, so we opted to use an 80*80 image for the final model.
The initial model encountered generator and memory errors. Subsequently, we built upon that model, and the notebook now features our third model as the first one successfully executed using Conv3D.
We are using the SGD optimizer, as we have found it effective with Conv2D models. We anticipate it will perform well with this Conv3D model too.

To get started with the model building process, you first need to get the data on your storage. 

In order to get the data on the storage, perform the following steps in order

 https://drive.google.com/uc?id=1ehyrYBQ5rbQQe6yL4XbLWe3FMvuVUGiL

     unzip Project_data.zip

## Technologies Used

Python 3.11.5
numpy 1.24.3
keras 2.15.0
tensorflow 2.15.0

# Final Results using different Hyperparameters and architectures have been recorded in the writeup

## Contact
Created by [@icsaiml @chinmaynayak] - feel free to contact me!
