# DSA-HW01
# Sorted Linked List Integer Processor

## Overview

This project reads integers from an input file, inserts them into a sorted linked list while avoiding duplicates, and writes the sorted unique integers to an output file.

## Files

- `main.py`: Contains the implementation of the `Node` class, `SortedLinkedList` class, and the `process_file` function.

## Usage

1. Ensure your input file is in the correct directory.
2. Run the script:
    ```python
    input_file_path = "./sample_inputs/sample_02.txt"
    output_file_path = "./sample_results/sample_02.txt"
    process_file(input_file_path, output_file_path)
    ```
3. The sorted unique integers will be written to the specified output file.

## Code Explanation

- **Node Class:** Represents a node in the linked list.
- **SortedLinkedList Class:** Maintains a sorted linked list and prevents duplicates.
- **process_file Function:** Reads integers from an input file, inserts them into a sorted linked list, and writes the sorted unique integers to an output file.
