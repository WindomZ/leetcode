# leetcode.go

> My solutions(Golang) of problems in https://leetcode.com/

[![Build Status](https://travis-ci.org/WindomZ/leetcode.go.svg?branch=master)](https://travis-ci.org/WindomZ/leetcode.go)
[![Coverage Status](https://coveralls.io/repos/github/WindomZ/leetcode.go/badge.svg?branch=master)](https://coveralls.io/github/WindomZ/leetcode.go?branch=master)
[![Go Report Card](https://goreportcard.com/badge/github.com/WindomZ/leetcode.go)](https://goreportcard.com/report/github.com/WindomZ/leetcode.go)

- [Pursue](#pursue)
- [Solutions](#solutions)
- [Testing](#testing)
- [Contributing](#contributing)
  - [Challenge](#challenge)
  - [Discuss](#discuss)
  - [Support](#support)

## Pursue

- **Faster** and **better** solutions.
- **100%** coverage tests.
- **Benchmark** tests.

## Solutions

| # | Problem | Solution | Difficulty | Single Repetition Duration | LeetCode Run Time |
| ---: | :----- | :--------: | :----------: | ----------: | ----------: |
|49|[Group Anagrams][Solutions-49]|[WindomZ][Solutions-49-Go]|Medium|[313 ns/op/3 test cases][Solutions-49-Test]|582 ms|
|48|[Rotate Image][Solutions-48]|[WindomZ][Solutions-48-Go]|Medium|[12.1 ns/op/3 test cases][Solutions-48-Test]|3 ms|
|47|[Permutations II][Solutions-47]|[WindomZ][Solutions-47-Go]|Medium|[198 ns/op/3 test cases][Solutions-47-Test]|19 ms|
|46|[Permutations][Solutions-46]|[WindomZ][Solutions-46-Go]|Medium|[484 ns/op/3 test cases][Solutions-46-Test]|9 ms|
|45|[Jump Game II][Solutions-45]|[WindomZ][Solutions-45-Go]|Hard|[5.14 ns/op/6 test cases][Solutions-45-Test]|19 ms|
|44|[Wildcard Matching][Solutions-44]|[WindomZ][Solutions-44-Go]|Hard|[10.9 ns/op/9 test cases][Solutions-44-Test]|15 ms|
|43|[Multiply Strings][Solutions-43]|[WindomZ][Solutions-43-Go]|Medium|[53.4 ns/op/6 test cases][Solutions-43-Test]|3 ms|
|42|[Trapping Rain Water][Solutions-42]|[WindomZ][Solutions-42-Go]|Hard|[14.4 ns/op/6 test cases][Solutions-42-Test]|6 ms|
|41|[First Missing Positive][Solutions-41]|[WindomZ][Solutions-41-Go]|Hard|[12.3 ns/op/6 test cases][Solutions-41-Test]|3 ms|
|40|[Combination Sum II][Solutions-40]|[WindomZ][Solutions-40-Go]|Medium|[203 ns/op/3 test cases][Solutions-40-Test]|3 ms|
|39|[Combination Sum][Solutions-39]|[WindomZ][Solutions-39-Go]|Medium|[165 ns/op/3 test cases][Solutions-39-Test]|6 ms|
|38|[Count and Say][Solutions-38]|[WindomZ][Solutions-38-Go]|Easy|[66.8 ns/op/4 test cases][Solutions-38-Test]|0 ms|
|37|[Sudoku Solver][Solutions-37]|[WindomZ][Solutions-37-Go]|Hard|[35497 ns/op/2 test cases][Solutions-37-Test]|0 ms|
|36|[Valid Sudoku][Solutions-36]|[WindomZ][Solutions-36-Go]|Medium|[135 ns/op/3 test cases][Solutions-36-Test]|6 ms|
|35|[Search Insert Position][Solutions-35]|[WindomZ][Solutions-35-Go]|Easy|[7.76 ns/op/8 test cases][Solutions-35-Test]|6 ms|
|34|[Search for a Range][Solutions-34]|[WindomZ][Solutions-34-Go]|Medium|[53.5 ns/op/8 test cases][Solutions-34-Test]|19 ms|
|33|[Search in Rotated Sorted Array][Solutions-33]|[WindomZ][Solutions-33-Go]|Medium|[30.0 ns/op/8 test cases][Solutions-33-Test]|3 ms|
|32|[Longest Valid Parentheses][Solutions-32]|[WindomZ][Solutions-32-Go]|Hard|[221 ns/op/8 test cases][Solutions-32-Test]|3 ms|
|31|[Next Permutation][Solutions-31]|[WindomZ][Solutions-31-Go]|Medium|[11.4 ns/op/4 test cases][Solutions-31-Test]|6 ms|
|30|[Substring with Concatenation of All Words][Solutions-30]|[WindomZ][Solutions-30-Go]|Hard|[1358 ns/op/3 test cases][Solutions-30-Test]|13 ms|
|29|[Divide Two Integers][Solutions-29]|[WindomZ][Solutions-29-Go]|Medium|[249 ns/op/12 test cases][Solutions-29-Test]|6 ms|
|28|[Implement strStr()][Solutions-28]|[WindomZ][Solutions-28-Go]|Easy|[34.0 ns/op/7 test cases][Solutions-28-Test]|0 ms|
|27|[Remove Element][Solutions-27]|[WindomZ][Solutions-27-Go]|Easy|[36.9 ns/op/6 test cases][Solutions-27-Test]|3 ms|
|26|[Remove Duplicates from Sorted Array][Solutions-26]|[WindomZ][Solutions-26-Go]|Easy|[38.3 ns/op/6 test cases][Solutions-26-Test]|102 ms|
|25|[Reverse Nodes in k-Group][Solutions-25]|[WindomZ][Solutions-25-Go]|Hard|[227 ns/op/3 test cases][Solutions-25-Test]|9 ms|
|24|[Swap Nodes in Pairs][Solutions-24]|[WindomZ][Solutions-24-Go]|Medium|[242 ns/op/4 test cases][Solutions-24-Test]|0 ms|
|23|[Merge k Sorted Lists][Solutions-23]|[WindomZ][Solutions-23-Go]|Hard|[354 ns/op/4 test cases][Solutions-23-Test]|19 ms|
|22|[Generate Parentheses][Solutions-22]|[WindomZ][Solutions-22-Go]|Medium|[1207 ns/op/4 test cases][Solutions-22-Test]|13 ms|
|21|[Merge Two Sorted Lists][Solutions-21]|[WindomZ][Solutions-21-Go]|Easy|[270 ns/op/3 test cases][Solutions-21-Test]|3 ms|
|20|[Valid Parentheses][Solutions-20]|[WindomZ][Solutions-20-Go]|Easy|[127 ns/op/6 test cases][Solutions-20-Test]|0 ms|
|19|[Remove Nth Node From End of List][Solutions-19]|[WindomZ][Solutions-19-Go]|Medium|[0.00 ns/op/6 test cases][Solutions-19-Test]|3 ms|
|18|[4Sum][Solutions-18]|[WindomZ][Solutions-18-Go]|Medium|[796 ns/op/3 test cases][Solutions-18-Test]|16 ms|
|17|[Letter Combinations of a Phone Number][Solutions-17]|[WindomZ][Solutions-17-Go]|Medium|[1466 ns/op/4 test cases][Solutions-17-Test]|0 ms|
|16|[3Sum Closest][Solutions-16]|[WindomZ][Solutions-16-Go]|Medium|[1426 ns/op/8 test cases][Solutions-16-Test]|9 ms|
|15|[3Sum][Solutions-15]|[WindomZ][Solutions-15-Go]|Medium|[614 ns/op/4 test cases][Solutions-15-Test]|1525 ms|
|14|[Longest Common Prefix][Solutions-14]|[WindomZ][Solutions-14-Go]|Easy|[45.8 ns/op/8 test cases][Solutions-14-Test]|3 ms|
|13|[Roman to Integer][Solutions-13]|[WindomZ][Solutions-13-Go]|Easy|[101 ns/op/8 test cases][Solutions-13-Test]|19 ms|
|12|[Integer to Roman][Solutions-12]|[WindomZ][Solutions-12-Go]|Medium|[96.6 ns/op/8 test cases][Solutions-12-Test]|22 ms|
|11|[Container With Most Water][Solutions-11]|[WindomZ][Solutions-11-Go]|Medium|[38.0 ns/op/5 test cases][Solutions-11-Test]|25 ms|
|10|[Regular Expression Matching][Solutions-10]|[WindomZ][Solutions-10-Go]|Hard|[630 ns/op/6 test cases][Solutions-10-Test]|3 ms|
|9|[Palindrome Number][Solutions-9]|[WindomZ][Solutions-9-Go]|Easy|[27.3 ns/op/7 test cases][Solutions-9-Test]|55 ms|
|8|[String to Integer (atoi)][Solutions-8]|[WindomZ][Solutions-8-Go]|Medium|[33.4 ns/op/5 test cases][Solutions-8-Test]|3 ms|
|7|[Reverse Integer][Solutions-7]|[WindomZ][Solutions-7-Go]|Easy|[39.3 ns/op/5 test cases][Solutions-7-Test]|3 ms|
|6|[ZigZag Conversion][Solutions-6]|[WindomZ][Solutions-6-Go]|Medium|[205 ns/op/5 test cases][Solutions-6-Test]|9 ms|
|5|[Longest Palindromic Substring][Solutions-5]|[WindomZ][Solutions-5-Go]|Medium|[151 ns/op/6 test cases][Solutions-5-Test]|9 ms|
|4|[Median of Two Sorted Arrays][Solutions-4]|[WindomZ][Solutions-4-Go]|Hard|[74.3 ns/op/14 test cases][Solutions-4-Test]|32 ms|
|3|[Longest Substring Without Repeating Characters][Solutions-3]|[WindomZ][Solutions-3-Go]|Medium|[103 ns/op/3 test cases][Solutions-3-Test]|6 ms|
|2|[Add Two Numbers][Solutions-2]|[WindomZ][Solutions-2-Go]|Medium|[79.4 ns/op/1 test cases][Solutions-2-Test]|29 ms|
|1|[Two Sum][Solutions-1]|[WindomZ][Solutions-1-Go]|Easy|[305 ns/op/3 test cases][Solutions-1-Test]|6 ms|

> **NOTE**: 'Single Repetition Duration' and 'LeetCode Run Time' are for _reference_ only.

> All tests should be run on a machine, and through multiple benchmark tests.

## Testing

```bash
git clone https://github.com/WindomZ/leetcode.go.git "$YOUR_PROJECT_PATH"
cd "$YOUR_PROJECT_PATH"
go test -v -run=. ./solutions/...
go test -bench=. -benchmem ./solutions/...
```

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

[Solutions-49-Test]:solutions/group_anagrams/groupAnagrams_test.go#L23
[Solutions-49-Go]:solutions/group_anagrams/groupAnagrams.go
[Solutions-49]:https://leetcode.com/group-anagrams/
[Solutions-48-Test]:solutions/rotate_image/rotate_test.go#L43
[Solutions-48-Go]:solutions/rotate_image/rotate.go
[Solutions-48]:https://leetcode.com/rotate-image/
[Solutions-47-Test]:solutions/permutations_ii/permuteUnique_test.go#L53
[Solutions-47-Go]:solutions/permutations_ii/permuteUnique.go
[Solutions-47]:https://leetcode.com/permutations-ii/
[Solutions-46-Test]:solutions/permutations/permute_test.go#L47
[Solutions-46-Go]:solutions/permutations/permute.go
[Solutions-46]:https://leetcode.com/permutations/
[Solutions-45-Test]:solutions/jump_game_ii/jump_test.go#L18
[Solutions-45-Go]:solutions/jump_game_ii/jump.go
[Solutions-45]:https://leetcode.com/jump-game-ii/
[Solutions-44-Test]:solutions/wildcard_matching/isMatch_test.go#L21
[Solutions-44-Go]:solutions/wildcard_matching/isMatch.go
[Solutions-44]:https://leetcode.com/wildcard-matching/
[Solutions-43-Test]:solutions/multiply_strings/multiply_test.go#L20
[Solutions-43-Go]:solutions/multiply_strings/multiply.go
[Solutions-43]:https://leetcode.com/multiply-strings/
[Solutions-42-Test]:solutions/trapping_rain_water/trap_test.go#L18
[Solutions-42-Go]:solutions/trapping_rain_water/trap.go
[Solutions-42]:https://leetcode.com/trapping-rain-water/
[Solutions-41-Test]:solutions/first_missing_positive/firstMissingPositive_test.go#L18
[Solutions-41-Go]:solutions/first_missing_positive/firstMissingPositive.go
[Solutions-41]:https://leetcode.com/first-missing-positive/
[Solutions-40-Test]:solutions/combination_sum_ii/combinationSum2_test.go#L16
[Solutions-40-Go]:solutions/combination_sum_ii/combinationSum2.go
[Solutions-40]:https://leetcode.com/combination-sum-ii/
[Solutions-39-Test]:solutions/combination_sum/combinationSum_test.go#L16
[Solutions-39-Go]:solutions/combination_sum/combinationSum.go
[Solutions-39]:https://leetcode.com/combination-sum/
[Solutions-38-Test]:solutions/count_and_say/countAndSay_test.go#L18
[Solutions-38-Go]:solutions/count_and_say/countAndSay.go
[Solutions-38]:https://leetcode.com/count-and-say/
[Solutions-37-Test]:solutions/sudoku_solver/solveSudoku_test.go#L61
[Solutions-37-Go]:solutions/sudoku_solver/solveSudoku.go
[Solutions-37]:https://leetcode.com/sudoku-solver/
[Solutions-36-Test]:solutions/valid_sudoku/isValidSudoku_test.go#L56
[Solutions-36-Go]:solutions/valid_sudoku/isValidSudoku.go
[Solutions-36]:https://leetcode.com/valid-sudoku/
[Solutions-35-Test]:solutions/search_insert_position/searchInsert_test.go#L22
[Solutions-35-Go]:solutions/search_insert_position/searchInsert.go
[Solutions-35]:https://leetcode.com/search-insert-position/
[Solutions-34-Test]:solutions/search_for_a_range/searchRange_test.go#L20
[Solutions-34-Go]:solutions/search_for_a_range/searchRange.go
[Solutions-34]:https://leetcode.com/search-for-a-range/
[Solutions-33-Test]:solutions/search_in_rotated_sorted_array/search_test.go#L20
[Solutions-33-Go]:solutions/search_in_rotated_sorted_array/search.go
[Solutions-33]:https://leetcode.com/search-in-rotated-sorted-array/
[Solutions-32-Test]:solutions/longest_valid_parentheses/longestValidParentheses_test.go#L23
[Solutions-32-Go]:solutions/longest_valid_parentheses/longestValidParentheses.go
[Solutions-32]:https://leetcode.com/longest-valid-parentheses/
[Solutions-31-Test]:solutions/next_permutation/nextPermutation_test.go#L33
[Solutions-31-Go]:solutions/next_permutation/nextPermutation.go
[Solutions-31]:https://leetcode.com/next-permutation/
[Solutions-30-Test]:solutions/substring_with_concatenation_of_all_words/findSubstring_test.go#L28
[Solutions-30-Go]:solutions/substring_with_concatenation_of_all_words/findSubstring.go
[Solutions-30]:https://leetcode.com/substring-with-concatenation-of-all-words/
[Solutions-29-Test]:solutions/divide_two_integers/divide_test.go#L24
[Solutions-29-Go]:solutions/divide_two_integers/divide.go
[Solutions-29]:https://leetcode.com/divide-two-integers/
[Solutions-28-Test]:solutions/implement_strstr/strStr_test.go#L19
[Solutions-28-Go]:solutions/implement_strstr/strStr.go
[Solutions-28]:https://leetcode.com/implement-strstr/
[Solutions-27-Test]:solutions/remove_element/removeElement_test.go#L18
[Solutions-27-Go]:solutions/remove_element/removeElement.go
[Solutions-27]:https://leetcode.com/problems/remove-element/
[Solutions-26-Test]:solutions/remove_duplicates_from_sorted_array/removeDuplicates_test.go#L18
[Solutions-26-Go]:solutions/remove_duplicates_from_sorted_array/removeDuplicates.go
[Solutions-26]:https://leetcode.com/problems/remove-duplicates-from-sorted-array/
[Solutions-25-Test]:solutions/reverse_nodes_in_k_group/reverseKGroup_test.go#L65
[Solutions-25-Go]:solutions/reverse_nodes_in_k_group/reverseKGroup.go
[Solutions-25]:https://leetcode.com/problems/reverse-nodes-in-k-group/
[Solutions-24-Test]:solutions/swap_nodes_in_pairs/swapPairs_test.go#L65
[Solutions-24-Go]:solutions/swap_nodes_in_pairs/swapPairs.go
[Solutions-24]:https://leetcode.com/problems/swap-nodes-in-pairs/
[Solutions-23-Test]:solutions/merge_k_sorted_lists/mergeKLists_test.go#L98
[Solutions-23-Go]:solutions/merge_k_sorted_lists/mergeKLists.go
[Solutions-23]:https://leetcode.com/problems/merge-k-sorted-lists/
[Solutions-22-Test]:solutions/generate_parentheses/generateParenthesis_test.go#L19
[Solutions-22-Go]:solutions/generate_parentheses/generateParenthesis.go
[Solutions-22]:https://leetcode.com/problems/generate-parentheses/
[Solutions-21-Test]:solutions/merge_two_sorted_lists/mergeTwoLists_test.go#L75
[Solutions-21-Go]:solutions/merge_two_sorted_lists/mergeTwoLists.go
[Solutions-21]:https://leetcode.com/problems/merge-two-sorted-lists/
[Solutions-20-Test]:solutions/valid_parentheses/isValid_test.go#L25
[Solutions-20-Go]:solutions/valid_parentheses/isValid.go
[Solutions-20]:https://leetcode.com/problems/valid-parentheses/
[Solutions-19-Test]:solutions/remove_nth_node_from_end_of_list/removeNthFromEnd_test.go#L72
[Solutions-19-Go]:solutions/remove_nth_node_from_end_of_list/removeNthFromEnd.go
[Solutions-19]:https://leetcode.com/problems/remove-nth-node-from-end-of-list/
[Solutions-18-Test]:solutions/4sum/fourSum_test.go#L28
[Solutions-18-Go]:solutions/4sum/fourSum.go
[Solutions-18]:https://leetcode.com/problems/4sum/
[Solutions-17-Test]:solutions/letter_combinations_of_a_phone_number/letterCombinations_test.go#L27
[Solutions-17-Go]:solutions/letter_combinations_of_a_phone_number/letterCombinations.go
[Solutions-17]:https://leetcode.com/problems/letter-combinations-of-a-phone-number/
[Solutions-16-Test]:solutions/3sum_closest/threeSumClosest_test.go#L20
[Solutions-16-Go]:solutions/3sum_closest/threeSumClosest.go
[Solutions-16]:https://leetcode.com/problems/3sum-closest/
[Solutions-15-Test]:solutions/3sum/threeSum_test.go#L20
[Solutions-15-Go]:solutions/3sum/threeSum.go
[Solutions-15]:https://leetcode.com/problems/3sum/
[Solutions-14-Test]:solutions/longest_common_prefix/longestCommonPrefix_test.go#L19
[Solutions-14-Go]:solutions/longest_common_prefix/longestCommonPrefix.go
[Solutions-14]:https://leetcode.com/problems/longest-common-prefix/
[Solutions-13-Test]:solutions/roman_to_integer/romanToInt_test.go#L23
[Solutions-13-Go]:solutions/roman_to_integer/romanToInt.go
[Solutions-13]:https://leetcode.com/problems/roman-to-integer/
[Solutions-12-Test]:solutions/integer_to_roman/intToRoman_test.go#L22
[Solutions-12-Go]:solutions/integer_to_roman/intToRoman.go
[Solutions-12]:https://leetcode.com/problems/integer-to-roman/
[Solutions-11-Test]:solutions/container_with_most_water/maxArea_test.go#L21
[Solutions-11-Go]:solutions/container_with_most_water/maxArea.go
[Solutions-11]:https://leetcode.com/problems/container-with-most-water/
[Solutions-10-Test]:solutions/regular_expression_matching/isMatch_test.go#L40
[Solutions-10-Go]:solutions/regular_expression_matching/isMatch.go
[Solutions-10]:https://leetcode.com/problems/regular-expression-matching/
[Solutions-9-Test]:solutions/palindrome_number/isPalindrome_test.go#L20
[Solutions-9-Go]:solutions/palindrome_number/isPalindrome.go
[Solutions-9]:https://leetcode.com/problems/palindrome-number/
[Solutions-8-Test]:solutions/string_to_integer_atoi/myAtoi_test.go#L34
[Solutions-8-Go]:solutions/string_to_integer_atoi/myAtoi.go
[Solutions-8]:https://leetcode.com/problems/string-to-integer-atoi/
[Solutions-7-Test]:solutions/reverse_integer/reverse_test.go#L32
[Solutions-7-Go]:solutions/reverse_integer/reverse.go
[Solutions-7]:https://leetcode.com/problems/reverse-integer/
[Solutions-6-Test]:solutions/zigzag_conversion/convert_test.go#L18
[Solutions-6-Go]:solutions/zigzag_conversion/convert.go
[Solutions-6]:https://leetcode.com/problems/zigzag-conversion/
[Solutions-5-Test]:solutions/longest_palindromic_substring/longestPalindrome_test.go#L18
[Solutions-5-Go]:solutions/longest_palindromic_substring/longestPalindrome.go
[Solutions-5]:https://leetcode.com/problems/longest-palindromic-substring/
[Solutions-4-Test]:solutions/median_of_two_sorted_arrays/findMedianSortedArrays_test.go#L71
[Solutions-4-Go]:solutions/median_of_two_sorted_arrays/findMedianSortedArrays.go
[Solutions-4]:https://leetcode.com/problems/median-of-two-sorted-arrays/
[Solutions-3-Test]:solutions/longest_substring_without_repeating_characters/lengthOfLongestSubstring_test.go#L16
[Solutions-3-Go]:solutions/longest_substring_without_repeating_characters/lengthOfLongestSubstring.go
[Solutions-3]:https://leetcode.com/problems/longest-substring-without-repeating-characters/
[Solutions-2-Test]:solutions/add_two_numbers/addTwoNumbers_test.go#L118
[Solutions-2-Go]:solutions/add_two_numbers/addTwoNumbers.go
[Solutions-2]:https://leetcode.com/problems/add-two-numbers/
[Solutions-1-Test]:solutions/two_sum/twoSum_test.go#L16
[Solutions-1-Go]:solutions/two_sum/twoSum.go
[Solutions-1]:https://leetcode.com/problems/two-sum/
