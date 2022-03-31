# Fall-Detection-Title (we haven't decided the title name yet).

In this project, I will carry out a further work that have been proposed in [previous project](https://github.com/hoangNguyen210/Fall-Detection-Project-/blob/main/README.md) 
Due to our work haven't been done yet, I will just update our proposed method as well as our result. Our code will be updated after submiting. 
<!-- In this repository, you'll be able to find the python programs written in Jupyter Notebook used for the **Fall Detection Title*.  -->


## Acknowledgements
- This project was also a part of my **Graduate Thesis** subject at university.
- This project was inspired by 2 of my teachers at HCMUS: Thao. V Ha and Binh Nguyen et. al
- My main responsibilities in this project were implementing code, visualization, and writing a paper.
- Our teacher helped me correct my writing mistakes and submitted the paper.



## Project Status
Project is:  _in progress_. Our goal is to submit to ISI Q1 Journal. Currently, I have finished our experiment proccess and currently writting a paper. 

## System requirement 
- numpy - version 1.0
- pandas - version 2.0
- tensorflow - version 3.0
- keras - version 
- sklearn - 

**Here is the short form of our paper.** (I changed the pictures of some models for my presentation at Seminar)
## Table of Contents
<!-- * [Acknowledgements](#acknowledgements) -->
* [Introduction](#introduction)
* [General Info](#general-information)
* [Dataset description](#dataset-description)
* [Data preprocessing](#d-p)
* [Proposed method](#proposed-method)
* [Result](#result)
* [Conclusion and Furture Work](#cc)
* [Room for Improvement](#room-for-improvement)
* [Contact](#contact)

<a name="introduction"></a>
## Introduction
<a name="general-information"></a>
## General Information
<a name="dataset-description"></a>
## Dataset description
- You can download UP-Fall Detection dataset in this [link](https://sites.google.com/up.edu.mx/har-up/) . This dataset includes over 850 GB of data from wearable sensors, ambient sensors, and vision equipment. 17 young healthy people with age ranging from 18–24 years old were invited to perform 11 different activities. Here is the summary of activities. 

| Activity ID | Description  | Duration (s)  |
| :-----:     | :-:          | :-:           |
|     1        | Falling forward using hands          | 10           |
| 2     | Falling forward using knees          | 10           |
| 3    | Falling backwards         | 10           |
| 4     | Falling sideward          | 10           |
| 5     | Falling sitting in empty chair         | 10           |
| 6     | Walking          | 60           |
| 7     | Standing         | 60           |
| 8     | Sitting          | 60           |
| 9     | Picking up an object         | 10           |
| 10     | Jumping          | 30           |
| 11     | Laying          | 60           |

|![Location of measure device](./img/location.png)|
|:--:| 
| *Location of measurement devices* |
<!-- If you have screenshots you'd like to share, include them here. -->
You can read more about this dataset at this [paper](https://www.mdpi.com/1424-8220/19/9/1988).

<a name="d-p"></a>
## Data preprocessing :


<a name="proposed-method"></a>
## Proposed methods :
<a name="result"></a>
## Result 
<!-- | Data | Model  | Accuracy  | Precision | Recall | F1-Score |
|---------------|-----------|-----------|--------|----------|
| S | XGBoost <br> CatBoost <br> MLP  |  | 99.21 <br> 99.05 <br> 99.04 <br> | 99.19 <br> 99.02 <br> 99.05 <br> | 99.21 <br> 99.05 <br> 99.03 <br>| 99.20 <br> 99.02 <br> 99.03 <br> | -->

- Performance of our proposed method for each dataset :

| Data | Model  | Accuracy  | Precision | Recall | F1-Score |
| :-----:     | :-:          | :-:           |  :-:           |  :-:           |  :-:           |
|     **S**        | XGBoost <br> CatBoost <br> MLP <br> | 99.21 <br> 99.05   <br>  99.04 <br>     | 99.19 <br> 99.02 <br>  99.05 <br>         | 99.21 <br> 99.05 <br> 99.03 <br> |99.20 <br> 99.02 <br> 99.03 <br> |
| **C1** | CNN | 99.17  | 99.24 | 99.12 | 99.16 |
| **C2** | CNN | 99.39  | 99.40 | 99.39 | 99.40 |

- Comparing with performance using Martinez's model :

| Data | Model  | Accuracy  | Precision | Recall | F1-Score |
| :-----:     | :-:          | :-:           |  :-:           |  :-:           |  :-:           |
|     **S**        | RF <br> SVM <br> KNN <br> MLP | 97.46 <br> 96.96   <br>  97.24 <br> 90.21 <br>     | 97.29 <br> 96.82 <br>  97.07 <br> 98.36   | 98.46 <br> 96.96 <br> 97.24 <br> 90.21 | 97.28 <br> 96.61 <br> 97.05 <br> 88.43 <br> |
| **C1** | CNN | 78.92 | 84.8 | 70.97 | 76.69 |
| **C2** | CNN | 88.24  | 90.32 | 86.13 | 86.96 |

- Combining dataset:

| Data | Model  | Accuracy  | Precision | Recall | F1-Score |
| :-----:     | :-:          | :-:           |  :-:           |  :-:           |  :-:           |
| **C1 + C2** | Combination | 99.47 | 99.46 | 99.47 | 99.46 |
| **C2** | Combination | 99.56  | 99.56 | 99.56 |99.55 |

<a name="#cc"></a>
## Conclusion and Future Work 
## Contact
Created by [hoangng210a@gmail.com] - feel free to contact me!

