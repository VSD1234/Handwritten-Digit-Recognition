# Handwritten-Digit-Recognition
This project is an extension to the previous MNIST handwritten digit recognition project.
In this project, I have created a tkinter application in which we can draw digits with the help of mouse, and by clicking on "identify" button, it will try to identify the digit that you have drawn.
I have created 3 models for this purpose:
  1) ANN using only numpy and pandas
  2) ANN using pytorch
  3) CNN using pytorch
The model which uses CNN gives the most consistent results of all three.
You can open any of those three files and run all the cells and one tkinter window will open which will let you draw any digit. After a successfull or unsuccessfull identification, you can either re-run the identification or clear the screen to try with any other digit.
If you are getting consecutively wrong results then please close the tkinter window and rerun the last cell.
Note: The output of the last cell is the guess of the algorithm.  
