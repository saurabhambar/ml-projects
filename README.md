# Machine Learning Projects

### Breast Cancer Classification
- Business Understanding:
    - How to classify tumors into malignant or benign
    - **Benign** tumors are non-cancerous, slow-growing, and don't spread across body.
    - **Malignant** tumors are cancerous, grow rapidly, and can invade surrounding tissues and spread to other body parts.
    - ML Techniques can improve the accuracy of diagnosis.
    - Research indicates that the most experienced physicians can diagnose cancer with 79% accuracy, while 91% correct diagnosis is achieved using ML techniques.
    - In this case study, we classify tumors into malignant or benign tumors using features obtained from several cell images.
    - <img width="580" alt="image" src="https://github.com/user-attachments/assets/4cd0665a-e182-4de5-ba4f-641e53805b11" />
        - The First Step is Fine Needle Aspirate(FNA), extracting some cells out of the tumor.
        - At this stage, we don't know if the tumor is malignant or benign.
        - The upper image is malignant, below image is benign.
    - We extract the features from the images, such as characteristics like radius, texture, perimeter, area, smoothness, and so on.
    - Feed this feature into the machine learning model to classify images or data to categorize into malignant or benign.
- ML
    - We have images acquired using the FNA technique. - We extract 30 features indicating radius, texture, area, and smoothness.
    - All dataset is done. - We have 30 features; we have to feed these into the ML model to classify.
    - <img width="1181" alt="image" src="https://github.com/user-attachments/assets/620bcda8-e26b-4db6-9c94-b82f636f7cd5" />
    - The technique we use is Support Vector Machines
    - Lets say out of 30 features, we have feature 1 on the x-axis and feature 2 on the y-axis.
        - On plotting the records, blues are malignant, and reds are benign.
        - Now we want the machine learning strategy or technique to separate the two classes. - Draw the line between the two.
        - <img width="1173" alt="image" src="https://github.com/user-attachments/assets/eae35735-f84e-4012-9d9b-3bf062a58d66" />
        - There will be multiple ways to draw the lines - the objective of the traning the model using svm method is to find the best line that seperate both the classes.
        - The best line reply mainly on the two red and blue close points - supported vectors.
        - <img width="1051" alt="image" src="https://github.com/user-attachments/assets/8db32c4b-2a64-4dd5-b77a-e9e6d7d5ca6d" />
        - That line is called **maxium margin hyperplane** - hyperplane or the line that seperate the two classes.
        - In order to get this line, we use distance called as **Maximum Margin Distance**. That's the Objective of SVM is to find or maximize that **Maximum Margin Distance** using the supported vector points.
        - Support Vectors are the points that we assume that these points are the kind of on boundary or the grey area - Not fully malignant or benign.
     
------------------------------------------------------------------------------------------------------------------------------------------------------
 
 

