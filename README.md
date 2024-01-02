# Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
i)	#Selection Sort
```
Program to sort the elements in the list using the Selection Sort algorithm.
Developed by: NAINA MOHAMED Z
RegisterNumber:23010605 
'''
def selection_sort(array,size):
    for ind in range(size):
        min_index=ind
        for j in range(ind+1,size):
            if array[j]<array[min_index]:
               min_index=j
        (array[ind],array[min_index])=(array[min_index],array[ind])
arr=eval(input())
size=len(arr)
selection_sort(arr,size)
print(arr)
    



```
ii)	#Insertion Sort
```
''' 
Program to sort the elements in the list using the Insertion Sort algorithm.
Developed by: your name
RegisterNumber: 
'''
def selection_sort(array,size):
    for ind in range(size):
        min_index=ind
        for j in range(ind+1,size):
            if array[j]<array[min_index]:
                min_index=j
        (array[ind],array[min_index])=(array[min_index],array[ind])
arr=eval(input())
size=len(arr)
selection_sort(arr,size)
print(arr)





```

## Output:
![image](https://github.com/nainamohamed09642/Sorting-Algorithm/assets/151916360/46efce89-de3f-443c-89d5-85d3e69b6a0f)
![image](https://github.com/nainamohamed09642/Sorting-Algorithm/assets/151916360/3dc725ab-6599-436f-8b46-3b9ef43da0ce)



## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
