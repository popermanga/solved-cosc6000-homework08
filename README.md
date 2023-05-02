Download Link: https://assignmentchef.com/product/solved-cosc6000-homework08
<br>
Develop a function that defines a 2­dimensional array of type ‘double’. Also develop a function to destroy the array.

Two functions should make following test code to work.

Example output:

https://tulane.instructure.com/courses/2165899/assignments/13467400                                                                                                                                   1/2

As you see in the code, it assigns numbers to mat2d[i][j], but doesn’t assign anythig to vect[i]. As you see in the example output, ‘mat2d’ and ‘vect’ have same values; ‘vect’ is a reshaped array of ‘mat2d’ in row­order. This is because ‘mat2d’ and ‘vect’ share a same memory block. Your function, makeDoubleArray2D() should previde this mechanism. Your function, destroyDoubleArray2D() frees the arrays allocated by makeDoubleArray2D().