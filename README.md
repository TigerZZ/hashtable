Hashtable implementation
------------------------
Hello. I wrote this mainly as an exercise to run some benchmark tests. I'm comparing this native implementation of hashtable in C with JS objects and Python dicts.

The implementation uses separate chaining with linked lists for collision resolution. Thus, we have a fixed array (malloc'd) which we have O(1) access to it, and each value is actually a linked list.

The dependency relation between ht and ll is asymmetric.

For benchmarks, check the `benchmarks` folder.

To build the tests, run `make tests`. To run them, write `make runtests`.

To build the examples, run `make examples`. To run them, write `make runexamples`.

To just build the library, write `make lib`.

To build everything, write `make`.

To cleanup, run `make clean`.

Boro Sitnikovski

February 2017
