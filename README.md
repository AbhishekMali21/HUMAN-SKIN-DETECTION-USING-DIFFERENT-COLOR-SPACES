# HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES

[![author](https://img.shields.io/badge/author-Abhishek-ff69b4.svg?style=flat-square)](https://www.linkedin.com/in/abhishekmali/)
[![GitHub followers](https://img.shields.io/github/followers/AbhishekMali21?style=social)](https://github.com/AbhishekMali21?tab=followers)
[![GitHub watchers](https://img.shields.io/github/watchers/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES?style=social)](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/watchers)
[![GitHub stars](https://img.shields.io/github/stars/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES?style=social)](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES?style=social)](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/network/members)

![GitHub language count](https://img.shields.io/github/languages/count/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES?style=flat-square)
![GitHub top language](https://img.shields.io/github/languages/top/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES?logoColor=9cf&style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES?logoColor=important&style=flat-square)

[![GitHub issues](https://img.shields.io/github/issues/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES?style=flat-square)](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/issues?q=is%3Aopen+is%3Aissue)
[![GitHub closed issues](https://img.shields.io/github/issues-closed/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES?style=flat-square)](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/issues?q=is%3Aissue+is%3Aclosed)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES?logoColor=yellow&style=flat-square)](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/pulls?q=is%3Aopen+is%3Apr)
[![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES?logoColor=yellow&style=flat-square)](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/pulls?q=is%3Apr+is%3Aclosed)
[![LICENSE](https://img.shields.io/dub/l/vibe-d.svg?style=flat-square)](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/blob/master/LICENSE)
[![HitCount](http://hits.dwyl.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES.svg)](http://hits.dwyl.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES)


## ABOUT THE PROJECT:
Designed and Created a **Human Skin Detection Model** to identify skin present in an image using color spaces such as RGB, HSV & YCbCr in achieving higher accuracy.

## OBJECTIVE:
Human skin detection plays a key role in human-computer interactions. As we can see that there are so many new technological advancements happening such as biometric authentication in our smart phones for face detection, adult content filtering, hand gesture recognition is a modern way of human computer interaction i.e., we can control our system by showing our hands in front of webcam and hand gesture recognition can be useful for all kinds of people. Based upon this idea of skin detection this paper is presented. This paper provides a detailed explanation to the procedure and methodologies for the human skin detection or recognition.

## SCOPE:
A reliable human skin detection method that is adaptable to different human skin colors and illumination conditions is essential for better human skin segmentation. Even though different human skin color detection solutions have been successfully applied, they are prone to false skin detection and are not able to cope with the variety of human skin colors across different ethnic. In this approach we refine the skin model by combining HSV & YCbCr color spaces. The proposed approach reduces computational costs as no training is required and it improves the accuracy of skin detection despite wide variation in ethnicity and illumination.

## PURPOSE:
Skin detection is the process of finding skin-colored pixels and regions in an image or a video. This process is typically used as a preprocessing step to find regions that potentially have human faces and limbs in images. Several computer vision approaches have been developed for skin detection. A skin detector typically transforms a given pixel into an appropriate color space and then use a skin classifier to label the pixel whether it is a skin or a non-skin pixel. A skin classifier defines a decision boundary of the skin color class in the color space based on a training database of skin-colored pixels.

## PYTHON LIBRARIES USED:
* os
* numpy
* cv2 - OpenCV
* tkinter
* easygui
* flask
* flask_cors
* webbrowser

## EXISTING SYSTEM:
Detection of human skin is most importance in numerous applications including gesture analysis, recognizing human by human and/or machine and face tracking. Detection of skin color pixels and non skin color pixels and its classification is quite challenging task. In an image the skin color is sensitive to various factors such as camera characteristics, ethnicity, hairstyle, makeup, shadows, illumination, motion background colors, also influence skin color appearance. A reliable human skin detection method that is adaptable to different human skin colors and illumination conditions is essential for better human skin segmentation. Although various human skin color detection solutions have been effectively applied, they prostrate with false skin detection and are not able to cope with the variety of human skin colors across different ethnic. Also, existing methods need high computational cost. Also, there are many human skin detection methods in the current trend, which uses different color spaces along with various algorithms on the images to overcome all the illuminations for detection of human skin. Such existing methods result in less accuracy, need high computational cost, and more execution time.

### DISADVANTAGES:
- The existing methods prostrate with false skin detection and are not able to cope with the variety of
human skin colors across different ethnic.
- Various factors such as camera characteristics, ethnicity, hairstyle, makeup, shadows, illumination, and
motion background colors are not considered.
- The existing skin detection methods require high computational cost and more execution time.

## PROPOSED SYSTEM:
The system aims at providing a method which provides more robust and accurate results with minimum computational cost irrespective of various factors such as camera characteristics, ethnicity, hairstyle, makeup, shadows, illumination, motion background colors, also influence skin color appearance. The suggested method combines HSV color space model image and YCbCr color space model image for automatic human skin detection in color images. This method reduces computational costs as no training is required and it also displays the output with higher accuracy of skin detection despite wide variation in illumination, ethnicity and Background. This system also overcomes the effect of illumination depending on the surroundings, individual characteristics varying skin tone with respect to different regions and other
factors such as background colors, shadows etc.

### ADVANTAGES:
- The system provides robust and accurate results.
- Implementation and deployment of this system requires minimum computational cost and minimum
executional time.
- Different color space models are used for skin detection. OpenCV consists of methods to apply HSV &
YCbCr color space models on the image.

## UML DIAGRAM
***

![UML DIAGRAM](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/blob/master/screenshots/Flow%20Chart.jpg)

***

## BACKEND DESIGN:
With the help of Python packages and use of Spyder IDE we proceed with our design to implement the
project:
1. Setting Spyder environment and importing packages OpenCV, Numpy & Webbrowser for running our code. For importing images, test images must be stored in the specified address in .jpeg, .img, .png extensions.
2. Test image is converted into RGB image model as the first phase of the model. RGB image model will be basic model for testing other model on the test image for calculating accuracy.
3. RGB model will be tested for two different model namely- 1) HSV(Hue-Saturation-Value) & 2) YCbCr (Luminance and Chrominance)
4. In second phase of testing RGB model will be converted to the HSV model (Binary Image) and accuracy of determining the skin from the test image is calculated
5. Similarly, RGB model will be converted to the YCbCr model (Binary Image) and accuracy of determining the skin from the test image calculated.
6. Results of both the HSV model and YCbCr model can be improvised by combining both the model results which accounts for giving highest accuracy than both the models individually.
7. When there is no face detected on the image, it will return a blank image (black). Therefore, for testing purposes we assumed that true face(s) are detected in the image
8. Resulting output will be displayed individually on a web page.
The accuracy is a score that uses the sum of true positive and true negative as measurement.

## FRONTEND DESIGN:
By running the HSV and YCbCr color models in the python environment the results will be displayed in a frontend interface on the browser. The expected individual outputs are displayed. The results include RGB (Original Image), HSV color space output, YCbCr color space output and the final global image which is the summation of both HSV & YCbCr color space model image outputs.

## FUTURE ENHANCEMENTS
The development of these methods and models are really vast. Further, the skin detection model can be developed in a way to identify a particular color out of a colored photo. The enhancement of this system can be done by applying different algorithms and methodologies such as Fuzzy Entropy, Fusion Methodologies, Artificial Neural Networks and Convolutional Neural Networks. This model also can be deployed in many ways such as face detection, adult content filtering, live skin detection and human interactions with systems etc… for better performing models.
The Models can be developed in different ways by using some latest packages like OpenGL, TensorFlow and Caffe that will help us to give alternative procedures which will identify skin and perform functions as per the requirement.

## SCREENSHOTS
***
* SPYDER IDE:

![SPYDER IDE](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/blob/master/screenshots/Spyder%20coding.jpg)

***
* WINDOW TO UPLOAD IMAGE:

![WINDOW TO UPLOAD IMAGE](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/blob/master/screenshots/upload%20window.jpg)

***
* WEBPAGE:

![WEBPAGE](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/blob/master/screenshots/page1.png)

***
* ORIGINAL IMAGE WITH ELEVATE ZOOM:

![ORIGINAL IMAGE WITH ELEVATE ZOOM](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/blob/master/screenshots/page2a.jpg)

***
* HSV COLOR MODEL IMAGE WITH ELEVATE ZOOM:

![HSV COLOR MODEL IMAGE WITH ELEVATE ZOOM](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/blob/master/screenshots/page2b.jpg)

***
* YCbCr COLOR MODEL IMAGE WITH ELEVATE ZOOM:

![YCbCr COLOR MODEL IMAGE WITH ELEVATE ZOOM](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/blob/master/screenshots/page2c.jpg)

***
* GLOBAL IMAGE MODEL IMAGE WITH ELEVATE ZOOM:

![GLOBAL IMAGE MODEL IMAGE WITH ELEVATE ZOOM](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/blob/master/screenshots/page2d.jpg)

***
* TRY WITH ANOTHER IMAGE BY CLICKING THE BUTTON:

![TRY WITH ANOTHER IMAGE BY CLICKING THE BUTTON](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/blob/master/screenshots/page4.jpg)

***

## SCREENSHOTS OF FULL WEBPAGES
***
* WEBPAGE 1:

![WEBPAGE 1](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/blob/master/screenshots/image1.png)

***
* WEBPAGE 2:

![WEBPAGE 2](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/blob/master/screenshots/image2.png)

***
* WEBPAGE 3:

![WEBPAGE 3](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/blob/master/screenshots/image3.png)

***
* WEBPAGE 4:

![WEBPAGE 4](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/blob/master/screenshots/image4.png)

***

## CONCLUSION
This model concludes by using the topics of computer vision like OpenCV, it can help in converting an image from one color space model to another, merge different color space models, mask the image in specified range, edit, modify and save images. This model can identify human skin by using color space models which is spontaneous and robust in nature. Further this model can be enhanced using different algorithms and methodologies too. This can provide ease use of systems and many other applications. So, the open CV is helping the users with different accessible forms of models that will make ease life.

## REFERENCES:
[1] An Analysis of Skin Pixel Detection using Different Skin Color Extraction Techniques. (Authors: Gururaj P Surampalli, Dayanand J, Dhananjay M) - International Journal of Computer Applications (0975 - 8887) Volume 54 - No. 17, September 2012

[2] Color Space Selection for Human Skin Detection Using Color-Texture Features and Neural Networks (Authors: Hani K. Al-Mohair, Junita Mohamad-Saleh and Shahrel Azmin Suandi)

[3] Human Skin Detection Using RGB, HSV and YCbCr Color Models (Authors: S. Kolkur, D. Kalbande, P. Shimpi, C. Bapat, and J. Jatakia)

[4] Detecting Skin Colors under Varying Illumination (Authors: Leyuan Liu, Rui Huang, Saiyong Yang, Nong Sang)

[5] Efficient Skin Detection Under Severe Illumination Changes and Shadows (Authors: Bishesh Khanal, Désiré Sidibé)

[6] Real-Time Skin Color Detection under Rapidly Changing Illumination Conditions (Authors: Leyuan Liu, Nong Sang, Saiyong Yang and Rui Huang)

[7] Skin Classification with Deep Learning. (cs.stanford.edu) - macmillan publishers limited, part of springer nature

[8] Fusion Technique for Human Skin Detection (Authors: Mr. Shoeb I. Shaikh, Dr. Manjush a Deshmukh) - International Journal of Engineering Research & Technology (IJERT) ISSN: 2278-0181

[9] A Fusion Approach for Efficient Human Skin Detection (Authors: Wei Ren Tan, Chee Seng Chan, Pratheepan Yogarajah and Joan Condell ) - Accepted In Ieee Transactions On Industrial Informatics, Vol.8(1), Pp. 138-147

[10] Face detection based on skin color (Author: Henning Arthur )

[11] Skin Detection - a Short Tutorial(Authors: Ahmed Elgammal, Crystal Muang and Dunxu Hu ) Department of Computer Science, Rutgers University, Piscataway, NJ, 08902, USA

[12] Adaptive Skin Detection Under Unconstrained Lighting Conditions Using A Bigaussian Model And Illumination Estimation (Authors: Jian-Hua Zheng, Chong-Yang Hao, Yang-Yu Fan And Xian-Yong Zang ) - Image Anal Stereol 2005;24:21-33 Original Research Paper

### CONTRIBUTING

Please read [CONTRIBUTING](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

### LICENSE

This project is licensed under the MIT License - see the [LICENSE](https://github.com/AbhishekMali21/HUMAN-SKIN-DETECTION-USING-DIFFERENT-COLOR-SPACES/blob/master/LICENSE) file for details
