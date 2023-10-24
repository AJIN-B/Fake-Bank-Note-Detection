# Fake-Bank-Note-Detection

A "Fake Bank Note Detection using K-means Clustering" project aims to build a system
that can identify counterfeit banknotes using the K-means clustering algorithm. 
This project leverages machine learning and pattern recognition techniques 
to differentiate genuine banknotes from counterfeit ones based on various features
extracted from images of the banknotes. Below is a detailed explanation of the project

---

## Project Overview
The Fake Bank Note Detection project involves the application of the K-means 
clustering algorithm to classify banknotes into genuine or counterfeit categories 
based on certain features extracted from images. 

### Dataset Description

Dataset link : [Download](https://archive.ics.uci.edu/ml/datasets/banknote+authentication)
In here we used a dataset that have 1372 entries of fake and normal banknote.
Data were extracted from images that were taken from genuine and forged banknote-like 
specimens. For digitization, an industrial camera usually used for print inspection 
was used. The final images have 400x 400 pixels. Due to the object lens and distance 
to the investigated object gray-scale pictures with a resolution of about 660 dpi were 
gained. Wavelet Transform tool were used to extract features from images.
•	V1 represents variance of Wavelet Transformed image (continuous).
•	V2 represents  skewness of Wavelet Transformed image (continuous).
•	V3 represents  curtosis of Wavelet Transformed image (continuous).
•	V4 represents  entropy of image (continuous).
•	Label represents class .
There are 762 normal banknote and  610 fake banknote.


### The project typically involves the following key steps

1. **Data Collection:** Gather a dataset comprising features extracted from images of genuine and counterfeit banknotes. 
The dataset should be labeled to distinguish between genuine and fake instances.

2. **Feature Extraction:** Extract relevant features from the banknote images that 
can effectively distinguish between genuine and counterfeit notes. 
These features could include aspects such as variance,skewness ,curtosis of Wavelet Transformed and entropy of image.

3. **Preprocessing:** Normalize and preprocess the extracted features to ensure 
they are on the same scale and format, enabling effective clustering.

4. **K-means Clustering:** Apply the K-means clustering algorithm to the preprocessed 
features. This algorithm groups the data points into clusters based on their 
similarities, thereby separating the genuine banknotes from the counterfeit ones.

5. **Model Evaluation:** Evaluate the performance of the K-means clustering model 
using metrics such as f1 score, recall and precision to assess the quality of the clusters 
and the effectiveness of the model in distinguishing between genuine and fake banknotes.

6. **Detection and Visualization:** Use the clustering results to detect counterfeit 
banknotes by examining the clusters' characteristics and visualizing the separation 
between the genuine and counterfeit banknotes.

**Benefits:**
- Automated detection of counterfeit banknotes.
- Enhanced security in banking and financial systems.
- Reduction of financial losses due to counterfeit money circulation.
- Quick and efficient decision-making for identifying counterfeit notes.

**Challenges:**
- Ensuring the availability of a comprehensive and diverse dataset for training the model.
- Achieving a balance between false positives and false negatives in the detection process.

**Applications:**
- Financial institutions and banks can use this system to verify the authenticity of banknotes.
- Government agencies and law enforcement bodies can employ the system to combat counterfeit money circulation.
- Retail businesses can use the system to safeguard against accepting fake currency.

A Fake Bank Note Detection project using K-means clustering represents an 
essential application of machine learning in ensuring the security and integrity 
of financial transactions and preventing economic losses due to counterfeit money.

### Basic Requirements:

- __[Python 3.8+](https://docs.python.org/3/)__
- __[scikit-learn](https://pypi.org/project/scikit-learn/)__ 
- __[matplotlib](https://pypi.org/project/matplotlib/)__ 
- __[Pandas](https://pypi.org/project/pandas/)__
- __[Numpy](https://pypi.org/project/numpy/)__ 
- __[mpl-tools](https://pypi.org/project/mpl-tools/)__ 
