Download Link: https://assignmentchef.com/product/solved-creating-2-arrays
<br>
In this program you will be creating 2 arrays – one will have values input into it, the second will be used to store values from the first array that are divisible by X (where X will be input).   Both arrays will be ints.

Part 1.

The main program should have 2 arrays both set to a maximum of 20 elements.   (The number of elements should be set to a const for easy changing.)

The purpose of part 1 is to fill the first array with values.   The user will enter how many elements should be entered and then call a function to fill the array.  Be sure the array won’t go out of bounds. After the number of elements has been input output a newline;

Once you have come back to the main program you will call a print function that will output the contents of the array – one element on each line.

The input function (do NOT call this function input). The function should take an int array and number of elements that will be input as an int, and an int indicating the maximum size of the array. It will return nothing.      Also, after all values have been input output a newline.

The output function (do not call the function output) will accept an int array and the number of element in the array as an int. It returns nothing.   Do not allow the function to change the values in the array passed in.

Part 2.

In part 2, in the main program asks the user to enter a value to check as a divisor.   The value will then be passed to a function along with both arrays. If the value in the first array (filled in function 1 above) is exactly divisible by the divisor value passed in then the value is to be stored in the second array.

The divisor function take the following parameters:   Two integer arrays followed by an int indicating how many elements are in the first array.   The first array should not be changed. There will be a second int passed in which is the divisor value previously entered. The function will return the number of elements in the second array.

There are two more functions required by this part. A function that returns the maximum value of an int array, and a function that returns the minimum value of an int array. Both functions are passed the array and an integer indicating the number of elements in the array. Do not allow the array to be changed. The maximum or minimum is returned respectively.

The print function from part 1 will no longer print the original array – in this part it should now print the divisor filled array followed by the min and max.