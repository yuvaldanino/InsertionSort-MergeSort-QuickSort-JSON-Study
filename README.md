# InsertionSort-MergeSort-QuickSort-JSON-Study
3 Programs:
- Program 1:
	- Takes JSON file as input that represents the output of a sorting algorithm and verifies that
		each sample is a sorted array.
	- If a sample array is not sorted, the algorithm finds the locations of the consecutive inversion 		which is when the i'th element is equal to or larger than the i + 1st element.
   	- The Program returns :
   	  	- A JSON object with the locations of the consecutive inversions.
   	  	- A JSON object with the dataset, array size, file name, number of samples, and number of samples with inversions.

- Program 2:
  	- Takes in 2 JSON files that represnt the output of 2 sorting algorithms and verifies that they are the same or finds their differences.
  	- The Program returns:
  	  	- A JSON object with the the mismatching locations and their values.
  	  	- A JSON object with the array size, name, and number of samples in files 1 and 2.
  	  	- A JSON object with the value of samples with conflicting results. 

- Program 3:
	- Takes in JSON file that represents a collection of arrays to be sorted and runs INSERTIONSORT, MERGESORT, and QUICKSORT on the samples.
 	- The Program returns:
    		- These statistics about InsertionSort, MergeSort, and QuickSort in CSV formatt:
 




  - These statistics about InsertionSort, MergeSort, and QuickSort in CSV formatt:
    	- These statistics about InsertionSort, MergeSort, and QuickSort in CSV formatt:
    			- Running Time 
    - Number of Comparisons
    - Number of memory accesses
      
