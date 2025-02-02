# BackSubstitution

Illustration of setting up a TBB flow graph to compute the solution to a lower
triangular set of equations by back substitution.

## What is it?

1. [src](src): directory containing the source code.
   1. [equations.h](src/equations.h): definition of a class to represent a set of equations.
   1. [equations.cpp](src/equations.cpp): implementation of the `Equation` class methods.
   1. [solver.h](src/solver.h): declarations of functions to solve the equations and
      verify the solution.
   1. [solver.cpp](src/solver.cpp): function implementations.
   1. [back_substitution_serial.cpp](src/back_substitution_serial.cpp): application to initialize/read
      a set of equations and solve them using a serial algorithm.
   1. [CMakeLists.txt](CMakeLists.txt): CMake file to build the  applications.
1. [CMakeLists.txt](CMakeLists.txt): CMake file to build the  applications.
1. [eqns.txt](eqns.txt): data file containing a small set of equations for
   testing purposes.
