# Metaprogramming: Code Generation for Bitonic Sorting Algorithm

## Purpose

This Python script demonstrates metaprogramming, a powerful programming technique that involves generating and manipulating code dynamically during runtime. The script showcases how metaprogramming can be used to create and implement the Bitonic Sorting algorithm for lists of different sizes.

## Bitonic Sorting Algorithm

The Bitonic Sorting algorithm is a comparison-based sorting algorithm primarily used to sort lists with a power-of-two number of elements. It efficiently performs parallel sorting and can be implemented in a bitonic sequence, where the list is first divided into two halves, each sorted in opposite orders. The sorted halves are then merged to form a fully sorted list.

## Functionality

The script provides the following functions specifically for the Bitonic Sorting algorithm:

1. `bitonic_merge(a_list, start, end, direction, statement=None)`: This function is used to recursively sort a bitonic sequence in ascending order. It takes a list (`a_list`), start index, end index, sorting direction (`direction`), and a statement (to keep track of the order of operations in each direction) as input.

2. `bitonic_sort(a_list, start, end, direction, statement=None)`: This function generates a bitonic sequence by recursively sorting its two halves in opposite sorting orders. It then calls the `bitonic_merge` function to merge the halves into a single sorted sequence with the same order.

3. `bitonic(a_list, statement=None)`: This function serves as the main caller for the Bitonic Sorting algorithm. It takes an input list (`a_list`) and, optionally, a statement (to keep track of the order of operations in each direction). The function sorts the entire array of length `N` in ascending order using the Bitonic Sorting algorithm.

4. `fixed_bitonic(size)`: This function generates a new sorting function called `bitonicN`, where `N` is the provided `size`. The `bitonicN` function uses the Bitonic Sorting algorithm to sort lists of length `N`.

## Execution

To run the metaprogramming script and witness the Bitonic Sorting algorithm in action, follow these steps:

1. Ensure you have Python installed on your system.

2. Run the Python script containing the provided code.

3. The script will dynamically generate sorting functions (`bitonicN`) for lists of different sizes based on the Bitonic Sorting algorithm.

4. You can test the generated sorting functions by using sample lists and observe the sorted results.

## Notes

- The Bitonic Sorting algorithm is particularly efficient for sorting lists with a power-of-two number of elements.

- Metaprogramming enables code generation and abstraction, leading to more flexible and scalable codebases.

## Contact

If you have any questions or feedback regarding the metaprogramming script and the Bitonic Sorting algorithm, feel free to reach out. You can find me on GitHub: [github.com/ayokunle321](https://github.com/ayokunle321).
