# Computation Structures

This subject is based on https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/index.htm.

## Basics of information

0. It's any data that manages to reduce uncertainty.
1. Different pieces of data reduce uncertainty by different amounts. More reduction equals more information conveyed.
2. In 1948, Claude Shannon tried to quantify information as I(x<sub>i</sub>) = log<sub>2</sub>(1/p<sub>i</sub>).  x<sub>i</sub> has a probability of p<sub>i</sub> of occurring. In other words, the lower the probability, the higher the information gained.
3. As an example, learning that a random deck card is a heard gives us: I(heart) = log<sub>2</sub>(1/(13/52)), which is equal to 2 bits.

