# Binary-Search-Tree
- The Insert() function inserts a node with the data value x in the tree. 
- For the Search() function, x is the data value of a leaf to be searched for. If the search is successful, the Search() function returns true; otherwise, it returns false. 
- The Remove() function first calls the Search() function to determine the result of the search for a leaf with the data value x, and if the search is successful, then it calls _Remove(); the private version of the Remove() function to remove the corresponding leaf from the tree and returns true; otherwise, it returns false. 
- The _Leaf() function simply checks if a node is a leaf.

The private versions of the member functions _Insert(), _Remove(), and _Search() can be implemented as recursive functions, but these functions have an additional argument, which is the root of the tree. The private version of the _Remove() function unlike its public version does not return any value.
