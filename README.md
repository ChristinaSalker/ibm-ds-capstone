# IBM Advanced Data Science Capstone 

Skin Lesion Type Classification using the HAM10000 dataset


## Introduction to the Use Case

According to the [WHO](https://www.who.int/news-room/q-a-detail/ultraviolet-(uv)-radiation-and-skin-cancer), currently, between 2 and 3 million non-melanoma skin cancers and 132,000 melanoma skin cancers occur globally each year. One in every three cancers diagnosed is a skin cancer and, according to Skin Cancer Foundation Statistics, one in every five Americans will develop skin cancer in their lifetime.

If skin cancer is left untreated, it can metastasize and spread to other organs across the body, becoming a life-threatening condition. Early detection of skin cancer can make all the difference and save lives.

## Introduction to the Dataset

The HAM10000 dataset is a large collection of multi-source dermatoscopic images of common pigmented skin lesions. The dataset has originally been released by the authors [Tschandl et al. (2018)](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T).

**Description from the authors Tschandl et al. (2018)**

Training of neural networks for automated diagnosis of pigmented skin lesions is hampered by the small size and lack of diversity of available dataset of dermatoscopic images. We tackle this problem by releasing the HAM10000 ("Human Against Machine with 10000 training images") dataset. We collected dermatoscopic images from different populations, acquired and stored by different modalities. The final dataset consists of 10015 dermatoscopic images which can serve as a training set for academic machine learning purposes. Cases include a representative collection of all important diagnostic categories in the realm of pigmented lesions: 

*   Actinic keratoses and intraepithelial carcinoma / Bowen's disease (akiec)
*   Basal cell carcinoma (bcc)
*   Benign keratosis-like lesions (solar lentigines / seborrheic keratoses and lichen-planus like keratoses, bkl)
*   Dermatofibroma (df)
*   Melanoma (mel)
*   Melanocytic nevi (nv)
*   Vascular lesions (angiomas, angiokeratomas, pyogenic granulomas and hemorrhage, vasc). 

## Solution to the Use Case

Training a CNN in TensorFlow, built with a Keras Sequential model, to detect the seven classes skin cancer.





