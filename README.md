# leetcode.go

> My solutions(Golang) of problems in https://leetcode.com/

[![Build Status](https://travis-ci.org/WindomZ/leetcode.go.svg?branch=master)](https://travis-ci.org/WindomZ/leetcode.go)
[![Coverage Status](https://coveralls.io/repos/github/WindomZ/leetcode.go/badge.svg?branch=master)](https://coveralls.io/github/WindomZ/leetcode.go?branch=master)
[![Go Report Card](https://goreportcard.com/badge/github.com/WindomZ/leetcode.go)](https://goreportcard.com/report/github.com/WindomZ/leetcode.go)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FWindomZ%2Fleetcode.go.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FWindomZ%2Fleetcode.go?ref=badge_shield)

## Pursue

- **Faster** and **Better** solutions.
- **100%** coverage tests.
- **100%** benchmark tests.

> Secret all in the subtle.

## Catalog

- [Pursue](#pursue)
- [Solutions](#solutions)
- [Testing](#testing)
- [Related](#related)
  - [Helper](#helper)
- [Contributing](#contributing)
  - [Challenge](#challenge)
  - [Discuss](#discuss)
  - [Support](#support)

## Solutions

> '`Single Repetition Duration`' and '`LeetCode Run Time`' are for **reference** only.

| # | **Problem** & **Solution** | Difficulty | Single Repetition Duration | LeetCode Run Time |
| ---: | :----- | :----------: | ----------: | ----------: |
|[90][Solutions-90]|[Subsets II][Solutions-90-Home]|Medium|[326 ns/op/5 test cases][Solutions-90-Test]|9 ms|
|[89][Solutions-89]|[Gray Code][Solutions-89-Home]|Medium|[88.6 ns/op/6 test cases][Solutions-89-Test]|9 ms|
|[88][Solutions-88]|[Merge Sorted Array][Solutions-88-Home]|Easy|[9.00 ns/op/6 test cases][Solutions-88-Test]|3 ms|
|[86][Solutions-86]|[Partition List][Solutions-86-Home]|Medium|[89.1 ns/op/3 test cases][Solutions-86-Test]|3 ms|
|[83][Solutions-83]|[Remove Duplicates from Sorted List][Solutions-83-Home]|Easy|[93.0 ns/op/6 test cases][Solutions-83-Test]|9 ms|
|[82][Solutions-82]|[Remove Duplicates from Sorted List II][Solutions-82-Home]|Medium|[9.62 ns/op/6 test cases][Solutions-82-Test]|6 ms|
|[81][Solutions-81]|[Search in Rotated Sorted Array II][Solutions-81-Home]|Medium|[11.7 ns/op/12 test cases][Solutions-81-Test]|9 ms|
|[80][Solutions-80]|[Remove Duplicates from Sorted Array II][Solutions-80-Home]|Medium|[9.82 ns/op/6 test cases][Solutions-80-Test]|12 ms|
|[79][Solutions-79]|[Word Search][Solutions-79-Home]|Medium|[73.3 ns/op/6 test cases][Solutions-79-Test]|6 ms|
|[78][Solutions-78]|[Subsets][Solutions-78-Home]|Medium|[447 ns/op/5 test cases][Solutions-78-Test]|6 ms|
|[77][Solutions-77]|[Combinations][Solutions-77-Home]|Medium|[336 ns/op/6 test cases][Solutions-77-Test]|246 ms|
|[75][Solutions-75]|[Sort Colors][Solutions-75-Home]|Medium|[13.4 ns/op/6 test cases][Solutions-75-Test]|3 ms|
|[74][Solutions-74]|[Search a 2D Matrix][Solutions-74-Home]|Medium|[32.5 ns/op/6 test cases][Solutions-74-Test]|16 ms|
|[73][Solutions-73]|[Set Matrix Zeroes][Solutions-73-Home]|Medium|[22.0 ns/op/6 test cases][Solutions-73-Test]|42 ms|
|[71][Solutions-71]|[Simplify Path][Solutions-71-Home]|Medium|[382 ns/op/6 test cases][Solutions-71-Test]|3 ms|
|[70][Solutions-70]|[Climbing Stairs][Solutions-70-Home]|Easy|[7.59 ns/op/9 test cases][Solutions-70-Test]|0 ms|
|[69][Solutions-69]|[Sqrt(x)][Solutions-69-Home]|Easy|[27.6 ns/op/8 test cases][Solutions-69-Test]|6 ms|
|[67][Solutions-67]|[Add Binary][Solutions-67-Home]|Easy|[84.0 ns/op/5 test cases][Solutions-67-Test]|3 ms|
|[66][Solutions-66]|[Plus One][Solutions-66-Home]|Easy|[29.8 ns/op/6 test cases][Solutions-66-Test]|3 ms|
|[65][Solutions-65]|[Valid Number][Solutions-65-Home]|Hard|[46.3 ns/op/8 test cases][Solutions-65-Test]|9 ms|
|[64][Solutions-64]|[Minimum Path Sum][Solutions-64-Home]|Medium|[48.4 ns/op/5 test cases][Solutions-64-Test]|16 ms|
|[63][Solutions-63]|[Unique Paths II][Solutions-63-Home]|Medium|[36.3 ns/op/5 test cases][Solutions-63-Test]|3 ms|
|[62][Solutions-62]|[Unique Paths][Solutions-62-Home]|Medium|[5.51 ns/op/11 test cases][Solutions-62-Test]|0 ms|
|[61][Solutions-61]|[Rotate List][Solutions-61-Home]|Medium|[34.0 ns/op/2 test cases][Solutions-61-Test]|6 ms|
|[60][Solutions-60]|[Permutation Sequence][Solutions-60-Home]|Medium|[73.9 ns/op/6 test cases][Solutions-60-Test]|3 ms|
|[59][Solutions-59]|[Spiral Matrix II][Solutions-59-Home]|Medium|[82.1 ns/op/3 test cases][Solutions-59-Test]|0 ms|
|[58][Solutions-58]|[Length of Last Word][Solutions-58-Home]|Easy|[4.02 ns/op/5 test cases][Solutions-58-Test]|0 ms|
|[56][Solutions-56]|[Merge Intervals][Solutions-56-Home]|Medium|[154 ns/op/5 test cases][Solutions-56-Test]|19 ms|
|[55][Solutions-55]|[Jump Game][Solutions-55-Home]|Medium|[7.32 ns/op/6 test cases][Solutions-55-Test]|19 ms|
|[54][Solutions-54]|[Spiral Matrix][Solutions-54-Home]|Medium|[45.5 ns/op/3 test cases][Solutions-54-Test]|0 ms|
|[53][Solutions-53]|[Maximum Subarray][Solutions-53-Home]|Easy|[10.3 ns/op/6 test cases][Solutions-53-Test]|12 ms|
|[50][Solutions-50]|[Pow(x, n)][Solutions-50-Home]|Medium|[7.31 ns/op/12 test cases][Solutions-50-Test]|3 ms|
|[49][Solutions-49]|[Group Anagrams][Solutions-49-Home]|Medium|[313 ns/op/3 test cases][Solutions-49-Test]|582 ms|
|[48][Solutions-48]|[Rotate Image][Solutions-48-Home]|Medium|[12.1 ns/op/3 test cases][Solutions-48-Test]|3 ms|
|[47][Solutions-47]|[Permutations II][Solutions-47-Home]|Medium|[198 ns/op/3 test cases][Solutions-47-Test]|19 ms|
|[46][Solutions-46]|[Permutations][Solutions-46-Home]|Medium|[484 ns/op/3 test cases][Solutions-46-Test]|9 ms|
|[45][Solutions-45]|[Jump Game II][Solutions-45-Home]|Hard|[5.14 ns/op/6 test cases][Solutions-45-Test]|19 ms|
|[44][Solutions-44]|[Wildcard Matching][Solutions-44-Home]|Hard|[10.9 ns/op/9 test cases][Solutions-44-Test]|15 ms|
|[43][Solutions-43]|[Multiply Strings][Solutions-43-Home]|Medium|[53.4 ns/op/6 test cases][Solutions-43-Test]|3 ms|
|[42][Solutions-42]|[Trapping Rain Water][Solutions-42-Home]|Hard|[14.4 ns/op/6 test cases][Solutions-42-Test]|6 ms|
|[41][Solutions-41]|[First Missing Positive][Solutions-41-Home]|Hard|[12.3 ns/op/6 test cases][Solutions-41-Test]|3 ms|
|[40][Solutions-40]|[Combination Sum II][Solutions-40-Home]|Medium|[203 ns/op/3 test cases][Solutions-40-Test]|3 ms|
|[39][Solutions-39]|[Combination Sum][Solutions-39-Home]|Medium|[165 ns/op/3 test cases][Solutions-39-Test]|6 ms|
|[38][Solutions-38]|[Count and Say][Solutions-38-Home]|Easy|[66.8 ns/op/4 test cases][Solutions-38-Test]|0 ms|
|[37][Solutions-37]|[Sudoku Solver][Solutions-37-Home]|Hard|[35497 ns/op/2 test cases][Solutions-37-Test]|0 ms|
|[36][Solutions-36]|[Valid Sudoku][Solutions-36-Home]|Medium|[135 ns/op/3 test cases][Solutions-36-Test]|6 ms|
|[35][Solutions-35]|[Search Insert Position][Solutions-35-Home]|Easy|[7.76 ns/op/8 test cases][Solutions-35-Test]|6 ms|
|[34][Solutions-34]|[Search for a Range][Solutions-34-Home]|Medium|[53.5 ns/op/8 test cases][Solutions-34-Test]|19 ms|
|[33][Solutions-33]|[Search in Rotated Sorted Array][Solutions-33-Home]|Medium|[30.0 ns/op/8 test cases][Solutions-33-Test]|3 ms|
|[32][Solutions-32]|[Longest Valid Parentheses][Solutions-32-Home]|Hard|[78.9 ns/op/8 test cases][Solutions-32-Test]|3 ms|
|[31][Solutions-31]|[Next Permutation][Solutions-31-Home]|Medium|[2.97 ns/op/4 test cases][Solutions-31-Test]|6 ms|
|[30][Solutions-30]|[Substring with Concatenation of All Words][Solutions-30-Home]|Hard|[331 ns/op/3 test cases][Solutions-30-Test]|13 ms|
|[29][Solutions-29]|[Divide Two Integers][Solutions-29-Home]|Medium|[63.2 ns/op/12 test cases][Solutions-29-Test]|6 ms|
|[28][Solutions-28]|[Implement strStr()][Solutions-28-Home]|Easy|[9.29 ns/op/7 test cases][Solutions-28-Test]|0 ms|
|[27][Solutions-27]|[Remove Element][Solutions-27-Home]|Easy|[8.75 ns/op/6 test cases][Solutions-27-Test]|3 ms|
|[26][Solutions-26]|[Remove Duplicates from Sorted Array][Solutions-26-Home]|Easy|[9.51 ns/op/6 test cases][Solutions-26-Test]|102 ms|
|[25][Solutions-25]|[Reverse Nodes in k-Group][Solutions-25-Home]|Hard|[58.6 ns/op/3 test cases][Solutions-25-Test]|9 ms|
|[24][Solutions-24]|[Swap Nodes in Pairs][Solutions-24-Home]|Medium|[62.1 ns/op/4 test cases][Solutions-24-Test]|0 ms|
|[23][Solutions-23]|[Merge k Sorted Lists][Solutions-23-Home]|Hard|[88.7 ns/op/4 test cases][Solutions-23-Test]|19 ms|
|[22][Solutions-22]|[Generate Parentheses][Solutions-22-Home]|Medium|[340 ns/op/4 test cases][Solutions-22-Test]|13 ms|
|[21][Solutions-21]|[Merge Two Sorted Lists][Solutions-21-Home]|Easy|[89.0 ns/op/3 test cases][Solutions-21-Test]|3 ms|
|[20][Solutions-20]|[Valid Parentheses][Solutions-20-Home]|Easy|[28.9 ns/op/6 test cases][Solutions-20-Test]|0 ms|
|[19][Solutions-19]|[Remove Nth Node From End of List][Solutions-19-Home]|Medium|[97.3 ns/op/6 test cases][Solutions-19-Test]|3 ms|
|[18][Solutions-18]|[4Sum][Solutions-18-Home]|Medium|[233 ns/op/3 test cases][Solutions-18-Test]|16 ms|
|[17][Solutions-17]|[Letter Combinations of a Phone Number][Solutions-17-Home]|Medium|[407 ns/op/4 test cases][Solutions-17-Test]|0 ms|
|[16][Solutions-16]|[3Sum Closest][Solutions-16-Home]|Medium|[379 ns/op/8 test cases][Solutions-16-Test]|9 ms|
|[15][Solutions-15]|[3Sum][Solutions-15-Home]|Medium|[183 ns/op/4 test cases][Solutions-15-Test]|1525 ms|
|[14][Solutions-14]|[Longest Common Prefix][Solutions-14-Home]|Easy|[10.6 ns/op/8 test cases][Solutions-14-Test]|3 ms|
|[13][Solutions-13]|[Roman to Integer][Solutions-13-Home]|Easy|[16.9 ns/op/8 test cases][Solutions-13-Test]|19 ms|
|[12][Solutions-12]|[Integer to Roman][Solutions-12-Home]|Medium|[26.4 ns/op/8 test cases][Solutions-12-Test]|22 ms|
|[11][Solutions-11]|[Container With Most Water][Solutions-11-Home]|Medium|[7.84 ns/op/5 test cases][Solutions-11-Test]|25 ms|
|[10][Solutions-10]|[Regular Expression Matching][Solutions-10-Home]|Hard|[183 ns/op/6 test cases][Solutions-10-Test]|3 ms|
|[9][Solutions-9]|[Palindrome Number][Solutions-9-Home]|Easy|[6.37 ns/op/7 test cases][Solutions-9-Test]|55 ms|
|[8][Solutions-8]|[String to Integer (atoi)][Solutions-8-Home]|Medium|[7.31 ns/op/5 test cases][Solutions-8-Test]|3 ms|
|[7][Solutions-7]|[Reverse Integer][Solutions-7-Home]|Easy|[9.00 ns/op/5 test cases][Solutions-7-Test]|3 ms|
|[6][Solutions-6]|[ZigZag Conversion][Solutions-6-Home]|Medium|[55.1 ns/op/5 test cases][Solutions-6-Test]|9 ms|
|[5][Solutions-5]|[Longest Palindromic Substring][Solutions-5-Home]|Medium|[39.1 ns/op/6 test cases][Solutions-5-Test]|9 ms|
|[4][Solutions-4]|[Median of Two Sorted Arrays][Solutions-4-Home]|Hard|[19.4 ns/op/14 test cases][Solutions-4-Test]|32 ms|
|[3][Solutions-3]|[Longest Substring Without Repeating Characters][Solutions-3-Home]|Medium|[21.3 ns/op/3 test cases][Solutions-3-Test]|6 ms|
|[2][Solutions-2]|[Add Two Numbers][Solutions-2-Home]|Medium|[19.4 ns/op/1 test cases][Solutions-2-Test]|29 ms|
|[1][Solutions-1]|[Two Sum][Solutions-1-Home]|Easy|[79.5 ns/op/3 test cases][Solutions-1-Test]|6 ms|

> All tests should be run on a **same** machine, and through **multiple** benchmark tests.

## Testing

```bash
git clone https://github.com/WindomZ/leetcode.go.git "$YOUR_PROJECT_PATH"
cd "$YOUR_PROJECT_PATH"
go test -v -run=. ./solutions/...
go test -bench=. -benchmem ./solutions/...
```

## Related

### Helper
- [WindomZ/leetcode-init](https://github.com/WindomZ/leetcode-init) - A tool to create leetcode code template via cli.

## Contributing

### Challenge
Welcome to **pull requests(PRs)** of the **better** solutions.

1. _Pass_ all LeetCode test cases.
1. _Pass_ all my test cases.
1. _Faster_ than mine! (on a machine, and run benchmark tests repeatedly)

### Discuss
Welcome to report bugs, suggest ideas and discuss on [issues page](https://github.com/WindomZ/leetcode.go/issues).

### Support
If you like it then you can put a :star:Star on it.

[Solutions-90]:https://leetcode.com/problems/subsets-ii/
[Solutions-90-Home]:solutions/subsets_ii/
[Solutions-90-Golang]:solutions/subsets_ii/subsetsii.go
[Solutions-90-Test]:solutions/subsets_ii/subsetsii_test.go#L55
[Solutions-89]:https://leetcode.com/problems/gray-code/
[Solutions-89-Home]:solutions/gray_code/
[Solutions-89-Golang]:solutions/gray_code/graycode.go
[Solutions-89-Test]:solutions/gray_code/graycode_test.go#L17
[Solutions-88]:https://leetcode.com/problems/merge-sorted-array/
[Solutions-88-Home]:solutions/merge_sorted_array/
[Solutions-88-Golang]:solutions/merge_sorted_array/mergesortedarray.go
[Solutions-88-Test]:solutions/merge_sorted_array/mergesortedarray_test.go#L35
[Solutions-86]:https://leetcode.com/problems/partition-list/
[Solutions-86-Home]:solutions/partition_list/
[Solutions-86-Golang]:solutions/partition_list/partitionlist.go
[Solutions-86-Test]:solutions/partition_list/partitionlist_test.go#L87
[Solutions-83]:https://leetcode.com/problems/remove-duplicates-from-sorted-list/
[Solutions-83-Home]:solutions/remove_duplicates_from_sorted_list/
[Solutions-83-Golang]:solutions/remove_duplicates_from_sorted_list/removeduplicatesfromsortedlist.go
[Solutions-83-Test]:solutions/remove_duplicates_from_sorted_list/removeduplicatesfromsortedlist_test.go#L86
[Solutions-82]:https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/
[Solutions-82-Home]:solutions/remove_duplicates_from_sorted_list_ii/
[Solutions-82-Golang]:solutions/remove_duplicates_from_sorted_list_ii/removeduplicatesfromsortedlistii.go
[Solutions-82-Test]:solutions/remove_duplicates_from_sorted_list_ii/removeduplicatesfromsortedlistii_test.go#L77
[Solutions-81]:https://leetcode.com/problems/search-in-rotated-sorted-array-ii/
[Solutions-81-Home]:solutions/search_in_rotated_sorted_array_ii/
[Solutions-81-Golang]:solutions/search_in_rotated_sorted_array_ii/searchinrotatedsortedarrayii.go
[Solutions-81-Test]:solutions/search_in_rotated_sorted_array_ii/searchinrotatedsortedarrayii_test.go#L25
[Solutions-80]:https://leetcode.com/problems/remove-duplicates-from-sorted-array-ii/
[Solutions-80-Home]:solutions/remove_duplicates_from_sorted_array_ii/
[Solutions-80-Golang]:solutions/remove_duplicates_from_sorted_array_ii/removeduplicatesfromsortedarrayii.go
[Solutions-80-Test]:solutions/remove_duplicates_from_sorted_array_ii/removeduplicatesfromsortedarrayii_test.go#L21
[Solutions-79]:https://leetcode.com/problems/word-search/
[Solutions-79-Home]:solutions/word_search/
[Solutions-79-Golang]:solutions/word_search/wordsearch.go
[Solutions-79-Test]:solutions/word_search/wordsearch_test.go#L30
[Solutions-78]:https://leetcode.com/problems/subsets/
[Solutions-78-Home]:solutions/subsets/
[Solutions-78-Golang]:solutions/subsets/subsets.go
[Solutions-78-Test]:solutions/subsets/subsets_test.go#L62
[Solutions-77]:https://leetcode.com/problems/combinations/
[Solutions-77-Home]:solutions/combinations/
[Solutions-77-Golang]:solutions/combinations/combinations.go
[Solutions-77-Test]:solutions/combinations/combinations_test.go#L32
[Solutions-75]:https://leetcode.com/problems/sort-colors/
[Solutions-75-Home]:solutions/sort_colors/
[Solutions-75-Golang]:solutions/sort_colors/sortcolors.go
[Solutions-75-Test]:solutions/sort_colors/sortcolors_test.go#L35
[Solutions-74]:https://leetcode.com/problems/search-a-2d-matrix/
[Solutions-74-Home]:solutions/search_a_2d_matrix/
[Solutions-74-Golang]:solutions/search_a_2d_matrix/searcha2dmatrix.go
[Solutions-74-Test]:solutions/search_a_2d_matrix/searcha2dmatrix_test.go#L38
[Solutions-73]:https://leetcode.com/problems/set-matrix-zeroes/
[Solutions-73-Home]:solutions/set_matrix_zeroes/
[Solutions-73-Golang]:solutions/set_matrix_zeroes/setmatrixzeroes.go
[Solutions-73-Test]:solutions/set_matrix_zeroes/setmatrixzeroes_test.go#L59
[Solutions-71]:https://leetcode.com/problems/simplify-path/
[Solutions-71-Home]:solutions/simplify_path/
[Solutions-71-Golang]:solutions/simplify_path/simplifypath.go
[Solutions-71-Test]:solutions/simplify_path/simplifypath_test.go#L19
[Solutions-70]:https://leetcode.com/problems/climbing-stairs/
[Solutions-70-Home]:solutions/climbing_stairs/
[Solutions-70-Golang]:solutions/climbing_stairs/climbingstairs.go
[Solutions-70-Test]:solutions/climbing_stairs/climbingstairs_test.go#L17
[Solutions-69]:https://leetcode.com/problems/sqrtx/
[Solutions-69-Home]:solutions/sqrtx/
[Solutions-69-Golang]:solutions/sqrtx/sqrtx.go
[Solutions-69-Test]:solutions/sqrtx/sqrtx_test.go#L23
[Solutions-67-Test]:solutions/add_binary/addbinary_test.go#L17
[Solutions-67-Home]:solutions/add_binary/
[Solutions-67-Golang]:solutions/add_binary/addbinary.go
[Solutions-67]:https://leetcode.com/problems/add-binary/
[Solutions-66-Test]:solutions/plus_one/plusone_test.go#L18
[Solutions-66-Home]:solutions/plus_one/
[Solutions-66-Golang]:solutions/plus_one/plusone.go
[Solutions-66]:https://leetcode.com/problems/plus-one/
[Solutions-65-Test]:solutions/valid_number/validnumber_test.go#L46
[Solutions-65-Home]:solutions/valid_number/
[Solutions-65-Golang]:solutions/valid_number/validnumber.go
[Solutions-65]:https://leetcode.com/problems/valid-number/
[Solutions-64-Test]:solutions/minimum_path_sum/minimumpathsum_test.go#L37
[Solutions-64-Home]:solutions/minimum_path_sum/
[Solutions-64-Golang]:solutions/minimum_path_sum/minimumpathsum.go
[Solutions-64]:https://leetcode.com/problems/minimum-path-sum/
[Solutions-63-Test]:solutions/unique_paths_ii/uniquepathsii_test.go#L22
[Solutions-63-Home]:solutions/unique_paths_ii/
[Solutions-63-Golang]:solutions/unique_paths_ii/uniquepathsii.go
[Solutions-63]:https://leetcode.com/problems/unique-paths-ii/
[Solutions-62-Test]:solutions/unique_paths/uniquepaths_test.go#L24
[Solutions-62-Home]:solutions/unique_paths/
[Solutions-62-Golang]:solutions/unique_paths/uniquepaths.go
[Solutions-62]:https://leetcode.com/problems/unique-paths/
[Solutions-61-Test]:solutions/rotate_list/rotatelist_test.go#L29
[Solutions-61-Home]:solutions/rotate_list/
[Solutions-61-Golang]:solutions/rotate_list/rotatelist.go
[Solutions-61]:https://leetcode.com/problems/rotate-list/
[Solutions-60-Test]:solutions/permutation_sequence/permutationsequence_test.go#L20
[Solutions-60-Home]:solutions/permutation_sequence/
[Solutions-60-Golang]:solutions/permutation_sequence/permutationsequence.go
[Solutions-60]:https://leetcode.com/problems/permutation-sequence/
[Solutions-59-Test]:solutions/spiral_matrix_ii/spiralmatrixii_test.go#L22
[Solutions-59-Home]:solutions/spiral_matrix_ii/
[Solutions-59-Golang]:solutions/spiral_matrix_ii/spiralmatrixii.go
[Solutions-59]:https://leetcode.com/problems/spiral-matrix-ii/
[Solutions-58-Test]:solutions/length_of_last_word/lengthOfLastWord_test.go#L17
[Solutions-58-Home]:solutions/length_of_last_word/
[Solutions-58-Golang]:solutions/length_of_last_word/lengthOfLastWord.go
[Solutions-58]:https://leetcode.com/problems/length-of-last-word/
[Solutions-56-Test]:solutions/merge_intervals/merge_test.go#L59
[Solutions-56-Home]:solutions/merge_intervals/
[Solutions-56-Golang]:solutions/merge_intervals/merge.go
[Solutions-56]:https://leetcode.com/problems/merge-intervals/
[Solutions-55-Test]:solutions/jump_game/canJump_test.go#L18
[Solutions-55-Home]:solutions/jump_game/
[Solutions-55-Golang]:solutions/jump_game/canJump.go
[Solutions-55]:https://leetcode.com/problems/jump-game/
[Solutions-54-Test]:solutions/spiral_matrix/spiralOrder_test.go#L53
[Solutions-54-Home]:solutions/spiral_matrix/
[Solutions-54-Golang]:solutions/spiral_matrix/spiralOrder.go
[Solutions-54]:https://leetcode.com/problems/spiral-matrix/
[Solutions-53-Test]:solutions/maximum_subarray/maxSubArray_test.go#L18
[Solutions-53-Home]:solutions/maximum_subarray/
[Solutions-53-Golang]:solutions/maximum_subarray/maxSubArray.go
[Solutions-53]:https://leetcode.com/problems/maximum-subarray/
[Solutions-50-Test]:solutions/powx_n/myPow_test.go#L26
[Solutions-50-Home]:solutions/powx_n/
[Solutions-50-Golang]:solutions/powx_n/myPow.go
[Solutions-50]:https://leetcode.com/problems/powx-n/
[Solutions-49-Test]:solutions/group_anagrams/groupAnagrams_test.go#L23
[Solutions-49-Home]:solutions/group_anagrams/
[Solutions-49-Golang]:solutions/group_anagrams/groupAnagrams.go
[Solutions-49]:https://leetcode.com/problems/group-anagrams/
[Solutions-48-Test]:solutions/rotate_image/rotate_test.go#L43
[Solutions-48-Home]:solutions/rotate_image/
[Solutions-48-Golang]:solutions/rotate_image/rotate.go
[Solutions-48]:https://leetcode.com/problems/rotate-image/
[Solutions-47-Test]:solutions/permutations_ii/permuteUnique_test.go#L53
[Solutions-47-Home]:solutions/permutations_ii/
[Solutions-47-Golang]:solutions/permutations_ii/permuteUnique.go
[Solutions-47]:https://leetcode.com/problems/permutations-ii/
[Solutions-46-Test]:solutions/permutations/permute_test.go#L47
[Solutions-46-Home]:solutions/permutations/
[Solutions-46-Golang]:solutions/permutations/permute.go
[Solutions-46]:https://leetcode.com/problems/permutations/
[Solutions-45-Test]:solutions/jump_game_ii/jump_test.go#L18
[Solutions-45-Home]:solutions/jump_game_ii/
[Solutions-45-Golang]:solutions/jump_game_ii/jump.go
[Solutions-45]:https://leetcode.com/problems/jump-game-ii/
[Solutions-44-Test]:solutions/wildcard_matching/isMatch_test.go#L21
[Solutions-44-Home]:solutions/wildcard_matching/
[Solutions-44-Golang]:solutions/wildcard_matching/isMatch.go
[Solutions-44]:https://leetcode.com/problems/wildcard-matching/
[Solutions-43-Test]:solutions/multiply_strings/multiply_test.go#L20
[Solutions-43-Home]:solutions/multiply_strings/
[Solutions-43-Golang]:solutions/multiply_strings/multiply.go
[Solutions-43]:https://leetcode.com/problems/multiply-strings/
[Solutions-42-Test]:solutions/trapping_rain_water/trap_test.go#L18
[Solutions-42-Home]:solutions/trapping_rain_water/
[Solutions-42-Golang]:solutions/trapping_rain_water/trap.go
[Solutions-42]:https://leetcode.com/problems/trapping-rain-water/
[Solutions-41-Test]:solutions/first_missing_positive/firstMissingPositive_test.go#L18
[Solutions-41-Home]:solutions/first_missing_positive/
[Solutions-41-Golang]:solutions/first_missing_positive/firstMissingPositive.go
[Solutions-41]:https://leetcode.com/problems/first-missing-positive/
[Solutions-40-Test]:solutions/combination_sum_ii/combinationSum2_test.go#L16
[Solutions-40-Home]:solutions/combination_sum_ii/
[Solutions-40-Golang]:solutions/combination_sum_ii/combinationSum2.go
[Solutions-40]:https://leetcode.com/problems/combination-sum-ii/
[Solutions-39-Test]:solutions/combination_sum/combinationSum_test.go#L16
[Solutions-39-Home]:solutions/combination_sum/
[Solutions-39-Golang]:solutions/combination_sum/combinationSum.go
[Solutions-39]:https://leetcode.com/problems/combination-sum/
[Solutions-38-Test]:solutions/count_and_say/countAndSay_test.go#L18
[Solutions-38-Home]:solutions/count_and_say/
[Solutions-38-Golang]:solutions/count_and_say/countAndSay.go
[Solutions-38]:https://leetcode.com/problems/count-and-say/
[Solutions-37-Test]:solutions/sudoku_solver/solveSudoku_test.go#L61
[Solutions-37-Home]:solutions/sudoku_solver/
[Solutions-37-Golang]:solutions/sudoku_solver/solveSudoku.go
[Solutions-37]:https://leetcode.com/problems/sudoku-solver/
[Solutions-36-Test]:solutions/valid_sudoku/isValidSudoku_test.go#L56
[Solutions-36-Home]:solutions/valid_sudoku/
[Solutions-36-Golang]:solutions/valid_sudoku/isValidSudoku.go
[Solutions-36]:https://leetcode.com/problems/valid-sudoku/
[Solutions-35-Test]:solutions/search_insert_position/searchInsert_test.go#L22
[Solutions-35-Home]:solutions/search_insert_position/
[Solutions-35-Golang]:solutions/search_insert_position/searchInsert.go
[Solutions-35]:https://leetcode.com/problems/search-insert-position/
[Solutions-34-Test]:solutions/search_for_a_range/searchRange_test.go#L20
[Solutions-34-Home]:solutions/search_for_a_range/
[Solutions-34-Golang]:solutions/search_for_a_range/searchRange.go
[Solutions-34]:https://leetcode.com/problems/search-for-a-range/
[Solutions-33-Test]:solutions/search_in_rotated_sorted_array/search_test.go#L20
[Solutions-33-Home]:solutions/search_in_rotated_sorted_array/
[Solutions-33-Golang]:solutions/search_in_rotated_sorted_array/search.go
[Solutions-33]:https://leetcode.com/problems/search-in-rotated-sorted-array/
[Solutions-32-Test]:solutions/longest_valid_parentheses/longestValidParentheses_test.go#L23
[Solutions-32-Home]:solutions/longest_valid_parentheses/
[Solutions-32-Golang]:solutions/longest_valid_parentheses/longestValidParentheses.go
[Solutions-32]:https://leetcode.com/problems/longest-valid-parentheses/
[Solutions-31-Test]:solutions/next_permutation/nextPermutation_test.go#L33
[Solutions-31-Home]:solutions/next_permutation/
[Solutions-31-Golang]:solutions/next_permutation/nextPermutation.go
[Solutions-31]:https://leetcode.com/problems/next-permutation/
[Solutions-30-Test]:solutions/substring_with_concatenation_of_all_words/findSubstring_test.go#L28
[Solutions-30-Home]:solutions/substring_with_concatenation_of_all_words/
[Solutions-30-Golang]:solutions/substring_with_concatenation_of_all_words/findSubstring.go
[Solutions-30]:https://leetcode.com/problems/substring-with-concatenation-of-all-words/
[Solutions-29-Test]:solutions/divide_two_integers/divide_test.go#L24
[Solutions-29-Home]:solutions/divide_two_integers/
[Solutions-29-Golang]:solutions/divide_two_integers/divide.go
[Solutions-29]:https://leetcode.com/problems/divide-two-integers/
[Solutions-28-Test]:solutions/implement_strstr/strStr_test.go#L19
[Solutions-28-Home]:solutions/implement_strstr/
[Solutions-28-Golang]:solutions/implement_strstr/strStr.go
[Solutions-28]:https://leetcode.com/problems/implement-strstr/
[Solutions-27-Test]:solutions/remove_element/removeElement_test.go#L18
[Solutions-27-Home]:solutions/remove_element/
[Solutions-27-Golang]:solutions/remove_element/removeElement.go
[Solutions-27]:https://leetcode.com/problems/remove-element/
[Solutions-26-Test]:solutions/remove_duplicates_from_sorted_array/removeDuplicates_test.go#L18
[Solutions-26-Home]:solutions/remove_duplicates_from_sorted_array/
[Solutions-26-Golang]:solutions/remove_duplicates_from_sorted_array/removeDuplicates.go
[Solutions-26]:https://leetcode.com/problems/remove-duplicates-from-sorted-array/
[Solutions-25-Test]:solutions/reverse_nodes_in_k_group/reverseKGroup_test.go#L65
[Solutions-25-Home]:solutions/reverse_nodes_in_k_group/
[Solutions-25-Golang]:solutions/reverse_nodes_in_k_group/reverseKGroup.go
[Solutions-25]:https://leetcode.com/problems/reverse-nodes-in-k-group/
[Solutions-24-Test]:solutions/swap_nodes_in_pairs/swapPairs_test.go#L65
[Solutions-24-Home]:solutions/swap_nodes_in_pairs/
[Solutions-24-Golang]:solutions/swap_nodes_in_pairs/swapPairs.go
[Solutions-24]:https://leetcode.com/problems/swap-nodes-in-pairs/
[Solutions-23-Test]:solutions/merge_k_sorted_lists/mergeKLists_test.go#L98
[Solutions-23-Home]:solutions/merge_k_sorted_lists/
[Solutions-23-Golang]:solutions/merge_k_sorted_lists/mergeKLists.go
[Solutions-23]:https://leetcode.com/problems/merge-k-sorted-lists/
[Solutions-22-Test]:solutions/generate_parentheses/generateParenthesis_test.go#L19
[Solutions-22-Home]:solutions/generate_parentheses/
[Solutions-22-Golang]:solutions/generate_parentheses/generateParenthesis.go
[Solutions-22]:https://leetcode.com/problems/generate-parentheses/
[Solutions-21-Test]:solutions/merge_two_sorted_lists/mergeTwoLists_test.go#L75
[Solutions-21-Home]:solutions/merge_two_sorted_lists/
[Solutions-21-Golang]:solutions/merge_two_sorted_lists/mergeTwoLists.go
[Solutions-21]:https://leetcode.com/problems/merge-two-sorted-lists/
[Solutions-20-Test]:solutions/valid_parentheses/isValid_test.go#L25
[Solutions-20-Home]:solutions/valid_parentheses/
[Solutions-20-Golang]:solutions/valid_parentheses/isValid.go
[Solutions-20]:https://leetcode.com/problems/valid-parentheses/
[Solutions-19-Test]:solutions/remove_nth_node_from_end_of_list/removeNthFromEnd_test.go#L72
[Solutions-19-Home]:solutions/remove_nth_node_from_end_of_list/
[Solutions-19-Golang]:solutions/remove_nth_node_from_end_of_list/removeNthFromEnd.go
[Solutions-19]:https://leetcode.com/problems/remove-nth-node-from-end-of-list/
[Solutions-18-Test]:solutions/4sum/fourSum_test.go#L28
[Solutions-18-Home]:solutions/4sum/
[Solutions-18-Golang]:solutions/4sum/fourSum.go
[Solutions-18]:https://leetcode.com/problems/4sum/
[Solutions-17-Test]:solutions/letter_combinations_of_a_phone_number/letterCombinations_test.go#L27
[Solutions-17-Home]:solutions/letter_combinations_of_a_phone_number/
[Solutions-17-Golang]:solutions/letter_combinations_of_a_phone_number/letterCombinations.go
[Solutions-17]:https://leetcode.com/problems/letter-combinations-of-a-phone-number/
[Solutions-16-Test]:solutions/3sum_closest/threeSumClosest_test.go#L20
[Solutions-16-Home]:solutions/3sum_closest/
[Solutions-16-Golang]:solutions/3sum_closest/threeSumClosest.go
[Solutions-16]:https://leetcode.com/problems/3sum-closest/
[Solutions-15-Test]:solutions/3sum/threeSum_test.go#L20
[Solutions-15-Home]:solutions/3sum/
[Solutions-15-Golang]:solutions/3sum/threeSum.go
[Solutions-15]:https://leetcode.com/problems/3sum/
[Solutions-14-Test]:solutions/longest_common_prefix/longestCommonPrefix_test.go#L19
[Solutions-14-Home]:solutions/longest_common_prefix/
[Solutions-14-Golang]:solutions/longest_common_prefix/longestCommonPrefix.go
[Solutions-14]:https://leetcode.com/problems/longest-common-prefix/
[Solutions-13-Test]:solutions/roman_to_integer/romanToInt_test.go#L23
[Solutions-13-Home]:solutions/roman_to_integer/
[Solutions-13-Golang]:solutions/roman_to_integer/romanToInt.go
[Solutions-13]:https://leetcode.com/problems/roman-to-integer/
[Solutions-12-Test]:solutions/integer_to_roman/intToRoman_test.go#L22
[Solutions-12-Home]:solutions/integer_to_roman/
[Solutions-12-Golang]:solutions/integer_to_roman/intToRoman.go
[Solutions-12]:https://leetcode.com/problems/integer-to-roman/
[Solutions-11-Test]:solutions/container_with_most_water/maxArea_test.go#L21
[Solutions-11-Home]:solutions/container_with_most_water/
[Solutions-11-Golang]:solutions/container_with_most_water/maxArea.go
[Solutions-11]:https://leetcode.com/problems/container-with-most-water/
[Solutions-10-Test]:solutions/regular_expression_matching/isMatch_test.go#L40
[Solutions-10-Home]:solutions/regular_expression_matching/
[Solutions-10-Golang]:solutions/regular_expression_matching/isMatch.go
[Solutions-10]:https://leetcode.com/problems/regular-expression-matching/
[Solutions-9-Test]:solutions/palindrome_number/isPalindrome_test.go#L20
[Solutions-9-Home]:solutions/palindrome_number/
[Solutions-9-Golang]:solutions/palindrome_number/isPalindrome.go
[Solutions-9]:https://leetcode.com/problems/palindrome-number/
[Solutions-8-Test]:solutions/string_to_integer_atoi/myAtoi_test.go#L34
[Solutions-8-Home]:solutions/string_to_integer_atoi/
[Solutions-8-Golang]:solutions/string_to_integer_atoi/myAtoi.go
[Solutions-8]:https://leetcode.com/problems/string-to-integer-atoi/
[Solutions-7-Test]:solutions/reverse_integer/reverse_test.go#L32
[Solutions-7-Home]:solutions/reverse_integer/
[Solutions-7-Golang]:solutions/reverse_integer/reverse.go
[Solutions-7]:https://leetcode.com/problems/reverse-integer/
[Solutions-6-Test]:solutions/zigzag_conversion/convert_test.go#L18
[Solutions-6-Home]:solutions/zigzag_conversion/
[Solutions-6-Golang]:solutions/zigzag_conversion/convert.go
[Solutions-6]:https://leetcode.com/problems/zigzag-conversion/
[Solutions-5-Test]:solutions/longest_palindromic_substring/longestPalindrome_test.go#L18
[Solutions-5-Home]:solutions/longest_palindromic_substring/
[Solutions-5-Golang]:solutions/longest_palindromic_substring/longestPalindrome.go
[Solutions-5]:https://leetcode.com/problems/longest-palindromic-substring/
[Solutions-4-Test]:solutions/median_of_two_sorted_arrays/findMedianSortedArrays_test.go#L71
[Solutions-4-Home]:solutions/median_of_two_sorted_arrays/
[Solutions-4-Golang]:solutions/median_of_two_sorted_arrays/findMedianSortedArrays.go
[Solutions-4]:https://leetcode.com/problems/median-of-two-sorted-arrays/
[Solutions-3-Test]:solutions/longest_substring_without_repeating_characters/lengthOfLongestSubstring_test.go#L16
[Solutions-3-Home]:solutions/longest_substring_without_repeating_characters/
[Solutions-3-Golang]:solutions/longest_substring_without_repeating_characters/lengthOfLongestSubstring.go
[Solutions-3]:https://leetcode.com/problems/longest-substring-without-repeating-characters/
[Solutions-2-Test]:solutions/add_two_numbers/addTwoNumbers_test.go#L118
[Solutions-2-Home]:solutions/add_two_numbers/
[Solutions-2-Golang]:solutions/add_two_numbers/addTwoNumbers.go
[Solutions-2]:https://leetcode.com/problems/add-two-numbers/
[Solutions-1-Test]:solutions/two_sum/twoSum_test.go#L16
[Solutions-1-Home]:solutions/two_sum/
[Solutions-1-Golang]:solutions/two_sum/twoSum.go
[Solutions-1]:https://leetcode.com/problems/two-sum/


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FWindomZ%2Fleetcode.go.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FWindomZ%2Fleetcode.go?ref=badge_large)
