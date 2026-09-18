1. At what array size did your baseline algorithm become noticeably sluggish to execute?
   My baseline algorithm became noticeably sluggish at around N = 5,000. At N = 2,500, it took about 0.079 seconds, but at N = 5,000, the execution time increased to about 0.306 seconds. By N = 10,000, it took about 1.23 seconds.

2. Based on your empirical data and the shape of your graph, estimate how long (in seconds, minutes, or hours) your baseline algorithm would take to process an array of $1,000,000$ elements. Show your reasoning.
   The baseline algorithm appears to have O(n^2) time complexity. When the array size increased from 5,000 to 10,000, the execution time increased from about 0.306 seconds to about 1.227 seconds, which is approximately four times longer.

   Increasing the array size from 10,000 to 1,000,000 is a factor of 100. Since the baseline algorithm is quadratic, the execution time should increase by approximately:

   100^2 = 10,000 times

   Using the measured time at N = 10,000:

   1.226751 × 10,000 = 12,267.51 seconds

   12,267.51 seconds is about 204 minutes, or about 3.4 hours.

   Therefore, I estimate that the baseline algorithm would take approximately 3.4 hours to process an array of 1,000,000 elements.

3. Based on your empirical data and the shape of your graph, estimate how long (in seconds, minutes, or hours) your Kadane's algorithm would take to process an array of $1,000,000$ elements. Show your reasoning.
   Kadane's algorithm appears to have O(n) time complexity. When the array size increased from 5,000 to 10,000, the execution time approximately doubled from 0.000143 seconds to 0.000282 seconds.

   Increasing the array size from 10,000 to 1,000,000 is a factor of 100. Since Kadane's algorithm is linear, the execution time should also increase by approximately 100 times.

   0.000282 × 100 = 0.0282 seconds

   Therefore, I estimate that Kadane's algorithm would take approximately 0.028 seconds to process an array of 1,000,000 elements.
