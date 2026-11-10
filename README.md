# EGR-444-Workshop
***By Jasmine Morales, Joseph Ladino and Marck Torres***

## Repository Description

This repository is used for our **EGR444 - Advanced Machine Learning** course, and is used to show our fellow peers something new that we think will be useful for them when working on their final projects. It uses Google Colab to ease the process of not having to configure this workshop on our own machine. It also reduces friction for issues that could potentially arise when cloning and setting up the repository on our local machines.

## Workshop Concept
The purpose of this workshop is to use object detection annotations from COCO to demonstrate how automated testing can catch data errors before they affect a computer vision model. This ties into our final project using a robotic arm that relies on identifying objects and their locations to perform pick-and-place tasks. This will help us identify any errors in our data prior to us working with our computer vision model.\
We will be using the COCO dataset as an example, and use our .ipynb file for our hands-on portion of the class to demonstrate and have everyone work through it together.

## Instructions
1. Download the .ipybn file located in the Notebooks folder.
2. Open file in your google drive account (Do not need to have pro version).
3. Go through steps as a group (or individually if doing this alone).

## Google Colab Trouble Shooting Tips
*Troubleshooting Guidance*

**Problem: FileNotFoundError**\
Cause: CSV file cannot be located\
Solution: Check Google Drive shortcut and file path moutning location

**Problem: Drive already mounted**\
Cause: Drive was mounted in earlier cell\
Solution: Continue running through the notebook

**Problem: ModuleNotFoundError: pytest**\
Cause: pytest is not installed\
Solution: Run !pip install pytest -q  

**Problem: no tests ran**\
Cause: Test file or function is not named correctly\
Solution: Check filename and make sure function begin with test_

**Problem: Category ID test fails**\
Cause: An ID is not included in the valid COCO category set\
Solution: Check category ID against official COCO categories
