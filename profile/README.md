![CentingApps Logo](https://github.com/Centing/CentingApps/blob/ver2/app/src/main/res/drawable/centing_logo2.png)

# CentingApps

CentingApps is an application project inspired by the fact that Indonesia have a large problem of stunting. It is created to face the problem by making it easier to test or detect if the person is stunting or not without actually needed to go to public health center or hospital with a heavy fee. To do so we applied not only the cloud computing side but also the machine learning side of technology.

## Features

- Detect Stunting
- History
- Separated data for each child
- Language English/Indonesia



## Technical Details

**Mobile Application**

The mobile application is made starting by the UI/UX using platform figma creating the Lo-Fi and Hi-Fi model, which then implemented using native Kotlin Android by utilizing supporting libraries such as Retrofit, Tensorflow, etc. 
![CentingApps Flowchart](https://github.com/CentingApps/.github/blob/main/%5BC241-PS220%5D%20-%20Flowchart%20Capst%20Stunting.drawio_page-0001.jpg)

**Cloud Computing**

<!--dijelasin pake apa apanya terus tambahin cloud architecture sama database structurenya sama link reponya apa aja boleh di masukin disini-->

**Machine Learning**

<!--dijelasin model machine learning stunting kita kayak gimana apa aja hasilnya dll.-->
This repository contains a machine learning-based solution for predicting the nutritional status of children (stunting) and providing recommendations based on the predictions. The model is trained on a dataset containing information about children's age, gender, height, and nutritional status.

**Stunting Detection**

The stunting detection in this system uses an artificial neural network model to classify a child's nutritional status based on age, gender, and height. The model is trained using a dataset that includes these variables and is then tested with a separate dataset to evaluate the detection accuracy. This system identifies the child's nutritional status into categories of 'normal', 'stunted', or 'severely stunted'. These detections help determine whether the child is in a healthy nutritional state or requires further intervention to improve their nutritional status. If a child is classified as 'stunted' or 'severely stunted', the system also provides nutritional and health recommendations to help the child achieve the ideal height according to their age and gender.

**Personalized Nutritional and Health Recommendations**

The recommendation feature in this system is designed to provide actionable guidance for improving or maintaining a child's nutritional status based on the detection results. If the system detects that a child is 'stunted' or 'severely stunted', it offers specific recommendations to help the child grow to an ideal height for their age and gender. These recommendations include:

* Nutritional Advice: Suggestions for providing exclusive breastfeeding for the first 6 months, introducing nutrient-rich complementary foods, ensuring adequate intake of vitamins and minerals, and maintaining regular meal schedules.
* Health and Hygiene: Emphasis on clean drinking water, maintaining personal and environmental hygiene to prevent infections, and ensuring the child receives all necessary immunizations.
* Regular Health Monitoring: Encouraging routine health check-ups to monitor the child's growth and development.
* Developmental Stimulation: Recommendations for providing physical and cognitive stimulation through educational games and activities.
* Emotional Support: Advising parents to show love and attention to support the child's emotional development.
  
If the child is detected as 'normal', the system congratulates the parents and provides tips to maintain the child's good nutritional status, which includes continued breastfeeding, balanced nutrition, regular health check-ups, and developmental activities.

## Getting Started

**Mobile Application**

To get started with the mobile development, you can start by installing Android Studio. Then cloning this [repository](https://github.com/Centing/CentingApps) to your local computer.

**Cloud Computing**

<!--tutorial apa aja step yang perlu dilakuin sama masukin link bila diperlukan-->

**Machine Learning**

<!--tutorial apa aja step yang perlu dilakuin sama masukin link bila diperlukan-->

## Contributing
We welcome contributions to enhance the stunting prediction models and stunting recommendation system. If you have any ideas, bug fixes, or improvements, feel free to email us as been put in the bio.
