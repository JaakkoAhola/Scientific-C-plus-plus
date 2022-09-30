# Tree

Example of using various types of pointers to implement a binary tree.

## What is it?

* Classic pointers
  * [node.h](node.h): definition of a template class for nodes in a tree data
      structure.
  * [tree.cpp](tree.cpp): main file to test node implementation.
* Shared pointers
  * [node_sptr.h](node_sptr.h): definition of a template class for nodes in a tree data
      structure.
  * [tree_sptr.cpp](tree_sptr.cpp): main file to test node implementation.
* Unique pointers
  * [node_uptr.h](node_uptr.h): definition of a template class for nodes in a tree data
      structure.
  * [tree_uptr.cpp](tree_uptr.cpp): main file to test node implementation.
* [CMakeLists.txt](CMakeLists.txt): CMake file to build the applications.
