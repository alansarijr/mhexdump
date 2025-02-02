# HexDump Utility in C

A custom implementation of a hexdump utility for binary file analysis, inspired by Unix/Linux `hexdump`. This tool parses binary files and displays their contents in a canonical hex/ASCII format, useful for low-level debugging, reverse engineering, and cybersecurity tasks.

---

## Features
- **Binary File Parsing**: Read and display binary files up to 1 KB (configurable buffer size).
- **Hex/ASCII Visualization**: 
  - **Hex Bytes**: Output in 2-digit hexadecimal format.
  - **ASCII Representation**: Substitute non-printable characters (e.g., `\x00`, `\x1B`) with `.`.
- **Address Offsets**: Display file offsets in 8-character hexadecimal format.
- **Error Handling**: Robust checks for:
  - File existence and readability.
  - Invalid buffer sizes.
  - Memory allocation failures.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hexdump-c.git
   cd hexdump-c
   ```
2. Compile using gcc:
  ```bash
  gcc hexdump.c -o hexdump
  ```
## Usage
```bash
./hexdump <filename>
```


