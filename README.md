# Episode-4
 How Computers Vision Works? – Let’s Harvest Some Tomatoes!

# Introduction

In this episode, we delve into the workings of computer vision—how computers process images and extract meaningful information from them. We explore the intricate process through which computers understand and interpret visual data. Specifically, we focus on the journey of image processing within a computer and the crucial information it leverages to make informed decisions. Additionally, we implemented a Machine Learning model called Support Vector Machine (SVM) for image classification. Our objective? To classify tomatoes!

# How Computers Process Images and Extract Information for ML Models

Essentially, computers fundamentally comprehend numbers. Every image comprises pixels, each with its own RGB (Red, Green, Blue) or grayscale distribution. Regardless of the task at hand, the initial step involves processing each image to facilitate algorithmic interpretation. The accompanying diagram provides a visual framework to enhance understanding:

![Diagrama en blanco - Página 1](https://github.com/user-attachments/assets/1d36d439-d549-4b4a-bc8e-531070406bb1)

# How Support Vector Machine works?

Support Vector Machines (SVMs) are like smart lines or curves that computers use to separate different groups of points in a special space where each point has lots of numbers (like coordinates). The goal is to draw a line or curve (called a "hyperplane") that maximizes the space between groups of points. This helps the computer decide where new points belong, like determining if a new picture of a tomato looks more like a good tomato or a bad one based on the numbers it knows about other pictures.

![Diagrama en blanco - Página 1 (1)](https://github.com/user-attachments/assets/869a6025-ab3a-4996-a991-a32e34cdaa0a)

# Our Model

During the training process, Support Vector Machines (SVMs) adjust their decision boundaries (lines or curves) to best separate different groups of points in the data. As the SVM learns from examples, it fine-tunes these boundaries to achieve optimal performance. This rigorous tuning can lead to impressive results, such as correctly classifying new images with 100% accuracy, even if the algorithm has never encountered those specific images before. SVMs excel at generalizing from the patterns they learn during training, allowing them to make accurate predictions on unseen data based on their understanding of similar examples.

![image](https://github.com/user-attachments/assets/b6935286-96a9-44b6-902a-ef835d33575a)
