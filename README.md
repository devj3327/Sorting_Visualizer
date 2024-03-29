# sorting.js
A visualization for a bunch of different sorting algorithms in Javascript.



More specifically, we visualize in-place comparison-based sorting algorithms by highlighting each comparison in blue and each swap in red. Currently the following sorting algorithms are implemented:

* [Bubble sort](https://en.wikipedia.org/wiki/Bubble_sort)
* [Selection sort](https://en.wikipedia.org/wiki/Selection_sort)
* [Insertion sort](https://en.wikipedia.org/wiki/Insertion_sort)
* [Odd-even sort](https://en.wikipedia.org/wiki/Odd%E2%80%93even_sort)
* [Cocktail sort](https://en.wikipedia.org/wiki/Cocktail_sort)
* [Quicksort](https://en.wikipedia.org/wiki/Quicksort)
* [Heapsort](https://en.wikipedia.org/wiki/Heapsort)
* [Merge sort](https://en.wikipedia.org/wiki/Merge_sort)
* [Bitonic mergesort](https://en.wikipedia.org/wiki/Bitonic_sorter)
* [Introsort](https://en.wikipedia.org/wiki/Introsort)

Quicksort and introsort recursively partition chunks of the array around a pivot value; the choice of pivot can have a big effect on the efficiency of the algorithm. We implement several pivoting choices discussed [here](https://en.wikipedia.org/wiki/Quicksort#Choice_of_pivot).
