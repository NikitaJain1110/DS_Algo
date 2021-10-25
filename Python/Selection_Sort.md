# What is Selection Sort?
SELECTION SORT is a comparison sorting algorithm that is used to sort a random list of items in ascending order. The comparison does not require a lot of extra space. It only requires one extra memory space for the temporal variable.

This is known as in-place sorting. The selection sort has a time complexity of O(n2) where n is the total number of items in the list. The time complexity measures the number of iterations required to sort the list. The list is divided into two partitions: The first list contains sorted items, while the second list contains unsorted items.

By default, the sorted list is empty, and the unsorted list contains all the elements. The unsorted list is then scanned for the minimum value, which is then placed in the sorted list. This process is repeated until all the values have been compared and sorted.

The following code shows the selection sort implementation using Python 3
```python
def selectionSort( itemsList ):
    n = len( itemsList )
    for i in range( n - 1 ): 
        minValueIndex = i

        for j in range( i + 1, n ):
            if itemsList[j] < itemsList[minValueIndex] :
                minValueIndex = j

        if minValueIndex != i :
            temp = itemsList[i]
            itemsList[i] = itemsList[minValueIndex]
            itemsList[minValueIndex] = temp

    return itemsList

el = [21,6,9,33,3]
print(selectionSort(el))
```
