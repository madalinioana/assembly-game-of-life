# Conway's Game of Life Simulation and Symmetric Encryption

## Overview

This repository contains an implementation of Conway's Game of Life, a zero-player game invented by mathematician John Horton Conway in 1970. Additionally, it includes functionality for symmetric encryption and decryption using cellular automata principles inspired by the game.

### Conway's Game of Life

Conway's Game of Life is a two-dimensional cellular automaton where the evolution of a system of cells is determined by simple rules based on the cells' immediate neighbors. The rules dictate whether a cell lives, dies, or is born in the next generation based on the number of live neighbors.

### Symmetric Encryption

Symmetric encryption is achieved using the cellular automaton system's evolution as a key. By encrypting or decrypting a message with the result of a cellular automaton generation, secure communication can be established.

## Features

- **Game of Life Simulation:**
  - Generate successive generations of cells based on predefined rules.
  - Input initial configurations and observe the evolution of the system.
  - Support for extending the matrix to handle boundary conditions.

- **Symmetric Encryption:**
  - Encrypt and decrypt messages using the cellular automaton's evolving states.
  - Input messages for encryption or decryption.
  - Provide options for encryption or decryption mode.

## Usage

### Game of Life Simulation

To simulate Conway's Game of Life:

1. Compile and execute the provided program.
2. Enter the number of rows, columns, initial live cells, their positions, and the number of generations.
3. View the successive generations of the cellular automaton.

### Symmetric Encryption

To perform symmetric encryption or decryption:

1. Compile and execute the encryption program.
2. Choose the encryption or decryption mode.
3. Input the message (plaintext or ciphertext).
4. View the encrypted or decrypted output.

## File Structure

- `src/`: Contains the source code for the Game of Life simulation and symmetric encryption.
- `docs/`: Documentation files, including this README.md.
- `input/`: Sample input files for testing.
- `output/`: Sample output files for reference.

## Requirements

- C compiler for compiling the source code.
- Standard libraries for file I/O operations.
- Text editor or IDE for code modifications.

## Example

To illustrate the usage, consider the following:

1. Simulating Conway's Game of Life with a predefined initial configuration.
2. Encrypting a message using the cellular automaton evolution as the encryption key.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- John Horton Conway for inventing the Game of Life.
- Contributors to the field of cellular automata and cryptography.

---

**Note:** For detailed instructions, refer to the documentation provided in the `docs/` directory.
