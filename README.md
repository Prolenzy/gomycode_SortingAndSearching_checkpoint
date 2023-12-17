Project title: insertion_sort


"arr" is the array of integers, and "n" is the array's length.
"i" and "j" are the two counters in which "i" represent the current position of the element being considered for insertion, and "j" represent the position in the sorted subarray where comparisons are done. 
From (For i from 1 to n - 1) outer loop iterates through each element of the "arr" array starting from the second element.
(While j >= 0 and arr[j] > key) is the inner loop and compares the current element (key) with the elements in the sorted subarray (arr[0] to arr[j]), shifting them from right as needed. The "j" value keeps decrementing until the correct position for "key" is attained. 
The "key" element is inserted into its correct position in the sorted subarray. 