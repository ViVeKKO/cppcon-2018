# cppcon-2018
# PROVINCE OF HEAPS
1. Make Heap from Any Vector: std::make_heap(begin(numbers),end(numbers));
2. To add an elemnet to proper Position in heap: std::push_heap(begin(numbers),end(numbers));
3. To Remove element from Heap: std::pop_heap(begin(numbers),end(numbers));

# Secret RUNES

1. stable: relative order
        stable_sort(begin(numbers),end(numbers));
        stable_partition(begin(numbers),end(numbers));
2. is: returns a boolean
        is_sorted(begin(numbers),end(numbers));
        is_partitioned(begin(numbers),end(numbers));
        is_heap(begin(numbers),end(numbers));
3. is until: returns iterator of first false val
        is_sorted_until(begin(numbers),end(numbers));
        is_partitioned_until(begin(numbers),end(numbers));

# Land of QUERIES

1. count
2. accumulate
3. inner_product
4. adjacent_difference
5. sample
6. partial_sum

Querying a property
1. all_of
2. any_of
3. none_of
4. equal
5. lexicographical_compare
6. mismatch

Searching a Value

Sorted                      Not Sorted
1. equal_range          1. find
2.                      2. adjacent_find

Searching a relative value
1. max_element
2. min_element
3. minmax_element

# Glorious county of algos on sets

1. set_difference
2. set_union
3. includes
4. set_intersection
5. set_symmetric_difference

# Territory of Movers

1. copy(first,last,out)
2. move(first,last,out)
3. swap_ranges(first,last,out)


