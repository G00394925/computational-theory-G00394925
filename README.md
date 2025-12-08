# Computational Theory

**Author**: Macdarach Carty Joyce - G00394925

## Overview

This repository contains a Jupyter Notebook that implements the Secure Hash Standard'd SHA-256 algorithm. It contains functions that that either implement the necessary steps to carry out a hashing of a message, or providing context to other elements used.

The notebook provides the solutions to five given problems, being:

1. **Binary Words and Operations** - Implement necessary bitwise operations to be used later in the hashing process.
2. **Fractional Parts of Cube Roots** - Calculate the constants defined in the Secure Hash Standard by finding the fractional parts of the cube roots of the first 64 prime numbers.
3. **Padding** - Implement the pre-processing step by padding a given message with '0's so that its bit length is congruent to 448 mod 512.
4. **Hashes** - Acquire the final hash value (message digest) of a given input.
5. **Passwords** - Crack three given passwords that were hashed using one pass of the SHA-256 algroithm, highlighting the necessity of choosing secure passwords.

## Contents

- `problems.ipynb` - Jupyter notebook containing all of the code solutions to five problems, as well as providing insight in markdown cells
- `most=common-pwds.txt` - Text file containing 10,000 of the most commonly used passwords, which is used to crack a given collection of hashed passwords

## Requirements

```
numpy
```

## Usage

1. Clone repository:

   ```bash
   git clone https://github.com/G00394925/computational-theory-G00394925.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook.

## References

- [FIPS PUB 180-4: Secure Hash Standard](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf)
- [Generator Functions](https://realpython.com/introduction-to-python-generators/)
- [Bytes Objects](https://realpython.com/python-bytes/)
- [Endianess](https://www.geeksforgeeks.org/dsa/little-and-big-endian-mystery/)
- [NordPass Most Common Passwords](https://nordpass.com/most-common-passwords-list/)
- [SecList Common Passwords](https://github.com/danielmiessler/SecLists/blob/master/Passwords/Common-Credentials/10k-most-common.txt)
