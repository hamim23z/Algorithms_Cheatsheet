```
**Insertion Sort**
Insertion sort is one of the more simple sorting algorithms. It works like this. Say we have an unsorted list and
then we want to arrange it from smallest to largest values. Using the second element in the list, we compare it
to the first. If it is smaller then the first, we move it to the left and then move the first element to the
right. Move to the third element and compare it with  the first two elements and put at its correct position.
We then repeat this until the element is sorted how we want it. 

In terms of inserting a new number to our list, it is essentially the same. But this time we start with the last
element. Say we have a list of 2 6 10 15 20 25 30. And we want to insert 12. We start with 30. 12 is less than
30 so we shift 30 to the right and place 12 there. And then compare 12 with 25. 12 is less than 25 so we shift
25 to the right and place 12 there. We repeat this process until 12 is in the right place. The list is now
2 6 10 12 15 20 25 30. 
```
.
.
.
.

```
**Merge Sort**
Merge is the next sorting algorithm we typically learn. Merge Sort is a divide and conquer algorithm so it is
called recursively. Say we have a large array of numbers, we then divide it into two subarrays and continue to
do so until it bottoms out. We then sort each subarray and then at the end combine our solutions to make the
full sorted list.

Merge Sort, for me, is best visualized when drawing a tree. It is the best to interpret and based on how you want
it sorted, it can be extremely easy. 
```
.
.
.
.

````
**Heap Sort**
Heap Sort is another sorting algorithm. Inside it are two needed components. Build Max Heap which builds a max heap
from an unsorted array. And Heapify which is similiar to Build Max Heap but faster because it assumes part of the
array is already sorted. Depending on how we want to sort, we make a tree with the largest or smallest element at
the top root node. I'll use largest because it's easier. And then going down the tree, are the largest to smallest
elements. The best way to get this is by watching videos on it and visualizing it. 

So we call/create our max heap aka a tree. And then we make the array. Rearrange array elements so that they form a
Max Heap. Repeat the following steps until the heap contains only one element:
- Swap the root element of the heap (which is the largest element in current heap) with the last element of the heap.
- Remove the last element of the heap (which is now in the correct position). We mainly reduce heap size and do not
remove element from the actual array.
- Heapify the remaining elements of the heap.
````
.
.
.
.

```
**Quick Sort**
This is another sorting algorithm and similar to merge sort it is a divde and conquer algorithm. It partitions the
array around a pivot element, sorting elements into two groups based on their relation to the pivot. We choose the
pivot to be the first, middle, or last element. And then based on that pivot we do our sorting, where to the left
is less than and to the right is greater than. 

We recursively apply quicksort to both partitions. And then combine the sorted partitions. Randomized Quicksort also
exists and that is essentially the same but a different way to choose the pivot, a random pivot. 
```
