# Byte-Squeeze
This application utilizes the Huffman coding algorithm to compress text files in a greedy manner, reducing their size efficiently. Huffman coding is a widely used technique for lossless data compression. It assigns variable-length codes to input characters, with shorter codes assigned to more frequent characters. This application provides an implementation of the Huffman algorithm specifically designed to compress text files.

Features:
Huffman coding algorithm implementation
Greedy approach for efficient compression
User-friendly command-line interface

Installation:
Clone the repository to your local machine:
git clone https://github.com/H-rshJoshi/Byte-Squeeze.git

Navigate to the project directory:
cd Byte Squeeze

Usage
To compress a text file, use the following command:
python compress.py input.txt output.bin
Replace input.txt with the path to your text file and output.bin with the desired name for the compressed binary file.

To decompress the compressed binary file, use the following command:
python decompress.py compressed.bin decompressed.txt
Replace compressed.bin with the path to your compressed binary file and decompressed.txt with the desired name for the decompressed text file.
