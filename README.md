

# SA-C-GENDER-CLASSIFIER
# Algorithm
1. Install the DeepFace library using the command pip install deepface
2. To Predict the gender of a person use this DeepFace library
3. Import the deepface class from DeepFace library, cv2 class from openCv2 library and Matplot library according to the requirements.
4. Load and display the image which we have imported. 
5. Pass the image to DeepFace library and analyze the image to predict gender of a person.
6. This prediction is stored in result variable and print the prediction using this algorithm.

## Program:
```
/*
Program to implement 
Developed by   : U.Bhavya
RegisterNumber :  212220230055
*/
```

```
!pip install deepface
from deepface import DeepFace
import cv2
import matplotlib.pyplot as plt
img1=cv2.imread('s1.jpg')
plt.imshow(img1[:,:,::-1])
plt.show()
result=DeepFace.analyze(img1,actions=['gender'])
print("Gender : ",result['gender'])
img2=cv2.imread('m1.jpg')
plt.imshow(img1[:,:,::-1])
plt.show()
result=DeepFace.analyze(img2,actions=['gender'])
print("Gender : ",result['gender'])
```

## OUTPUT:
![s1](https://user-images.githubusercontent.com/75235293/172665895-5f21d4b9-00f4-4af1-8e95-602575577467.jpeg)
![s2](https://user-images.githubusercontent.com/75235293/172665954-5cd9dee5-894e-4ee4-9f41-45b688949fef.jpeg)
![s3](https://user-images.githubusercontent.com/75235293/172665978-f835f817-f53b-49ed-a1a1-77d5245f4c93.jpeg)
![s4](https://user-images.githubusercontent.com/75235293/172666019-8987ce64-2e41-43f1-bfb8-6934d9e06937.jpeg)


DEMO VIDEO YOUTUBE LINK:

https://youtu.be/dIBAdwEpzAU
