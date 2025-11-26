# Ex.No:1

# Ex.Name: Write a CPP Program to get the elements of an Array which needs to be sorted using insertion sort.

## Date:

## Aim:
To read elements of an array from the user and sort the array using Insertion Sort in C++.


## Algorithm:
STEP 1: Start the program.

STEP 2: Read n elements into the array using input(arr[]).

STEP 3: Consider the first element as sorted.

STEP 4: Pick the next element from the unsorted portion.

STEP 5: Compare it with elements in the sorted portion and shift all greater elements one position to the right.

STEP 6: Insert the picked element at the correct position in the sorted portion.

STEP 7: Repeat Steps 4–6 for all remaining elements.

STEP 8: The array becomes fully sorted.

STEP 9: Display the sorted array.

STEP 10: End the program.




## Program:
```
void input(int arr[])
{
    for(int i=0;i<5;i++)
    {
        cin>>arr[i];
    }
}
```


## Output:
<img width="783" height="460" alt="{018A633A-12B2-4583-8C98-971B86215825}" src="https://github.com/user-attachments/assets/4bdac034-8d06-4e8b-a16b-3f3aa1c8959b" />



## Result:
The program outputs the sorted array in ascending order.


