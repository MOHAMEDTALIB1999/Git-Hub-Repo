# Bubble sort algorithm 

We are Using bubble sort algorithm to sort a list of numbers.

## Description of the file 

Bubble Sort is the simplest sorting algorithm that works by repeatedly swapping the adjacent elements if they are in wrong order. in this programme we will use bubble sort to arrange an array of numbers into ascending order 
the aray of numbers is [19,2,31,45,6,11,121,27].

## Getting Started

### Dependencies

* pyhton is required to be install on your operating system. as this is the simplest algorithm. it does not have much dependencies.

### Executing program

*we need to type the program in python, and state the condition and the array.
*Step-by-step bullets
```
I.Type in the code to run bubble sort
 1.Define the bubble sort algorithm using:- 
def bubblesort(list):

 2.State the function to arrange the list in ascending order using:-
for iter_num in range(len(list)-1,0,-1):
      for idx in range(iter_num):
         if list[idx]>list[idx+1]:
            temp = list[idx]
            list[idx] = list[idx+1]
            list[idx+1] = temp
 3.Define the list:-
list = [19,2,31,45,6,11,121,27]

 4.Bubble sort the array
bubblesort(list)

 5.Print the result
print(list) 

II.Run the code 
```

## Help

The code should be correct. One can use any numbers in the list.

## Authors

ex. Mohamed talib

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [Git and GitHub for Beginners - Crash Course](https://www.youtube.com/watch?v=RGOj5yH7evk)
