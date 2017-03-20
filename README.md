# algorithms-and-data-structures
1) C++ STL set has "lower_bound" and "upper_bound" function,but it does not have a function to get the rank of a number directly.
I think this function is pretty useful because if we update the relevant property stored in nodes when inserting or deleting 
numbers. We can get the rank through finding the node which time complexity is O(log n). However, we now need firstly find this 
node, then iterate to the end of the bst tree, which is O(n)
