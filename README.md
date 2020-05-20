## Minimal example: CMake Google Test integration as as git submodule

This project contains a minimal example of integrating Google Test as a submodule.

To build and run tests:
```
mkdir build
cd build
cmake .. -G Ninja
ninja
ctest
```

Output:
```
    Start 1: Foo.Sum
1/2 Test #1: Foo.Sum ..........................   Passed    0.02 sec
    Start 2: Foo.Diff
2/2 Test #2: Foo.Diff .........................   Passed    0.02 sec
```