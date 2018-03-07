**Question Link** - https://www.hackerrank.com/contests/cqm-5-2/challenges/up-and-down-1

**Required Knowledge** – Sliding Window

**Difficulty** – Easy

Save the values in an array. Calculate the sum of first `K` elements of the array.
These first `K` values form our initial window and the sum of these values is our initial sum. 
Initialize three variables (use long as data type) `win`, `down` and `up` to this sum. 
Now we slide this window to obtain the sum of all consecutive windows possible of size `K`. 
For this add the element which comes exactly after the window and subtract the first number of the window.
Update the `min` to minimum of `min` and the current window sum and the `max` to maximum of `max` and the current window sum. 
Repeat until the all the last element is reached. Finally print the difference `max – min`.

**Use long data type for saving the `sum`, `max` and `min`.**
