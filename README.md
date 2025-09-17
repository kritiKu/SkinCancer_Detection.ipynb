# SkinCancer_Detection.ipynb

Abstract
Skin cancer is one of the most common forms of cancer, with more than two hundred different types identified by medical research. Among these, melanoma is considered to be the most dangerous and life-threatening if left untreated. Fortunately, it is highly curable when detected at its early stages. The conventional diagnostic approach involves an initial clinical screening of the skin lesion, followed by dermoscopic imaging and finally a histopathological biopsy. Dermatoscopic imaging alone has an accuracy of about 65 to 80 percent, which improves up to 84 percent when examined by trained dermatologists. However, despite the accuracy, the process is time-consuming. A biopsy report may take a week or longer, during which patients often remain anxious and untreated. This project makes an attempt to shorten this diagnostic gap through an automated classification system based on deep learning techniques, designed to detect skin cancer directly from dermoscopic images.
Problem Statement
In the skin biopsy, the dermatologist takes some part of the skin lesion and examines it under the microscope. The current process takes almost a week or more, starting from getting a dermatologist appointment to getting a biopsy report. The aims to shorten the current gap to just a couple of days by providing the predictive model. The approach uses Convolutional Neural Network (CNN) to classify nine types of skin cancer from outlier lesions images. This reduction of a gap has the opportunity to impact millions of people positively.

Motivation
The overarching goal is to support the efforts to reduce the death caused by skin cancer. The primary motivation that drives the project is to use the advanced image classification technology for the well-being of the people. Computer vision has made good progress in machine learning and deep learning that are scalable across domains.

Dataset
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images.
