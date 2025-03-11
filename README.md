# LeetCode-in-C

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/LeetCode-in-C/LeetCode-in-C/blob/main/LICENSE)
[![](https://img.shields.io/github/stars/LeetCode-in-C/LeetCode-in-C?style=flat-square)](https://github.com/LeetCode-in-C/LeetCode-in-C)
[![](https://img.shields.io/github/forks/LeetCode-in-C/LeetCode-in-C?style=flat-square)](https://github.com/LeetCode-in-C/LeetCode-in-C/fork)

C-based LeetCode algorithm problem solutions, regularly updated.

> ["For coding interview preparation, LeetCode is one of the best online resource providing a rich library of more than 300 real coding interview questions for you to practice from using one of the 7 supported languages - C, C++, Java, Python, C#, JavaScript, Ruby."](https://www.quora.com/How-effective-is-Leetcode-for-preparing-for-technical-interviews)

##
* [Algorithm II](#algorithm-ii)
* [Binary Search I](#binary-search-i)
* [Binary Search II](#binary-search-ii)
* [Dynamic Programming I](#dynamic-programming-i)
* [Programming Skills I](#programming-skills-i)
* [Programming Skills II](#programming-skills-ii)
* [Graph Theory I](#graph-theory-i)
* [SQL I](#sql-i)
* [Level 1](#level-1)
* [Level 2](#level-2)
* [Udemy](#udemy)
* [Top Interview 150](#top-interview-150)
* [Data Structure I](#data-structure-i)
* [Data Structure II](#data-structure-ii)
* [Algorithm I](#algorithm-i)

### Algorithm II

#### Day 1 Binary Search

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0034 |[Find First and Last Position of Element in Sorted Array](src/main/c/g0001_0100/s0034_find_first_and_last_position_of_element_in_sorted_array/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Binary_Search, Big_O_Time_O(log_n)_Space_O(1) | 0 | 100.00
| 0033 |[Search in Rotated Sorted Array](src/main/c/g0001_0100/s0033_search_in_rotated_sorted_array/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Binary_Search, Big_O_Time_O(log_n)_Space_O(1) | 0 | 100.00
| 0074 |[Search a 2D Matrix](src/main/c/g0001_0100/s0074_search_a_2d_matrix/Solution.c)| Medium | Top_100_Liked_Questions, Array, Binary_Search, Matrix, Big_O_Time_O(endRow+endCol)_Space_O(1) | 0 | 100.00

#### Day 2 Binary Search

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0153 |[Find Minimum in Rotated Sorted Array](src/main/c/g0101_0200/s0153_find_minimum_in_rotated_sorted_array/Solution.c)| Medium | Top_100_Liked_Questions, Array, Binary_Search, Big_O_Time_O(log_N)_Space_O(log_N) | 0 | 100.00

#### Day 3 Two Pointers

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0015 |[3Sum](src/main/c/g0001_0100/s0015_3sum/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Sorting, Two_Pointers, Big_O_Time_O(n\*log(n))_Space_O(n^2) | 47 | 87.75

#### Day 4 Two Pointers

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0011 |[Container With Most Water](src/main/c/g0001_0100/s0011_container_with_most_water/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Greedy, Two_Pointers, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00

#### Day 5 Sliding Window

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0438 |[Find All Anagrams in a String](src/main/c/g0401_0500/s0438_find_all_anagrams_in_a_string/Solution.c)| Medium | Top_100_Liked_Questions, String, Hash_Table, Sliding_Window, Big_O_Time_O(n+m)_Space_O(1) | 0 | 100.00

#### Day 6 Breadth First Search Depth First Search

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0200 |[Number of Islands](src/main/c/g0101_0200/s0200_number_of_islands/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Depth_First_Search, Breadth_First_Search, Matrix, Union_Find, Big_O_Time_O(M\*N)_Space_O(M\*N) | 14 | 96.18

#### Day 7 Breadth First Search Depth First Search

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 8 Breadth First Search Depth First Search

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 9 Recursion Backtracking

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0078 |[Subsets](src/main/c/g0001_0100/s0078_subsets/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Bit_Manipulation, Backtracking, Big_O_Time_O(2^n)_Space_O(n\*2^n) | 0 | 100.00

#### Day 10 Recursion Backtracking

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0039 |[Combination Sum](src/main/c/g0001_0100/s0039_combination_sum/Solution.c)| Medium | Top_100_Liked_Questions, Array, Backtracking, Big_O_Time_O(2^n)_Space_O(n+2^n) | 0 | 100.00

#### Day 11 Recursion Backtracking

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0017 |[Letter Combinations of a Phone Number](src/main/c/g0001_0100/s0017_letter_combinations_of_a_phone_number/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Hash_Table, Backtracking, Big_O_Time_O(4^n)_Space_O(n) | 0 | 100.00
| 0022 |[Generate Parentheses](src/main/c/g0001_0100/s0022_generate_parentheses/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Dynamic_Programming, Backtracking, Big_O_Time_O(2^n)_Space_O(n) | 0 | 100.00
| 0079 |[Word Search](src/main/c/g0001_0100/s0079_word_search/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Matrix, Backtracking, Big_O_Time_O(4^(m\*n))_Space_O(m\*n) | 121 | 92.31

#### Day 12 Dynamic Programming

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0055 |[Jump Game](src/main/c/g0001_0100/s0055_jump_game/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Greedy, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00

#### Day 13 Dynamic Programming

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0045 |[Jump Game II](src/main/c/g0001_0100/s0045_jump_game_ii/Solution.c)| Medium | Top_100_Liked_Questions, Array, Dynamic_Programming, Greedy, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0062 |[Unique Paths](src/main/c/g0001_0100/s0062_unique_paths/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Dynamic_Programming, Math, Combinatorics, Big_O_Time_O(m\*n)_Space_O(m\*n) | 0 | 100.00

#### Day 14 Dynamic Programming

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0005 |[Longest Palindromic Substring](src/main/c/g0001_0100/s0005_longest_palindromic_substring/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Dynamic_Programming, Big_O_Time_O(n)_Space_O(n) | 2 | 97.74

#### Day 15 Dynamic Programming

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0139 |[Word Break](src/main/c/g0101_0200/s0139_word_break/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Hash_Table, Dynamic_Programming, Trie, Memoization, Big_O_Time_O(M+max\*N)_Space_O(M+N+max) | 0 | 100.00

#### Day 16 Dynamic Programming

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0300 |[Longest Increasing Subsequence](src/main/c/g0201_0300/s0300_longest_increasing_subsequence/Solution.c)| Medium | Top_100_Liked_Questions, Array, Dynamic_Programming, Binary_Search, Big_O_Time_O(n\*log_n)_Space_O(n) | 0 | 100.00

#### Day 17 Dynamic Programming

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 1143 |[Longest Common Subsequence](src/main/c/g1101_1200/s1143_longest_common_subsequence/Solution.c)| Medium | Top_100_Liked_Questions, String, Dynamic_Programming, Big_O_Time_O(n\*m)_Space_O(n\*m) | 21 | 84.72

#### Day 18 Dynamic Programming

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0072 |[Edit Distance](src/main/c/g0001_0100/s0072_edit_distance/Solution.c)| Medium | Top_100_Liked_Questions, String, Dynamic_Programming, Big_O_Time_O(n^2)_Space_O(n2) | 0 | 100.00
| 0322 |[Coin Change](src/main/c/g0301_0400/s0322_coin_change/Solution.c)| Medium | Top_100_Liked_Questions, Array, Dynamic_Programming, Breadth_First_Search, Big_O_Time_O(m\*n)_Space_O(amount) | 22 | 87.50

#### Day 19 Bit Manipulation

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 20 Others

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 21 Others

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

### Binary Search I

#### Day 1

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 2

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0035 |[Search Insert Position](src/main/c/g0001_0100/s0035_search_insert_position/Solution.c)| Easy | Top_100_Liked_Questions, Array, Binary_Search, Big_O_Time_O(log_n)_Space_O(1) | 0 | 100.00

#### Day 3

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 4

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 5

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0034 |[Find First and Last Position of Element in Sorted Array](src/main/c/g0001_0100/s0034_find_first_and_last_position_of_element_in_sorted_array/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Binary_Search, Big_O_Time_O(log_n)_Space_O(1) | 0 | 100.00

#### Day 6

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 7

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 8

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0074 |[Search a 2D Matrix](src/main/c/g0001_0100/s0074_search_a_2d_matrix/Solution.c)| Medium | Top_100_Liked_Questions, Array, Binary_Search, Matrix, Big_O_Time_O(endRow+endCol)_Space_O(1) | 0 | 100.00

#### Day 9

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 10

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 11

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0033 |[Search in Rotated Sorted Array](src/main/c/g0001_0100/s0033_search_in_rotated_sorted_array/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Binary_Search, Big_O_Time_O(log_n)_Space_O(1) | 0 | 100.00

#### Day 12

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0153 |[Find Minimum in Rotated Sorted Array](src/main/c/g0101_0200/s0153_find_minimum_in_rotated_sorted_array/Solution.c)| Medium | Top_100_Liked_Questions, Array, Binary_Search, Big_O_Time_O(log_N)_Space_O(log_N) | 0 | 100.00

### Binary Search II

#### Day 1

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 2

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 3

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0300 |[Longest Increasing Subsequence](src/main/c/g0201_0300/s0300_longest_increasing_subsequence/Solution.c)| Medium | Top_100_Liked_Questions, Array, Dynamic_Programming, Binary_Search, Big_O_Time_O(n\*log_n)_Space_O(n) | 0 | 100.00

#### Day 4

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 5

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0287 |[Find the Duplicate Number](src/main/c/g0201_0300/s0287_find_the_duplicate_number/Solution.c)| Medium | Top_100_Liked_Questions, Array, Binary_Search, Two_Pointers, Bit_Manipulation, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00

#### Day 6

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 7

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 8

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0240 |[Search a 2D Matrix II](src/main/c/g0201_0300/s0240_search_a_2d_matrix_ii/Solution.c)| Medium | Top_100_Liked_Questions, Array, Binary_Search, Matrix, Divide_and_Conquer, Big_O_Time_O(n+m)_Space_O(1) | 42 | 96.34

#### Day 9

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 10

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 11

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 12

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 13

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 14

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 15

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 16

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 17

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 18

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 19

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 20

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

### Dynamic Programming I

#### Day 1

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 2

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0070 |[Climbing Stairs](src/main/c/g0001_0100/s0070_climbing_stairs/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Dynamic_Programming, Math, Memoization, Big_O_Time_O(n)_Space_O(n) | 1 | 100.00

#### Day 3

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0198 |[House Robber](src/main/c/g0101_0200/s0198_house_robber/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00

#### Day 4

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0055 |[Jump Game](src/main/c/g0001_0100/s0055_jump_game/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Greedy, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0045 |[Jump Game II](src/main/c/g0001_0100/s0045_jump_game_ii/Solution.c)| Medium | Top_100_Liked_Questions, Array, Dynamic_Programming, Greedy, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00

#### Day 5

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0053 |[Maximum Subarray](src/main/c/g0001_0100/s0053_maximum_subarray/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Divide_and_Conquer, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00

#### Day 6

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0152 |[Maximum Product Subarray](src/main/c/g0101_0200/s0152_maximum_product_subarray/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Big_O_Time_O(N)_Space_O(1) | 0 | 100.00

#### Day 7

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0121 |[Best Time to Buy and Sell Stock](src/main/c/g0101_0200/s0121_best_time_to_buy_and_sell_stock/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Big_O_Time_O(N)_Space_O(1) | 0 | 100.00

#### Day 8

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 9

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0139 |[Word Break](src/main/c/g0101_0200/s0139_word_break/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Hash_Table, Dynamic_Programming, Trie, Memoization, Big_O_Time_O(M+max\*N)_Space_O(M+N+max) | 0 | 100.00
| 0042 |[Trapping Rain Water](src/main/c/g0001_0100/s0042_trapping_rain_water/Solution.c)| Hard | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Two_Pointers, Stack, Monotonic_Stack, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00

#### Day 10

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 11

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0096 |[Unique Binary Search Trees](src/main/c/g0001_0100/s0096_unique_binary_search_trees/Solution.c)| Medium | Dynamic_Programming, Math, Tree, Binary_Tree, Binary_Search_Tree, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00

#### Day 12

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 13

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 14

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 15

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0062 |[Unique Paths](src/main/c/g0001_0100/s0062_unique_paths/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Dynamic_Programming, Math, Combinatorics, Big_O_Time_O(m\*n)_Space_O(m\*n) | 0 | 100.00

#### Day 16

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0064 |[Minimum Path Sum](src/main/c/g0001_0100/s0064_minimum_path_sum/Solution.c)| Medium | Top_100_Liked_Questions, Array, Dynamic_Programming, Matrix, Big_O_Time_O(m\*n)_Space_O(m\*n) | 0 | 100.00
| 0221 |[Maximal Square](src/main/c/g0201_0300/s0221_maximal_square/Solution.c)| Medium | Array, Dynamic_Programming, Matrix, Big_O_Time_O(m\*n)_Space_O(m\*n) | 0 | 100.00

#### Day 17

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0005 |[Longest Palindromic Substring](src/main/c/g0001_0100/s0005_longest_palindromic_substring/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Dynamic_Programming, Big_O_Time_O(n)_Space_O(n) | 2 | 97.74

#### Day 18

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0300 |[Longest Increasing Subsequence](src/main/c/g0201_0300/s0300_longest_increasing_subsequence/Solution.c)| Medium | Top_100_Liked_Questions, Array, Dynamic_Programming, Binary_Search, Big_O_Time_O(n\*log_n)_Space_O(n) | 0 | 100.00

#### Day 19

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 1143 |[Longest Common Subsequence](src/main/c/g1101_1200/s1143_longest_common_subsequence/Solution.c)| Medium | Top_100_Liked_Questions, String, Dynamic_Programming, Big_O_Time_O(n\*m)_Space_O(n\*m) | 21 | 84.72
| 0072 |[Edit Distance](src/main/c/g0001_0100/s0072_edit_distance/Solution.c)| Medium | Top_100_Liked_Questions, String, Dynamic_Programming, Big_O_Time_O(n^2)_Space_O(n2) | 0 | 100.00

#### Day 20

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0322 |[Coin Change](src/main/c/g0301_0400/s0322_coin_change/Solution.c)| Medium | Top_100_Liked_Questions, Array, Dynamic_Programming, Breadth_First_Search, Big_O_Time_O(m\*n)_Space_O(amount) | 22 | 87.50

#### Day 21

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

### Programming Skills I

#### Day 1 Basic Data Type

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 2 Operator

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 3 Conditional Statements

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 4 Loop

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 5 Function

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 6 Array

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0283 |[Move Zeroes](src/main/c/g0201_0300/s0283_move_zeroes/Solution.c)| Easy | Top_100_Liked_Questions, Array, Two_Pointers, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00

#### Day 7 Array

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 8 String

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 9 String

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 10 Linked List and Tree

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0104 |[Maximum Depth of Binary Tree](src/main/c/g0101_0200/s0104_maximum_depth_of_binary_tree/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Depth_First_Search, Breadth_First_Search, Tree, Binary_Tree, Big_O_Time_O(N)_Space_O(H) | 0 | 100.00

#### Day 11 Containers and Libraries

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 12 Class and Object

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

### Programming Skills II

#### Day 1

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 2

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 3

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 4

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 5

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 6

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0739 |[Daily Temperatures](src/main/c/g0701_0800/s0739_daily_temperatures/Solution.c)| Medium | Top_100_Liked_Questions, Array, Stack, Monotonic_Stack, Big_O_Time_O(n)_Space_O(n) | 3 | 98.31

#### Day 7

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0048 |[Rotate Image](src/main/c/g0001_0100/s0048_rotate_image/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Math, Matrix, Big_O_Time_O(n^2)_Space_O(1) | 0 | 100.00

#### Day 8

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 9

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 10

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 11

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0049 |[Group Anagrams](src/main/c/g0001_0100/s0049_group_anagrams/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, String, Hash_Table, Sorting, Big_O_Time_O(n\*k_log_k)_Space_O(n) | 3 | 100.00

#### Day 12

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0438 |[Find All Anagrams in a String](src/main/c/g0401_0500/s0438_find_all_anagrams_in_a_string/Solution.c)| Medium | Top_100_Liked_Questions, String, Hash_Table, Sliding_Window, Big_O_Time_O(n+m)_Space_O(1) | 0 | 100.00

#### Day 13

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 14

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0138 |[Copy List with Random Pointer](src/main/c/g0101_0200/s0138_copy_list_with_random_pointer/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Hash_Table, Linked_List, Big_O_Time_O(N)_Space_O(N) | 4 | 91.18

#### Day 15

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0002 |[Add Two Numbers](src/main/c/g0001_0100/s0002_add_two_numbers/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Math, Linked_List, Recursion, Big_O_Time_O(max(N,M))_Space_O(max(N,M)), AI_can_be_used_to_solve_the_task | 12 | 70.50

#### Day 16

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 17

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 18

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0155 |[Min Stack](src/main/c/g0101_0200/s0155_min_stack/MinStack.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Stack, Design, Big_O_Time_O(1)_Space_O(N) | 0 | 100.00

#### Day 19

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 20

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

### Graph Theory I

#### Day 1 Matrix Related Problems

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0200 |[Number of Islands](src/main/c/g0101_0200/s0200_number_of_islands/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Depth_First_Search, Breadth_First_Search, Matrix, Union_Find, Big_O_Time_O(M\*N)_Space_O(M\*N) | 14 | 96.18

#### Day 2 Matrix Related Problems

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 3 Matrix Related Problems

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 4 Matrix Related Problems

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 5 Matrix Related Problems

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 6 Matrix Related Problems

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 7 Standard Traversal

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 8 Standard Traversal

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 9 Standard Traversal

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 10 Standard Traversal

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 11 Breadth First Search

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 12 Breadth First Search

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 13 Graph Theory

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 14 Graph Theory

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

### SQL I

#### Day 1 Select

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 2 Select and Order

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 3 String Processing Functions

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 4 Union and Select

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 5 Union

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 6 Union

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 7 Function

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 8 Function

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 9 Control of Flow

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 10 Where

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

### Level 1

#### Day 1 Prefix Sum

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 2 String

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 3 Linked List

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0021 |[Merge Two Sorted Lists](src/main/c/g0001_0100/s0021_merge_two_sorted_lists/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Linked_List, Recursion, Big_O_Time_O(m+n)_Space_O(m+n) | 0 | 100.00
| 0206 |[Reverse Linked List](src/main/c/g0201_0300/s0206_reverse_linked_list/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Linked_List, Recursion, Big_O_Time_O(N)_Space_O(1) | 0 | 100.00

#### Day 4 Linked List

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0142 |[Linked List Cycle II](src/main/c/g0101_0200/s0142_linked_list_cycle_ii/Solution.c)| Medium | Top_100_Liked_Questions, Hash_Table, Two_Pointers, Linked_List, Big_O_Time_O(N)_Space_O(1) | 4 | 81.55

#### Day 5 Greedy

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0121 |[Best Time to Buy and Sell Stock](src/main/c/g0101_0200/s0121_best_time_to_buy_and_sell_stock/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Big_O_Time_O(N)_Space_O(1) | 0 | 100.00

#### Day 6 Tree

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0102 |[Binary Tree Level Order Traversal](src/main/c/g0101_0200/s0102_binary_tree_level_order_traversal/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Breadth_First_Search, Tree, Binary_Tree, Big_O_Time_O(N)_Space_O(N) | 0 | 100.00

#### Day 7 Binary Search

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 8 Binary Search Tree

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0098 |[Validate Binary Search Tree](src/main/c/g0001_0100/s0098_validate_binary_search_tree/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Depth_First_Search, Tree, Binary_Tree, Binary_Search_Tree, Big_O_Time_O(N)_Space_O(log(N)) | 0 | 100.00

#### Day 9 Graph/BFS/DFS

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0200 |[Number of Islands](src/main/c/g0101_0200/s0200_number_of_islands/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Depth_First_Search, Breadth_First_Search, Matrix, Union_Find, Big_O_Time_O(M\*N)_Space_O(M\*N) | 14 | 96.18

#### Day 10 Dynamic Programming

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0070 |[Climbing Stairs](src/main/c/g0001_0100/s0070_climbing_stairs/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Dynamic_Programming, Math, Memoization, Big_O_Time_O(n)_Space_O(n) | 1 | 100.00

#### Day 11 Dynamic Programming

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0062 |[Unique Paths](src/main/c/g0001_0100/s0062_unique_paths/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Dynamic_Programming, Math, Combinatorics, Big_O_Time_O(m\*n)_Space_O(m\*n) | 0 | 100.00

#### Day 12 Sliding Window/Two Pointer

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0438 |[Find All Anagrams in a String](src/main/c/g0401_0500/s0438_find_all_anagrams_in_a_string/Solution.c)| Medium | Top_100_Liked_Questions, String, Hash_Table, Sliding_Window, Big_O_Time_O(n+m)_Space_O(1) | 0 | 100.00

#### Day 13 Hashmap

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0001 |[Two Sum](src/main/c/g0001_0100/s0001_two_sum/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Array, Hash_Table, Big_O_Time_O(n)_Space_O(n), AI_can_be_used_to_solve_the_task | 2 | 99.56

#### Day 14 Stack

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0394 |[Decode String](src/main/c/g0301_0400/s0394_decode_string/Solution.c)| Medium | Top_100_Liked_Questions, String, Stack, Recursion, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00

#### Day 15 Heap

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

### Level 2

#### Day 1 Implementation/Simulation

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 2 String

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 3 Linked List

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0019 |[Remove Nth Node From End of List](src/main/c/g0001_0100/s0019_remove_nth_node_from_end_of_list/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Two_Pointers, Linked_List, Big_O_Time_O(L)_Space_O(L) | 0 | 100.00
| 0234 |[Palindrome Linked List](src/main/c/g0201_0300/s0234_palindrome_linked_list/Solution.c)| Easy | Top_100_Liked_Questions, Two_Pointers, Stack, Linked_List, Recursion, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00

#### Day 4 Linked List

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0148 |[Sort List](src/main/c/g0101_0200/s0148_sort_list/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Sorting, Two_Pointers, Linked_List, Divide_and_Conquer, Merge_Sort, Big_O_Time_O(log(N))_Space_O(log(N)) | 3 | 100.00

#### Day 5 Greedy

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 6 Tree

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0226 |[Invert Binary Tree](src/main/c/g0201_0300/s0226_invert_binary_tree/Solution.c)| Easy | Top_100_Liked_Questions, Depth_First_Search, Breadth_First_Search, Tree, Binary_Tree, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00

#### Day 7 Tree

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0543 |[Diameter of Binary Tree](src/main/c/g0501_0600/s0543_diameter_of_binary_tree/Solution.c)| Easy | Top_100_Liked_Questions, Depth_First_Search, Tree, Binary_Tree, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0437 |[Path Sum III](src/main/c/g0401_0500/s0437_path_sum_iii/Solution.c)| Medium | Depth_First_Search, Tree, Binary_Tree, Big_O_Time_O(n)_Space_O(n) | 6 | 96.00

#### Day 8 Binary Search

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0074 |[Search a 2D Matrix](src/main/c/g0001_0100/s0074_search_a_2d_matrix/Solution.c)| Medium | Top_100_Liked_Questions, Array, Binary_Search, Matrix, Big_O_Time_O(endRow+endCol)_Space_O(1) | 0 | 100.00
| 0033 |[Search in Rotated Sorted Array](src/main/c/g0001_0100/s0033_search_in_rotated_sorted_array/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Binary_Search, Big_O_Time_O(log_n)_Space_O(1) | 0 | 100.00

#### Day 9 Binary Search Tree

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0230 |[Kth Smallest Element in a BST](src/main/c/g0201_0300/s0230_kth_smallest_element_in_a_bst/Solution.c)| Medium | Top_100_Liked_Questions, Depth_First_Search, Tree, Binary_Tree, Binary_Search_Tree, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00

#### Day 10 Graph/BFS/DFS

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 11 Graph/BFS/DFS

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 12 Dynamic Programming

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0198 |[House Robber](src/main/c/g0101_0200/s0198_house_robber/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0322 |[Coin Change](src/main/c/g0301_0400/s0322_coin_change/Solution.c)| Medium | Top_100_Liked_Questions, Array, Dynamic_Programming, Breadth_First_Search, Big_O_Time_O(m\*n)_Space_O(amount) | 22 | 87.50

#### Day 13 Dynamic Programming

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0416 |[Partition Equal Subset Sum](src/main/c/g0401_0500/s0416_partition_equal_subset_sum/Solution.c)| Medium | Top_100_Liked_Questions, Array, Dynamic_Programming, Big_O_Time_O(n\*sums)_Space_O(n\*sums) | 47 | 78.26
| 0152 |[Maximum Product Subarray](src/main/c/g0101_0200/s0152_maximum_product_subarray/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Big_O_Time_O(N)_Space_O(1) | 0 | 100.00

#### Day 14 Sliding Window/Two Pointer

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0003 |[Longest Substring Without Repeating Characters](src/main/c/g0001_0100/s0003_longest_substring_without_repeating_characters/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Hash_Table, Sliding_Window, Big_O_Time_O(n)_Space_O(1) | 15 | 29.93
| 0076 |[Minimum Window Substring](src/main/c/g0001_0100/s0076_minimum_window_substring/Solution.c)| Hard | Top_100_Liked_Questions, Top_Interview_Questions, String, Hash_Table, Sliding_Window, Big_O_Time_O(s.length())_Space_O(1) | 0 | 100.00

#### Day 15 Tree

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0101 |[Symmetric Tree](src/main/c/g0101_0200/s0101_symmetric_tree/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Depth_First_Search, Breadth_First_Search, Tree, Binary_Tree, Big_O_Time_O(N)_Space_O(log(N)) | 0 | 100.00

#### Day 16 Design

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0155 |[Min Stack](src/main/c/g0101_0200/s0155_min_stack/MinStack.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Stack, Design, Big_O_Time_O(1)_Space_O(N) | 0 | 100.00
| 0208 |[Implement Trie (Prefix Tree)](src/main/c/g0201_0300/s0208_implement_trie_prefix_tree/Trie.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Hash_Table, Design, Trie, Big_O_Time_O(word.length())_or_O(prefix.length())_Space_O(N) | 7 | 100.00

#### Day 17 Interval

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0056 |[Merge Intervals](src/main/c/g0001_0100/s0056_merge_intervals/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Sorting, Big_O_Time_O(n_log_n)_Space_O(n) | 0 | 100.00

#### Day 18 Stack

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 19 Union Find

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 20 Brute Force/Backtracking

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0039 |[Combination Sum](src/main/c/g0001_0100/s0039_combination_sum/Solution.c)| Medium | Top_100_Liked_Questions, Array, Backtracking, Big_O_Time_O(2^n)_Space_O(n+2^n) | 0 | 100.00
| 0046 |[Permutations](src/main/c/g0001_0100/s0046_permutations/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Backtracking, Big_O_Time_O(n\*n!)_Space_O(n+n!) | 0 | 100.00

### Udemy

#### Udemy Integers

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0136 |[Single Number](src/main/c/g0101_0200/s0136_single_number/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Array, Bit_Manipulation, Big_O_Time_O(N)_Space_O(1) | 0 | 100.00
| 0007 |[Reverse Integer](src/main/c/g0001_0100/s0007_reverse_integer/Solution.c)| Medium | Top_Interview_Questions, Math | 0 | 100.00
| 0009 |[Palindrome Number](src/main/c/g0001_0100/s0009_palindrome_number/Solution.c)| Easy | Math | 0 | 100.00

#### Udemy Strings

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0003 |[Longest Substring Without Repeating Characters](src/main/c/g0001_0100/s0003_longest_substring_without_repeating_characters/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Hash_Table, Sliding_Window, Big_O_Time_O(n)_Space_O(1) | 15 | 29.93
| 0020 |[Valid Parentheses](src/main/c/g0001_0100/s0020_valid_parentheses/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, String, Stack, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0005 |[Longest Palindromic Substring](src/main/c/g0001_0100/s0005_longest_palindromic_substring/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Dynamic_Programming, Big_O_Time_O(n)_Space_O(n) | 2 | 97.74
| 0394 |[Decode String](src/main/c/g0301_0400/s0394_decode_string/Solution.c)| Medium | Top_100_Liked_Questions, String, Stack, Recursion, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0049 |[Group Anagrams](src/main/c/g0001_0100/s0049_group_anagrams/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, String, Hash_Table, Sorting, Big_O_Time_O(n\*k_log_k)_Space_O(n) | 3 | 100.00

#### Udemy Binary Search

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0033 |[Search in Rotated Sorted Array](src/main/c/g0001_0100/s0033_search_in_rotated_sorted_array/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Binary_Search, Big_O_Time_O(log_n)_Space_O(1) | 0 | 100.00
| 0153 |[Find Minimum in Rotated Sorted Array](src/main/c/g0101_0200/s0153_find_minimum_in_rotated_sorted_array/Solution.c)| Medium | Top_100_Liked_Questions, Array, Binary_Search, Big_O_Time_O(log_N)_Space_O(log_N) | 0 | 100.00

#### Udemy Arrays

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0121 |[Best Time to Buy and Sell Stock](src/main/c/g0101_0200/s0121_best_time_to_buy_and_sell_stock/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Big_O_Time_O(N)_Space_O(1) | 0 | 100.00
| 0283 |[Move Zeroes](src/main/c/g0201_0300/s0283_move_zeroes/Solution.c)| Easy | Top_100_Liked_Questions, Array, Two_Pointers, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0001 |[Two Sum](src/main/c/g0001_0100/s0001_two_sum/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Array, Hash_Table, Big_O_Time_O(n)_Space_O(n), AI_can_be_used_to_solve_the_task | 2 | 99.56
| 0189 |[Rotate Array](src/main/c/g0101_0200/s0189_rotate_array/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Math, Two_Pointers, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0055 |[Jump Game](src/main/c/g0001_0100/s0055_jump_game/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Greedy, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0075 |[Sort Colors](src/main/c/g0001_0100/s0075_sort_colors/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Sorting, Two_Pointers, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0238 |[Product of Array Except Self](src/main/c/g0201_0300/s0238_product_of_array_except_self/Solution.c)| Medium | Top_100_Liked_Questions, Array, Prefix_Sum, Big_O_Time_O(n^2)_Space_O(n) | 0 | 100.00
| 0041 |[First Missing Positive](src/main/c/g0001_0100/s0041_first_missing_positive/Solution.c)| Hard | Top_100_Liked_Questions, Top_Interview_Questions, Array, Hash_Table, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0239 |[Sliding Window Maximum](src/main/c/g0201_0300/s0239_sliding_window_maximum/Solution.c)| Hard | Top_100_Liked_Questions, Array, Heap_Priority_Queue, Sliding_Window, Queue, Monotonic_Queue, Big_O_Time_O(n\*k)_Space_O(n+k) | 4 | 95.24

#### Udemy Two Pointers

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0042 |[Trapping Rain Water](src/main/c/g0001_0100/s0042_trapping_rain_water/Solution.c)| Hard | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Two_Pointers, Stack, Monotonic_Stack, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0015 |[3Sum](src/main/c/g0001_0100/s0015_3sum/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Sorting, Two_Pointers, Big_O_Time_O(n\*log(n))_Space_O(n^2) | 47 | 87.75

#### Udemy Famous Algorithm

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0053 |[Maximum Subarray](src/main/c/g0001_0100/s0053_maximum_subarray/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Divide_and_Conquer, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0169 |[Majority Element](src/main/c/g0101_0200/s0169_majority_element/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Array, Hash_Table, Sorting, Counting, Divide_and_Conquer, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00

#### Udemy Sorting Algorithms

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Udemy 2D Arrays/Matrix

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0074 |[Search a 2D Matrix](src/main/c/g0001_0100/s0074_search_a_2d_matrix/Solution.c)| Medium | Top_100_Liked_Questions, Array, Binary_Search, Matrix, Big_O_Time_O(endRow+endCol)_Space_O(1) | 0 | 100.00
| 0048 |[Rotate Image](src/main/c/g0001_0100/s0048_rotate_image/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Math, Matrix, Big_O_Time_O(n^2)_Space_O(1) | 0 | 100.00
| 0073 |[Set Matrix Zeroes](src/main/c/g0001_0100/s0073_set_matrix_zeroes/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Hash_Table, Matrix, Big_O_Time_O(m\*n)_Space_O(1) | 0 | 100.00
| 0056 |[Merge Intervals](src/main/c/g0001_0100/s0056_merge_intervals/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Sorting, Big_O_Time_O(n_log_n)_Space_O(n) | 0 | 100.00

#### Udemy Linked List

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0114 |[Flatten Binary Tree to Linked List](src/main/c/g0101_0200/s0114_flatten_binary_tree_to_linked_list/Solution.c)| Medium | Top_100_Liked_Questions, Depth_First_Search, Tree, Binary_Tree, Stack, Linked_List, Big_O_Time_O(N)_Space_O(N) | 0 | 100.00
| 0024 |[Swap Nodes in Pairs](src/main/c/g0001_0100/s0024_swap_nodes_in_pairs/Solution.c)| Medium | Top_100_Liked_Questions, Linked_List, Recursion, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0142 |[Linked List Cycle II](src/main/c/g0101_0200/s0142_linked_list_cycle_ii/Solution.c)| Medium | Top_100_Liked_Questions, Hash_Table, Two_Pointers, Linked_List, Big_O_Time_O(N)_Space_O(1) | 4 | 81.55
| 0141 |[Linked List Cycle](src/main/c/g0101_0200/s0141_linked_list_cycle/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Hash_Table, Two_Pointers, Linked_List, Big_O_Time_O(N)_Space_O(1) | 6 | 92.85
| 0206 |[Reverse Linked List](src/main/c/g0201_0300/s0206_reverse_linked_list/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Linked_List, Recursion, Big_O_Time_O(N)_Space_O(1) | 0 | 100.00
| 0021 |[Merge Two Sorted Lists](src/main/c/g0001_0100/s0021_merge_two_sorted_lists/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Linked_List, Recursion, Big_O_Time_O(m+n)_Space_O(m+n) | 0 | 100.00
| 0160 |[Intersection of Two Linked Lists](src/main/c/g0101_0200/s0160_intersection_of_two_linked_lists/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Hash_Table, Two_Pointers, Linked_List, Big_O_Time_O(M+N)_Space_O(1) | 33 | 78.91
| 0234 |[Palindrome Linked List](src/main/c/g0201_0300/s0234_palindrome_linked_list/Solution.c)| Easy | Top_100_Liked_Questions, Two_Pointers, Stack, Linked_List, Recursion, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0138 |[Copy List with Random Pointer](src/main/c/g0101_0200/s0138_copy_list_with_random_pointer/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Hash_Table, Linked_List, Big_O_Time_O(N)_Space_O(N) | 4 | 91.18
| 0025 |[Reverse Nodes in k-Group](src/main/c/g0001_0100/s0025_reverse_nodes_in_k_group/Solution.c)| Hard | Top_100_Liked_Questions, Linked_List, Recursion, Big_O_Time_O(n)_Space_O(k) | 0 | 100.00
| 0146 |[LRU Cache](src/main/c/g0101_0200/s0146_lru_cache/LRUCache.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Hash_Table, Design, Linked_List, Doubly_Linked_List, Big_O_Time_O(1)_Space_O(capacity) | 37 | 91.67

#### Udemy Tree Stack Queue

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0094 |[Binary Tree Inorder Traversal](src/main/c/g0001_0100/s0094_binary_tree_inorder_traversal/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Depth_First_Search, Tree, Binary_Tree, Stack, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0102 |[Binary Tree Level Order Traversal](src/main/c/g0101_0200/s0102_binary_tree_level_order_traversal/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Breadth_First_Search, Tree, Binary_Tree, Big_O_Time_O(N)_Space_O(N) | 0 | 100.00
| 0543 |[Diameter of Binary Tree](src/main/c/g0501_0600/s0543_diameter_of_binary_tree/Solution.c)| Easy | Top_100_Liked_Questions, Depth_First_Search, Tree, Binary_Tree, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0226 |[Invert Binary Tree](src/main/c/g0201_0300/s0226_invert_binary_tree/Solution.c)| Easy | Top_100_Liked_Questions, Depth_First_Search, Breadth_First_Search, Tree, Binary_Tree, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0104 |[Maximum Depth of Binary Tree](src/main/c/g0101_0200/s0104_maximum_depth_of_binary_tree/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Depth_First_Search, Breadth_First_Search, Tree, Binary_Tree, Big_O_Time_O(N)_Space_O(H) | 0 | 100.00
| 0124 |[Binary Tree Maximum Path Sum](src/main/c/g0101_0200/s0124_binary_tree_maximum_path_sum/Solution.c)| Hard | Top_100_Liked_Questions, Top_Interview_Questions, Dynamic_Programming, Depth_First_Search, Tree, Binary_Tree, Big_O_Time_O(N)_Space_O(N) | 0 | 100.00
| 0098 |[Validate Binary Search Tree](src/main/c/g0001_0100/s0098_validate_binary_search_tree/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Depth_First_Search, Tree, Binary_Tree, Binary_Search_Tree, Big_O_Time_O(N)_Space_O(log(N)) | 0 | 100.00
| 0236 |[Lowest Common Ancestor of a Binary Tree](src/main/c/g0201_0300/s0236_lowest_common_ancestor_of_a_binary_tree/Solution.c)| Medium | Top_100_Liked_Questions, Depth_First_Search, Tree, Binary_Tree, Big_O_Time_O(n)_Space_O(n) | 15 | 90.08

#### Udemy Trie and Heap

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0208 |[Implement Trie (Prefix Tree)](src/main/c/g0201_0300/s0208_implement_trie_prefix_tree/Trie.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Hash_Table, Design, Trie, Big_O_Time_O(word.length())_or_O(prefix.length())_Space_O(N) | 7 | 100.00

#### Udemy Graph

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0200 |[Number of Islands](src/main/c/g0101_0200/s0200_number_of_islands/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Depth_First_Search, Breadth_First_Search, Matrix, Union_Find, Big_O_Time_O(M\*N)_Space_O(M\*N) | 14 | 96.18

#### Udemy Dynamic Programming

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0139 |[Word Break](src/main/c/g0101_0200/s0139_word_break/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Hash_Table, Dynamic_Programming, Trie, Memoization, Big_O_Time_O(M+max\*N)_Space_O(M+N+max) | 0 | 100.00
| 0152 |[Maximum Product Subarray](src/main/c/g0101_0200/s0152_maximum_product_subarray/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Big_O_Time_O(N)_Space_O(1) | 0 | 100.00
| 0198 |[House Robber](src/main/c/g0101_0200/s0198_house_robber/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0070 |[Climbing Stairs](src/main/c/g0001_0100/s0070_climbing_stairs/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Dynamic_Programming, Math, Memoization, Big_O_Time_O(n)_Space_O(n) | 1 | 100.00
| 0064 |[Minimum Path Sum](src/main/c/g0001_0100/s0064_minimum_path_sum/Solution.c)| Medium | Top_100_Liked_Questions, Array, Dynamic_Programming, Matrix, Big_O_Time_O(m\*n)_Space_O(m\*n) | 0 | 100.00
| 0300 |[Longest Increasing Subsequence](src/main/c/g0201_0300/s0300_longest_increasing_subsequence/Solution.c)| Medium | Top_100_Liked_Questions, Array, Dynamic_Programming, Binary_Search, Big_O_Time_O(n\*log_n)_Space_O(n) | 0 | 100.00
| 1143 |[Longest Common Subsequence](src/main/c/g1101_1200/s1143_longest_common_subsequence/Solution.c)| Medium | Top_100_Liked_Questions, String, Dynamic_Programming, Big_O_Time_O(n\*m)_Space_O(n\*m) | 21 | 84.72
| 0072 |[Edit Distance](src/main/c/g0001_0100/s0072_edit_distance/Solution.c)| Medium | Top_100_Liked_Questions, String, Dynamic_Programming, Big_O_Time_O(n^2)_Space_O(n2) | 0 | 100.00
| 0010 |[Regular Expression Matching](src/main/c/g0001_0100/s0010_regular_expression_matching/Solution.c)| Hard | Top_Interview_Questions, String, Dynamic_Programming, Recursion, Big_O_Time_O(m\*n)_Space_O(m\*n) | 0 | 100.00

#### Udemy Backtracking/Recursion

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0022 |[Generate Parentheses](src/main/c/g0001_0100/s0022_generate_parentheses/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Dynamic_Programming, Backtracking, Big_O_Time_O(2^n)_Space_O(n) | 0 | 100.00
| 0039 |[Combination Sum](src/main/c/g0001_0100/s0039_combination_sum/Solution.c)| Medium | Top_100_Liked_Questions, Array, Backtracking, Big_O_Time_O(2^n)_Space_O(n+2^n) | 0 | 100.00
| 0078 |[Subsets](src/main/c/g0001_0100/s0078_subsets/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Bit_Manipulation, Backtracking, Big_O_Time_O(2^n)_Space_O(n\*2^n) | 0 | 100.00
| 0017 |[Letter Combinations of a Phone Number](src/main/c/g0001_0100/s0017_letter_combinations_of_a_phone_number/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Hash_Table, Backtracking, Big_O_Time_O(4^n)_Space_O(n) | 0 | 100.00
| 0046 |[Permutations](src/main/c/g0001_0100/s0046_permutations/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Backtracking, Big_O_Time_O(n\*n!)_Space_O(n+n!) | 0 | 100.00

#### Udemy Bit Manipulation

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0338 |[Counting Bits](src/main/c/g0301_0400/s0338_counting_bits/Solution.c)| Easy | Dynamic_Programming, Bit_Manipulation, Big_O_Time_O(num)_Space_O(num) | 0 | 100.00

#### Udemy Design

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0155 |[Min Stack](src/main/c/g0101_0200/s0155_min_stack/MinStack.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Stack, Design, Big_O_Time_O(1)_Space_O(N) | 0 | 100.00

### Top Interview 150

#### Top Interview 150 Array/String

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0169 |[Majority Element](src/main/c/g0101_0200/s0169_majority_element/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Array, Hash_Table, Sorting, Counting, Divide_and_Conquer, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0189 |[Rotate Array](src/main/c/g0101_0200/s0189_rotate_array/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Math, Two_Pointers, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0121 |[Best Time to Buy and Sell Stock](src/main/c/g0101_0200/s0121_best_time_to_buy_and_sell_stock/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Big_O_Time_O(N)_Space_O(1) | 0 | 100.00
| 0055 |[Jump Game](src/main/c/g0001_0100/s0055_jump_game/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Greedy, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0045 |[Jump Game II](src/main/c/g0001_0100/s0045_jump_game_ii/Solution.c)| Medium | Top_100_Liked_Questions, Array, Dynamic_Programming, Greedy, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0238 |[Product of Array Except Self](src/main/c/g0201_0300/s0238_product_of_array_except_self/Solution.c)| Medium | Top_100_Liked_Questions, Array, Prefix_Sum, Big_O_Time_O(n^2)_Space_O(n) | 0 | 100.00
| 0042 |[Trapping Rain Water](src/main/c/g0001_0100/s0042_trapping_rain_water/Solution.c)| Hard | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Two_Pointers, Stack, Monotonic_Stack, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0006 |[Zigzag Conversion](src/main/c/g0001_0100/s0006_zigzag_conversion/Solution.c)| Medium | String | 0 | 100.00

#### Top Interview 150 Two Pointers

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0011 |[Container With Most Water](src/main/c/g0001_0100/s0011_container_with_most_water/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Greedy, Two_Pointers, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0015 |[3Sum](src/main/c/g0001_0100/s0015_3sum/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Sorting, Two_Pointers, Big_O_Time_O(n\*log(n))_Space_O(n^2) | 47 | 87.75

#### Top Interview 150 Sliding Window

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0003 |[Longest Substring Without Repeating Characters](src/main/c/g0001_0100/s0003_longest_substring_without_repeating_characters/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Hash_Table, Sliding_Window, Big_O_Time_O(n)_Space_O(1) | 15 | 29.93
| 0076 |[Minimum Window Substring](src/main/c/g0001_0100/s0076_minimum_window_substring/Solution.c)| Hard | Top_100_Liked_Questions, Top_Interview_Questions, String, Hash_Table, Sliding_Window, Big_O_Time_O(s.length())_Space_O(1) | 0 | 100.00

#### Top Interview 150 Matrix

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0048 |[Rotate Image](src/main/c/g0001_0100/s0048_rotate_image/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Math, Matrix, Big_O_Time_O(n^2)_Space_O(1) | 0 | 100.00
| 0073 |[Set Matrix Zeroes](src/main/c/g0001_0100/s0073_set_matrix_zeroes/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Hash_Table, Matrix, Big_O_Time_O(m\*n)_Space_O(1) | 0 | 100.00

#### Top Interview 150 Hashmap

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0049 |[Group Anagrams](src/main/c/g0001_0100/s0049_group_anagrams/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, String, Hash_Table, Sorting, Big_O_Time_O(n\*k_log_k)_Space_O(n) | 3 | 100.00
| 0001 |[Two Sum](src/main/c/g0001_0100/s0001_two_sum/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Array, Hash_Table, Big_O_Time_O(n)_Space_O(n), AI_can_be_used_to_solve_the_task | 2 | 99.56
| 0128 |[Longest Consecutive Sequence](src/main/c/g0101_0200/s0128_longest_consecutive_sequence/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Hash_Table, Union_Find, Big_O_Time_O(N_log_N)_Space_O(1) | 19 | 89.29

#### Top Interview 150 Intervals

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0056 |[Merge Intervals](src/main/c/g0001_0100/s0056_merge_intervals/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Sorting, Big_O_Time_O(n_log_n)_Space_O(n) | 0 | 100.00

#### Top Interview 150 Stack

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0020 |[Valid Parentheses](src/main/c/g0001_0100/s0020_valid_parentheses/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, String, Stack, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0155 |[Min Stack](src/main/c/g0101_0200/s0155_min_stack/MinStack.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Stack, Design, Big_O_Time_O(1)_Space_O(N) | 0 | 100.00

#### Top Interview 150 Linked List

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0141 |[Linked List Cycle](src/main/c/g0101_0200/s0141_linked_list_cycle/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Hash_Table, Two_Pointers, Linked_List, Big_O_Time_O(N)_Space_O(1) | 6 | 92.85
| 0002 |[Add Two Numbers](src/main/c/g0001_0100/s0002_add_two_numbers/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Math, Linked_List, Recursion, Big_O_Time_O(max(N,M))_Space_O(max(N,M)), AI_can_be_used_to_solve_the_task | 12 | 70.50
| 0021 |[Merge Two Sorted Lists](src/main/c/g0001_0100/s0021_merge_two_sorted_lists/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Linked_List, Recursion, Big_O_Time_O(m+n)_Space_O(m+n) | 0 | 100.00
| 0138 |[Copy List with Random Pointer](src/main/c/g0101_0200/s0138_copy_list_with_random_pointer/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Hash_Table, Linked_List, Big_O_Time_O(N)_Space_O(N) | 4 | 91.18
| 0025 |[Reverse Nodes in k-Group](src/main/c/g0001_0100/s0025_reverse_nodes_in_k_group/Solution.c)| Hard | Top_100_Liked_Questions, Linked_List, Recursion, Big_O_Time_O(n)_Space_O(k) | 0 | 100.00
| 0019 |[Remove Nth Node From End of List](src/main/c/g0001_0100/s0019_remove_nth_node_from_end_of_list/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Two_Pointers, Linked_List, Big_O_Time_O(L)_Space_O(L) | 0 | 100.00
| 0146 |[LRU Cache](src/main/c/g0101_0200/s0146_lru_cache/LRUCache.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Hash_Table, Design, Linked_List, Doubly_Linked_List, Big_O_Time_O(1)_Space_O(capacity) | 37 | 91.67

#### Top Interview 150 Binary Tree General

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0104 |[Maximum Depth of Binary Tree](src/main/c/g0101_0200/s0104_maximum_depth_of_binary_tree/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Depth_First_Search, Breadth_First_Search, Tree, Binary_Tree, Big_O_Time_O(N)_Space_O(H) | 0 | 100.00
| 0226 |[Invert Binary Tree](src/main/c/g0201_0300/s0226_invert_binary_tree/Solution.c)| Easy | Top_100_Liked_Questions, Depth_First_Search, Breadth_First_Search, Tree, Binary_Tree, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0101 |[Symmetric Tree](src/main/c/g0101_0200/s0101_symmetric_tree/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Depth_First_Search, Breadth_First_Search, Tree, Binary_Tree, Big_O_Time_O(N)_Space_O(log(N)) | 0 | 100.00
| 0105 |[Construct Binary Tree from Preorder and Inorder Traversal](src/main/c/g0101_0200/s0105_construct_binary_tree_from_preorder_and_inorder_traversal/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Hash_Table, Tree, Binary_Tree, Divide_and_Conquer, Big_O_Time_O(N)_Space_O(N) | 3 | 95.24
| 0114 |[Flatten Binary Tree to Linked List](src/main/c/g0101_0200/s0114_flatten_binary_tree_to_linked_list/Solution.c)| Medium | Top_100_Liked_Questions, Depth_First_Search, Tree, Binary_Tree, Stack, Linked_List, Big_O_Time_O(N)_Space_O(N) | 0 | 100.00
| 0124 |[Binary Tree Maximum Path Sum](src/main/c/g0101_0200/s0124_binary_tree_maximum_path_sum/Solution.c)| Hard | Top_100_Liked_Questions, Top_Interview_Questions, Dynamic_Programming, Depth_First_Search, Tree, Binary_Tree, Big_O_Time_O(N)_Space_O(N) | 0 | 100.00
| 0236 |[Lowest Common Ancestor of a Binary Tree](src/main/c/g0201_0300/s0236_lowest_common_ancestor_of_a_binary_tree/Solution.c)| Medium | Top_100_Liked_Questions, Depth_First_Search, Tree, Binary_Tree, Big_O_Time_O(n)_Space_O(n) | 15 | 90.08

#### Top Interview 150 Binary Tree BFS

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0102 |[Binary Tree Level Order Traversal](src/main/c/g0101_0200/s0102_binary_tree_level_order_traversal/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Breadth_First_Search, Tree, Binary_Tree, Big_O_Time_O(N)_Space_O(N) | 0 | 100.00

#### Top Interview 150 Binary Search Tree

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0230 |[Kth Smallest Element in a BST](src/main/c/g0201_0300/s0230_kth_smallest_element_in_a_bst/Solution.c)| Medium | Top_100_Liked_Questions, Depth_First_Search, Tree, Binary_Tree, Binary_Search_Tree, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0098 |[Validate Binary Search Tree](src/main/c/g0001_0100/s0098_validate_binary_search_tree/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Depth_First_Search, Tree, Binary_Tree, Binary_Search_Tree, Big_O_Time_O(N)_Space_O(log(N)) | 0 | 100.00

#### Top Interview 150 Graph General

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0200 |[Number of Islands](src/main/c/g0101_0200/s0200_number_of_islands/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Depth_First_Search, Breadth_First_Search, Matrix, Union_Find, Big_O_Time_O(M\*N)_Space_O(M\*N) | 14 | 96.18
| 0207 |[Course Schedule](src/main/c/g0201_0300/s0207_course_schedule/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Depth_First_Search, Breadth_First_Search, Graph, Topological_Sort, Big_O_Time_O(N)_Space_O(N) | 0 | 100.00

#### Top Interview 150 Graph BFS

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Top Interview 150 Trie

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0208 |[Implement Trie (Prefix Tree)](src/main/c/g0201_0300/s0208_implement_trie_prefix_tree/Trie.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Hash_Table, Design, Trie, Big_O_Time_O(word.length())_or_O(prefix.length())_Space_O(N) | 7 | 100.00

#### Top Interview 150 Backtracking

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0017 |[Letter Combinations of a Phone Number](src/main/c/g0001_0100/s0017_letter_combinations_of_a_phone_number/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Hash_Table, Backtracking, Big_O_Time_O(4^n)_Space_O(n) | 0 | 100.00
| 0046 |[Permutations](src/main/c/g0001_0100/s0046_permutations/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Backtracking, Big_O_Time_O(n\*n!)_Space_O(n+n!) | 0 | 100.00
| 0039 |[Combination Sum](src/main/c/g0001_0100/s0039_combination_sum/Solution.c)| Medium | Top_100_Liked_Questions, Array, Backtracking, Big_O_Time_O(2^n)_Space_O(n+2^n) | 0 | 100.00
| 0022 |[Generate Parentheses](src/main/c/g0001_0100/s0022_generate_parentheses/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Dynamic_Programming, Backtracking, Big_O_Time_O(2^n)_Space_O(n) | 0 | 100.00
| 0079 |[Word Search](src/main/c/g0001_0100/s0079_word_search/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Matrix, Backtracking, Big_O_Time_O(4^(m\*n))_Space_O(m\*n) | 121 | 92.31

#### Top Interview 150 Divide and Conquer

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0148 |[Sort List](src/main/c/g0101_0200/s0148_sort_list/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Sorting, Two_Pointers, Linked_List, Divide_and_Conquer, Merge_Sort, Big_O_Time_O(log(N))_Space_O(log(N)) | 3 | 100.00
| 0023 |[Merge k Sorted Lists](src/main/c/g0001_0100/s0023_merge_k_sorted_lists/Solution.c)| Hard | Top_100_Liked_Questions, Top_Interview_Questions, Heap_Priority_Queue, Linked_List, Divide_and_Conquer, Merge_Sort, Big_O_Time_O(k\*n\*log(k))_Space_O(log(k)) | 0 | 100.00

#### Top Interview 150 Kadane's Algorithm

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0053 |[Maximum Subarray](src/main/c/g0001_0100/s0053_maximum_subarray/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Divide_and_Conquer, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00

#### Top Interview 150 Binary Search

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0035 |[Search Insert Position](src/main/c/g0001_0100/s0035_search_insert_position/Solution.c)| Easy | Top_100_Liked_Questions, Array, Binary_Search, Big_O_Time_O(log_n)_Space_O(1) | 0 | 100.00
| 0074 |[Search a 2D Matrix](src/main/c/g0001_0100/s0074_search_a_2d_matrix/Solution.c)| Medium | Top_100_Liked_Questions, Array, Binary_Search, Matrix, Big_O_Time_O(endRow+endCol)_Space_O(1) | 0 | 100.00
| 0033 |[Search in Rotated Sorted Array](src/main/c/g0001_0100/s0033_search_in_rotated_sorted_array/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Binary_Search, Big_O_Time_O(log_n)_Space_O(1) | 0 | 100.00
| 0034 |[Find First and Last Position of Element in Sorted Array](src/main/c/g0001_0100/s0034_find_first_and_last_position_of_element_in_sorted_array/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Binary_Search, Big_O_Time_O(log_n)_Space_O(1) | 0 | 100.00
| 0153 |[Find Minimum in Rotated Sorted Array](src/main/c/g0101_0200/s0153_find_minimum_in_rotated_sorted_array/Solution.c)| Medium | Top_100_Liked_Questions, Array, Binary_Search, Big_O_Time_O(log_N)_Space_O(log_N) | 0 | 100.00
| 0004 |[Median of Two Sorted Arrays](src/main/c/g0001_0100/s0004_median_of_two_sorted_arrays/Solution.c)| Hard | Top_100_Liked_Questions, Top_Interview_Questions, Array, Binary_Search, Divide_and_Conquer, Big_O_Time_O(log(min(N,M)))_Space_O(1) | 0 | 100.00

#### Top Interview 150 Heap

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0215 |[Kth Largest Element in an Array](src/main/c/g0201_0300/s0215_kth_largest_element_in_an_array/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Sorting, Heap_Priority_Queue, Divide_and_Conquer, Quickselect, Big_O_Time_O(n\*log(n))_Space_O(log(n)) | 0 | 100.00
| 0295 |[Find Median from Data Stream](src/main/c/g0201_0300/s0295_find_median_from_data_stream/MedianFinder.c)| Hard | Top_100_Liked_Questions, Sorting, Two_Pointers, Design, Heap_Priority_Queue, Data_Stream, Big_O_Time_O(n\*log_n)_Space_O(n) | 28 | 100.00

#### Top Interview 150 Bit Manipulation

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0136 |[Single Number](src/main/c/g0101_0200/s0136_single_number/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Array, Bit_Manipulation, Big_O_Time_O(N)_Space_O(1) | 0 | 100.00

#### Top Interview 150 Math

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0009 |[Palindrome Number](src/main/c/g0001_0100/s0009_palindrome_number/Solution.c)| Easy | Math | 0 | 100.00

#### Top Interview 150 1D DP

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0070 |[Climbing Stairs](src/main/c/g0001_0100/s0070_climbing_stairs/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Dynamic_Programming, Math, Memoization, Big_O_Time_O(n)_Space_O(n) | 1 | 100.00
| 0198 |[House Robber](src/main/c/g0101_0200/s0198_house_robber/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0139 |[Word Break](src/main/c/g0101_0200/s0139_word_break/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Hash_Table, Dynamic_Programming, Trie, Memoization, Big_O_Time_O(M+max\*N)_Space_O(M+N+max) | 0 | 100.00
| 0322 |[Coin Change](src/main/c/g0301_0400/s0322_coin_change/Solution.c)| Medium | Top_100_Liked_Questions, Array, Dynamic_Programming, Breadth_First_Search, Big_O_Time_O(m\*n)_Space_O(amount) | 22 | 87.50
| 0300 |[Longest Increasing Subsequence](src/main/c/g0201_0300/s0300_longest_increasing_subsequence/Solution.c)| Medium | Top_100_Liked_Questions, Array, Dynamic_Programming, Binary_Search, Big_O_Time_O(n\*log_n)_Space_O(n) | 0 | 100.00

#### Top Interview 150 Multidimensional DP

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0064 |[Minimum Path Sum](src/main/c/g0001_0100/s0064_minimum_path_sum/Solution.c)| Medium | Top_100_Liked_Questions, Array, Dynamic_Programming, Matrix, Big_O_Time_O(m\*n)_Space_O(m\*n) | 0 | 100.00
| 0005 |[Longest Palindromic Substring](src/main/c/g0001_0100/s0005_longest_palindromic_substring/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Dynamic_Programming, Big_O_Time_O(n)_Space_O(n) | 2 | 97.74
| 0072 |[Edit Distance](src/main/c/g0001_0100/s0072_edit_distance/Solution.c)| Medium | Top_100_Liked_Questions, String, Dynamic_Programming, Big_O_Time_O(n^2)_Space_O(n2) | 0 | 100.00
| 0221 |[Maximal Square](src/main/c/g0201_0300/s0221_maximal_square/Solution.c)| Medium | Array, Dynamic_Programming, Matrix, Big_O_Time_O(m\*n)_Space_O(m\*n) | 0 | 100.00

### Data Structure I

#### Day 1 Array

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0053 |[Maximum Subarray](src/main/c/g0001_0100/s0053_maximum_subarray/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Divide_and_Conquer, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00

#### Day 2 Array

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0001 |[Two Sum](src/main/c/g0001_0100/s0001_two_sum/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Array, Hash_Table, Big_O_Time_O(n)_Space_O(n), AI_can_be_used_to_solve_the_task | 2 | 99.56

#### Day 3 Array

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0121 |[Best Time to Buy and Sell Stock](src/main/c/g0101_0200/s0121_best_time_to_buy_and_sell_stock/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Big_O_Time_O(N)_Space_O(1) | 0 | 100.00

#### Day 4 Array

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 5 Array

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0074 |[Search a 2D Matrix](src/main/c/g0001_0100/s0074_search_a_2d_matrix/Solution.c)| Medium | Top_100_Liked_Questions, Array, Binary_Search, Matrix, Big_O_Time_O(endRow+endCol)_Space_O(1) | 0 | 100.00

#### Day 6 String

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 7 Linked List

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0141 |[Linked List Cycle](src/main/c/g0101_0200/s0141_linked_list_cycle/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Hash_Table, Two_Pointers, Linked_List, Big_O_Time_O(N)_Space_O(1) | 6 | 92.85
| 0021 |[Merge Two Sorted Lists](src/main/c/g0001_0100/s0021_merge_two_sorted_lists/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Linked_List, Recursion, Big_O_Time_O(m+n)_Space_O(m+n) | 0 | 100.00

#### Day 8 Linked List

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0206 |[Reverse Linked List](src/main/c/g0201_0300/s0206_reverse_linked_list/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Linked_List, Recursion, Big_O_Time_O(N)_Space_O(1) | 0 | 100.00

#### Day 9 Stack Queue

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0020 |[Valid Parentheses](src/main/c/g0001_0100/s0020_valid_parentheses/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, String, Stack, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00

#### Day 10 Tree

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0094 |[Binary Tree Inorder Traversal](src/main/c/g0001_0100/s0094_binary_tree_inorder_traversal/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Depth_First_Search, Tree, Binary_Tree, Stack, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00

#### Day 11 Tree

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0102 |[Binary Tree Level Order Traversal](src/main/c/g0101_0200/s0102_binary_tree_level_order_traversal/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Breadth_First_Search, Tree, Binary_Tree, Big_O_Time_O(N)_Space_O(N) | 0 | 100.00
| 0104 |[Maximum Depth of Binary Tree](src/main/c/g0101_0200/s0104_maximum_depth_of_binary_tree/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Depth_First_Search, Breadth_First_Search, Tree, Binary_Tree, Big_O_Time_O(N)_Space_O(H) | 0 | 100.00
| 0101 |[Symmetric Tree](src/main/c/g0101_0200/s0101_symmetric_tree/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Depth_First_Search, Breadth_First_Search, Tree, Binary_Tree, Big_O_Time_O(N)_Space_O(log(N)) | 0 | 100.00

#### Day 12 Tree

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0226 |[Invert Binary Tree](src/main/c/g0201_0300/s0226_invert_binary_tree/Solution.c)| Easy | Top_100_Liked_Questions, Depth_First_Search, Breadth_First_Search, Tree, Binary_Tree, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00

#### Day 13 Tree

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 14 Tree

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0098 |[Validate Binary Search Tree](src/main/c/g0001_0100/s0098_validate_binary_search_tree/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Depth_First_Search, Tree, Binary_Tree, Binary_Search_Tree, Big_O_Time_O(N)_Space_O(log(N)) | 0 | 100.00

### Data Structure II

#### Day 1 Array

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0136 |[Single Number](src/main/c/g0101_0200/s0136_single_number/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Array, Bit_Manipulation, Big_O_Time_O(N)_Space_O(1) | 0 | 100.00
| 0169 |[Majority Element](src/main/c/g0101_0200/s0169_majority_element/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Array, Hash_Table, Sorting, Counting, Divide_and_Conquer, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0015 |[3Sum](src/main/c/g0001_0100/s0015_3sum/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Sorting, Two_Pointers, Big_O_Time_O(n\*log(n))_Space_O(n^2) | 47 | 87.75

#### Day 2 Array

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0075 |[Sort Colors](src/main/c/g0001_0100/s0075_sort_colors/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Sorting, Two_Pointers, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0056 |[Merge Intervals](src/main/c/g0001_0100/s0056_merge_intervals/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Sorting, Big_O_Time_O(n_log_n)_Space_O(n) | 0 | 100.00

#### Day 3 Array

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0048 |[Rotate Image](src/main/c/g0001_0100/s0048_rotate_image/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Math, Matrix, Big_O_Time_O(n^2)_Space_O(1) | 0 | 100.00

#### Day 4 Array

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0240 |[Search a 2D Matrix II](src/main/c/g0201_0300/s0240_search_a_2d_matrix_ii/Solution.c)| Medium | Top_100_Liked_Questions, Array, Binary_Search, Matrix, Divide_and_Conquer, Big_O_Time_O(n+m)_Space_O(1) | 42 | 96.34

#### Day 5 Array

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0238 |[Product of Array Except Self](src/main/c/g0201_0300/s0238_product_of_array_except_self/Solution.c)| Medium | Top_100_Liked_Questions, Array, Prefix_Sum, Big_O_Time_O(n^2)_Space_O(n) | 0 | 100.00
| 0560 |[Subarray Sum Equals K](src/main/c/g0501_0600/s0560_subarray_sum_equals_k/Solution.c)| Medium | Top_100_Liked_Questions, Array, Hash_Table, Prefix_Sum, Big_O_Time_O(n)_Space_O(n) | 20 | 100.00

#### Day 6 String

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 7 String

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0763 |[Partition Labels](src/main/c/g0701_0800/s0763_partition_labels/Solution.c)| Medium | String, Hash_Table, Greedy, Two_Pointers, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00

#### Day 8 String

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0049 |[Group Anagrams](src/main/c/g0001_0100/s0049_group_anagrams/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, String, Hash_Table, Sorting, Big_O_Time_O(n\*k_log_k)_Space_O(n) | 3 | 100.00

#### Day 9 String

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0005 |[Longest Palindromic Substring](src/main/c/g0001_0100/s0005_longest_palindromic_substring/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Dynamic_Programming, Big_O_Time_O(n)_Space_O(n) | 2 | 97.74

#### Day 10 Linked List

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0002 |[Add Two Numbers](src/main/c/g0001_0100/s0002_add_two_numbers/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Math, Linked_List, Recursion, Big_O_Time_O(max(N,M))_Space_O(max(N,M)), AI_can_be_used_to_solve_the_task | 12 | 70.50
| 0142 |[Linked List Cycle II](src/main/c/g0101_0200/s0142_linked_list_cycle_ii/Solution.c)| Medium | Top_100_Liked_Questions, Hash_Table, Two_Pointers, Linked_List, Big_O_Time_O(N)_Space_O(1) | 4 | 81.55

#### Day 11 Linked List

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0160 |[Intersection of Two Linked Lists](src/main/c/g0101_0200/s0160_intersection_of_two_linked_lists/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Hash_Table, Two_Pointers, Linked_List, Big_O_Time_O(M+N)_Space_O(1) | 33 | 78.91

#### Day 12 Linked List

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0024 |[Swap Nodes in Pairs](src/main/c/g0001_0100/s0024_swap_nodes_in_pairs/Solution.c)| Medium | Top_100_Liked_Questions, Linked_List, Recursion, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00

#### Day 13 Linked List

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0025 |[Reverse Nodes in k-Group](src/main/c/g0001_0100/s0025_reverse_nodes_in_k_group/Solution.c)| Hard | Top_100_Liked_Questions, Linked_List, Recursion, Big_O_Time_O(n)_Space_O(k) | 0 | 100.00

#### Day 14 Stack Queue

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0155 |[Min Stack](src/main/c/g0101_0200/s0155_min_stack/MinStack.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Stack, Design, Big_O_Time_O(1)_Space_O(N) | 0 | 100.00

#### Day 15 Tree

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0105 |[Construct Binary Tree from Preorder and Inorder Traversal](src/main/c/g0101_0200/s0105_construct_binary_tree_from_preorder_and_inorder_traversal/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Hash_Table, Tree, Binary_Tree, Divide_and_Conquer, Big_O_Time_O(N)_Space_O(N) | 3 | 95.24

#### Day 16 Tree

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 17 Tree

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0230 |[Kth Smallest Element in a BST](src/main/c/g0201_0300/s0230_kth_smallest_element_in_a_bst/Solution.c)| Medium | Top_100_Liked_Questions, Depth_First_Search, Tree, Binary_Tree, Binary_Search_Tree, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00

#### Day 18 Tree

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0236 |[Lowest Common Ancestor of a Binary Tree](src/main/c/g0201_0300/s0236_lowest_common_ancestor_of_a_binary_tree/Solution.c)| Medium | Top_100_Liked_Questions, Depth_First_Search, Tree, Binary_Tree, Big_O_Time_O(n)_Space_O(n) | 15 | 90.08

#### Day 19 Graph

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 20 Heap Priority Queue

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0215 |[Kth Largest Element in an Array](src/main/c/g0201_0300/s0215_kth_largest_element_in_an_array/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Sorting, Heap_Priority_Queue, Divide_and_Conquer, Quickselect, Big_O_Time_O(n\*log(n))_Space_O(log(n)) | 0 | 100.00
| 0347 |[Top K Frequent Elements](src/main/c/g0301_0400/s0347_top_k_frequent_elements/Solution.c)| Medium | Top_100_Liked_Questions, Array, Hash_Table, Sorting, Heap_Priority_Queue, Counting, Divide_and_Conquer, Quickselect, Bucket_Sort, Big_O_Time_O(n\*log(n))_Space_O(k) | 0 | 100.00

#### Day 21 Heap Priority Queue

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

### Algorithm I

#### Day 1 Binary Search

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0035 |[Search Insert Position](src/main/c/g0001_0100/s0035_search_insert_position/Solution.c)| Easy | Top_100_Liked_Questions, Array, Binary_Search, Big_O_Time_O(log_n)_Space_O(1) | 0 | 100.00

#### Day 2 Two Pointers

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0189 |[Rotate Array](src/main/c/g0101_0200/s0189_rotate_array/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Math, Two_Pointers, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00

#### Day 3 Two Pointers

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0283 |[Move Zeroes](src/main/c/g0201_0300/s0283_move_zeroes/Solution.c)| Easy | Top_100_Liked_Questions, Array, Two_Pointers, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00

#### Day 4 Two Pointers

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 5 Two Pointers

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0019 |[Remove Nth Node From End of List](src/main/c/g0001_0100/s0019_remove_nth_node_from_end_of_list/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Two_Pointers, Linked_List, Big_O_Time_O(L)_Space_O(L) | 0 | 100.00

#### Day 6 Sliding Window

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0003 |[Longest Substring Without Repeating Characters](src/main/c/g0001_0100/s0003_longest_substring_without_repeating_characters/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Hash_Table, Sliding_Window, Big_O_Time_O(n)_Space_O(1) | 15 | 29.93

#### Day 7 Breadth First Search Depth First Search

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 8 Breadth First Search Depth First Search

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 9 Breadth First Search Depth First Search

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 10 Recursion Backtracking

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0021 |[Merge Two Sorted Lists](src/main/c/g0001_0100/s0021_merge_two_sorted_lists/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Linked_List, Recursion, Big_O_Time_O(m+n)_Space_O(m+n) | 0 | 100.00
| 0206 |[Reverse Linked List](src/main/c/g0201_0300/s0206_reverse_linked_list/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Linked_List, Recursion, Big_O_Time_O(N)_Space_O(1) | 0 | 100.00

#### Day 11 Recursion Backtracking

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0046 |[Permutations](src/main/c/g0001_0100/s0046_permutations/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Backtracking, Big_O_Time_O(n\*n!)_Space_O(n+n!) | 0 | 100.00

#### Day 12 Dynamic Programming

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0070 |[Climbing Stairs](src/main/c/g0001_0100/s0070_climbing_stairs/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Dynamic_Programming, Math, Memoization, Big_O_Time_O(n)_Space_O(n) | 1 | 100.00
| 0198 |[House Robber](src/main/c/g0101_0200/s0198_house_robber/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00

#### Day 13 Bit Manipulation

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-

#### Day 14 Bit Manipulation

| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- -->
|-|-|-|-|-|-
| 0136 |[Single Number](src/main/c/g0101_0200/s0136_single_number/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Array, Bit_Manipulation, Big_O_Time_O(N)_Space_O(1) | 0 | 100.00

## Algorithms

| #    |      Title     | Difficulty  | Tag         | Time, ms | Time, %
|------|----------------|-------------|-------------|----------|---------
| 1143 |[Longest Common Subsequence](src/main/c/g1101_1200/s1143_longest_common_subsequence/Solution.c)| Medium | Top_100_Liked_Questions, String, Dynamic_Programming, Algorithm_II_Day_17_Dynamic_Programming, Dynamic_Programming_I_Day_19, Udemy_Dynamic_Programming, Big_O_Time_O(n\*m)_Space_O(n\*m) | 21 | 84.72
| 0763 |[Partition Labels](src/main/c/g0701_0800/s0763_partition_labels/Solution.c)| Medium | String, Hash_Table, Greedy, Two_Pointers, Data_Structure_II_Day_7_String, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0739 |[Daily Temperatures](src/main/c/g0701_0800/s0739_daily_temperatures/Solution.c)| Medium | Top_100_Liked_Questions, Array, Stack, Monotonic_Stack, Programming_Skills_II_Day_6, Big_O_Time_O(n)_Space_O(n) | 3 | 98.31
| 0647 |[Palindromic Substrings](src/main/c/g0601_0700/s0647_palindromic_substrings/Solution.c)| Medium | String, Dynamic_Programming, Big_O_Time_O(n^2)_Space_O(n) | 0 | 100.00
| 0560 |[Subarray Sum Equals K](src/main/c/g0501_0600/s0560_subarray_sum_equals_k/Solution.c)| Medium | Top_100_Liked_Questions, Array, Hash_Table, Prefix_Sum, Data_Structure_II_Day_5_Array, Big_O_Time_O(n)_Space_O(n) | 20 | 100.00
| 0543 |[Diameter of Binary Tree](src/main/c/g0501_0600/s0543_diameter_of_binary_tree/Solution.c)| Easy | Top_100_Liked_Questions, Depth_First_Search, Tree, Binary_Tree, Level_2_Day_7_Tree, Udemy_Tree_Stack_Queue, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0494 |[Target Sum](src/main/c/g0401_0500/s0494_target_sum/Solution.c)| Medium | Array, Dynamic_Programming, Backtracking, Big_O_Time_O(n\*(sum+s))_Space_O(n\*(sum+s)) | 7 | 70.83
| 0438 |[Find All Anagrams in a String](src/main/c/g0401_0500/s0438_find_all_anagrams_in_a_string/Solution.c)| Medium | Top_100_Liked_Questions, String, Hash_Table, Sliding_Window, Algorithm_II_Day_5_Sliding_Window, Programming_Skills_II_Day_12, Level_1_Day_12_Sliding_Window/Two_Pointer, Big_O_Time_O(n+m)_Space_O(1) | 0 | 100.00
| 0437 |[Path Sum III](src/main/c/g0401_0500/s0437_path_sum_iii/Solution.c)| Medium | Depth_First_Search, Tree, Binary_Tree, Level_2_Day_7_Tree, Big_O_Time_O(n)_Space_O(n) | 6 | 96.00
| 0416 |[Partition Equal Subset Sum](src/main/c/g0401_0500/s0416_partition_equal_subset_sum/Solution.c)| Medium | Top_100_Liked_Questions, Array, Dynamic_Programming, Level_2_Day_13_Dynamic_Programming, Big_O_Time_O(n\*sums)_Space_O(n\*sums) | 47 | 78.26
| 0394 |[Decode String](src/main/c/g0301_0400/s0394_decode_string/Solution.c)| Medium | Top_100_Liked_Questions, String, Stack, Recursion, Level_1_Day_14_Stack, Udemy_Strings, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0347 |[Top K Frequent Elements](src/main/c/g0301_0400/s0347_top_k_frequent_elements/Solution.c)| Medium | Top_100_Liked_Questions, Array, Hash_Table, Sorting, Heap_Priority_Queue, Counting, Divide_and_Conquer, Quickselect, Bucket_Sort, Data_Structure_II_Day_20_Heap_Priority_Queue, Big_O_Time_O(n\*log(n))_Space_O(k) | 0 | 100.00
| 0338 |[Counting Bits](src/main/c/g0301_0400/s0338_counting_bits/Solution.c)| Easy | Dynamic_Programming, Bit_Manipulation, Udemy_Bit_Manipulation, Big_O_Time_O(num)_Space_O(num) | 0 | 100.00
| 0322 |[Coin Change](src/main/c/g0301_0400/s0322_coin_change/Solution.c)| Medium | Top_100_Liked_Questions, Array, Dynamic_Programming, Breadth_First_Search, Algorithm_II_Day_18_Dynamic_Programming, Dynamic_Programming_I_Day_20, Level_2_Day_12_Dynamic_Programming, Big_O_Time_O(m\*n)_Space_O(amount) | 22 | 87.50
| 0300 |[Longest Increasing Subsequence](src/main/c/g0201_0300/s0300_longest_increasing_subsequence/Solution.c)| Medium | Top_100_Liked_Questions, Array, Dynamic_Programming, Binary_Search, Algorithm_II_Day_16_Dynamic_Programming, Binary_Search_II_Day_3, Dynamic_Programming_I_Day_18, Udemy_Dynamic_Programming, Big_O_Time_O(n\*log_n)_Space_O(n) | 0 | 100.00
| 0295 |[Find Median from Data Stream](src/main/c/g0201_0300/s0295_find_median_from_data_stream/MedianFinder.c)| Hard | Top_100_Liked_Questions, Sorting, Two_Pointers, Design, Heap_Priority_Queue, Data_Stream, Big_O_Time_O(n\*log_n)_Space_O(n) | 28 | 100.00
| 0287 |[Find the Duplicate Number](src/main/c/g0201_0300/s0287_find_the_duplicate_number/Solution.c)| Medium | Top_100_Liked_Questions, Array, Binary_Search, Two_Pointers, Bit_Manipulation, Binary_Search_II_Day_5, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0283 |[Move Zeroes](src/main/c/g0201_0300/s0283_move_zeroes/Solution.c)| Easy | Top_100_Liked_Questions, Array, Two_Pointers, Algorithm_I_Day_3_Two_Pointers, Programming_Skills_I_Day_6_Array, Udemy_Arrays, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0240 |[Search a 2D Matrix II](src/main/c/g0201_0300/s0240_search_a_2d_matrix_ii/Solution.c)| Medium | Top_100_Liked_Questions, Array, Binary_Search, Matrix, Divide_and_Conquer, Data_Structure_II_Day_4_Array, Binary_Search_II_Day_8, Big_O_Time_O(n+m)_Space_O(1) | 42 | 96.34
| 0239 |[Sliding Window Maximum](src/main/c/g0201_0300/s0239_sliding_window_maximum/Solution.c)| Hard | Top_100_Liked_Questions, Array, Heap_Priority_Queue, Sliding_Window, Queue, Monotonic_Queue, Udemy_Arrays, Big_O_Time_O(n\*k)_Space_O(n+k) | 4 | 95.24
| 0238 |[Product of Array Except Self](src/main/c/g0201_0300/s0238_product_of_array_except_self/Solution.c)| Medium | Top_100_Liked_Questions, Array, Prefix_Sum, Data_Structure_II_Day_5_Array, Udemy_Arrays, Big_O_Time_O(n^2)_Space_O(n) | 0 | 100.00
| 0236 |[Lowest Common Ancestor of a Binary Tree](src/main/c/g0201_0300/s0236_lowest_common_ancestor_of_a_binary_tree/Solution.c)| Medium | Top_100_Liked_Questions, Depth_First_Search, Tree, Binary_Tree, Data_Structure_II_Day_18_Tree, Udemy_Tree_Stack_Queue, Big_O_Time_O(n)_Space_O(n) | 15 | 90.08
| 0234 |[Palindrome Linked List](src/main/c/g0201_0300/s0234_palindrome_linked_list/Solution.c)| Easy | Top_100_Liked_Questions, Two_Pointers, Stack, Linked_List, Recursion, Level_2_Day_3_Linked_List, Udemy_Linked_List, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0230 |[Kth Smallest Element in a BST](src/main/c/g0201_0300/s0230_kth_smallest_element_in_a_bst/Solution.c)| Medium | Top_100_Liked_Questions, Depth_First_Search, Tree, Binary_Tree, Binary_Search_Tree, Data_Structure_II_Day_17_Tree, Level_2_Day_9_Binary_Search_Tree, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0226 |[Invert Binary Tree](src/main/c/g0201_0300/s0226_invert_binary_tree/Solution.c)| Easy | Top_100_Liked_Questions, Depth_First_Search, Breadth_First_Search, Tree, Binary_Tree, Data_Structure_I_Day_12_Tree, Level_2_Day_6_Tree, Udemy_Tree_Stack_Queue, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0221 |[Maximal Square](src/main/c/g0201_0300/s0221_maximal_square/Solution.c)| Medium | Array, Dynamic_Programming, Matrix, Dynamic_Programming_I_Day_16, Big_O_Time_O(m\*n)_Space_O(m\*n) | 0 | 100.00
| 0215 |[Kth Largest Element in an Array](src/main/c/g0201_0300/s0215_kth_largest_element_in_an_array/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Sorting, Heap_Priority_Queue, Divide_and_Conquer, Quickselect, Data_Structure_II_Day_20_Heap_Priority_Queue, Big_O_Time_O(n\*log(n))_Space_O(log(n)) | 0 | 100.00
| 0208 |[Implement Trie (Prefix Tree)](src/main/c/g0201_0300/s0208_implement_trie_prefix_tree/Trie.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Hash_Table, Design, Trie, Level_2_Day_16_Design, Udemy_Trie_and_Heap, Big_O_Time_O(word.length())_or_O(prefix.length())_Space_O(N) | 7 | 100.00
| 0207 |[Course Schedule](src/main/c/g0201_0300/s0207_course_schedule/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Depth_First_Search, Breadth_First_Search, Graph, Topological_Sort, Big_O_Time_O(N)_Space_O(N) | 0 | 100.00
| 0206 |[Reverse Linked List](src/main/c/g0201_0300/s0206_reverse_linked_list/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Linked_List, Recursion, Data_Structure_I_Day_8_Linked_List, Algorithm_I_Day_10_Recursion_Backtracking, Level_1_Day_3_Linked_List, Udemy_Linked_List, Big_O_Time_O(N)_Space_O(1) | 0 | 100.00
| 0200 |[Number of Islands](src/main/c/g0101_0200/s0200_number_of_islands/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Depth_First_Search, Breadth_First_Search, Matrix, Union_Find, Algorithm_II_Day_6_Breadth_First_Search_Depth_First_Search, Graph_Theory_I_Day_1_Matrix_Related_Problems, Level_1_Day_9_Graph/BFS/DFS, Udemy_Graph, Big_O_Time_O(M\*N)_Space_O(M\*N) | 14 | 96.18
| 0198 |[House Robber](src/main/c/g0101_0200/s0198_house_robber/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Algorithm_I_Day_12_Dynamic_Programming, Dynamic_Programming_I_Day_3, Level_2_Day_12_Dynamic_Programming, Udemy_Dynamic_Programming, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0189 |[Rotate Array](src/main/c/g0101_0200/s0189_rotate_array/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Math, Two_Pointers, Algorithm_I_Day_2_Two_Pointers, Udemy_Arrays, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0169 |[Majority Element](src/main/c/g0101_0200/s0169_majority_element/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Array, Hash_Table, Sorting, Counting, Divide_and_Conquer, Data_Structure_II_Day_1_Array, Udemy_Famous_Algorithm, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0160 |[Intersection of Two Linked Lists](src/main/c/g0101_0200/s0160_intersection_of_two_linked_lists/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Hash_Table, Two_Pointers, Linked_List, Data_Structure_II_Day_11_Linked_List, Udemy_Linked_List, Big_O_Time_O(M+N)_Space_O(1) | 33 | 78.91
| 0155 |[Min Stack](src/main/c/g0101_0200/s0155_min_stack/MinStack.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Stack, Design, Data_Structure_II_Day_14_Stack_Queue, Programming_Skills_II_Day_18, Level_2_Day_16_Design, Udemy_Design, Big_O_Time_O(1)_Space_O(N) | 0 | 100.00
| 0153 |[Find Minimum in Rotated Sorted Array](src/main/c/g0101_0200/s0153_find_minimum_in_rotated_sorted_array/Solution.c)| Medium | Top_100_Liked_Questions, Array, Binary_Search, Algorithm_II_Day_2_Binary_Search, Binary_Search_I_Day_12, Udemy_Binary_Search, Big_O_Time_O(log_N)_Space_O(log_N) | 0 | 100.00
| 0152 |[Maximum Product Subarray](src/main/c/g0101_0200/s0152_maximum_product_subarray/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Dynamic_Programming_I_Day_6, Level_2_Day_13_Dynamic_Programming, Udemy_Dynamic_Programming, Big_O_Time_O(N)_Space_O(1) | 0 | 100.00
| 0148 |[Sort List](src/main/c/g0101_0200/s0148_sort_list/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Sorting, Two_Pointers, Linked_List, Divide_and_Conquer, Merge_Sort, Level_2_Day_4_Linked_List, Big_O_Time_O(log(N))_Space_O(log(N)) | 3 | 100.00
| 0146 |[LRU Cache](src/main/c/g0101_0200/s0146_lru_cache/LRUCache.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Hash_Table, Design, Linked_List, Doubly_Linked_List, Udemy_Linked_List, Big_O_Time_O(1)_Space_O(capacity) | 37 | 91.67
| 0142 |[Linked List Cycle II](src/main/c/g0101_0200/s0142_linked_list_cycle_ii/Solution.c)| Medium | Top_100_Liked_Questions, Hash_Table, Two_Pointers, Linked_List, Data_Structure_II_Day_10_Linked_List, Level_1_Day_4_Linked_List, Udemy_Linked_List, Big_O_Time_O(N)_Space_O(1) | 4 | 81.55
| 0141 |[Linked List Cycle](src/main/c/g0101_0200/s0141_linked_list_cycle/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Hash_Table, Two_Pointers, Linked_List, Data_Structure_I_Day_7_Linked_List, Udemy_Linked_List, Big_O_Time_O(N)_Space_O(1) | 6 | 92.85
| 0139 |[Word Break](src/main/c/g0101_0200/s0139_word_break/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Hash_Table, Dynamic_Programming, Trie, Memoization, Algorithm_II_Day_15_Dynamic_Programming, Dynamic_Programming_I_Day_9, Udemy_Dynamic_Programming, Big_O_Time_O(M+max\*N)_Space_O(M+N+max) | 0 | 100.00
| 0138 |[Copy List with Random Pointer](src/main/c/g0101_0200/s0138_copy_list_with_random_pointer/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Hash_Table, Linked_List, Programming_Skills_II_Day_14, Udemy_Linked_List, Big_O_Time_O(N)_Space_O(N) | 4 | 91.18
| 0136 |[Single Number](src/main/c/g0101_0200/s0136_single_number/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Array, Bit_Manipulation, Data_Structure_II_Day_1_Array, Algorithm_I_Day_14_Bit_Manipulation, Udemy_Integers, Big_O_Time_O(N)_Space_O(1) | 0 | 100.00
| 0131 |[Palindrome Partitioning](src/main/c/g0101_0200/s0131_palindrome_partitioning/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Hash_Table, Union_Find, Big_O_Time_O(N_log_N)_Space_O(1) | 19 | 89.29
| 0128 |[Longest Consecutive Sequence](src/main/c/g0101_0200/s0128_longest_consecutive_sequence/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Hash_Table, Union_Find, Big_O_Time_O(N_log_N)_Space_O(1) | 19 | 89.29
| 0124 |[Binary Tree Maximum Path Sum](src/main/c/g0101_0200/s0124_binary_tree_maximum_path_sum/Solution.c)| Hard | Top_100_Liked_Questions, Top_Interview_Questions, Dynamic_Programming, Depth_First_Search, Tree, Binary_Tree, Udemy_Tree_Stack_Queue, Big_O_Time_O(N)_Space_O(N) | 0 | 100.00
| 0121 |[Best Time to Buy and Sell Stock](src/main/c/g0101_0200/s0121_best_time_to_buy_and_sell_stock/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Data_Structure_I_Day_3_Array, Dynamic_Programming_I_Day_7, Level_1_Day_5_Greedy, Udemy_Arrays, Big_O_Time_O(N)_Space_O(1) | 0 | 100.00
| 0114 |[Flatten Binary Tree to Linked List](src/main/c/g0101_0200/s0114_flatten_binary_tree_to_linked_list/Solution.c)| Medium | Top_100_Liked_Questions, Depth_First_Search, Tree, Binary_Tree, Stack, Linked_List, Udemy_Linked_List, Big_O_Time_O(N)_Space_O(N) | 0 | 100.00
| 0105 |[Construct Binary Tree from Preorder and Inorder Traversal](src/main/c/g0101_0200/s0105_construct_binary_tree_from_preorder_and_inorder_traversal/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Hash_Table, Tree, Binary_Tree, Divide_and_Conquer, Data_Structure_II_Day_15_Tree, Big_O_Time_O(N)_Space_O(N) | 3 | 95.24
| 0104 |[Maximum Depth of Binary Tree](src/main/c/g0101_0200/s0104_maximum_depth_of_binary_tree/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Depth_First_Search, Breadth_First_Search, Tree, Binary_Tree, Data_Structure_I_Day_11_Tree, Programming_Skills_I_Day_10_Linked_List_and_Tree, Udemy_Tree_Stack_Queue, Big_O_Time_O(N)_Space_O(H) | 0 | 100.00
| 0102 |[Binary Tree Level Order Traversal](src/main/c/g0101_0200/s0102_binary_tree_level_order_traversal/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Breadth_First_Search, Tree, Binary_Tree, Data_Structure_I_Day_11_Tree, Level_1_Day_6_Tree, Udemy_Tree_Stack_Queue, Big_O_Time_O(N)_Space_O(N) | 0 | 100.00
| 0101 |[Symmetric Tree](src/main/c/g0101_0200/s0101_symmetric_tree/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Depth_First_Search, Breadth_First_Search, Tree, Binary_Tree, Data_Structure_I_Day_11_Tree, Level_2_Day_15_Tree, Big_O_Time_O(N)_Space_O(log(N)) | 0 | 100.00
| 0098 |[Validate Binary Search Tree](src/main/c/g0001_0100/s0098_validate_binary_search_tree/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Depth_First_Search, Tree, Binary_Tree, Binary_Search_Tree, Data_Structure_I_Day_14_Tree, Level_1_Day_8_Binary_Search_Tree, Udemy_Tree_Stack_Queue, Big_O_Time_O(N)_Space_O(log(N)) | 0 | 100.00
| 0096 |[Unique Binary Search Trees](src/main/c/g0001_0100/s0096_unique_binary_search_trees/Solution.c)| Medium | Dynamic_Programming, Math, Tree, Binary_Tree, Binary_Search_Tree, Dynamic_Programming_I_Day_11, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0094 |[Binary Tree Inorder Traversal](src/main/c/g0001_0100/s0094_binary_tree_inorder_traversal/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Depth_First_Search, Tree, Binary_Tree, Stack, Data_Structure_I_Day_10_Tree, Udemy_Tree_Stack_Queue, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0084 |[Largest Rectangle in Histogram](src/main/c/g0001_0100/s0084_largest_rectangle_in_histogram/Solution.c)| Hard | Top_100_Liked_Questions, Top_Interview_Questions, Array, Stack, Monotonic_Stack, Big_O_Time_O(n_log_n)_Space_O(log_n) | 7 | 86.96
| 0079 |[Word Search](src/main/c/g0001_0100/s0079_word_search/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Matrix, Backtracking, Algorithm_II_Day_11_Recursion_Backtracking, Big_O_Time_O(4^(m\*n))_Space_O(m\*n) | 121 | 92.31
| 0078 |[Subsets](src/main/c/g0001_0100/s0078_subsets/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Bit_Manipulation, Backtracking, Algorithm_II_Day_9_Recursion_Backtracking, Udemy_Backtracking/Recursion, Big_O_Time_O(2^n)_Space_O(n\*2^n) | 0 | 100.00
| 0076 |[Minimum Window Substring](src/main/c/g0001_0100/s0076_minimum_window_substring/Solution.c)| Hard | Top_100_Liked_Questions, Top_Interview_Questions, String, Hash_Table, Sliding_Window, Level_2_Day_14_Sliding_Window/Two_Pointer, Big_O_Time_O(s.length())_Space_O(1) | 0 | 100.00
| 0075 |[Sort Colors](src/main/c/g0001_0100/s0075_sort_colors/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Sorting, Two_Pointers, Data_Structure_II_Day_2_Array, Udemy_Arrays, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0074 |[Search a 2D Matrix](src/main/c/g0001_0100/s0074_search_a_2d_matrix/Solution.c)| Medium | Top_100_Liked_Questions, Array, Binary_Search, Matrix, Data_Structure_I_Day_5_Array, Algorithm_II_Day_1_Binary_Search, Binary_Search_I_Day_8, Level_2_Day_8_Binary_Search, Udemy_2D_Arrays/Matrix, Big_O_Time_O(endRow+endCol)_Space_O(1) | 0 | 100.00
| 0073 |[Set Matrix Zeroes](src/main/c/g0001_0100/s0073_set_matrix_zeroes/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Hash_Table, Matrix, Udemy_2D_Arrays/Matrix, Big_O_Time_O(m\*n)_Space_O(1) | 0 | 100.00
| 0072 |[Edit Distance](src/main/c/g0001_0100/s0072_edit_distance/Solution.c)| Medium | Top_100_Liked_Questions, String, Dynamic_Programming, Algorithm_II_Day_18_Dynamic_Programming, Dynamic_Programming_I_Day_19, Udemy_Dynamic_Programming, Big_O_Time_O(n^2)_Space_O(n2) | 0 | 100.00
| 0070 |[Climbing Stairs](src/main/c/g0001_0100/s0070_climbing_stairs/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Dynamic_Programming, Math, Memoization, Algorithm_I_Day_12_Dynamic_Programming, Dynamic_Programming_I_Day_2, Level_1_Day_10_Dynamic_Programming, Udemy_Dynamic_Programming, Big_O_Time_O(n)_Space_O(n) | 1 | 100.00
| 0064 |[Minimum Path Sum](src/main/c/g0001_0100/s0064_minimum_path_sum/Solution.c)| Medium | Top_100_Liked_Questions, Array, Dynamic_Programming, Matrix, Dynamic_Programming_I_Day_16, Udemy_Dynamic_Programming, Big_O_Time_O(m\*n)_Space_O(m\*n) | 0 | 100.00
| 0062 |[Unique Paths](src/main/c/g0001_0100/s0062_unique_paths/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Dynamic_Programming, Math, Combinatorics, Algorithm_II_Day_13_Dynamic_Programming, Dynamic_Programming_I_Day_15, Level_1_Day_11_Dynamic_Programming, Big_O_Time_O(m\*n)_Space_O(m\*n) | 0 | 100.00
| 0056 |[Merge Intervals](src/main/c/g0001_0100/s0056_merge_intervals/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Sorting, Data_Structure_II_Day_2_Array, Level_2_Day_17_Interval, Udemy_2D_Arrays/Matrix, Big_O_Time_O(n_log_n)_Space_O(n) | 0 | 100.00
| 0055 |[Jump Game](src/main/c/g0001_0100/s0055_jump_game/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Greedy, Algorithm_II_Day_12_Dynamic_Programming, Dynamic_Programming_I_Day_4, Udemy_Arrays, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0053 |[Maximum Subarray](src/main/c/g0001_0100/s0053_maximum_subarray/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Divide_and_Conquer, Data_Structure_I_Day_1_Array, Dynamic_Programming_I_Day_5, Udemy_Famous_Algorithm, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0051 |[N-Queens](src/main/c/g0001_0100/s0051_n_queens/Solution.c)| Hard | Top_100_Liked_Questions, Array, Backtracking, Big_O_Time_O(N!)_Space_O(N) | 0 | 100.00
| 0049 |[Group Anagrams](src/main/c/g0001_0100/s0049_group_anagrams/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, String, Hash_Table, Sorting, Data_Structure_II_Day_8_String, Programming_Skills_II_Day_11, Udemy_Strings, Big_O_Time_O(n\*k_log_k)_Space_O(n) | 3 | 100.00
| 0048 |[Rotate Image](src/main/c/g0001_0100/s0048_rotate_image/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Math, Matrix, Data_Structure_II_Day_3_Array, Programming_Skills_II_Day_7, Udemy_2D_Arrays/Matrix, Big_O_Time_O(n^2)_Space_O(1) | 0 | 100.00
| 0046 |[Permutations](src/main/c/g0001_0100/s0046_permutations/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Backtracking, Algorithm_I_Day_11_Recursion_Backtracking, Level_2_Day_20_Brute_Force/Backtracking, Udemy_Backtracking/Recursion, Big_O_Time_O(n\*n!)_Space_O(n+n!) | 0 | 100.00
| 0045 |[Jump Game II](src/main/c/g0001_0100/s0045_jump_game_ii/Solution.c)| Medium | Top_100_Liked_Questions, Array, Dynamic_Programming, Greedy, Algorithm_II_Day_13_Dynamic_Programming, Dynamic_Programming_I_Day_4, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0042 |[Trapping Rain Water](src/main/c/g0001_0100/s0042_trapping_rain_water/Solution.c)| Hard | Top_100_Liked_Questions, Top_Interview_Questions, Array, Dynamic_Programming, Two_Pointers, Stack, Monotonic_Stack, Dynamic_Programming_I_Day_9, Udemy_Two_Pointers, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0041 |[First Missing Positive](src/main/c/g0001_0100/s0041_first_missing_positive/Solution.c)| Hard | Top_100_Liked_Questions, Top_Interview_Questions, Array, Hash_Table, Udemy_Arrays, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0039 |[Combination Sum](src/main/c/g0001_0100/s0039_combination_sum/Solution.c)| Medium | Top_100_Liked_Questions, Array, Backtracking, Algorithm_II_Day_10_Recursion_Backtracking, Level_2_Day_20_Brute_Force/Backtracking, Udemy_Backtracking/Recursion, Big_O_Time_O(2^n)_Space_O(n+2^n) | 0 | 100.00
| 0035 |[Search Insert Position](src/main/c/g0001_0100/s0035_search_insert_position/Solution.c)| Easy | Top_100_Liked_Questions, Array, Binary_Search, Algorithm_I_Day_1_Binary_Search, Binary_Search_I_Day_2, Big_O_Time_O(log_n)_Space_O(1) | 0 | 100.00
| 0034 |[Find First and Last Position of Element in Sorted Array](src/main/c/g0001_0100/s0034_find_first_and_last_position_of_element_in_sorted_array/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Binary_Search, Algorithm_II_Day_1_Binary_Search, Binary_Search_I_Day_5, Big_O_Time_O(log_n)_Space_O(1) | 0 | 100.00
| 0033 |[Search in Rotated Sorted Array](src/main/c/g0001_0100/s0033_search_in_rotated_sorted_array/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Binary_Search, Algorithm_II_Day_1_Binary_Search, Binary_Search_I_Day_11, Level_2_Day_8_Binary_Search, Udemy_Binary_Search, Big_O_Time_O(log_n)_Space_O(1) | 0 | 100.00
| 0032 |[Longest Valid Parentheses](src/main/c/g0001_0100/s0032_longest_valid_parentheses/Solution.c)| Hard | Top_100_Liked_Questions, String, Dynamic_Programming, Stack, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0031 |[Next Permutation](src/main/c/g0001_0100/s0031_next_permutation/Solution.c)| Medium | Top_100_Liked_Questions, Array, Two_Pointers, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0025 |[Reverse Nodes in k-Group](src/main/c/g0001_0100/s0025_reverse_nodes_in_k_group/Solution.c)| Hard | Top_100_Liked_Questions, Linked_List, Recursion, Data_Structure_II_Day_13_Linked_List, Udemy_Linked_List, Big_O_Time_O(n)_Space_O(k) | 0 | 100.00
| 0024 |[Swap Nodes in Pairs](src/main/c/g0001_0100/s0024_swap_nodes_in_pairs/Solution.c)| Medium | Top_100_Liked_Questions, Linked_List, Recursion, Data_Structure_II_Day_12_Linked_List, Udemy_Linked_List, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0023 |[Merge k Sorted Lists](src/main/c/g0001_0100/s0023_merge_k_sorted_lists/Solution.c)| Hard | Top_100_Liked_Questions, Top_Interview_Questions, Heap_Priority_Queue, Linked_List, Divide_and_Conquer, Merge_Sort, Big_O_Time_O(k\*n\*log(k))_Space_O(log(k)) | 0 | 100.00
| 0022 |[Generate Parentheses](src/main/c/g0001_0100/s0022_generate_parentheses/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Dynamic_Programming, Backtracking, Algorithm_II_Day_11_Recursion_Backtracking, Udemy_Backtracking/Recursion, Big_O_Time_O(2^n)_Space_O(n) | 0 | 100.00
| 0021 |[Merge Two Sorted Lists](src/main/c/g0001_0100/s0021_merge_two_sorted_lists/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Linked_List, Recursion, Data_Structure_I_Day_7_Linked_List, Algorithm_I_Day_10_Recursion_Backtracking, Level_1_Day_3_Linked_List, Udemy_Linked_List, Big_O_Time_O(m+n)_Space_O(m+n) | 0 | 100.00
| 0020 |[Valid Parentheses](src/main/c/g0001_0100/s0020_valid_parentheses/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, String, Stack, Data_Structure_I_Day_9_Stack_Queue, Udemy_Strings, Big_O_Time_O(n)_Space_O(n) | 0 | 100.00
| 0019 |[Remove Nth Node From End of List](src/main/c/g0001_0100/s0019_remove_nth_node_from_end_of_list/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Two_Pointers, Linked_List, Algorithm_I_Day_5_Two_Pointers, Level_2_Day_3_Linked_List, Big_O_Time_O(L)_Space_O(L) | 0 | 100.00
| 0017 |[Letter Combinations of a Phone Number](src/main/c/g0001_0100/s0017_letter_combinations_of_a_phone_number/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Hash_Table, Backtracking, Algorithm_II_Day_11_Recursion_Backtracking, Udemy_Backtracking/Recursion, Big_O_Time_O(4^n)_Space_O(n) | 0 | 100.00
| 0015 |[3Sum](src/main/c/g0001_0100/s0015_3sum/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Sorting, Two_Pointers, Data_Structure_II_Day_1_Array, Algorithm_II_Day_3_Two_Pointers, Udemy_Two_Pointers, Big_O_Time_O(n\*log(n))_Space_O(n^2) | 47 | 87.75
| 0011 |[Container With Most Water](src/main/c/g0001_0100/s0011_container_with_most_water/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Array, Greedy, Two_Pointers, Algorithm_II_Day_4_Two_Pointers, Big_O_Time_O(n)_Space_O(1) | 0 | 100.00
| 0010 |[Regular Expression Matching](src/main/c/g0001_0100/s0010_regular_expression_matching/Solution.c)| Hard | Top_Interview_Questions, String, Dynamic_Programming, Recursion, Udemy_Dynamic_Programming, Big_O_Time_O(m\*n)_Space_O(m\*n) | 0 | 100.00
| 0009 |[Palindrome Number](src/main/c/g0001_0100/s0009_palindrome_number/Solution.c)| Easy | Math, Udemy_Integers | 0 | 100.00
| 0008 |[String to Integer (atoi)](src/main/c/g0001_0100/s0008_string_to_integer_atoi/Solution.c)| Medium | Top_Interview_Questions, String | 0 | 100.00
| 0007 |[Reverse Integer](src/main/c/g0001_0100/s0007_reverse_integer/Solution.c)| Medium | Top_Interview_Questions, Math, Udemy_Integers | 0 | 100.00
| 0006 |[Zigzag Conversion](src/main/c/g0001_0100/s0006_zigzag_conversion/Solution.c)| Medium | String | 0 | 100.00
| 0005 |[Longest Palindromic Substring](src/main/c/g0001_0100/s0005_longest_palindromic_substring/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Dynamic_Programming, Data_Structure_II_Day_9_String, Algorithm_II_Day_14_Dynamic_Programming, Dynamic_Programming_I_Day_17, Udemy_Strings, Big_O_Time_O(n)_Space_O(n) | 2 | 97.74
| 0004 |[Median of Two Sorted Arrays](src/main/c/g0001_0100/s0004_median_of_two_sorted_arrays/Solution.c)| Hard | Top_100_Liked_Questions, Top_Interview_Questions, Array, Binary_Search, Divide_and_Conquer, Big_O_Time_O(log(min(N,M)))_Space_O(1) | 0 | 100.00
| 0003 |[Longest Substring Without Repeating Characters](src/main/c/g0001_0100/s0003_longest_substring_without_repeating_characters/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, String, Hash_Table, Sliding_Window, Algorithm_I_Day_6_Sliding_Window, Level_2_Day_14_Sliding_Window/Two_Pointer, Udemy_Strings, Big_O_Time_O(n)_Space_O(1) | 15 | 29.93
| 0002 |[Add Two Numbers](src/main/c/g0001_0100/s0002_add_two_numbers/Solution.c)| Medium | Top_100_Liked_Questions, Top_Interview_Questions, Math, Linked_List, Recursion, Data_Structure_II_Day_10_Linked_List, Programming_Skills_II_Day_15, Big_O_Time_O(max(N,M))_Space_O(max(N,M)), AI_can_be_used_to_solve_the_task | 12 | 70.50
| 0001 |[Two Sum](src/main/c/g0001_0100/s0001_two_sum/Solution.c)| Easy | Top_100_Liked_Questions, Top_Interview_Questions, Array, Hash_Table, Data_Structure_I_Day_2_Array, Level_1_Day_13_Hashmap, Udemy_Arrays, Big_O_Time_O(n)_Space_O(n), AI_can_be_used_to_solve_the_task | 2 | 99.56

## Contributing
Your ideas/fixes/algorithms are more than welcome!

1. Fork this repo
2. Clone your forked repo (`git clone https://github.com/YOUR_GITHUB_USERNAME/LeetCode-in-C.git`) onto your local machine
3. `cd` into your cloned directory, create your feature branch (`git checkout -b my-awesome-fix`)
4. `git add` your desired changes to this repo
5. Commit your changes (`git commit -m 'Added some awesome features/fixes'`)
6. Push to the branch (`git push origin my-awesome-feature`)
7. Open your forked repo on Github website, create a new Pull Request to this repo!
