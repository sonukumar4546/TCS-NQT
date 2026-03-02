## Problems

| # | Problem Name | Question | Remarks |
|---:|-------------|----------|---------|
| 1 | Sum of Array | https://www.geeksforgeeks.org/problems/sum-of-array2326/1 | Use a loop and accumulate the sum. |
| 2 | Remove duplicates from unsorted array | https://www.geeksforgeeks.org/problems/remove-duplicates-from-unsorted-array4141/1 | Use a map to track seen elements map.find(arr[i])==map.end(); add unseen elements to the result vector and in map . |
| 3 | Second Largest | https://www.geeksforgeeks.org/problems/second-largest3735/1?page=1&sprint=63af446b97dfa5601c7b06b52b991d07&sortBy=submissions | (Add solution file link here) |
| 4 | Binary Search | https://www.geeksforgeeks.org/problems/binary-search-1587115620/1?page=1&sprint=63af446b97dfa5601c7b06b52b991d07&sortBy=submissions | Use two pointers (low=0, high=n-1).  |
| 5 | Equilibrium Point | https://www.geeksforgeeks.org/problems/equilibrium-point-1587115620/1?page=1&sprint=63af446b97dfa5601c7b06b52b991d07&sortBy=submissions | Use prefix sums (or keep totalSum as right sum). For each index i: leftSum = prefix[i-1], rightSum = totalSum - prefix[i]. If leftSum == rightSum, i is the equilibrium index. |
| 6 | Two Sum (Key Pair) | https://www.geeksforgeeks.org/problems/key-pair5616/1?page=1&sprint=63af446b97dfa5601c7b06b52b991d07&sortBy=submissions | Sort the array, then use two pointers (l=0, r=n-1). If a[l]+a[r]==X return true; if sum<X l++; else r--. |
