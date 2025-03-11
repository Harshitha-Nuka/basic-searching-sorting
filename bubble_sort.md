# Bubble Sort

Bubble sort psuedocode

```
# Write the psuedocode 
START
function bubbleSort(arr):
    n = len(arr)
    for i in range(n - 1):  # Loop through the array n-1 times
        swapped = False  # Flag to check if any swaps occurred
        for j in range(n - i - 1):  # Compare adjacent elements
            if arr[j] > arr[j + 1]:  # If elements are out of order
                temp = arr[j]  # Swap elements
                arr[j] = arr[j + 1]
                arr[j + 1] = temp
                swapped = True
        if not swapped:  # If no swaps, array is sorted, break
            break
END
```
