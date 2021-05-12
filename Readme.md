# About:

- This list was initially created for personal use
- Headers and footers of source code are generated from extension `LeetCode` in VSCode

## My profile:
https://leetcode.com/jummyegg/

## Tips and Tricks for Beginner:

- Solve problem by Topic: when you first started, it is important to understand the topic quickly and solving 10-20 problems per topic is a good way to grasp it.
- If you are using Python and are interested in writing Pythonic code, I created a repo for [Python tips and tricks](https://github.com/trung-hn/python-tips-and-tricks)
- Always aim to get a better solution by reading the dicussion after you successfully solve it. Leetcode's community is amazing, you will learn of lot of tips and tricks to make your code cleaner and faster from the dicussion posts.
- Leetcode has a "Taking Note" system where you can take notes of things you learn for each problem. Make good use of it.
- Leetcode's category of difficulty (Easy, Medium, Hard) is not always correct. My rule of thumb is looking at the acceptance rate. `>55%` means Easy and `<35%` means Hard
- What is correct is the amount of likes and dislikes in a problem. Problems with more dislikes than likes is usually not worth solving. Try a different one.
- When you stuck, there are a few things you can do to give yourself hints:
  - Look at the tag for the problem and see what kind of algorithm or data strucutre is needed to solve it
  - Look at the hints provided by Leetcode
  - Quickly look at the discussion to see what the expected complexity is or the name of the algorithm.
  - Estimate the Time Complexity of the problem based on the input constraints (see next tip)
- You can estimate the Time complexity based on the input constraints:

| input size | estimated time complexity |
|---|---|
| `N <= 10` | `O(N!)` |
| `N <= 20` | `O(2^N)` |
| `N <= 500` | `O(N^3)` |
| `N <= 5000` | `O(N^2)` |
| `N <= 10^6` | `O(N)` or `O(NlogN)` |
| `N > 10^6` | `O(1)` or `O(logN)` |

# Solutions list (500+ problems)

| # | Title | Level | Time | Space | Tags | Note | Premium 🔒 |
|---|---|---|---|---|---|---|---|
| 1 | Two Sum | Easy | O(N) | O(N) | | | |
| 7 | Reverse Integer | Easy | O(log x) | O(1) | | Tricky | |
| 11 | Container With Most Water | Medium | O(N) | O(1) | Array, Two Pointers | | |
| 12 | Integer to Roman | Medium | O(N) | O(N) | Math, String | | |
| 12 | Roman to Integer | Easy | O(N) | O(1) | Math, String | | |
| 15 | 3Sum | Medium | O(N^2) | O(N^2) | Array, Two Pointers | | |
| 17 | Letter Combinations of a Phone Number | Medium | O(2^2) | O(2^N) | String, Backtracking, DFS, Recursion | | |
| 19 | Remove Nth Node From End of List | Medium | O(N) | O(1) | Linked List, Two Pointers | | |
| 20 | Valid Parentheses | Easy | O(N) | O(N) | String, Stack | | |
| 21 | Merge Two Sorted Lists | Easy | O(N) | O(1) | Linked List | | |
| 22 | Generate Parentheses | Medium | Complicated | Complicated | String, Backtracking | | |
| 24 | Swap Nodes in Pairs | Medium | O(N) | O(N) | Linked List | | |
| 30 | Substring with Concatenation of All Words | Hard | O(NK) | O(K) | Array, Backtracking | | |
| 32 | Longest Valid Parentheses | Hard | O(N) | O(N) | String, Dynamic Programming | | |
| 34 | Find First and Last Position of Element in Sorted Array | Medium | O(logN) | O(1) | Array, Binary Search | Template for Binary Search | |
| 39 | Combination Sum | Medium | O(N^2) | O(N) | Array, Backtracking | | |
| 42 | Trapping Rain Water | Hard | O(N) | O(N) | Array, Two Pointers, Dynamic Programming, Stack | | |
| 45 | Jump Game II | Medium | O(N) | O(1) | Array, Greedy | | |
| 46 | Permutations | Medium | O(N!) | O(N!) | Backtracking | | |
| 47 | Permutations II | Medium | O(N!) | O(N!) | Backtracking | | |
| 48 | Rotate Image | Medium | O(N*M) | O(1) | Array | | |
| 53 | Maximum Subarray | Easy | O(N) | O(1) | | | |
| 57 | Insert Interval | Hard | O(N) | O(N) | Array, Sort, Greedy | | |
| 59 | Spiral Matrix II | Medium | O(N^2) | O(N^2) | Array | | |
| 61 | Rotate List | Medium | O(N) | O(1) | Linked List, Two Pointers | | |
| 63 | Unique Paths II | Medium | O(M*N) | O(M) | Array, Dynamic Programming | | |
| 71 | Simplify Path | Medium | O(N) | O(N) | String, Stack | | |
| 72 | Edit Distance | Hard | O(N * M) | O(N) | String, Dynamic Programming | | |
| 74 | Search a 2D Matrix | Medium | O(logN + logM) | O(1) | Binary Search | | |
| 76 | Minimum Window Substring | Hard | O(S+T) | O(S+T) | Hash Table, Two Pointers, String, Sliding Window | | |
| 78 | Subsets | Medium | O(N\*2^N) | O(N\*2^N) | Backtracking, Bit Manipulation | | |
| 80 | Remove Duplicates from Sorted Array II | Medium | O(N) | O(1) | Array, Two Pointers | | |
| 82 | Remove Duplicates from Sorted List II | Medium | O(N) | O(1) | Linked List | | |
| 91 | Decode Ways | Medium | O(N) | O(N) | String, Dynamic Programming | | |
| 99 | Recover Binary Search Tree | Hard | O(N) | O(N) | Tree, DFS | | |
| 100 | Same Tree | Easy | O(N) | O(H) | Tree, Pythonic | | |
| 107 | Binary Tree Level Order Traversal II | Easy | O(N) | O(N) | Tree, BFS | | |
| 111 | Minimum Depth of Binary Tree | Easy | O(N) | O(H) | Tree, DFS, BFS | | |
| 114 | Flatten Binary Tree to Linked List | Medium | O(N) | O(1) | Tree, DFS | | |
| 115 | Distinct Subsequences | Medium | O(N) | O(1) | String, Dynamic Programming | | |
| 116 | Populating Next Right Pointers in Each Node | Medium | O(N) | O(N) | Tree, DFS, BFS | | |
| 119 | Pascal's Triangle II | Easy | O(k^2) | O(k) | Array | | |
| 121 | Best Time to Buy and Sell Stock | Easy | O(N) | O(1) | Dynamic Programming | | |
| 122 | Best Time to Buy and Sell Stock II | Easy | O(N) | O(1) | Array, Greedy | | |
| 125 | Valid Palindrome | Easy | O(1) | O(1) | String | | |
| 127 | Word Ladder | Hard | O(M^2\*N) | O(M^2\*N) | BFS | | |
| 133 | Clone Graph | Medium | O(N+M) | O(N) | DFS, BFS, Graph | | |
| 134 | Gas Station | Medium | O(N) | O(N) | Dynamic Programming, Greedy | | |
| 138 | Copy List with Random Pointer | Medium | O(N) | O(N) | Hash Table, Linked List | | |
| 139 | Word Break | Medium | O(N^2) | O(N) | Dynamic Programming | | |
| 141 | Linked List Cycle | Easy | O(N) | O(1) | Linked List, Two Pointers | | |
| 142 | Linked List Cycle II | Medium | O(N) | O(1) | Linked List, Two Pointers | | |
| 143 | Reorder List | Medium | O(N) | O(1) | Linked List | | |
| 147 | Sort, Linked List | Medium | O(N^2) | O(1) | Sort, Linked List | | |
| 151 | Reverse Words in a String | Easy | O(N) | O(N) | String | | |
| 152 | Maximum Product Subarray | Medium | O(N) | O(N) | Dynamic Programming, Array | | |
| 153 | Find Minimum in Rotated Sorted Array | Medium | O(logN) | O(1) | Binary Search | | |
| 154 | Find Minimum in Rotated Sorted Array II | Hard | O(logN) | O(1) | Binary Search | | |
| 159 | Longest Substring with At Most Two Distinct Characters | Medium | O(N) | O(1) | Premium, Hash Table, Two Pointers, String, Sliding Window | | |
| 165 | Compare Version Numbers | Medium | O(N) | O(1) | String | | |
| 168 | Excel Sheet Column Title | Medium | O(logN) | O(logN) | Math | Math Tricks | |
| 171 | Excel Sheet Column Number | Easy | O(N) | O(1) | String | | |
| 179 | Largest Number | Medium | O(NlogN) | O(1) | Sort | | |
| 187 | Repeated DNA Sequences | Medium | O(N-L) | O(N-L) | Hash Table, Bit Manipulation | | |
| 190 | Reverse Bits | Easy | O(1) | O(1) | Bit Manipulation | | |
| 198 | House Robber | Easy | O(N) | O(1) | Dynamic Programming | | |
| 204 | Count Primes | Medium | O(loglogN) | O(N) | Hash Table, Math | | |
| 207 | Course Schedule | Medium | O(N + E) | O(N + E) | BFS, DFS, Graph, Topological Sort | | |
| 208 | Implement Trie (Prefix Tree) | Medium | Varying | Varying | Design, Trie | | |
| 209 | Minimum Size Subarray Sum | Medium | O(N) | O(1) | Array, Two Pointers, Binary Search | | |
| 211 | Add and Search Word - Data structure design | Medium | O(M) | O(1) | Trie, Design | | |
| 213 | House Robber II | Medium | O(N) | O(1) | Dynamic Programming | | |
| 215 | Kth Largest Element in an Array | Medium | O(NlogK) | O(K) | Heap | | |
| 216 | Combination Sum III | Medium | O(N^2) | O(N^2) | Array, Backtracking | | |
| 218 | The Skyline Problem | Hard | O(NlogN) | O(N) | Divide and Conquer, Heap, Binary Indexed Tree, Segment Tree, Line Sweep | | |
| 220 | Contains Duplicate III | Medium | O(N) | O(N) | Sort, Ordered Map | | |
| 221 | Maximal Square | Medium | O(N * M) | O(1) | Array, Dynamic Programming | | |
| 222 | Count Complete Tree Nodes | Medium | O(logN * logN) | O(1) | Binary Search, Tree | | |
| 227 | Basic Calculator II | Medium | O(N) | O(N) | String, Stack | |
| 228 | Summary Ranges | Easy | O(N) | O(1) | Array | |
| 229 | Majority Element II | Medium | O(N) | O(1) | Array | |
| 230 | Kth Smallest Element in a BST | Medium | O(H + k) | O(H + k) | Tree, DFS | Use general formula for tree traversal | |
| 231 | Power of Two | Easy | O(1) | O(1) | Bit Manipulation | Important technique in bit manipulation | |
| 234 | Palindrome Linked List | Easy | O(N) | O(1) | Linked List, Two Pointers | | |
| 239 | Sliding Window Maximum | Hard | O(N) | O(N) | Monotonic Dequeue, Sliding Window, Heap | | |
| 252 | Meeting Rooms | Easy | O(NlogN) | O(1) | Premium, Sort | | 🔒 |
| 253 | Meeting Rooms II | Medium | O(NlogN) | O(N) | Premium, Heap, Greedy, Sort | | 🔒 |
| 264 | Ugly Number II | Medium | O(1) | O(1) | Heap, Dynamic Programming | | |
| 268 | Missing Number | Easy | O(N) | O(1) | Array, Math, Bit Manipulation  | | |
| 270 | Closest Binary Search Tree Value | Easy | O(H) | O(1) | Premium, Binary Search, Tree | | 🔒 |
| 273 | Integer to English Words | Medium | O(logN) | O(1) | Math, String |  | |
| 274 | H-Index | Medium | O(NlogN) | O(N) | Hash Table, Sort | There is a better solution | |
| 284 | Peeking Iterator | Medium | O(NlogN) | O(N) | Design | | |
| 289 | Game of Life | Medium | O(M*N) | O(1) | Array | | |
| 290 | Word Pattern | Easy | O(N) | O(N) | Hash Table | | |
| 295 | Find Median from Data Stream | Hard | O(logN) | O(N) | Design, Hard, Heap | | |
| 296 | Best Meeting Point | Hard | O(M*N) | O(M+N) | Premium, Math | | 🔒 |
| 297 | Serialize and Deserialize Binary Tree | Hard | O(N) | O(N) | Tree, Design | | |
| 299 | Bulls and Cows | Easy | O(N) | O(N) | Hash Table | | |
| 300 | Longest Increasing Subsequence | Medium | O(NlogN) | O(N) | Binary Search, Dynamic Programming | | |
| 304 | Range Sum Query 2D - Immutable | Medium | O(1) | O(R*C) | Dynamic Programming | Matrix Range Sum Trick | |
| 310 | Minimum Height Trees | Medium | O(V) | O(V) | BFS, Graph | | |
| 316 | Remove Duplicate Letters | Hard | O(N) | O(1) | Greedy, Tricky, Stack | | |
| 317 | Shortest Distance from All Buildings | Hard | O(N\*M) | O(N\*M) | BFS, Premium | | 🔒 |
| 319 | Bulb Switcher | Medium | O(1) | O(1) | Math, Tricky | | |
| 320 | Generalized Abbreviation | Medium | O(N*2^N) | O(N) | Premium, Backtracking | | 🔒 |
| 322 | Coin Change | Medium | O(A*N) | O(A) | Dynamic Programming | | |
| 328 | Odd Even Linked List | Medium | O(N) | O(1) | Linked List | | |
| 329 | Longest Increasing Path in a Matrix | Hard | O(R\*C) | O(R\*C) | DFS, Topology Sort, Memoization | | |
| 334 | Increasing Triplet Subsequence | Medium | O(N) | O(1) | Array | | |
| 337 | House Robber III | Medium | O(N) | O(N) | Dynamic Programming, Tree, DFS | | |
| 338 | Counting Bits | Medium | O(N) | O(N) | Dynamic Programming, Bit Manipulation | | |
| 342 | Power of Four | Easy | O(1) | O(1) | Math, Bit Manipulation | | |
| 344 | Reverse String | Easy | O(N) | O(1) | Two Pointers, String | | |
| 346 | Moving Average from Data Stream | Easy | O(1) | O(N) | Premium, Design | | 🔒 |
| 347 | Top K Frequent Elements | Medium | O(N) | O(N) | Hash Table, Heap | | |
| 348 | Design Tic-Tac-Toe | Medium | O(1) | O(N^2) | Premium, Design | | 🔒 |
| 351 | Android Unlock Patterns | Medium | O(N!) | O(N) | Dynamic Programming, Backtracking, Premium | | 🔒 |
| 354 | Russian Doll Envelopes | Hard | O(NlogN) | O(N) | Binary Search, Dynamic Programming | | |
| 357 | Count Numbers with Unique Digits | Medium | O(1) | O(1) | Math, Dynamic Programming, Backtracking | | |
| 361 | Bomb Enemy | Medium | O(N\*M) | O(N\*M) | Premium, Dynamic Programming | | 🔒 |
| 362 | Design Hit Counter | Medium | O(1) | O(N) | Design, Premium | | 🔒 |
| 367 | Valid Perfect Square | Easy | O(logN) | O(1) | Math, Binary Search | | |
| 376 | Wiggle Subsequence | Medium | O(N) | O(1) | Greedy, Dynamic Programming | | |
| 377 | Combination Sum IV | Medium | O(T*N) | O(T) | Dynamic Programming | | |
| 378 | Kth Smallest Element in a Sorted Matrix | Medium | O(N^2logK) | O(K) | Heap, Binary Search | | |
| 380 | Insert Delete GetRandom | Medium | O(1) | O(N) | Array, Hash Table, Design | | |
| 384 | Shuffle an Array | Medium | O(N) | O(N) | | | |
| 387 | First Unique Character in a String | Easy | O(N) | O(N) | | | |
| 389 | Find the Difference | Medium | O(N) | O(1) | Hash Table, Bit Manipulation | | |
| 394 | Decode String | Medium | O(maxK*N) | O(N) | Stack, DFS | | |
| 395 | Longest Substring with At Least K Repeating Characters | Medium | O(NlogN) | O(N) | Divide and Conquer, Recursion, Sliding Window | | |
| 399 | Evaluate Division | Medium | O(N*M) | O(N) | Union Find, Graph | | |
| 402 | Remove K Digits | Medium | O(N) | O(N) | Greedy | | |
| 404 | Sum of Left Leaves | Easy | O(N) | O(H) | Tree | | |
| 406 | Queue Reconstruction by Height | Medium | O(N^2) | O(N) | Greedy | Clever solution | |
| 413 | Arithmetic Slices | Medium | O(N) | O(1) | Math, Dynamic Programming | | |
| 416 | Partition Equal Subset Sum | Medium | O(M*N) | O(M) | Dynamic Programming | | |
| 417 | Pacific Atlantic Water Flow | Medium | O(R\*C) | O(R\*C) | DFS, BFS | | |
| 419 | Battleships in a Board | Medium | O(N*N) | O(1) | Array, DFS | | |
| 425 | Word Squares | Hard | Complex | Complex | Back Tracking, Trie, Premium | | 🔒 |
| 423 | Reconstruct Original Digits from English | Medium | O(N) | O(N) | Math | | |
| 428 | Serialize and Deserialize N-ary Tree | Hard | O(N) | O(H) | Tree, Premium | | 🔒 |
| 431 | Encode N-ary Tree to Binary Tree | Hard | O(N) | O(H) | Tree, Premium | | 🔒 |
| 435 | Non-overlapping Intervals | Medium | O(NlogN) | O(1) | Greedy | Tricky, Hard | |
| 436 | Find Right Interval | Medium | O(NlogN) | O(N) | Binary Search | Bad Description | |
| 437 | Path Sum III | Medium | O(N) | O(N) | Tree | Tricky, Hard | |
| 438 | Find All Anagrams in a String | Medium | O(N_s + N_p) | O(1) | Hash Table | | |
| 442 | Find All Duplicates in an Array | Medium | O(N) | O(1) | Array | | |
| 445 | Add Two Numbers II | Medium | O(N) | O(N) | Linked List | | |
| 449 | Serialize and Deserialize BST | Medium | O(N) | O(N) | Tree | | |
| 450 | Delete Node in a BST | Medium | O(H) | O(H) | Binary Search Tree | | |
| 451 | Sort Characters By Frequency | Medium | O(N) | O(N) | Hash Table, Sorting, Pythonic | | |
| 452 | Minimum Number of Arrows to Burst Balloons | Medium | O(NlogN) | O(1) | Sort, Greedy | | |
| 454 | 4Sum II | Medium | O(N^2) | O(N^2) | Array | | |
| 456 | 132 Pattern | Medium | O(N) | O(N) | Stack | | |
| 458 | Poor Pigs | Hard | O(1) | O(1) | Math | | |
| 462 | Minimum Moves to Equal Array Elements II | Median | O(NlogN) | O(N) | Math | | |
| 463 | Island Perimeter | Easy | O(N*M) | O(1) | Greedy | | |
| 470 | Implement Rand10() Using Rand7() | Medium | O(1) | O(1) | Math | | |
| 474 | Ones and Zeroes | Medium | O(K\*M\*N) | O(K\*M\*N) | Dynamic Programming | | |
| 476 | Number Complement | Easy | O(N) | O(1) | Bit Manipulation | | |
| 478 | Generate Random Point in a Circle | Medium | O(1) | O(1) | Math, Random, Rejection Sampling | | |
| 491 | Increasing Subsequences | Medium | O(Combination) | O(Combination) | DFS | | |
| 494 | Target Sum | Medium | O(N\*T) | O(T) | Dynamic Programming, DFS | Template for DP | |
| 495 | Teemo Attacking | Medium | O(N) | O(1) | Array | | |
| 497 | Random Point in Non-overlapping Rectangles | Medium | O(logN) | O(N) | Design, Binary Search | | |
| 498 | Diagonal Traverse | Medium | O(R\*C) | O(R\*C) | Array | | |
| 510 | Inorder Successor in BST II | Medium | O(H) | O(1) | Tree, Premium | | 🔒 |
| 520 | Detect Capital | Easy | O(N) | O(1) | | | |
| 524 | Longest Word in Dictionary through Deleting | Medium | O(Complex) | O(Complex) | Two Pointers, Sort | | |
| 525 | Contiguous Array | Medium | O(N) | O(N) | Hash Table | Very good problem | |
| 528 | Random Pick with Weight | Medium | O(N), O(logN) | O(N), O(1) | Binary Search, Random | Pythonic | |
| 532 | K-diff Pairs in an Array | Medium | O(N) | O(N) | Array, Two Pointers | | |
| 538 | Convert BST to Greater Tree | Medium | O(N) | O(H) | Tree, BFS, DFS, Recursion | | |
| 540 | Single Element in a Sorted Array | Medium | O(logN) | O(1) | Binary Search | | |
| 542 | 01 Matrix | Medium | O(R\*C) | O(R\*C) | BFS, DFS | | |
| 544 | Brick Wall | Medium | O(N) | O(N) | Hash Table | | |
| 563 | Binary Tree Tilt | Easy | O(N) | O(H) | Tree, DFS, Recursion | | |
| 567 | Permutation in String | Medium | O(S1 + S2) | O(1) | String, Two Pointers, Sliding Window | | |
| 573 | Squirrel Simulation | Medium | O(N) | O(1) | Premium, Math | | 🔒 |
| 581 | Shortest Unsorted Continuous Subarray | Medium | O(N) | O(1) | Array | | |
| 583 | Delete Operation for Two Strings | Medium | O(N^2) | O(N) | Dynamic Programming, String | | |
| 589 | N-ary Tree Preorder Traversal | Easy | O(N) | O(N) | Tree | | |
| 593 | Valid Square | Medium | O(1) | O(1) | Math | | |
| 605 | Can Place Flowers | Easy | O(N) | O(1) | Array, Greedy | | |
| 622 | Design Circular Queue | Medium | O(1) | O(1) | Design, Queue | | |
| 623 | Add One Row to Tree | Medium | O(N) | O(N) | Tree | | |
| 624 | Maximum Distance in Arrays | Easy | O(N) | O(1) | Hash Table, Array, Premium | | 🔒 |
| 646 | Maximum Length of Pair Chain | Medium | O(NlogN) | O(N) | Greedy, Dynamic Programming | | |
| 655 | Print Binary Tree | Medium | O(N) | O(H) | Tree | | |
| 658 | Find K Closest Elements | Medium | O(logN+K) | O(K) | Tree | | |
| 659 | Split Array into Consecutive Subsequences | Medium | O(N) | O(1) | Greedy | | |
| 662 | Maximum Width of Binary Tree | Medium | O(N) | O(N) | Tree | | |
| 665 | Non-decreasing Array | Medium | O(N) | O(1) | Array | | |
| 667 | Beautiful Arrangement II | Medium | O(N) | O(N) | Array | | |
| 669 | Trim a Binary Search Tree | Medium | O(N) | O(N) | Tree, Recursion | | |
| 670 | Maximum Swap | Medium | O(N) | O(N) | Array, Math | | |
| 673 | Number of Longest Increasing Subsequence | Medium | O(N^2) | O(N) | Dynamic Programming | | |
| 677 | Map Sum Pairs | Medium | O(K) | O(K) | Trie | | |
| 696 | Count Binary Substrings | Medium | O(N) | O(1) | String | | |
| 700 | Search in a Binary Search Tree | Easy | O(H) | O(1) | Tree | | |
| 701 | Insert into a Binary Search Tree | Medium | O(H) | O(1) | Tree | | |
| 702 | Search in a Sorted Array of Unknown Size | Medium | O(logN) | O(1) | Binary Search, Premium | | 🔒 |
| 705 | Design HashSet | Easy | Varies | Varies | Design HashSet | | |
| 708 | Insert into a Sorted Circular Linked List | Medium | O(N) | O(1) | Linked List, Premium | | 🔒 |
| 713 | Subarray Product Less Than K | Medium | O(N) | O(1) | Array, Two Pointers | | |
| 714 | Best Time to Buy and Sell Stock with Transaction Fee | Medium | O(N) | O(1) | Array, Dynamic Programming, Greedy | | |
| 721 | Accounts Merge | Medium | O(Complex) | O(Complex) | Union-Find, DFS | Template for Union-Find | |
| 725 | Split Linked List in Parts | Medium | O(N) | O(N) | Linked List | | |
| 729 | My Calendar I | Medium | O(NlogN) | O(N) | Tree | | |
| 733 | Flood Fill | Easy | O(N) | O(N) | DFS | | |
| 734 | Sentence Similarity | Easy | O(N) | O(N) | Premium, Hash Table | | 🔒 |
| 735 | Asteroid Collision | Medium | O(N) | O(N) | Stack | | |
| 737 | Sentence Similarity II | Medium | O(NlogP + P) or o(NP) | O(N) | Premium, DFS, Union Find | | 🔒 |
| 738 | Monotone Increasing Digits | Medium | O(logN) | O(logN) | Greedy | | |
| 739 | Daily Temperatures | Medium | O(N) | O(N) | Hash Table, Stack | | |
| 740 | Delete and Earn | Medium | O(N+M) | O(N+M) | Dynamic Programming | | |
| 743 | Network Delay Time | Medium | O(ElogE) | O(N + E) | Heap, BFS, DFS, Graph | | |
| 754 | Reach a Number | Medium | O(logN) | O(1) | Math | | |
| 763 | Partition Labels | Medium | O(N) | O(N) | Greedy, Two Pointers | | |
| 767 | Reorganize String | Medium | O(NlogN) | O(N) |  String, Heap, Greedy, Sort | | |
| 768 | Max Chunks To Make Sorted II | Hard | O(N) | O(N) | Array | | |
| 769 | Max Chunks To Make Sorted | Medium | O(N) | O(1) | Array | | |
| 775 | Global and Local Inversions | Medium | O(N) | O(1) | Array, Math | | |
| 784 | Letter Case Permutation | Medium | O(2^N) | O(2^N) | Backtracking, Bit Manipulation | | |
| 785 | Is Graph Bipartite? | Medium | O(E+V) | O(E+V) | BFS, DFS, Graph | | |
| 787 | Cheapest Flights Within K Stops | Medium | Complex | Complex | Dijkstra's Algorithm, Graph | Quite hard | |
| 789 | Escape The Ghosts | Medium | O(N) | O(1) | Math | | |
| 791 | Custom Sort String | Medium | O(N) | O(N) | String | | |
| 792 | Number of Matching Subsequences | Medium | O(N + M * L) | O(M) | Array | | |
| 794 | Valid Tic-Tac-Toe State | Medium | O(1) | O(1) | Array, String | | |
| 797 | All Paths From Source to Target | Medium | O(2^N * N) | O(2^N * N) | Backtracking, DFS | | |
| 799 | Champagne Tower | Medium | O(R^2) | O(R^2) | Dynamic Programming | | |
| 802 | Find Eventual Safe States | Medium | O(V+E) | O(V+E) | DFS, Graph | | |
| 820 | Short Encoding of Words | Medium | O(N\*M) | O(N\*M) | Trie | | |
| 823 | Binary Trees With Factors | Medium | O(N*N) | O(N) | Dynamic Programming | | |
| 825 | Friends Of Appropriate Ages | Medium | O(N) | O(1) | Array | | |
| 830 | Positions of Large Groups | Easy | O(N) | O(1) | | | |
| 833 | Find And Replace in String | Medium | O(N) | O(N) | Dynamic Programming | | |
| 835 | Image Overlap | Medium | O(N^2) | O(N) | | | |
| 838 | Push Dominoes | Medium | O(N) | O(N) | | | |
| 841 | Keys and Rooms | Medium | O(N^2) | O(N) | DFS, Graph | | |
| 845 | Longest Mountain in Array | Medium | O(N) | O(1) | Two Pointers | | |
| 846 | Hand of Straights | Medium | O(MlogM+NW) | O(N) | Ordered Map | | |
| 849 | Maximize Distance to Closest Person | Medium | O(N) | O(1) | Array | | |
| 851 | Loud and Rich | Medium | O(N^2) | O(N^2) | DFS | | |
| 853 | Car Fleet | Medium | O(NlogN) | O(N) | Sort | | |
| 858 | Mirror Reflection | Medium | O(logN) | O(1) | Math | | |
| 859 | Buddy Strings | Easy | O(N) | O(1) | String | | |
| 863 | All Nodes Distance K in Binary Tree | Medium | O(N) | O(N) | Tree, BFS, DFS | | |
| 865 | Smallest Subtree with all the Deepest Nodes | Medium | O(N) | O(N) | Tree, BFS, DFS, Recursion | | |
| 869 | Reordered Power of 2 | Medium | O(logN) | O(1) | Math | | |
| 870 | Advantage Shuffle | Medium | O(NlogN) | O(N) | Array, Greedy | | |
| 873 | Length of Longest Fibonacci Subsequence | Medium | O(N^2) | O(N^2) | Array, Dynamic Programming | | |
| 875 | Koko Eating Bananas | Medium | O(NlogN) | O(1) | Binary Search | | |
| 880 | Decoded String at Index | Medium | O(N) | O(1) | Stack | Good problem | |
| 881 | Boats to Save People | Medium | O(NlogN) | O(N) | Two Pointers, Greedy | | |
| 886 | Possible Bipartition | Medium | O(N + E) | O(N + E) | DFS | Good problem | |
| 892 | Surface Area of 3D Shapes | Easy | O(N*N) | O(1) | Math, Geometry | | |
| 895 | Maximum Frequency Stack | Medium | O(1) | O(N) | Hash Table, Stack | | |
| 901 | Online Stock Span | Medium | O(1) | O(N) | Monotonic Stack | | |
| 902 | Numbers At Most N Given Digit Set | Hard | O(LogN) | O(1) | Math, Dynamic Programming | | |
| 904 | Fruit Into Baskets | Medium | O(N) | O(1) | Two Pointers | | |
| 905 | Sort Array By Parity | Easy | O(N) | O(1) | Array | | |
| 906 | Super Palindromes | Hard | Complex | Complex | Math | | |
| 910 | Smallest Range II | Medium | O(NlogN) | O(N) | Math, Greedy | | |
| 911 | Online Election | Medium | O(N + QlogN) | O(N) | Binary Search | | |
| 915 | Partition Array into Disjoint Intervals | Medium | O(N) | O(N) | Array | | |
| 916 | Word Subsets | Medium | O(A_t + B_t) | O(L) | String | | |
| 918 | Maximum Sum Circular Subarray | Medium | O(N) | O(1) | Array, Dynamic Programming | | |
| 919 | Complete Binary Tree Inserter | Medium | O(N) | O(1) | Tree | | |
| 923 | 3Sum With Multiplicity | Medium | O(N^2) | O(N) | Two Pointers | | |
| 926 | Flip String to Monotone Increasing | Medium | O(N) | O(N) | Array | | |
| 930 | Binary Subarrays With Sum | Medium | O(N) | O(N) | Hash Table, Two Pointers | | |
| 933 | Number of Recent Calls | Easy | O(1) | O(1) | Queue | | |
| 934 | Shortest Bridge | Medium | O(E+V) | O(E+V) | BFS, DFS | | |
| 935 | Knight Dialer | Medium | O(N) | O(1) | Dynamic Programming | | |
| 941 | Valid Mountain Array | Easy | O(N) | O(1) | Array | | |
| 946 | Validate Stack Sequences | Medium | O(N) | O(N) | Stack | | |
| 948 | Bag of Tokens | Medium | O(NlogN) | O(N) | Greedy | | |
| 953 | Verifying an Alien Dictionary | Easy | O(A) | O(1) | Hash Table | | |
| 957 | Prison Cells After N Days | Medium | O(1) | O(1) | Hash Table | | |
| 958 | Check Completeness of a Binary Tree | Medium | O(N) | O(N) | Tree | | |
| 962 | Maximum Width Ramp | Medium | O(NlogN) | O(N) | Array | | |
| 966 | Vowel Spellchecker | Medium | O(N) | O(N) | Hash Table, String | | |
| 967 | Numbers With Same Consecutive Differences | Medium | O(N*2^N) | O(2^N) | DFS | | |
| 969 | Pancake Sorting | Medium | O(N^2) | O(N) | Array | | |
| 970 | Powerful Integers | Medium | O(logx*logy) | O(logx+logy) | Hash Table, Math | | |
| 971 | Flip Binary Tree To Match Preorder Traversal | Medium | O(N) | O(N) | Tree, DFS | | |
| 973 | K Closest Points to Origin | Medium | O(N log(K)) | O(K) | Divide and Conquer, Heap, Sort | | |
| 974 | Subarray Sums Divisible by K | Medium | O(N) | O(K) | Array, Hash Table | | |
| 976 | Largest Perimeter Triangle | Medium | O(NlogN) | O(N) | Math, Sort | | |
| 977 | Squares of a Sorted Array | Easy | O(N) | O(N) | Array, Two Pointers | | |
| 979 | Distribute Coins in Binary Tree | Medium | O(N) | O(H) | Tree, DFS | | |
| 980 | Unique Paths III | Medium | O(2^N) | O(N) | Backtracking, DFS | | |
| 983 | Minimum Cost For Tickets | Medium | O(365) | O(365) | LRU Cache, Dynamic Programming | | |
| 986 | Interval List Intersections | Medium | O(N + M) | O(1) | Two Pointers | | |
| 987 | Vertical Order Traversal of a Binary Tree | Medium | O(NlogN) | O(N) | Hash Table, Tree | | |
| 991 | Broken Calculator | Medium | O(logN) | O(1) | Math, Greedy | | |
| 992 | Subarrays with K Different Integers | Hard | O(N) | O(N) | Hash Talble, Two Pointers, Sliding Window | | |
| 993 | Cousins in Binary Tree | Easy | O(N) | O(H) | Trees, Recursion | | |
| 994 | Rotting Oranges | Medium | O(N^2) | O(N) | Trees, Recursion | | |
| 1003 | Check If Word Is Valid After Substitutions | Medium | O(N) | O(N) | String, Stack | | |
| 1004 | Max Consecutive Ones III | Medium | O(N) | O(1) | Sliding Window, Two Pointers | | |
| 1007 | Minimum Domino Rotations For Equal Row | Medium | O(N) | O(1) | Array, Greedy | | |
| 1010 | Pairs of Songs With Total Durations Divisible by 60 | Medium | O(N) | O(1) | Array, Math | | |
| 1011 | Capacity To Ship Packages Within D Days | Medium | O(NlogN) | O(1) | Array, Binary Search | | |
| 1014 | Best Sightseeing Pair | Medium | O(N) | O(1) | Array | | |
| 1015 | Smallest Integer Divisible by K | Medium | O(K) | O(K) | Math | | |
| 1022 | Sum of Root To Leaf Binary Numbers | Easy | O(N) | O(H) | Tree | | |
| 1023 | Camelcase Matching | Medium | O(Q*N) | O(Q) | String, Trie | | |
| 1024 | Video Stitching | Medium | O(NlogN) | O(1) | Dynamic Programming | | |
| 1026 | Maximum Difference Between Node and Ancestor | Medium | O(N) | O(H) | Tree, DFS | | |
| 1029 | Two City Scheduling | Easy | O(NlogN) | O(N) | Greedy | Good Problem | |
| 1032 | Stream of Characters | Hard | O(M) | O(M) | Trie | | |
| 1035 | Uncrossed Lines | Medium | O(N^2) | O(N) | Array, Dynamic Programming | | |
| 1042 | Flower Planting With No Adjacent | Medium | O(|V|+|E|) | O(|V|+|E|) | Graph | | |
| 1052 | Grumpy Bookstore Owner | Medium | O(N) | O(N) | Sliding Window, Array | | |
| 1053 | Previous Permutation With One Swap | Medium | O(N) | O(N) | Array, Greedy | | |
| 1054 | Distant Barcodes | Medium | O(NlogN) | O(N) | Sort, Heap | | |
| 1060 | Missing Element in Sorted Array | Medium | O(logN) | O(1) | Binary Search, Premium | | 🔒 |
| 1061 | Lexicographically Smallest Equivalent String | Medium | O(N) | O(N) | DFS, Union Find, Premium | | 🔒 |
| 1074 | Number of Submatrices That Sum to Target | Hard | O(R\*R\*C) | O(R\*C) | Array, Dynamic Programming, Sliding Window | | |
| 1080 | Insufficient Nodes in Root to Leaf Paths | Medium | O(N) | O(N) | DFS | | |
| 1091 | Shortest Path in Binary Matrix | Medium | O(N) | O(N) | BFS | | |
| 1094 | Car Pooling | Medium | O(N) | O(1) | Car Pooling | | |
| 1109 | Corporate Flight Bookings | Medium | O(N) | O(N) | Array, Math | | |
| 1130 | Minimum Cost Tree From Leaf Values | Medium | O(N) | O(N) | Dynamic Programming, Tree, Stack | | |
| 1162 | As Far from Land as Possible | Medium | O(N\*M) | O(N\*M) | Graph, BFS | | |
| 1192 | Critical Connections in a Network | Medium | O(V+E) | O(V+E) | DFS, Tarjan | New Algorithm | |
| 1209 | Remove All Adjacent Duplicates in String II | Medium | O(N) | O(N) | Stack | | |
| 1217 | Minimum Cost to Move Chips to The Same Position | Easy | O(N) | O(1) | Math, Greedy, Array | | |
| 1218 | Longest Arithmetic Subsequence of Given Difference | Medium | O(N) | O(N) | Hash Table, Math, Dynamic Programming | | |
| 1219 | Minimum CostPath with Maximum Gold | Medium | O(R\*C+N\*2^N) | O(N) | Backtracking | | |
| 1232 | Check If It Is a Straight Line | Easy | O(N) | O(1) | Math, Pythonic, Geometry | | |
| 1239 | Maximum Length of a Concatenated String with Unique Characters | Medium | O(2^N) | O(N) | Backtracking, Bit Manipulation | | |
| 1249 | Minimum Remove to Make Valid Parentheses | Medium | O(N) | O(N) | Stack, String | | |
| 1277 | Count Square Submatrices with All Ones | Medium | O(N * M) | O(1) | Array, Dynamic Programming | | |
| 1283 | Find the Smallest Divisor Given a Threshold | Medium | O(NlogNmax) | O(1) | Binary Search | | |
| 1288 | Remove Covered Intervals | Medium | O(N) | O(1) | Greedy, Sort, Line Sweep | | |
| 1290 | Convert Binary Number in a Linked List to Integer | Easy | O(N) | O(1) | Linked List, Bit Manipulation | | |
| 1291 | Sequential Digits | Medium | O(N) | O(N) | Backtracking | | |
| 1298 | Maximum Candies You Can Get from Boxes | Medium | O(B+K) | O(B) | BFS | | |
| 1305 | All Elements in Two Binary Search Trees | Medium | O(N) | O(N) | Sort, Tree | | |
| 1306 | All Elements inJump Game III | Medium | O(N) | O(N) | BFS, DFS, Recursion | | |
| 1315 | Sum of Nodes with Even-Valued Grandparent | Medium | O(N) | O(N) | Tree, DFS | | |
| 1332 | Remove Palindromic Subsequences | Easy | O(N) | O(1) | String | | |
| 1337 | The K Weakest Rows in a Matrix | Easy | O(MlogKlogN) | O(K) | Heap, Array, Binary Search | | |
| 1344 | Angle Between Hands of a Clock | Medium | O(1) | O(1) | Math | | |
| 1345 | Jump Game IV | Hard | O(N) | O(N) | BFS | | |
| 1354 | Construct Target Array With Multiple Sums | Hard | O(NlogN) | O(N) | Greedy, Heap | Very Hard | |
| 1371 | Find the Longest Substring Containing Vowels in Even Counts | Medium | O(N) | O(N) | String | | |
| 1375 | Bulb Switcher III | Medium | O(N) | O(1) | Array | | |
| 1387 | Sort Integers by The Power Value | Medium | O(NlogK) | O(N) | Sort, Graph | | |
| 1395 | Count Number of Teams | Medium | O(N^2) | O(1) | Array | | |
| 1396 | Design Underground System | Medium | O(N) | O(N) | Design | | |
| 1405 | Longest Happy String | Medium | O(N) | O(N) | Greedy, Dynamic Programming | | |
| 1419 | Minimum Number of Frogs Croaking | Medium | O(N) | O(1) | String | | |
| 1423 | Maximum Points You Can Obtain from Cards | Medium | O(N) | O(1) | Array, Dynamic Programming, Sliding Window | | |
| 1424 | Diagonal Traverse II | Medium | O(A) | O(A) | Array | | |
| 1426 | Counting Elements | Easy | O(N) | O(N) | Array, Premium | | 🔒 |
| 1427 | Perform String Shifts | Easy | O(N + S) | O(1) | Premium | | 🔒 |
| 1437 | Check If All 1's Are at Least Length K Places Away | Easy | O(N) | O(1) | Array | | |
| 1441 | Build an Array With Stack Operations | Easy | O(N) | O(N) | Pythonic | | |
| 1442 | Count Triplets That Can Form Two Arrays of Equal XOR | Medium | O(N) | O(N) | Array, Math, Bit Manipulation | | |
| 1443 | Minimum Time to Collect All Apples in a Tree | Medium | O(E) | O(E) | Tree, DFS | | |
| 1444 | Number of Ways of Cutting a Pizza | Hard | O(K\*R\*C\*(R+C)) | O(K\*R\*C) | Dynamic Programming | | |
| 1446 | Consecutive Characters | Easy | O(N) | O(1) | String | | |
| 1447 | Simplified Fractions | Medium | Varying | Varying | | | |
| 1448 | Count Good Nodes in Binary Tree | Medium | O(N) | O(H) | Tree, DFS | | |
| 1450 | Number of Students Doing Homework at a Given Time | Easy | O(N) | O(1) | | | |
| 1451 | Rearrange Words in a Sentence | Medium | O(N * logN) | O(1) | String, Sort | | |
| 1452 | People Whose List of Favorite Companies Is Not a Subset of Another List | Medium | O(N^2) | O(N) | String, Sort | There is a better solution | |
| 1455 | Check If a Word Occurs As a Prefix of Any Word in a Sentence | Medium | O(N) | O(1) | String, Pythonic | | |
| 1456 | Maximum Number of Vowels in a Substring of Given Length | Medium | O(N) | O(1) | String, Sliding Window | | |
| 1457 | Pseudo-Palindromic Paths in a Binary Tree | Medium | O(N) | O(H) | Bit Manipulation, Tree, DFS   | | |
| 1460 | Make Two Arrays Equal by Reversing Sub-arrays | Easy | O(N) | O(1) | Array | | |
| 1461 | Check If a String Contains All Binary Codes of Size K | Medium | O(N) | O(2**K) | String, Bit Manipulation | | |
| 1463 | Cherry Pickup II | hard | O(R\*C\*C) | O(R\*C\*C) | Dynamic Programming | | |
| 1464 | Maximum Product of Two Elements in an Array | Easy | O(N) | O(1) | Array | | |
| 1466 | Reorder Routes to Make All Paths Lead to the City Zero | Medium | O(\|V\|) | O(\|V\|) | Tree, DFS | | |
| 1470 | Shuffle the Array | Easy | O(N) | O(N) | Array | There is a better solution | |
| 1471 | The k Strongest Values in an Array | Medium | O(NlogN) | O(N) | Array, Sort | There is a better solution | |
| 1472 | Design Browser History | Medium | O(1) | O(1) | Design | | |
| 1474 | Delete N Nodes After M Nodes of a Linked List | Easy | O(N) | O(1) | Linked List, Premium | | 🔒 |
| 1475 | Final Prices With a Special Discount in a Shop | Easy | O(N) | O(1) | Monotonic Stack | | |
| 1476 | Subrectangle Queries | Easy | Varies | Varies | Design | | |
| 1480 | Running Sum of 1d Array | Easy | O(N) | O(1) | | | |
| 1481 | Least Number of Unique Integers after K Removals | Medium | O(NlogN) | O(N) | Array, Sort | | |
| 1482 | Minimum Number of Days to Make m Bouquets | Medium | O(NlogN) | O(N) | Array, Binary Search | | |
| 1486 | XOR Operation in an Array | Easy | O(1) | O(1) | Bit Manipulation | | |
| 1491 | Average Salary Excluding the Minimum and Maximum Salary | Easy | O(N) | O(1) | | | |
| 1492 | The kth Factor of n | Medium | O(logN) | O(logN) | Math, Tricky | | |
| 1493 | Longest Subarray of 1's After Deleting One Element | Medium | O(N) | O(1) | Array | | |
| 1496 | Path Crossing | Easy | O(N) | O(N) | String | | |
| 1502 | Can Make Arithmetic Progression From Sequence | Easy | O(NlogN) | O(1) | Array | | |
| 1507 | Reformat Date | Easy | O(1) | O(1) | String | | |
| 1508 | Range Sum of Sorted Subarray Sums | Medium | O(N^2logN) | O(N^2) | | | |
| 1509 | Minimum Difference Between Largest and Smallest Value in Three Moves | Medium | O(NlogN) | O(1) | | | |
| 1510 | Stone Game IV | Hard | O(N*N^0.5) | O(N) | Dynamic Programming | | |
| 1512 | Number of Good Pairs | Easy | O(N) | O(N) | | | |
| 1513 | Number of Substrings With Only 1s | Medium | O(N) | O(N) | String, Math | | |
| 1518 | Water Bottles | Easy | O(1) | O(1) | Greedy, Simulation | | |
| 1523 | Count Odd Numbers in an Interval Range | Easy | O(1) | O(1) | Math | | |
| 1524 | Number of Sub-arrays With Odd Sum | Medium | O(N) | O(1) | Array, Math, Dynamic Programming | | |
| 1525 | Number of Good Ways to Split a String | Medium | O(N) | O(N) | String | | |
| 1528 | Shuffle String | Easy | O(N) | O(N) | String | | |
| 1529 | Bulb Switcher IV | Medium | O(N) | O(1) | String | | |
| 1530 | Number of Good Leaf Nodes Pairs | Medium | O(N^2logN) | O(N) | Tree, DFS | | |
| 1533 | Find the Index of the Large Integer | Medium | O(logN) | O(1) | Premium, Binary Search | | 🔒 |
| 1535 | Find the Winner of an Array Game | Medium | O(N) | O(1) | Array | | |
| 1539 | Kth Missing Positive Number | Easy | O(logN) | O(1) | Binary Search | | |
| 1544 | Make The String Great | Easy | O(N) | O(N) | String, Stack | | |
| 1545 | Find Kth Bit in Nth Binary String | Medium | O(N^2) | O(N^2) | String | Not Optimal | |
| 1550 | Three Consecutive Odds | Easy | O(N) | O(1) | Array | | |
| 1551 | Minimum Operations to Make Array Equal | Medium | O(1) | O(1) | Math | | |
| 1552 | Magnetic Force Between Two Balls | Medium | O(NlogN) | O(1) | Binary Search | Template for Binary Search | |
| 1556 | Thousand Separator | Easy | O(N) | O(N) | String | | |
| 1557 | Minimum Number of Vertices to Reach All Nodes | Medium | O(N) | O(N) | Graph | | |
| 1558 | Minimum Numbers of Function Calls to Make Target Array | Medium | O(NlogK) | O(N) | Greedy, Simulation | | |
| 1560 | Most Visited Sector in a Circular Track | Easy | O(N) | O(1) | Array | | |
| 1561 | Maximum Number of Coins You Can Get | Medium | O(N) | O(1) | Sort | | |
| 1564 | Put Boxes Into the Warehouse I | Medium | O(NlogN) | O(N) | Greedy | | 🔒 |
| 1566 | Detect Pattern of Length M Repeated K or More Times | Easy | O(N) | O(1) | Array | | |
| 1572 | Matrix Diagonal Sum | Easy | O(N) | O(1) | Array | | |
| 1573 | Number of Ways to Split a String | Medium | O(N) | O(N) | String | | |
| 1576 | Replace All ?'s to Avoid Consecutive Repeating Characters | Easy | O(N) | O(N) | String | | |
| 1578 | Minimum Deletion Cost to Avoid Repeating Letters | Medium | O(N) | O(1) | Greedy | | |
| 1580 | Put Boxes Into the Warehouse II | Medium | O(NlogN) | O(N) | Greedy | | 🔒 |
| 1582 | Special Positions in a Binary Matrix | Easy | O(N) | O(N) | Array | | |
| 1583 | Count Unhappy Friends | Medium | O(N^2) | O(N^2) | Array | | |
| 1588 | Sum of All Odd Length Subarrays | Easy | O(N) | O(1) | Array | | |
| 1592 | Rearrange Spaces Between Words | Easy | O(N) | O(N) | String | | |
| 1598 | Crawler Log Folder | Easy | O(N) | O(1) | Stack | | |
| 1600 | Throne Inheritance | Medium | O(N) | O(N) | Tree, Design | | |
| 1602 | Find Nearest Right Node in Binary Tree | Medium | O(N) | O(N) | Premium, Tree, BFS | | 🔒 |
| 1604 | Alert Using Same Key-Card Three or More Times in a One Hour Period | Medium | O(NlogN) | O(N) | String, Ordered Map | | |
| 1605 | Find Valid Matrix Given Row and Column Sums | Medium | O(NM) | O(NM) | Greedy | | |
| 1608 | Special Array With X Elements Greater Than or Equal X | Easy | O(NlogN) | O(N) | Binary Search, Array | | |
| 1609 | Even Odd Tree | Easy | O(N) | O(N) | Tree | | |
| 1614 | Maximum Nesting Depth of the Parentheses | Easy | O(N) | O(1) | String | | |
| 1615 | Maximal Network Rank | Medium | O(N) | O(1) | Graph | | |
| 1618 | Maximum Font to Fit a Sentence in a Screen | Medium | O(logN) | O(1) | Premium, String, Binary Search | | 🔒 |
| 1624 | Largest Substring Between Two Equal Characters | Easy | O(N) | O(1) | String | | |
| 1625 | Lexicographically Smallest String After Applying Operations | Medium | O(N*N) | O(N) | BFS, DFS | | |
| 1629 | Slowest Key | Easy | O(N) | O(1) | String | | |
| 1631 | Path With Minimum Effort | Medium | O(N\*M\*logH) | O(M\*N) | Binary Search, DFS, BFS, Union Find, Graph | | |
| 1634 | Add Two Polynomials Represented as Linked Lists | Medium | O(N) | O(1) | Premium, Linked List | | 🔒 |
| 1639 | Number of Ways to Form a Target String Given a Dictionary | Hard | O(N\*M) | O(N\*M) | Dynamic Programming | | |
| 1640 | Check Array Formation Through Concatenation | Medium | O(N) | O(N) | Array | | |
| 1641 | Count Sorted Vowel Strings | Medium | O(N) | O(1) | Dynamic Programming, Math, Backtracking | | |
| 1642 | Furthest Building You Can Reach | Medium | O(NlogN) | O(N) | Binary Search, Heap | | |
| 1644 | Lowest Common Ancestor of a Binary Tree II | Medium | O(N) | O(H) | Premium, Tree | | 🔒 |
| 1646 | Get Maximum in Generated Array | Easy | O(N) | O(N) | Array | | |
| 1647 | Minimum Deletions to Make Character Frequencies Unique | Medium | O(1) | O(1) | Greedy, Sort | | |
| 1650 | Lowest Common Ancestor of a Binary Tree III | Medium | O(H) | O(1) | Premium, Tree | | 🔒 |
| 1652 | Defuse the Bomb | Medium | O(N) | O(N) | Array | | |
| 1653 | Minimum Deletions to Make String Balanced | Medium | O(N) | O(N) | Greedy, String | | |
| 1656 | Design an Ordered Stream | Easy | O(N) | O(N) | Array, Design | | |
| 1657 | Determine if Two Strings Are Close | Medium | O(N) | O(1) | Greedy | | |
| 1658 | Minimum Operations to Reduce X to Zero | Medium | O(N) | O(N) | Greedy, Sliding Window | | |
| 1663 | Smallest String With A Given Numeric Value | Medium | O(N) | O(1) | Greedy | | |
| 1664 | Ways to Make a Fair Array | Medium | O(N) | O(1) | Dynamic Programming, Greedy | | |
| 1673 | Find the Most Competitive Subsequence | Medium | O(N) | O(K) | Stack, Heap, Greedy, Queue | | |
| 1679 | Max Number of K-Sum Pairs | Medium | O(N) | O(N) | Hash Table | | |
| 1684 | Count the Number of Consistent Strings | Easy | O(N) | O(1) | String | | |
| 1685 | Sum of Absolute Differences in a Sorted Array | Medium | O(N) | O(N) | Math, Greedy | | |
| 1695 | Maximum Erasure Value | Medium | O(N) | O(1) | Two Pointers | | |
| 1700 | Number of Students Unable to Eat Lunch | Medium | O(N) | O(1) | Array | | |
| 1705 | Maximum Number of Eaten Apples | Medium | O(NlogN) | O(N) | Heap, Greedy | | |
| 1706 | Where Will the Ball Fall | Medium | O(N*M) | O(M) | Dynamic Programming | | |
| 1710 | Maximum Units on a Truck | Medium | O(NlogN) | O(N) | Greedy, Sort | | |
| 1716 | Calculate Money in Leetcode Bank | Easy | O(N) | O(1) | Math, Greedy | | |
| 1721 | Swapping Nodes in a Linked List | Medium | O(N) | O(1) | Linked List | | |
| 1725 | Number Of Rectangles That Can Form The Largest Square | Easy | O(N) | O(1) | Greedy | | |
| 1726 | Tuple with Same Product | Medium | O(N^2) | O(N) | Array, Hash Table | | |
| 1732 | Find the Highest Altitude | Easy | O(N) | O(1) | Array | | |
| 1736 | Latest Time by Replacing Hidden Digits | Easy | O(1) | O(1) | String, Greedy | | |
| 1748 | Sum of Unique Elements | Easy | O(N) | O(N) | Array, Hash Table | | |
| 1749 | Maximum Absolute Sum of Any Subarray | Medium | O(N) | O(1) | Greedy | | |
| 1750 | Minimum Length of String After Deleting Similar Ends | Medium | O(N) | O(1) | Two Pointers | | |
| 1752 | Check if Array Is Sorted and Rotated | Easy | O(N) | O(1) | Array | | |
| 1753 | Maximum Score From Removing Stones | Medium | O(1) | O(1) | Math, Heap | | |
| 1758 | Minimum Changes To Make Alternating Binary String | Easy | O(N) | O(1) | Array, Greedy | | |
| 1759 | Count Number of Homogenous Substrings | Medium | O(N) | O(1) | String, Greedy | | |
| 1763 | Longest Nice Substring | Easy | O(NlogN) | O(N) | String | | |
| 1764 | Form Array by Concatenating Subarrays of Another Array | Medium | O(N+M) | O(M) | Array, Greedy | New Algorithm (KMP) | |
| 1765 | Map of Highest Peak | Medium | O(N\*M) | O(N\*M) | BFS, Graph | | |
| 1768 | Merge Strings Alternately | Easy | O(N) | O(N) | String | | |
| 1769 | Minimum Number of Operations to Move All Balls to Each Box | Medium | O(N) | O(N) | Array, Greedy | | |
| 1773 | Count Items Matching a Rule | Easy | O(N) | O(1) | Array, String | | |
| 1774 | Closest Dessert Cost | Medium | O(N\*M\*V) | O(M\*V) | Greedy | | |
| 1779 | Find Nearest Point That Has the Same X or Y Coordinate | Easy | O(N) | O(1) | Array | | |
| 1780 | Check if Number is a Sum of Powers of Three | Medium | O(logN) | O(1) | Math, Backtracking, Recursion | | |
| 1783 | Sum of Beauty of All Substrings | Medium | O(N^2) | O(1) | Hash Table, String | | |
| 1784 | Check if Binary String Has at Most One Segment of Ones | Easy | O(N) | O(1) | Greedy | | |
| 1791 | Find Center of Star Graph | Medium | O(1) | O(1) | Graph | | |
| 1792 | Maximum Average Pass Ratio | Medium | O(N+KlogN) | O(N) | Heap | | |
| 1816 | Truncate Sentence | Easy | O(N) | O(1) | String | | |
| 1818 | Minimum Absolute Sum Difference | Medium | O(NlogN) | O(sort) | Binary Search, Greedy | | |
| 1827 | Minimum Operations to Make the Array Increasing | Easy | O(N) | O(1) | Array, Greedy | | |
| 1828 | Queries on Number of Points Inside a Circle | Medium | O(N*M) | O(M) | Math | | |
| 1832 | Check if the Sentence Is Pangram | Easy | O(N) | O(1) | String | | |
| 1833 | Maximum Ice Cream Bars | Medium | O(NlogN) | O(sort) | Array, Sort | | |
| 1837 | Sum of Digits in Base K | Medium | O(logN) | O(1) | Math, Bit Manipulation | | |
| 1839 | Longest Substring Of All Vowels in Order | Medium | O(N) | O(1) | Two Pointers, String | | |

# Useful Posts:

- [Important and Useful links from all over the LeetCode](https://leetcode.com/discuss/general-discussion/665604/Important-and-Useful-links-from-all-over-the-LeetCode)
- Graph: https://leetcode.com/discuss/general-discussion/655708/Graph-For-Beginners-Problems-or-Pattern-or-Sample-Solutions 
- Sliding Windows: https://leetcode.com/discuss/general-discussion/657507/Sliding-Window-for-Beginners-Problems-or-Template-or-Sample-Solutions
- Trie: https://leetcode.com/discuss/general-discussion/680706/Article-on-Trie.-General-Template-and-List-of-problems. 
- Graph: https://leetcode.com/discuss/general-discussion/969327/graph-algorithms-one-place-dijkstra-bellman-ford-floyd-warshall-prims-kruskals-dsu
- [Template for Hard String Problems](https://leetcode.com/problems/minimum-window-substring/discuss/26808/Here-is-a-10-line-template-that-can-solve-most-'substring'-problems)
- [Powerful studying program for Beginners and Intermediate levels. All common mistakes analyzed.](https://leetcode.com/discuss/general-discussion/1129503/powerful-studying-program-for-beginners-and-intermediate-levels-all-common-mistakes-analyzed)
- [Bit Hacks](https://leetcode.com/discuss/general-discussion/1151183/bits-can-hack-the-world-beginners-guide-bit-hacks-with-proper-approach)
- [More Bit Hacks](https://leetcode.com/discuss/study-guide/1151183/things-which-you-cant-ignore-in-coding)

## Dynamic Programming

- https://leetcode.com/discuss/general-discussion/662866/dp-for-beginners-problems-patterns-sample-solutions
- https://leetcode.com/discuss/interview-question/491522/dynamic-programming-questions-thread
- https://leetcode.com/discuss/general-discussion/458695/Dynamic-Programming-Patterns
- https://leetcode.com/discuss/general-discussion/868902/dynamic-programming
- https://leetcode.com/discuss/general-discussion/1081421/powerful-dynamic-programming-explanation

## System Design

- [✅ Helpful list of LeetCode Posts on System Design at Facebook, Google, Amazon, Uber, Microsoft](https://leetcode.com/discuss/interview-question/1140451/helpful-list-of-leetcode-posts-on-system-design-at-facebook-google-amazon-uber-microsoft)
- https://leetcode.com/discuss/interview-question/object-oriented-design/1177601/flipkart-machine-coding-design-online-coding-platform-coding-blox-design-leetcode-lld

## LP

- [Amazon LPs Compiled](https://leetcode.com/discuss/interview-experience/1149636/amazon-lps-compiled)

## Others

- https://leetcode.com/discuss/general-discussion/705117/requesting-guidance-from-those-who-solved-1000-leets-so-far

## List

- [Amazon Questions](https://leetcode.com/list/5ecpr1th/)