# Ex.No:2

# Ex.Name: Write a CPP Program to print the sorted elements of the Array.

## Date:
## Aim:
To sort an array using insertion sort and print the sorted elements in ascending order in C++.

## Algorithm:
STEP 1: Start the program.

STEP 2: Read 5 elements into an array using cin.

STEP 3: Consider the first element as sorted.

STEP 4: Pick the next element from the unsorted portion.

STEP 5: Compare it with elements in the sorted portion and shift all greater elements one position ahead.

STEP 6: Insert the picked element at the correct position in the sorted portion.

STEP 7: Repeat Steps 4–6 until all elements are sorted.

STEP 8: Call the print() function to display the sorted array.

STEP 9: End the program.




## Program:
```
void print(int arr[])
{
    cout<<"After Sorting the Array: "<<endl;
    for (int i = 0; i < 5; i++)
    {
        cout<<arr[i]<<" ";
    }
}
```


## Output:
<img width="905" height="452" alt="{470435C4-88AB-4779-A56B-14A62FF95DB0}" src="https://github.com/user-attachments/assets/5c4fc2d1-f7b4-48f4-8251-024abf61326b" />



## Result:
The program outputs the sorted array in ascending order.


