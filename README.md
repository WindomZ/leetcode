# leetcode.go

> My solutions(Golang) of problems in https://leetcode.com/

[![Build Status](https://travis-ci.org/WindomZ/leetcode.go.svg?branch=master)](https://travis-ci.org/WindomZ/leetcode.go)
[![Coverage Status](https://coveralls.io/repos/github/WindomZ/leetcode.go/badge.svg?branch=master)](https://coveralls.io/github/WindomZ/leetcode.go?branch=master)
[![Go Report Card](https://goreportcard.com/badge/github.com/WindomZ/leetcode.go)](https://goreportcard.com/report/github.com/WindomZ/leetcode.go)

- [Pursue](#pursue)
- [Algorithms](#algorithms)
- [Testing](#testing)
- [Contributing](#contributing)
  - [Challenge](#challenge)
  - [Discuss](#discuss)
  - [Support](#support)

## Pursue

- **Faster** and **better** solutions.
- **100%** coverage tests.
- **Benchmark** tests.

## Algorithms

| # | Problem | Solution | Difficulty | Single Repetition Duration | LeetCode Run Time |
| ---: | :----- | :--------: | :----------: | ----------: | ----------: |
|31|[Next Permutation][Algorithms-31]|[WindomZ][Algorithms-31-Go]|Medium|[11.4 ns/op/4 test cases][Algorithms-31-Test]|6 ms|
|30|[Substring with Concatenation of All Words][Algorithms-30]|[WindomZ][Algorithms-30-Go]|Hard|[1358 ns/op/3 test cases][Algorithms-30-Test]|13 ms|
|29|[Divide Two Integers][Algorithms-29]|[WindomZ][Algorithms-29-Go]|Medium|[249 ns/op/12 test cases][Algorithms-29-Test]|6 ms|
|28|[Implement strStr()][Algorithms-28]|[WindomZ][Algorithms-28-Go]|Easy|[34.0 ns/op/7 test cases][Algorithms-28-Test]|0 ms|
|27|[Remove Element][Algorithms-27]|[WindomZ][Algorithms-27-Go]|Easy|[36.9 ns/op/6 test cases][Algorithms-27-Test]|3 ms|
|26|[Remove Duplicates from Sorted Array][Algorithms-26]|[WindomZ][Algorithms-26-Go]|Easy|[38.3 ns/op/6 test cases][Algorithms-26-Test]|102 ms|
|25|[Reverse Nodes in k-Group][Algorithms-25]|[WindomZ][Algorithms-25-Go]|Hard|[227 ns/op/3 test cases][Algorithms-25-Test]|9 ms|
|24|[Swap Nodes in Pairs][Algorithms-24]|[WindomZ][Algorithms-24-Go]|Medium|[242 ns/op/4 test cases][Algorithms-24-Test]|0 ms|
|23|[Merge k Sorted Lists][Algorithms-23]|[WindomZ][Algorithms-23-Go]|Hard|[354 ns/op/4 test cases][Algorithms-23-Test]|19 ms|
|22|[Generate Parentheses][Algorithms-22]|[WindomZ][Algorithms-22-Go]|Medium|[1207 ns/op/4 test cases][Algorithms-22-Test]|13 ms|
|21|[Merge Two Sorted Lists][Algorithms-21]|[WindomZ][Algorithms-21-Go]|Easy|[270 ns/op/3 test cases][Algorithms-21-Test]|3 ms|
|20|[Valid Parentheses][Algorithms-20]|[WindomZ][Algorithms-20-Go]|Easy|[127 ns/op/6 test cases][Algorithms-20-Test]|0 ms|
|19|[Remove Nth Node From End of List][Algorithms-19]|[WindomZ][Algorithms-19-Go]|Medium|[0.00 ns/op/6 test cases][Algorithms-19-Test]|3 ms|
|18|[4Sum][Algorithms-18]|[WindomZ][Algorithms-18-Go]|Medium|[796 ns/op/3 test cases][Algorithms-18-Test]|16 ms|
|17|[Letter Combinations of a Phone Number][Algorithms-17]|[WindomZ][Algorithms-17-Go]|Medium|[1466 ns/op/4 test cases][Algorithms-17-Test]|0 ms|
|16|[3Sum Closest][Algorithms-16]|[WindomZ][Algorithms-16-Go]|Medium|[1426 ns/op/8 test cases][Algorithms-16-Test]|9 ms|
|15|[3Sum][Algorithms-15]|[WindomZ][Algorithms-15-Go]|Medium|[614 ns/op/4 test cases][Algorithms-15-Test]|1525 ms|
|14|[Longest Common Prefix][Algorithms-14]|[WindomZ][Algorithms-14-Go]|Easy|[45.8 ns/op/8 test cases][Algorithms-14-Test]|3 ms|
|13|[Roman to Integer][Algorithms-13]|[WindomZ][Algorithms-13-Go]|Easy|[101 ns/op/8 test cases][Algorithms-13-Test]|19 ms|
|12|[Integer to Roman][Algorithms-12]|[WindomZ][Algorithms-12-Go]|Medium|[96.6 ns/op/8 test cases][Algorithms-12-Test]|22 ms|
|11|[Container With Most Water][Algorithms-11]|[WindomZ][Algorithms-11-Go]|Medium|[38.0 ns/op/5 test cases][Algorithms-11-Test]|25 ms|
|10|[Regular Expression Matching][Algorithms-10]|[WindomZ][Algorithms-10-Go]|Hard|[630 ns/op/6 test cases][Algorithms-10-Test]|3 ms|
|9|[Palindrome Number][Algorithms-9]|[WindomZ][Algorithms-9-Go]|Easy|[27.3 ns/op/7 test cases][Algorithms-9-Test]|55 ms|
|8|[String to Integer (atoi)][Algorithms-8]|[WindomZ][Algorithms-8-Go]|Medium|[33.4 ns/op/5 test cases][Algorithms-8-Test]|3 ms|
|7|[Reverse Integer][Algorithms-7]|[WindomZ][Algorithms-7-Go]|Easy|[39.3 ns/op/5 test cases][Algorithms-7-Test]|3 ms|
|6|[ZigZag Conversion][Algorithms-6]|[WindomZ][Algorithms-6-Go]|Medium|[205 ns/op/5 test cases][Algorithms-6-Test]|9 ms|
|5|[Longest Palindromic Substring][Algorithms-5]|[WindomZ][Algorithms-5-Go]|Medium|[151 ns/op/6 test cases][Algorithms-5-Test]|9 ms|
|4|[Median of Two Sorted Arrays][Algorithms-4]|[WindomZ][Algorithms-4-Go]|Hard|[74.3 ns/op/14 test cases][Algorithms-4-Test]|32 ms|
|3|[Longest Substring Without Repeating Characters][Algorithms-3]|[WindomZ][Algorithms-3-Go]|Medium|[103 ns/op/3 test cases][Algorithms-3-Test]|6 ms|
|2|[Add Two Numbers][Algorithms-2]|[WindomZ][Algorithms-2-Go]|Medium|[79.4 ns/op/1 test cases][Algorithms-2-Test]|29 ms|
|1|[Two Sum][Algorithms-1]|[WindomZ][Algorithms-1-Go]|Easy|[305 ns/op/3 test cases][Algorithms-1-Test]|6 ms|

> NOTE: 'Single Repetition Duration' and 'LeetCode Run Time' are for _reference_ only.

> All tests should be run on a machine, and through multiple benchmark tests.

## Testing

```bash
git clone https://github.com/WindomZ/leetcode.go "$YOUR_PROJECT_PATH"
cd "$YOUR_PROJECT_PATH"
go test -v --run=".*" ./algorithms/...
go test -test.bench=".*" ./algorithms/...
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
If you like it then you can put a :star: on it.

[Algorithms-31-Test]:algorithms/next_permutation/nextPermutation_test.go#L33
[Algorithms-31-Go]:algorithms/next_permutation/nextPermutation.go
[Algorithms-31]:https://leetcode.com/next-permutation/
[Algorithms-30-Test]:algorithms/substring_with_concatenation_of_all_words/findSubstring_test.go#L28
[Algorithms-30-Go]:algorithms/substring_with_concatenation_of_all_words/findSubstring.go
[Algorithms-30]:https://leetcode.com/substring-with-concatenation-of-all-words/
[Algorithms-29-Test]:algorithms/divide_two_integers/divide_test.go#L24
[Algorithms-29-Go]:algorithms/divide_two_integers/divide.go
[Algorithms-29]:https://leetcode.com/divide-two-integers/
[Algorithms-28-Test]:algorithms/implement_strstr/strStr_test.go#L19
[Algorithms-28-Go]:algorithms/implement_strstr/strStr.go
[Algorithms-28]:https://leetcode.com/implement-strstr/
[Algorithms-27-Test]:algorithms/remove_element/removeElement_test.go#L18
[Algorithms-27-Go]:algorithms/remove_element/removeElement.go
[Algorithms-27]:https://leetcode.com/problems/remove-element/
[Algorithms-26-Test]:algorithms/remove_duplicates_from_sorted_array/removeDuplicates_test.go#L18
[Algorithms-26-Go]:algorithms/remove_duplicates_from_sorted_array/removeDuplicates.go
[Algorithms-26]:https://leetcode.com/problems/remove-duplicates-from-sorted-array/
[Algorithms-25-Test]:algorithms/reverse_nodes_in_k_group/reverseKGroup_test.go#L65
[Algorithms-25-Go]:algorithms/reverse_nodes_in_k_group/reverseKGroup.go
[Algorithms-25]:https://leetcode.com/problems/reverse-nodes-in-k-group/
[Algorithms-24-Test]:algorithms/swap_nodes_in_pairs/swapPairs_test.go#L65
[Algorithms-24-Go]:algorithms/swap_nodes_in_pairs/swapPairs.go
[Algorithms-24]:https://leetcode.com/problems/swap-nodes-in-pairs/
[Algorithms-23-Test]:algorithms/merge_k_sorted_lists/mergeKLists_test.go#L98
[Algorithms-23-Go]:algorithms/merge_k_sorted_lists/mergeKLists.go
[Algorithms-23]:https://leetcode.com/problems/merge-k-sorted-lists/
[Algorithms-22-Test]:algorithms/generate_parentheses/generateParenthesis_test.go#L19
[Algorithms-22-Go]:algorithms/generate_parentheses/generateParenthesis.go
[Algorithms-22]:https://leetcode.com/problems/generate-parentheses/
[Algorithms-21-Test]:algorithms/merge_two_sorted_lists/mergeTwoLists_test.go#L75
[Algorithms-21-Go]:algorithms/merge_two_sorted_lists/mergeTwoLists.go
[Algorithms-21]:https://leetcode.com/problems/merge-two-sorted-lists/
[Algorithms-20-Test]:algorithms/valid_parentheses/isValid_test.go#L25
[Algorithms-20-Go]:algorithms/valid_parentheses/isValid.go
[Algorithms-20]:https://leetcode.com/problems/valid-parentheses/
[Algorithms-19-Test]:algorithms/remove_nth_node_from_end_of_list/removeNthFromEnd_test.go#L72
[Algorithms-19-Go]:algorithms/remove_nth_node_from_end_of_list/removeNthFromEnd.go
[Algorithms-19]:https://leetcode.com/problems/remove-nth-node-from-end-of-list/
[Algorithms-18-Test]:algorithms/4sum/fourSum_test.go#L28
[Algorithms-18-Go]:algorithms/4sum/fourSum.go
[Algorithms-18]:https://leetcode.com/problems/4sum/
[Algorithms-17-Test]:algorithms/letter_combinations_of_a_phone_number/letterCombinations_test.go#L27
[Algorithms-17-Go]:algorithms/letter_combinations_of_a_phone_number/letterCombinations.go
[Algorithms-17]:https://leetcode.com/problems/letter-combinations-of-a-phone-number/
[Algorithms-16-Test]:algorithms/3sum_closest/threeSumClosest_test.go#L20
[Algorithms-16-Go]:algorithms/3sum_closest/threeSumClosest.go
[Algorithms-16]:https://leetcode.com/problems/3sum-closest/
[Algorithms-15-Test]:algorithms/3sum/threeSum_test.go#L20
[Algorithms-15-Go]:algorithms/3sum/threeSum.go
[Algorithms-15]:https://leetcode.com/problems/3sum/
[Algorithms-14-Test]:algorithms/longest_common_prefix/longestCommonPrefix_test.go#L19
[Algorithms-14-Go]:algorithms/longest_common_prefix/longestCommonPrefix.go
[Algorithms-14]:https://leetcode.com/problems/longest-common-prefix/
[Algorithms-13-Test]:algorithms/roman_to_integer/romanToInt_test.go#L23
[Algorithms-13-Go]:algorithms/roman_to_integer/romanToInt.go
[Algorithms-13]:https://leetcode.com/problems/roman-to-integer/
[Algorithms-12-Test]:algorithms/integer_to_roman/intToRoman_test.go#L22
[Algorithms-12-Go]:algorithms/integer_to_roman/intToRoman.go
[Algorithms-12]:https://leetcode.com/problems/integer-to-roman/
[Algorithms-11-Test]:algorithms/container_with_most_water/maxArea_test.go#L21
[Algorithms-11-Go]:algorithms/container_with_most_water/maxArea.go
[Algorithms-11]:https://leetcode.com/problems/container-with-most-water/
[Algorithms-10-Test]:algorithms/regular_expression_matching/isMatch_test.go#L40
[Algorithms-10-Go]:algorithms/regular_expression_matching/isMatch.go
[Algorithms-10]:https://leetcode.com/problems/regular-expression-matching/
[Algorithms-9-Test]:algorithms/palindrome_number/isPalindrome_test.go#L20
[Algorithms-9-Go]:algorithms/palindrome_number/isPalindrome.go
[Algorithms-9]:https://leetcode.com/problems/palindrome-number/
[Algorithms-8-Test]:algorithms/string_to_integer_atoi/myAtoi_test.go#L34
[Algorithms-8-Go]:algorithms/string_to_integer_atoi/myAtoi.go
[Algorithms-8]:https://leetcode.com/problems/string-to-integer-atoi/
[Algorithms-7-Test]:algorithms/reverse_integer/reverse_test.go#L32
[Algorithms-7-Go]:algorithms/reverse_integer/reverse.go
[Algorithms-7]:https://leetcode.com/problems/reverse-integer/
[Algorithms-6-Test]:algorithms/zigzag_conversion/convert_test.go#L18
[Algorithms-6-Go]:algorithms/zigzag_conversion/convert.go
[Algorithms-6]:https://leetcode.com/problems/zigzag-conversion/
[Algorithms-5-Test]:algorithms/longest_palindromic_substring/longestPalindrome_test.go#L18
[Algorithms-5-Go]:algorithms/longest_palindromic_substring/longestPalindrome.go
[Algorithms-5]:https://leetcode.com/problems/longest-palindromic-substring/
[Algorithms-4-Test]:algorithms/median_of_two_sorted_arrays/findMedianSortedArrays_test.go#L71
[Algorithms-4-Go]:algorithms/median_of_two_sorted_arrays/findMedianSortedArrays.go
[Algorithms-4]:https://leetcode.com/problems/median-of-two-sorted-arrays/
[Algorithms-3-Test]:algorithms/longest_substring_without_repeating_characters/lengthOfLongestSubstring_test.go#L16
[Algorithms-3-Go]:algorithms/longest_substring_without_repeating_characters/lengthOfLongestSubstring.go
[Algorithms-3]:https://leetcode.com/problems/longest-substring-without-repeating-characters/
[Algorithms-2-Test]:algorithms/add_two_numbers/addTwoNumbers_test.go#L118
[Algorithms-2-Go]:algorithms/add_two_numbers/addTwoNumbers.go
[Algorithms-2]:https://leetcode.com/problems/add-two-numbers/
[Algorithms-1-Test]:algorithms/two_sum/twoSum_test.go#L16
[Algorithms-1-Go]:algorithms/two_sum/twoSum.go
[Algorithms-1]:https://leetcode.com/problems/two-sum/
