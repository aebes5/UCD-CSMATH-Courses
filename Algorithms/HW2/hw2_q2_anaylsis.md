## Insertion Sort vs Merge Sort Analysis:

The insertion sort and merge sort had two totally different run times when running these files. It wasn't bad at first, where the 1000 numbers were sorted in 0.05 seconds with insertion sort vs 0.005 seconds with merge sort. However, once the file size grew past 10,000 numbers, insertion sort couldn't keep up with merge sort. 10,000(7 seconds vs 0.09 seconds), 100,000(~13 minutes vs 0.9 seconds), 250,000(~94 minutes vs 2.6 seconds), 500,000(~11 hours vs 5.6 seconds), and 1,000,000(~28 hours vs 12 seconds). While the insertion sort was certainly easier to implement, it had its drawbacks when it came to sorting larger lists of numbers. Overall, we can't say merge sort is always better than insertion sort. After all, a small list of numbers would get sorted seemingly equivalent, while an insertion sort would be easier to implement. This being said, merge sort certainly outperforms insertion sort with larger lists of numbers. 28 hours vs 12 seconds tells you all you really need to know when comparing these two algorithms' run times.