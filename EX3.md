# Ex.No:3

# Ex.Name: Write the quickSort module of Quick Sort in CPP.

## Date:

## Aim:
To write a C++ function that implements the Quick Sort algorithm using the divide-and-conquer approach, where the array is recursively partitioned around a pivot element and sorted.

## Algorithm:
Step 1: Start the function quickSort(array, low, high).

Step 2: Check if low < high. If false, stop because the subarray is already sorted.

Step 3: Call the function partition(array, low, high) to obtain the pivot index pi.

Step 4: Recursively call quickSort(array, low, pi - 1) to sort the left subarray.

Step 5: Recursively call quickSort(array, pi + 1, high) to sort the right subarray.

Step 6: Continue recursion until all subarrays are sorted.

Step 7: End the process when the entire array becomes sorted.




## Program:
```
void quickSort(int array[], int low, int high) 
{
    if(low<high)
    {
        int pi = partition(array,low,high);
        quickSort(array,low,pi-1);
        quickSort(array,pi+1,high);
    }
}
```



## Output:
<img width="1067" height="300" alt="{5D4E5C99-1EAD-4F03-879F-723241ED514B}" src="https://github.com/user-attachments/assets/602b2a0c-8e68-4c7c-82df-5940daaca499" />



## Result:
The given array is successfully sorted in ascending order using the Quick Sort algorithm.
