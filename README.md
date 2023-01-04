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

 **3. WebApp Interface**
 
 - *Home page*
 
 
