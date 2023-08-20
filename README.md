# Attendance Management System using Face Rec Library

The Attendance Management System is a Python-based project aimed at automating the process of recording attendance using face recognition technology. This project utilizes various machine learning and computer vision algorithms to detect and recognize faces in images, and then generates an Excel sheet containing attendance records with corresponding names and dates.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Dependencies](#dependencies)

## Introduction

The Attendance Management System simplifies the attendance-taking process by leveraging the power of face recognition. It uses a pre-trained face recognition library along with other machine learning and computer vision techniques to identify and track individuals in images. The system is capable of comparing faces in the "known" folder (which contains a database of known faces with their corresponding names) against faces in the "unknown" folder (which contains images to be processed), and it generates an Excel sheet with attendance details.

## Features

- Face detection and recognition using the face recognition library.
- Automatic cropping of faces from input images.
- Comparison of detected faces with the known faces database.
- Generation of an Excel sheet with attendance records including names and dates.

## Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/kotharitanishka/attendance-management-system.git
```

2. Navigate to the project directory:

```bash
cd attendance-management-system
```

3. Open the `Attendance Management System.ipynb` file in Google Colab.

## Usage

1. Ensure you have the required images of known individuals saved in the "known" folder.
2. Place the images containing faces to be recognized in the "unknown" folder.
3. Run the code cells in the `Attendance Management System.ipynb` notebook.
4. The system will process the images, compare them against the known faces, and generate an Excel sheet with attendance details.

## Folder Structure

```
attendance-management-system/
│
├── known/
│   ├── person1.jpg
│   ├── person2.jpg
│   └── ...
│
├── unknown/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
│
└── Attendance Management System.ipynb
```

- The `known` folder contains images of individuals whose faces are recognized.
- The `unknown` folder contains images with faces to be identified.
- The `Attendance Management System.ipynb` is the main Colab notebook containing the project code.

## Dependencies

The project requires the following libraries:

- [face_recognition](https://pypi.org/project/face-recognition/)
- Other necessary libraries for image manipulation, data processing, and Excel sheet generation.
