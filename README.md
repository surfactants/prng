# Pseudo-Random Numnber Generator

A short and simple random number generator using C++11's <random> library.
  
Everything is contained within the **prng** namespace. No seeding is required.

## Functions
  - **number(T floor, t ceil)** returns a random number or character within the provided range
  - **number(size_type s)** returns a random number within range of a container's size
  - **boolean()** returns a random bool (50% chance)
  - **boolean(float chance)** Returns a weighted bool (chance as a percent of 1.f)
