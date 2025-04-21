# Contributors
- Jeremiah Webb (WebbJ31@my.erau.edu)
- Clay Pate
- Caleb Hall

# Summary
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/illusion173/CS555UAV/blob/main/CS555Proj.ipynb)

This project serves as a way to practice AI training, data ingestion and overall the lessons we learned in CS555.

To edit this project, either execute it in google colab using the link above, or download this repo locally.

## Editing
- Download and unzip the drone dataset from the kaggle link [below](#links) into a mounted google drive path as indicated in the first cell.
- View the sections of the code before any editing, instructions are often in the comments of each section.

## Usage
- Download and unzip the drone dataset from the kaggle link [below](#links) into a mounted google drive path as indicated in the first cell. (Root Folder of Google Drive)
- Execute the first cell to initialize the runtime and download libraries.
- Execute all Cells to demonstrate training and validation of the YoloV11 model.

## Editing Locally
- Clone this repo locally.
- Ensure to activate a Python virtual environment in Python3, install the required libraries as denoted by requirements.txt
- Edit the CS555Proj.ipynb file as needed.
- The model folder contains the physical models that we have trained.
- The data folder 

## Local Usage
- Clone this repo locally.
- Ensure to have all the needed libraries according to the second cell.

## Dataset
The dataset used are photos of rotary drones. We plan to use this dataset to train a model to assist with dodging other UAVs in the air.

## Ingestion Methodology
The ingestion is simple, since the dataset is already in YOLO format, all we need to do is organize the photos and labels into appropriate folders, as shown in the notebook.

## Model
We use the Yolo V11 Mini and xlarge model to demonstrate the performance difference and usability of the model in different situations. Nano for more lightweight workloads, xlarge for potentially demonstrating multiple drones.

### Links
[Drone Dataset Link (Kaggle)](https://www.kaggle.com/datasets/dasmehdixtr/drone-dataset-uav)
[Yolo V11 Model Link](https://docs.ultralytics.com/models/yolo11/)
