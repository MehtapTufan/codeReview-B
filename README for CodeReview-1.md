# Question
Write a C program to make some calculations with 2 defined 2D arrays. The 2D arrays should be created with 5x5 elements. 
Firstly, the user should enter a calculation type from shown menu which is given below: 
------Menu------ 
1-Addition 
2-Substraction 
3-Multiplication 
4-Division 
What is your selection?:

After that you need to ask for saving values into arrays as row based or column-based way. According to this decision you need to ask user to enter values 
for the elements of 2 arrays. Based on the menu selection, 3rd array values should be filled. Every calculation type listed in the menu should be done in different functions 
(ex. Add function should be called for addition, sub function should be called for subtraction and so on. In division results should be in decimal numbers.). 
While making calculation, 1st array’s first element and 2nd array’s first element should be used for 3rd array’s first element. Every element should be calculated with 
same logic. After calculation of 3rd array, there should be other calculations function in order to find the maximum, minimum and average values of 3rd array 
(which is created based on menu selection). For this function maximum, minimum and average values should be sent as parameters. 
Result of these values should be written on main function. In addition to that the 3rd array should be shown to user on the screen, 
but you need to ask user that if the user want to see resultant array elements’ as numbers or not. If the user says Y/y than you need to show numerical values of 
elements of 3rd array, but if user says N/n than you need to show ‘X’ for odd numbers and ‘O’ for even numbers, instead of showing the numerical values of the array.
