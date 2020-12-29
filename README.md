# Still under progress
# ds-and-algos
Lightweight and efficient C++ header-only template library for data structures and algorithms .

This library is dedicated towards data structures and algorithms that are useful in competitive programming . 

## Table of Contents 
- [Usage](#usage)
- [Library](#library)
  - [Number Theory](#number-theory)
  - [Data Structures](#data-structures)
- [License](#license)

### Usage
- Clone the repository (and star it if you like it)
- copy _path/to/repo/include_ to the directory where you need to use the library 
- include header files of the data structures and algorithms you need to use in your code 
- path of header file in _include "header_file"_ should be relative to _path/to/current/working/directory/ds-and-algos/include
- Include `-Ipath/to/current/working/directory/ds-and-algos/include` flag while compiling files.
- That's it .
### Library

#### Number Theory
| Name                                                                                                  | Examples                                                             | Good resources to study                                                                                                                                                                |
| ----------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------  |
| [Binary exponentiation](include/dragon/number-theory/binary-exponentiation.hpp)                       | [Link](examples/number-theory/binary-exponentiation)                 | [cp-algorithms](https://cp-algorithms.com/algebra/binary-exp.html), [random-site-1](https://eli.thegreenplace.net/2009/03/21/efficient-integer-exponentiation-algorithms),             |
| [Extended euclid](include/dragon/number-theory/extended-euclid.hpp)                                   | [Link](examples/number-theory/extended-euclid)                       | [cp-algorithms](https://cp-algorithms.com/algebra/extended-euclid-algorithm.html), [brilliant](https://brilliant.org/wiki/extended-euclidean-algorithm/),                              |
| [Linear diophantine equation](include/dragon/number-theory/linera-diophantine-equation.hpp)           | [Link](examples/number-theory/linera-diophantine-equation)           | [cp-algorithms](https://cp-algorithms.com/algebra/linear-diophantine-equation.html), [brilliant](https://brilliant.org/wiki/linear-diophantine-equations-one-equation/),               |
| [Mod inverse](include/dragon/number-theory/mod-inverse.hpp)                                           | [Link](examples/number-theory/mod-inverse)                           | [cp-algorithms](https://cp-algorithms.com/algebra/module-inverse.html), [gfg](https://www.geeksforgeeks.org/multiplicative-inverse-under-modulo-m/),                                   |
| [Chinese remainder theorem](include/dragon/number-theory/chinese-remainder-theorem.hpp)               | [Link](examples/number-theory/chinese-remainder-theorem)             | [brilliant](https://brilliant.org/wiki/chinese-remainder-theorem/), [AOPS](https://artofproblemsolving.com/wiki/index.php/Chinese_Remainder_Theorem),                                  |
| [Sieve of eratosthenes](include/dragon/number-theory/sieve.hpp)                                       | [Link](examples/number-theory/sieve)                                 | [cp-algorithms](https://cp-algorithms.com/algebra/sieve-of-eratosthenes.html), [brilliant](https://brilliant.org/wiki/sieve-of-eratosthenes/),                                         |
| [Euler totient](include/dragon/number-theory/euler-totient.hpp)                                       | [Link](examples/number-theory/euler-totient)                         | [cp-algorithms](https://cp-algorithms.com/algebra/phi-function.html), [brilliant](https://brilliant.org/wiki/eulers-totient-function/),                                                |


#### Data Structures

- [Sparse Table](src/ds/sparse-table.hpp)

### License
This project is licensed under the MIT License. See the license [here](LICENSE)
