# sparse_arrays

There is a collection of input strings and a collection of query strings. For each query string, determine how many times it occurs in the list of input strings.

For example, given input strings = ['ab',' ab' ,abc'] and queries = ['ab',' abc', bc'], we find z instances of ab', 1 of 'abc' and 0 of 'bc'. For each query, we add an element to our return array, results = [2,1,0].

Function Description

Complete the function matchingStrings in the editor below. The function must return an array of integers representing the frequency of occurrence of each query string in strings.

matchingStrings has the following parameters:

strings - an array of strings to search
queries - an array of query strings
Input Format

The first line contains and integer , the size of . 
Each of the next  lines contains a string . 
The next line contains , the size of . 
Each of the next  lines contains a string .

Constraints

1 <= n <= 1000
1 <= q <= 1000
1 <= |string[i]|, |queries[i]| <= 20

Output Format

Return an integer array of the results of all queries in order.