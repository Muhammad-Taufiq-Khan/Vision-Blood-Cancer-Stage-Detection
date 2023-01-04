# Vision - Blood Cancer Stage Detection using Image Processing
---
- Environment: [Blood Cancer Stage Detection Live WebAPP](https://blood-cancer-stage-detection.onrender.com)
- Tools: Python, Flask, Tensorflow-cpu, OpenCV, etc.
- Supporting Algorithm: MobileNet V2
---

 **1. Project Objective**

In this project we have diagnosed a type of blood cancer that is known as Leukemia. The most dangerous and deadly type of leukemia is acute lymphoblastic leukemia (ALL), which affects people of all age groups, including children and adults. In this project, we develop an automated system to detect various-shaped ALL blast cells from microscopic blood smears images using multiple Deep Neural Networks (DNN). The system can detect four stages of ALL by analyzing blood cells with an accuracy of 98 percent. Moreover, we have developed a telediagnosis software to provide real-time support to diagnose current stages from microscopic blood smears images. Applied algorithms are MobileNet V2, ConvNet, VGG19, and ResNet50.
  
**2. Expalaination of the directory tree**
```
- Notebooks       : Google colab notebooks and dataset to train the Machine Learning model.
- models_dump     : Saved/dumped best models's objects.
- static          : CSS, JavaScript, and image files.
- templates       : HTML pages to render.
- .gitignore      : Script to automaticallty ignore redundant files and directories during version control.
- main.py         : Python script to preprocess the upcoming data using preprocessing objects (dumped) and classify using dumped model.
- app.py          : Flask script to handle get and post requests.
- reqirements.txt : Required dependencies list with preferred version.
```

**3. Dataset Description**

We have used the Acute Lymphoblastic Leukemia (ALL) Image dataset. The images of this 
dataset were prepared in the Bone Marrow Laboratory of Taleqani Hospital 
(Tehran, Iran). This dataset consisted of 3256 peripheral blood smear (PBS) images from 
89 patients suspected of ALL, whose blood samples were prepared and stained by skillful 
laboratory staff, including 25 healthy individuals with a benign diagnosis (hematogone) and 
64 patients with a definitive diagnosis of ALL subtypes, Early Pre-B, Pre-B, and Pro-B 
ALL. This dataset is divided into two classes benign and malignant. The former comprises 
hematogenous and the latter is the ALL group with three subtypes of malignant 
lymphoblasts: Early Pre-B, Pre-B, and Pro-B ALL. All the images were taken by using a 
Zeiss camera in a microscope with a 100x magnification and saved as JPG files. A specialist 
using the flow cytometry tool made the definitive determination of the types and subtypes 
of these cells. After color thresholding-based segmentation in the HSV color space, dataset 
collectors also provide segmented images. Figure 3.1.1 - 3.1.4 depicts the images of Benign 
(hematogone) Cells, Early Pre-B ALL Cells, Pre-B ALL Cells, and Pro-B ALL Cells 
respectively.

![image](https://user-images.githubusercontent.com/70132613/210604781-0e333d2f-5cd9-4a04-8d33-6c69a052aec1.png)

***Fig. 3.1.1 Benign (hematogone) cells***

![image](https://user-images.githubusercontent.com/70132613/210604861-16ad7986-5be4-45fb-ac32-ce274d68cd43.png)

***Fig. 3.1.2 Early Pre-B ALL cells***

![image](https://user-images.githubusercontent.com/70132613/210604952-45a48329-894f-4821-81aa-4b622288d7ce.png)

***Fig. 3.1.3 Pre-B ALL cells***

![image](https://user-images.githubusercontent.com/70132613/210605239-7da9398f-73d7-47db-8882-d4283791a427.png)

***Fig. 3.1.4 Pro-B ALL cells***

**4. Method Workflow**

![image](https://user-images.githubusercontent.com/70132613/210605295-b16ff6d0-7284-4ea4-be04-6a08300c140c.png)



 **3. WebApp Interface**
 
 - *Home page*
 
 
