<br />
<p align="center">
  <h3 align="center">Welcome to the Algorithm Visualizer Project</h3>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#installation-and-usage">Installation and Usage</a>
    </li>
    <li><a href="#contributors">Contributors</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Welcome to the Algorithm Visualizer Project.
This project mainly foccuses on two categories of algorithms
1. Searching Algorithms : Binary Search and ternary Search
2. Sorting Algorithms : Bubble Sort, Selection Sort, Merge Sort, Quick Sort and Heap Sort

**Searching Algorithms**
1. Binary Search 
    * Efficiently checks whether a given element in present in a sorted array by dividing the array into 2 halves and checking which half does the element belong to
    * Works in Time Complexity of O(log(n))
2. Ternary Search
    * Similar to Binary Search but instead divided the elements into 3 parts
    * Also works in Time Complexing O(log(n))

**Sorting Algorithms**
1. Bubble Sort 
    * Works by repeatedly swapping the adjacent elements if they are in wrong order.
    * Works in Time Complexity of O(n^2)
2. Selection Sort
    * divided into two parts, the sorted part at the left end and the unsorted part at the right end.
    * Initially, the sorted part is empty
    * The smallest element is selected from the unsorted array and swapped with the leftmost element, and that element becomes a part of the sorted array.
    * Works in Time Complexing O(n^2)
3. Merge Sort
    * recursively divides the array into 2 halves and seperately solves both the halves
    * meges the sorted array of the two halves to get the complete sorted array
    * Works in Time Complexing O(nlog(n))
4. Quick Sort
    * Recursively selects the last element as the pivot element and partitions the aarray into two subarrays such that the elements in left subarray are less than the pivot and the elements in the right subarray are greter than the pivot
    * calls Quicksort on the resulting left and right subarrays
    * Works in Average Time Complexing O(nlog(n))
5. Heap Sort
    * Similar to Selection Sort, divides its input into a sorted and an unsorted region, and iteratively shrinks the unsorted region by extracting the largest element from it and inserting it into the sorted region.
    * Works in Time Complexing O(nlog(n))

### Built With

* [Python](https://www.python.org/)
* [tkinter](https://docs.python.org/3/library/tkinter.html)


<!-- Installation and Usage -->
## Installation and Usage

1. Clone the repository onto your local system
2. Visualizing Sorting Algorithms
    * Compile and Run sortingUI.py file in your computer
    * A window like this will appear
    * Select the visualization speed from the drop down menu
    * Select the required array size from the slider option
    * Click on the Generate New Array Button to geneate a random array of the selected array size.
    * Finally, select the required sorting algorithm and the visualization will start
    
3. Visualizing Binary / Ternary Search
    * Compile and Run binarySearchUI.py / ternarysearchUI.py file in your computer
    * A window like this will appear
    * Select the visualization speed from the drop down menu
    * Select the required array size from the slider option
    * Click on the Generate New Sorted Array Button to geneate a random array of the selected array size.
    * Enter the value of the element that you would like to search in the array
    * Finally, click the Start button to start the visualization
    
<!-- Contributors -->
## Contributors

1. Ashish Manglani
2. Yash Bhagwat
