# Pseudo-Random Number Generator

A short and simple random number generator using C++11's <random> library.
  
Everything is contained within the **prng** namespace. No seeding is required.

## Functions
  - **number(T floor, t ceil)** returns a random alphanumeric within the provided range
  - **number(size_type s)** returns a random unsigned int within range of a container's size
  - **boolean()** returns a random bool (50% chance)
  - **boolean(float chance)** Returns a weighted bool (chance as a percent of 1.f)
