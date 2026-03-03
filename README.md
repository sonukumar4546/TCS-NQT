## Problems

| # | Problem Name | Question | Remarks |
|---:|-------------|----------|---------|
| 1 | Sum of Array | https://www.geeksforgeeks.org/problems/sum-of-array2326/1 | Use a loop and accumulate the sum. |
| 2 | Remove duplicates from unsorted array | https://www.geeksforgeeks.org/problems/remove-duplicates-from-unsorted-array4141/1 | Use a map to track seen elements map.find(arr[i])==map.end(); add uns[...] |
| 3 | Second Largest | https://www.geeksforgeeks.org/problems/second-largest3735/1?page=1&sprint=63af446b97dfa5601c7b06b52b991d07&sortBy=submissions | (Add solution file link here) |
| 4 | Binary Search | https://www.geeksforgeeks.org/problems/binary-search-1587115620/1?page=1&sprint=63af446b97dfa5601c7b06b52b991d07&sortBy=submissions | Use two pointers (low=0, high=n-1).  |
| 5 | Equilibrium Point | https://www.geeksforgeeks.org/problems/equilibrium-point-1587115620/1?page=1&sprint=63af446b97dfa5601c7b06b52b991d07&sortBy=submissions | Use prefix sums (or keep totalSum as[...] |
| 6 | Two Sum (Key Pair) | https://www.geeksforgeeks.org/problems/key-pair5616/1?page=1&sprint=63af446b97dfa5601c7b06b52b991d07&sortBy=submissions | Sort the array, then use two pointers (l=0, r=n-1).[...] |
| 7 | First Repeating Element | https://www.geeksforgeeks.org/problems/first-repeating-element4018/1?page=3&category=Arrays,two-pointer-algorithm,Pointers&sortBy=submissions | Use unordered_map to cou[...] |
| 8 | Frequency of Array Elements | https://www.geeksforgeeks.org/problems/frequency-of-array-elements-1587115620/1?page=1&sprint=63af446b97dfa5601c7b06b52b991d07&sortBy=submissions | Convert array in[...] |
| 9 | Reverse an Array | https://www.geeksforgeeks.org/problems/reverse-an-array/1?page=2&category=Arrays,Pointers&difficulty=Basic,Easy&sortBy=submissions | Use two pointers (l=0, r=n-1) and swap whi[...] |
| 10 | Count Pairs with Given Sum 0 | https://www.geeksforgeeks.org/problems/count-pairs-with-given-sum5022/1?page=1&category=Arrays,Pointers&difficulty=Basic,Easy&sortBy=submissions |  |
| 11| Reverse a Number | [https://www.geeksforgeeks.org/problems/reverse-a-number/0](https://www.geeksforgeeks.org/problems/reverse-digit0316/1) | rev = rev*10 + (n%10); n/=10; stop when n==0. If inpu[...] |
| 12 | Prime Number | https://www.geeksforgeeks.org/problems/prime-number2314/1 | Handle n<=1 as not prime; check divisibility from 2 to  (or i*i<=n) and return prime if none. |
| 13 | Number of Factors | https://www.geeksforgeeks.org/problems/number-of-factors1435/1 | Count divisors by looping i=1..sqrt(n). If i divides n, add 2 (i and n/i); add 1 if i*i==n. |
| 14 | Palindrome Number | https://www.geeksforgeeks.org/problems/palindrome0746/1 | Reverse the number and compare with original (store a copy). Or compare digits from both ends without converting to string. Handle negatives as not palindrome (if applicable). |