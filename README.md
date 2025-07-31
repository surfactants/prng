# prng
## About
Written by [surfactants](https://github.com/surfactants).

A simple pseudo-random number generator using the C++11 \<random\> library.
  
Everything is contained within the **prng** namespace. Seeding is internal and automatic.

## Functions
  - **number(T floor, t ceil)** returns a random alphanumeric within the provided range
  - **number(size_type s)** returns a random unsigned int within range of a container's size
  - **boolean()** returns a random bool (50% chance)
  - **boolean(float chance)** Returns a weighted bool (chance as a percent of 1.f)
