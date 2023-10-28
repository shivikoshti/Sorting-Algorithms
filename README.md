# Sorting Algorithms

This repository provides implementations and explanations for three fundamental sorting algorithms: Bubble Sort, Insertion Sort, and Selection Sort. Each algorithm is explained with the help of diagrams and brief descriptions.

## 1. Bubble Sort

Bubble Sort is a simple comparison-based sorting algorithm. The main idea is to repeatedly step through the list, compare adjacent elements, and swap them if they are in the wrong order. The process is repeated for every element until no swaps are needed.

![Bubble Sort Illustration](link_to_your_bubble_sort_image)

### How it works:
- Start from the first element and compare it with the next one.
- If the first element is greater than the next one, swap them.
- Move to the next element and repeat the process until the end of the list is reached.
- After the first pass, the largest element will have "bubbled up" to the last position.
- Repeat the process, excluding the last element, and continue doing this until no more swaps are needed.

## 2. Insertion Sort

Insertion Sort builds the final sorted array one item at a time. It is much less efficient on large lists than more advanced algorithms such as quicksort, heapsort, or merge sort.

![Insertion Sort Illustration](link_to_your_insertion_sort_image)

### How it works:
- Start from the second element (consider the first element as sorted).
- Compare the current element with the previous elements.
- If the current element is smaller than the previous one, compare it with the elements before the previous one. Continue this process until you reach an element smaller than the current element or reach the start of the array.
- Insert the current element in the correct position so that the elements before are smaller than the current element and the elements after are bigger.

## 3. Selection Sort

Selection Sort is a comparison-based sorting algorithm. The main idea behind the algorithm is to divide the input list into two parts: a sorted sublist and an unsorted sublist. The algorithm repeatedly selects the smallest (or largest) element from the unsorted sublist and moves it to the end of the sorted sublist.

![Selection Sort Illustration](link_to_your_selection_sort_image)

### How it works:
- Start with the first element as the minimum.
- Search for the smallest element in the unsorted sublist and swap it with the first element.
- Move the boundary between the sorted and unsorted sublists one element to the right.
- Repeat the process until the entire list is sorted.
