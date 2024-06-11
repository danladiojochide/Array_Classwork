GROUP MEMBERS:
JOHN MANAYI GOODNESS	        BHU/23/04/09/0092
DANLANDI QUEEN MARVELLOUS	BHU/23/04/05/0096
NZE  KELECHI  EMMANUELLA	BHU/22/04/05/0089
KUMDET   KYENPIA   FAVOUR	BHU/22/04/05/0093
UBONGABASI  DEBORAH  OFFIONG	BHU/22/04/05/0085

ARRAY CLASSWORK

1. We created a java class named "Rotate" and also import Arrys from java util to allow us to use array

2.We created an int method named 'rotLeft' given it two paramer of int namely a and d

3.Inside the method we created another variable of int n to get the lenght of the parameter 'a' and the parameter 'd' was assigned the value of the remainder of the int d with a.length

4.We creates an array of int with the same length as the original array a to store the elements after the left rotations. This new array is essential for holding the final rotated value without modifying the original array.

5.We created a for loop to iterates over each element in the original array, calculates its new position after d left rotations using the formula (i + n - d) % n, and assigns the element to this new position in the rotatedArray. This approach ensures that all elements are correctly repositioned, resulting in the rotated array.

6. then we returned the rotatedArray calling it in the main method of our class by given it two parameter to work with 'a' the list of arrays then 'd' the number of times it is to rotate the array given in 'a'
