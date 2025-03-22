# Kaggle Team Lactic Acid: Algorithmic Justice League : Dermatology AI

---

### **👥 Team Members**

| Name | GitHub Handle | Contribution |
| ----- | ----- | ----- |
| Samantha Nadler | @samanthanadler  | Built CNN model, performed data augmentation, created image generators |
| Keerthana Talla | @ |  Add info here   |
| Debasree Sen | @ | Add info here |
| Pooja Garlapati | @pogarla3 | Set up Codebase, Image Preprocessing, Built CNN backbone
| Cindy Su |  @ |  Add info here | 
| Benine TAYEB | @ | Add info here |


---

## **🎯 Project Highlights**

* Built a RCNN model using Keras and Pytorch to solve \[Equitable AI for Dermatology\]
* Achieved an F1 score of \[insert score\] and a ranking of \[insert ranking out of participating teams\] on the final Kaggle Leaderboard
* Used \[explainability tool\] to interpret model decisions
* Implemented \[data preprocessing method\] to optimize results within compute constraints

🔗 [Equitable AI for Dermatology | Kaggle Competition Page](https://www.kaggle.com/competitions/bttai-ajl-2025/overview)
🔗 [WiDS Datathon 2025 | Kaggle Competition Page](https://www.kaggle.com/competitions/widsdatathon2025/overview)

---

## **👩🏽‍💻 Setup & Execution**

* How to clone the repository\
  * ` git clone https://github.com/wallaweebs/DermatologyAI.git `
* How to set up the environment\ 
  Option: If you have conda:
  * `conda create --name pref_name`
  * `conda activate pref_name`
* How to access the dataset(s)  <a href="https://colab.research.google.com/drive/16LFhaqD3kE0ysUlQa5ci7FTxmX-U6hH-">Set up Dataset</a>  

---

## **🏗️ Project Overview**

*This project is part of a Kaggle competition by Break Through Tech AI and the Algorithmic Justice League, focused on building an inclusive ML model to classify 21 skin conditions across diverse skin tones.
*The challenge addresses the issue of biased dermatology AI tools that often underperform on darker skin, leading to diagnostic disparities.
* Our goal is to improve model performance and in turn, improve fairness and equity in healthcare.

---

## **📊 Data Exploration**

* The dataset(s) used 21 different classes of skin conditions across various parts of body on a variety of skin tones. 
* We noticed that Data exploration and preprocessing approaches
explore all csv files, observe commonalities, further understanding of expectations
First visualizing the dataset through discussion understanding how we can traverse through and filter through
maybe put double array for training to go through each folder/dataframe
we need to go into the specifics of each skin conditions (symptoms, causes, demographic, etc) relation of partion labels creates a connection with the other symptoms using the scale (similar w/ fitzpatrick)

* Challenges and assumptions when working with the dataset(s)
Understanding our Data: create a document of all the skin conditions we will work with and list their features. (might help with feature engineering on the long run)
Time management: understanding the limits as to how far we can train and run our model through different weights throughout this program
Model Performance: being cautious of our model’s access throughout the dataset and tweaking certain hyperparameters for it to generalize better and prevent overfitting or high bias. 

**Potential visualizations to include:**

* Plots, charts, heatmaps, feature visualizations, sample dataset images


---

## **🧠 Model Development**

* Model(s) used
CNN with transfer learning, regression models, ResNet, Yolo

* Feature selection and Hyperparameter tuning strategies

* Training setup (e.g., % of data for training/validation, evaluation metric, baseline performance)
Focused on Sklearn’s test_train_split method: 65% train, 15% validate, 20% test
---

## **📈 Results & Key Findings**

* Performance metrics (e.g., Kaggle Leaderboard score, F1-score)
* How your model performed overall
* How your model performed across different skin tones (AJL)
* Insights from evaluating model fairness (AJL)



**Potential visualizations to include:**
* Confusion matrix, precision-recall curve, feature importance plot, prediction distribution, outputs from fairness or explainability tools

---

## **🖼️ Impact Narrative**

**AJL challenge:**

As Dr. Randi mentioned in her challenge overview, “Through poetry, art, and storytelling, you can reach others who might not know enough to understand what’s happening with the machine learning model or data visualizations, but might still be heavily impacted by this kind of work.”
As you answer the questions below, consider using not only text, but also illustrations, annotated visualizations, poetry, or other creative techniques to make your work accessible to a wider audience.
Check out [this guide](https://drive.google.com/file/d/1kYKaVNR\_l7Abx2kebs3AdDi6TlPviC3q/view) from the Algorithmic Justice League for inspiration!

---

## **🚀 Next Steps & Future Improvements**
Throughout our model training, we noticed that our model would perform better (a higher accuracy) towards some skin conditions vs others. We see that there is a certain bias for the variety of models considered to accurately detect 1-2 skin conditions out of the 21 classes. We see that could be due to the limited access to the dataset, the variety of features considered or our hyperparameter metrics. 
We would like to have done more data augmentation and preprocessing techniques working with this dataset to have a better understanding of our constraints or new model considerations.  
We hope to explore several similar datasets that explore various skin conditions and with multiple classes. This new challenge shows how much 

---

## **📄 References & Additional Resources**

* https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10690980
* https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10342692
* https://arxiv.org/html/2401.13280v1




















