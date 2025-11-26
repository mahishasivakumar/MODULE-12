# Ex.No:5

# Ex.Name: Write the Greater than Module of Binary Search in CPP

## Date:
## Aim:
To write the GreaterThan() module in C++ that checks whether the middle element of an array is greater than the search element during Binary Search.

## Algorithm:
Step 1: Start the function GreaterThan(a, mid, search).

Step 2: Compare the value a[mid] with the search value.

Step 3: If a[mid] is greater than search, return 1.

Step 4: Otherwise, return 0.

Step 5: End the function.




## Program:
```
int GreaterThan(int a[], int mid, int search)
{
    if(a[mid] > search)
    {
        return 1;
    }
    else
    {
        return 0;
    }
}
```


## Output:
<img width="935" height="384" alt="{C5362D3B-356F-499C-96F2-ED6C3A003F22}" src="https://github.com/user-attachments/assets/cd6aa24d-55b8-4539-b599-cb606565c0f2" />

## Result:
The function successfully returns 1 when the middle element is greater than the search value, otherwise returns 0, helping the Binary Search algorithm decide the direction of search.

