# Ex.No:4

# Ex.Name: Write the printArray Module of Merge Sort in CPP

## Date:

## Aim:
To write a C++ function printArray() that prints all elements of an array after performing Merge Sort.

## Algorithm:
Step 1: Start the function printArray(A, size).

Step 2: Initialize a loop variable i = 0.

Step 3: Iterate the loop from i = 0 to i < size.

Step 4: For each iteration, print the element A[i] with a space.

Step 5: After the loop ends, print a newline.

Step 6: End the function.




## Program:
```
void printArray(int A[], int size)
{
    for(int i=0;i<size;i++)
    {
        cout<<A[i]<<" ";
    }
    cout<<endl;
}
```


## Output:
<img width="959" height="316" alt="{09D450FE-217A-41DE-B598-DE72BB97E825}" src="https://github.com/user-attachments/assets/68350554-3c1b-483b-b4b4-4d645a5d2693" />



## Result:
The elements of the array are successfully printed after Merge Sort is performed.

