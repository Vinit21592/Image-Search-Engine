# Image-Search-Engine
## About:
This is a demo project on how to build an image retrieval using python. This project uses the concept of content-based image retrieval.

## Content-Based Image Retrieval:
Content-based image retrieval (CBIR) is a system for retrieving relevant images based on a given image. The system consists of an image query and an image database.
The process of the system will begin by extracting features on all images, whether it’s the query or the image database by using a feature extraction algorithm. Then, the system will calculate similarities between the query with all images on the database. At the end, the system will retrieve all the images that have a great similarity with the query.

## Flowchart of the CBIR:
![Flow of the CBIR](https://user-images.githubusercontent.com/78821357/135757973-9ac4193b-ece0-409b-80f8-14e414360e9a.JPG)

## Workflow:
![Flow](https://user-images.githubusercontent.com/78821357/135760220-2738ace9-3ca1-4d23-a046-4d5e35a7d970.JPG)

## Implementation:
To implement the CBIR, we will use Python as the programming language, Tensorflow for feature extraction, and Numpy for calculating the distance. If we summarize, here are the steps that we will do,
Download the dataset
Extract features from image database
Insert the query image and extract its features
Calculate the similarities with all images
Retrieve the most similar result
