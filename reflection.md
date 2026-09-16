1. At what array size did your baseline algorithm become noticeably sluggish to execute?
   when the array size is from 5,000 to 10,000.

2. Based on your empirical data and the shape of your graph, estimate how long (in seconds, minutes, or hours) your baseline algorithm would take to process an array of $1,000,000$ elements. Show your reasoning.
   Baseline is double nested loop, which takes O(n²) time complexity.
   5,000 -> 10,000: 0.312041s -> 1.228175s (around four times).

3. Based on your empirical data and the shape of your graph, estimate how long (in seconds, minutes, or hours) your Kadane's algorithm would take to process an array of $1,000,000$ elements. Show your reasoning.
   Kadane is linear time complexity.
   Array size = 2,500: 0.000077s
   Array size = 5,000: 0.000142s
   Array size = 10,000: 0.000286s

When array size is 1,000,000, which means 100 times of 10,000, 0.000286s \* 100 = 0.0286s
