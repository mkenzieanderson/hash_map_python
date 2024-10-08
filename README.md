**Author:** Mackenzie Anderson

**GitHub username:** mkenzieanderson

**Date:** March 2024


The following python files contain implementations of the separate chaining and open addressing hash map data structures. Both of these hash map variations utilize dynamic arrays to organize and store key-value pair data. Additionally, the separate chaining hash map uses a singly linked list data structure to organize the buckets at each hash index. Testing code is also provided at the bottom of each hash map file.

There are two hashing functions available for both of the hash map variations. The separate chaining hash map data structure resizes to maintain a load factor that is less than 1. The open addressing hash map data structure resizes once the load factor exceeds 0.5. Due to the limitations on load factor, standard operations for both data structures run at O(1) complexity.
