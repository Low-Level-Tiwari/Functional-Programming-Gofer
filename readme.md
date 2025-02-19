
# Functional Programming Library in Gofer  

## Overview  

This project is a **basic algebra and functional programming library** implemented using **Gofer**, a variant of **Haskell**. It includes a variety of list, tree, and number-processing functions, demonstrating recursion, higher-order functions, and functional paradigms.  

## Features  

- **Algebraic Functions**: Operations such as `add`, `mul`, and numerical comparisons (`iseq`, `islessthan`).  
- **List Operations**: Implementations of `map`, `filter`, `reduce`, `zipWith`, `take`, `drop`, `concat`.  
- **Tree Structures**: Definitions for `Tree` and `Tree2`, with functions like `mapTree` and `zipWithTree`.  
- **Boolean Logic**: Includes `and`, `or`, and `not`.  
- **Recursion-Based Iterators**: Functions like `iterate`, `repeat`, and `takewhile`.  

## Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/Low-Level-Tiwari/Functional-Programming-Gofer.git
   cd Functional-Programming-Gofer
   ```
2. Run the Gofer interpreter and load the library:  
   ```bash
   gofer
   :load lib2
   ```  

## Usage  

Once the library is loaded, you can call functions interactively:  
```haskell
add 5 3  -- Example addition function  
map (*2) [1,2,3]  -- Doubles each element in the list  
zipWith (+) [1,2,3] [4,5,6]  -- Adds corresponding elements  
```

## Future Enhancements  

- Implement additional algebraic structures.  
- Extend tree-based operations.  
- Improve optimization for recursive functions.  

## License  

This project is released under the **MIT License**.  

## Contact  

For questions or discussions, open an issue on **GitHub**.  
