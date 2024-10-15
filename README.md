---

# File Compression and Decompression Tool Using Huffman Coding

This project showcases a tool designed for compressing and decompressing files through the Huffman coding algorithm. Developed from May 2023 to July 2023, the tool effectively reduces the size of large text files by encoding frequently occurring characters with shorter binary representations, thereby optimizing storage space without compromising data integrity. It highlights the efficiency of Huffman coding by offering both compression and decompression capabilities.

## Project Highlights

- **Huffman Coding Implementation:** The tool employs the Huffman coding algorithm, a well-regarded lossless compression method that minimizes text file size by assigning shorter binary codes to more frequently used characters while giving longer codes to less common characters.

- **Encoding and Decoding Functions:** It includes robust functions to convert a file into a compressed binary format and to reverse the process, accurately restoring the original file. The operations are executed efficiently using a Huffman tree.

- **Bit-Level Operations:** The project exemplifies a deep understanding of bit manipulation, which is crucial for achieving maximum compression during the encoding phase.

- **Priority Queue Utilization:** A priority queue is implemented to facilitate the optimal construction of the Huffman tree, ensuring that the most common characters are encoded with shorter paths.

- **Binary Tree Structure:** The tool builds and utilizes a binary tree (Huffman tree), where each leaf node corresponds to a character and its frequency from the input text. The path from the root to a leaf node defines the compressed binary code for that character.

## Key Features

- **Efficient Compression:** Converts a text file into a significantly smaller binary file while preserving all original data.

- **Accurate Decompression:** Effectively reconstructs the original file from the compressed binary data using the same Huffman tree.

- **Advanced Data Structures:** Implements priority queues for efficient tree construction and leverages bit manipulation for optimal encoding and decoding performance.

## Technical Details

- **Algorithm Design:** Utilizes the Huffman coding algorithm, which optimally compresses storage space by handling frequently used characters more efficiently compared to those that are less frequent.

- **Data Structures:** Utilizes priority queues to manage character frequencies and constructs a binary tree (Huffman tree) to develop the encoding scheme for each character.

- **Python Proficiency:** Demonstrates strong Python programming skills, utilizing various libraries to implement advanced algorithms for both compression and decompression.

## How to Use

1. **Clone the Repository:** Start by cloning the repository to your local system.

   ```bash
   git clone <repository-url>
   ```

2. **Run the Huffman Tool:** To perform compression and decompression on the included sample text file (`sample.txt`), open your terminal and execute:

   ```bash
   python3 useHuffman.py
   ```

   - **File Outputs:** The tool will generate both compressed and decompressed versions of the `sample.txt` file in the same directory.

   - **Custom File Compression:** To compress a different text file, modify the path variable in the `useHuffman.py` file to point to your desired file.

## Future Enhancements

- **Improved Compression Options:** Future versions may explore additional compression algorithms for comparative analysis with Huffman coding.

- **Expanded File Format Support:** The tool could be extended to accommodate other file types, such as images and videos.

- **User-Friendly Graphical Interface:** Consider adding a graphical interface to facilitate easier file selection and manage compression and decompression processes.

---

