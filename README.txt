Project Title: Favicon Generator

----------
Table of Contents: 
1. Project Description
2. Dependencies
3. Setup 
4. How to Run The Converter
5. Credits


----------
1. Project Description

This python script creates a favicon website icon - it intakes a .png file and outputs a .ico file.


----------
2. Dependencies

Python 3.12
Pillow Library 10.1.0


----------
3. Setup

- Download the repository
- Create a virtual environment with the Pillow (Python Imaging Library) library
  - Open a new powershell terminal (Windows)
  - cd to the folder that you want the virtual environment in
  - run: python -m venv Favicon-Generator-Virtual-Env
- Update the run-generator.bat file to have the correct virtual environment path


----------
4. How to Run the Generator: 

- Save a .png file to the project folder
  * Note: make sure there are no other .png files in the folder
- Double-click the 'run-generator.bat' file
- The favicon will appear in the project folder (of file type .ico)
  * Note: This converter will not resize the image, so make sure the input file has the correct dimensions (recommended: 32px x 32px)


----------
5. Credits

Michelle Flandin