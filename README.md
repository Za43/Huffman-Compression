# Huffman Compression

## Overview

A straightforward implementation of Huffman coding, this Java-based project provides a means to compress and decompress text files using this well-known algorithm. Ideal for educational purposes or for use in simple compression tasks.

### Features

- **Huffman Coding**: Implements Huffman coding for file compression and decompression.
- **File I/O**: Includes Java classes to handle file input and output streams.
- **User Interface**: A basic file selector for choosing files to compress or decompress.
- **Error Handling**: Custom exception handling with `HuffException`.

### Project Structure

- `HuffProcessor.java`: Core logic for Huffman compression and decompression.
- `HuffMainCompress.java`: Entry point for compression operation.
- `HuffMainDecompress.java`: Entry point for decompression operation.
- `FileSelector.java`: GUI component to select files.
- `BitInputStream.java` & `BitOutputStream.java`: Stream classes for reading and writing binary data.
- `Diff.java`: Utility to compare the original and decompressed files for equality.
- `HuffException.java`: Custom exception class for error handling.

### Usage

To compress a file, use the `FileSelector` GUI to choose a target file and then initiate the compression process. For decompression, select a previously compressed file with the GUI to restore it to its original form.
