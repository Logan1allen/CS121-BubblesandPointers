# CS121-BubblesandPointers
##Main
#include <stdio.h>
const int MAX=9;

void printValues(int*);
void sort(int*);
void swap(int*, int*);

defines the array as values
prints the values

//test swap
defines ints x and y
prints the values of x and y
use the swap command with parameters x and y
prints the swapped values of x and y

sort with parameter values
prints after
prints the final verison of the sorted line 

returns 0


##printValues
takes an int pointer representing the array
step through the arry with a for loop
    print each number in the array
print new line
return void

##Swap
takes two int pointer parameters
make a temporary integer called temp
copy the value of a to temp
copy the value of b to a
copy temp to the value of b
return void

##sort
Use Bubble sort on the array
constant MAX is max length of array
function sort (array):
    create integer variables i and j
    for i from zero to MAX - 1:
        for j from zero to MAX - 1:
            if array[j] > array[j+1]:
                swap array[j] with array[j+1]
                printArray(array)
