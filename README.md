# sortified
Sortified is an interactive project built using Teachable Machine and web technologies, developed for a coding competition. It combines machine learning and a visual interface to make sorting concepts more engaging.

This project uses a custom-trained model from Teachable Machine to allow gesture or image-based input, adding a fun and intuitive way to interact with sorting algorithms. Whether you're learning about sorting or exploring how machine learning can be used creatively, Sortified offers a unique experience.

## 🔧 Built with:
Teachable Machine (Google)

I also made a website about it

## 🚀 Features:
ML model trained with Teachable Machine

Visual sorting algorithm demos

User interaction via gestures or webcam input (if supported)

Clean and responsive interface

Created as part of a coding competition challenge, Sortified focuses on innovation, accessibility, and fun.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### downloading the model

* A modern web browser (like Chrome, Firefox, Edge, Safari).
* You have to download sotified ai.tm, and to get the website you have to download all the other files.
* When you exported your model from Teachable Machine, you should have downloaded a `.zip` file. Extract this `.zip` file. You should find three files: `model.json`, `weights.bin`, and `metadata.json`.
* **Copy** these three files (`model.json`, `weights.bin`, and `metadata.json`) into the `my_model` folder in your project directory. Make sure you are copying the files *themselves*, not the original `.zip` file.

Your project folder structure should look something like this:

your-project-folder/
├── project.html
└── my_model/
├── model.json
├── weights.bin
└── metadata.json


## Running the Project

It's very easy to run the website locally:

1.  Open the `project.html` file directly in your web browser. You can usually do this by double-clicking the `project.html` file.
2.  Navigate to the "Live Demo" section.
3.  Click the "Start" button.
4.  Your browser will likely ask for permission to access your webcam. Grant the permission.
5.  The webcam feed should appear, and the model predictions will be displayed below it.

*Note: The live demo requires an internet connection to load the necessary libraries (TensorFlow.js and Teachable Machine) from content delivery networks (CDNs).* 

