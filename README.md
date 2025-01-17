# Huffman Text File Compressor & Decompressor

A C++ project implementing Huffman coding for efficient text file compression and decompression. This project minimizes file size while preserving content integrity using advanced bitwise operations and data structures.

## Features
- **Text File Compression**: Implements Huffman coding to assign variable-length binary codes based on character frequency, reducing file size by up to 40%.
- **Bitwise Operations**: Efficiently handles data at the bit level for optimized compression and storage.
- **Huffman Tree Generation**: Constructs a binary tree to visualize and assign codes to characters.
- **Decompression**: Reconstructs the original file using a decoding tree, ensuring accuracy in decompressed data.
- **Compression Analysis**: Displays encoding tree, character frequency, and calculates compression ratios.

## Technologies
- **Languages**: C++
- **Data Structures**: Priority Queues, Binary Trees, Vectors
- **File Handling**: Custom bitwise read/write operations for binary data
- **Developer Tools**: GCC, GDB, Makefile

## How It Works
1. **Compression**: The program reads the input text file, calculates the frequency of each character, and builds a Huffman tree. It then generates a binary code for each character and compresses the file by replacing each character with its corresponding binary code.
2. **Decompression**: The compressed file is decompressed by traversing the Huffman tree and decoding the binary data back to its original text format.

