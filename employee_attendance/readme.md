# Capstone Project Team 5
# Employee Attendance Checker

Basic functions of the product: It will take the attendance of the employees at the warehouse by camera. 
To do so, it continuously captures the real time image from the camera and after it recognizes the persons face it will save the name, 
picture and the time of the attendance and will send it to telegram for storage.

# Required packages to install:
<ul>
  <li> python version 3.9</li>
<li> to detect faces: cmake, dlib, face-recognition</li>
<li> to send telegram messages: telepot</li>
  </ul>
  
# How to add a person to database:
<ul>
<li> 1. Take a picture of the person</li>
<li> 2. Save the photo to images folder</li>
<li> 3. Add name of the person to the required spaces in compare_functions.py</li>
 </ul>

