# What is functional programming?

Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data. — Wikipedia

two way to know if something is a pure function.

1. It returns the same result if given the same arguments (it is also referred as deterministic)

2. It does not cause any observable side effects

Any function that relies on a random number generator cannot be a pure function.

Pure functions do not cause any observable side effects

When data is immutable, its state cannot change after it’s created.