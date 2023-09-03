# InsertionSort-MergeSort-QuickSort-JSON-Study
3 Programs:
- Program 1:
	- Takes JSON file as input that represents the output of a sorting algorithm and verifies that
		each sample is a sorted array.
	- If a sample array is not sorted, the algorithm finds the locations of the consecutive inversion 		which is when the i'th element is equal to or larger than the i + 1st element.
   	- The Program returns :
   	  	- A JSON object with the locations of the consecutive inversions.
   	  	- A JSON object with the dataset, array size, file name, number of samples, and number of samples with inversions. 
