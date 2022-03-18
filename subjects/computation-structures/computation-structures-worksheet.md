# Computation Structures Worksheet

This subject is based on https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/index.htm.

## Table of contents
[Basics of Information](#basics-of-information)  
[The Digital Abstraction](#the-digital-abstraction)  


## Basics of Information

1. You are given an unknown 3-bit binary number. You are then told that the binary representation contains exactly two 1’s. How much information have you been given?   
    - [ ] log<sub>2</sub>(8/3)
    - [ ] 8
    - [ ] log<sub>2</sub>3
    - [ ] log<sub>2</sub>(2/8)
    - [ ] log<sub>2</sub>(3/8)

2. You are then given the additional information that the number is also odd. How much additional information have you been given? 
    - [ ] log<sub>2</sub>(3/2)
    - [ ] 3
    - [ ] log<sub>2</sub>3
    - [ ] log<sub>2</sub>(2/3)
    - [ ] log<sub>2</sub>(3/8)

3. A random variable X represents the outcome of flipping an unfair coin, where p(HEADS) = 0.6. Please give the value for the entropy H(X).
    - [ ] 0.97 bits
    - [ ] 0.96 bits
    - [ ] 0.98 bits
    - [ ] 0.99 bits
    - [ ] 0.95 bits

4. A single decimal digit is chosen at random and you’re told that its value is 0 mod 3. How much information have you learned about the digit?
    - [ ] log<sub>2</sub>(10/4)
    - [ ] log<sub>2</sub>(1)
    - [ ] log<sub>2</sub>(1/4)
    - [ ] log<sub>2</sub>(10)
    - [ ] log<sub>2</sub>(3)

5. X is an unknown 8-bit binary number. You are given another 8-bit binary number, 10101100, and told that the Hamming distance between X and 10101100 is one. How many bits of information about X have you been given?
    - [ ] 5 bits
    - [ ] 4 bits
    - [ ] 6 bits
    - [ ] 3 bits
    - [ ] 7 bits

6. We wish to transmit messages comprised of the four symbols shown below with their associated probabilities and 5-bit fixed-length encoding. An unknown symbol is received and you are told it’s not delta. How much information have you received?
    - [ ] log<sub>2</sub>(8/7)
    - [ ] log<sub>2</sub>(8/5)
    - [ ] log<sub>2</sub>(4)
    - [ ] log<sub>2</sub>(4/3)
    - [ ] log<sub>2</sub>(5/4)

    | Symbol | p(symbol) | encoding |
    |--------|-----------|----------|
    | alpha  | 0.5       | 00000    |
    | beta   | 0.125     | 11100    |
    | gamma  | 0.25      | 11011    |
    | delta  | 0.125     | 10111    |


## The Digital Abstraction

