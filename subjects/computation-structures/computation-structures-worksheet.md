# Computation Structures Worksheet

This subject is based on https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/index.htm.

## Table of contents
[Basics of Information](#basics-of-information)  
[The Digital Abstraction](#the-digital-abstraction)  


## Basics of Information

**{1}** You are given an unknown 3-bit binary number. You are then told that the binary representation contains exactly two 1’s. How much information have you been given?   
- [ ] log<sub>2</sub>(8/3) bits
- [ ] 8 bits
- [ ] log<sub>2</sub>3 bits
- [ ] log<sub>2</sub>(2/8) bits
- [ ] log<sub>2</sub>(3/8) bits

**{2}** You are then given the additional information that the number is also odd. How much additional information have you been given? 
- [ ] log<sub>2</sub>(3/2) bits
- [ ] 3 bits
- [ ] log<sub>2</sub>3 bits
- [ ] log<sub>2</sub>(2/3) bits
- [ ] log<sub>2</sub>(3/8) bits

**{3}** A random variable X represents the outcome of flipping an unfair coin, where p(HEADS) = 0.6. Please give the value for the entropy H(X).
- [ ] 0.97 bits
- [ ] 0.96 bits
- [ ] 0.98 bits
- [ ] 0.99 bits
- [ ] 0.95 bits

**{4}** A single decimal digit is chosen at random and you’re told that its value is 0 mod 3. How much information have you learned about the digit?
- [ ] log<sub>2</sub>(10/4) bits
- [ ] log<sub>2</sub>(1) bits
- [ ] log<sub>2</sub>(1/4) bits
- [ ] log<sub>2</sub>(10) bits
- [ ] log<sub>2</sub>(3) bits

**{5}** X is an unknown 8-bit binary number. You are given another 8-bit binary number, 10101100, and told that the Hamming distance between X and 10101100 is one. How many bits of information about X have you been given?
- [ ] 5 bits
- [ ] 4 bits
- [ ] 6 bits
- [ ] 3 bits
- [ ] 7 bits

**{6}** We wish to transmit messages comprised of the four symbols shown below with their associated probabilities and 5-bit fixed-length encoding. An unknown symbol is received and you are told it’s not delta. How much information have you received?
- [ ] log<sub>2</sub>(8/7) bits
- [ ] log<sub>2</sub>(8/5) bits
- [ ] log<sub>2</sub>(4) bits
- [ ] log<sub>2</sub>(4/3) bits
- [ ] log<sub>2</sub>(5/4) bits

| Symbol | p(symbol) | encoding |
|--------|-----------|----------|
| alpha  | 0.5       | 00000    |
| beta   | 0.125     | 11100    |
| gamma  | 0.25      | 11011    |
| delta  | 0.125     | 10111    |

**{7}** When transmitting a message comprised of these four symbols with the probabilities as given above, what is the expected amount of information received (also known as entropy) when you are told the next symbol in the message?
- [ ] 1.75 bits
- [ ] 1.5 bits
- [ ] 2 bits
- [ ] 1.25 bits
- [ ] 2.25 bits

**{8}** You are given an unknown 5-bit binary number. You are then told that the first and last bits are the same. How much information have you been given?
- [ ] 1 bit
- [ ] 1.5 bits
- [ ] 2 bits
- [ ] 1.25 bits
- [ ] 2.25 bits

**{9}** I've randomly selected a letter from the alphabet and tell you that my selection is neither "X", "Y", nor "Z". How much information have I given you about my letter?
- [ ] log<sub>2</sub>(26/23) bits
- [ ] 3 bits
- [ ] 1 bit
- [ ] log<sub>2</sub>(32/29) bits
- [ ] 2.25 bits

**{10}** I make up a random 4-bit two’s complement number by flipping a fair coin to determine each bit. You’re trying to guess the number. If I tell you that the number is positive (> 0), how many bits of information have I given you?
- [ ] log<sub>2</sub>(16/7) bits
- [ ] 3 bits
- [ ] 1 bit
- [ ] log<sub>2</sub>(32/29) bits
- [ ] 2.25 bits

**{11}** What is the 6-bit two’s complement representation of the decimal number -21?
- [ ] 101011
- [ ] 110101
- [ ] 100100
- [ ] 100101
- [ ] 100111

**{12}** What is the hexadecimal representation for decimal -51 encoded as an 8-bit two’s complement number?
- [ ] 0xCD
- [ ] 0xCC
- [ ] 0xDD
- [ ] 0xCA
- [ ] 0xDA

**{13}** The hexadecimal representation for an 8-bit two’s complement number is 0xD6. What is its decimal representation?
- [ ] -42
- [ ] -41
- [ ] -43
- [ ] -40
- [ ] -44

**{14}** Since the start of official pitching statistics in 1988, the highest number of pitches in a single game has been 172. Assuming that remains the upper bound on pitch count, how many bits would we need to record the pitch count for each game as a two’s complement binary number?
- [ ] 9 bits
- [ ] 8 bits
- [ ] 10 bits
- [ ] 7 bits
- [ ] 11 bits

**{15}** What is the sum of two 2’s complement numbers 0xB3 + 0x47 using an 8-bit 2’s complement representation? Please encode the result using hex. 
- [ ] 0xFA
- [ ] 0xFB
- [ ] 0xE9
- [ ] 0xFC
- [ ] Bit overflow

**{16}** What is the sum of two 2’s complement numbers 0xB3 + 0xB1 using an 8-bit 2’s complement representation? Please encode the result using hex. 
- [ ] Bit overflow
- [ ] 0xFB
- [ ] 0xE9
- [ ] 0xFC
- [ ] 0xE8

**{17}** Please compute the value of the expression 0xBB – 8 using 8-bit two’s complement arithmetic and give the result in decimal (base 10). 
- [ ] -77 
- [ ] -76
- [ ] -78
- [ ] -75
- [ ] -79

**{18}** What is the smallest (most negative) integer that can be represented as an 8-bit two’s complement integer? Give your answer as a decimal integer.
- [ ] -128
- [ ] -64
- [ ] -256
- [ ] -32
- [ ] -512

**{19}** In hexadecimal, using a 8-bit adder with 2's complement encoding, how much is 0xF0 + 0x34? 
- [ ] 0x24
- [ ] 0x92
- [ ] 0x23
- [ ] 0x91
- [ ] 0x93

**{20}** In hexadecimal, using a 8-bit adder with 2's complement encoding, how much is 0xF0 + 0x80? 
- [ ] 0x70
- [ ] 0xB8
- [ ] 0x71
- [ ] 0xB9
- [ ] 0x72

## The Digital Abstraction

