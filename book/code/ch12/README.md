# Shor's Algorithm

- Core algorithm - can be implemented using classical algorithms only (for learning).  
- Optimization techniques are key to both classical and quantum implementations of Shor's Algorithm.
- Wikipedia definition - [link](https://en.wikipedia.org/wiki/Shor%27s_algorithm)

## What is it?

- Problem: Given an odd integer N, find its prime factors (p,q)
- The algorithm is composed of two parts
    - Classical part -  turns the factoring problem into the problem of finding the period of a function 
    - Quantum speedup -  finds the period using the quantum Fourier transform (QFT) and modular exponentiation by repeated squarings

## Learn More

- Qiskit textbook - [link](https://qiskit.org/textbook/ch-algorithms/shor.html#1.-The-Problem:-Period-Finding)
- Classical example notebook - [link](https://github.com/PotatoDrug/Quantum-Cryptography/blob/master/Shor/Shor's%20Algorithm.ipynb)
- Medium Article - [link](https://towardsdatascience.com/quantum-factorization-b3f44be9d738)

### Other Info

Fermat’s little theorem implies that...

<img src="https://github.com/lynnlangit/learning-quantum/blob/main/images/fermat.png" width=300 align=left>

This theorem gives us the hint that such exponents may have periods.  Potential factors are determined using classical methods, potential periods are found using quantum methods.