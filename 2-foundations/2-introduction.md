# Introduction to C++

## 1. Intro
- see next section for example of how course is taught

## 2. Motion Planning
- sample of the course's style of teaching

## 3. Maze
- another example

# 4. Quiz
- verifying you followed the example

# 5. Shortest Path
- use cells, block out walls, label cells
- one cell is start, another is goal
- check each possible successor moves
- for each move expand all its possible moves
    - only expand cell with smallest g value
- count steps each expansion (g value)
- do not check already checked steps

## 6. Your First C++ Program
- must have a `main` function
- simplest is `main.cpp` file with a `main` function
- compile using `g++`, run the file that output
```C++
int main() {
    return 0;
}
```

## 7. Compiled vs. Scripted
- advantages, disadvantages

## 8. Output
- `#include` for header file, here `<iostream>`
- `using` for namespace
- `std::cout` to print

## 9. Output to Console
- compile and run a function that prints "Hello"

## 10-12 Store Data
- object used according to its definition
- so mostly strongly staticly typed
- primitive types: `int`, `float`, `string`
- cannot redeclare variable in same closure?
- use `std::string` after importing `<string>`

## 13-14 Vectors
- "linear sequene of contiguously allocated memory"
- linked lists as overused
- hash tables for constant time lookup
- initialization: `vector<int> name {1,2,3,4};`
    - can also set `=` or declare then assign later
- multidimensional like: `vector<vector<int>>{{1,2}, {3,4}}`

## 15. Comments
- // single line vs /* block */

## 16. Auto
- use `auto` to have C++ infer type

## 17. Store a Grid
- write a function storing a vector of int vectors

## 18-19 Print a Grid
- write a function to print the grid
- `cout` values from array accessed using bracket index
- no out of bounds errors when accesssing outside array
- array has a `.size`

## 20. For Loops
- 
