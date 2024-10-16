# Basic Search Engine

This project implements a simple text-based search engine using Python. It indexes text files and allows users to search for words within those files, displaying the relevance based on the frequency of occurrence. The search engine mimics a basic search functionality by indexing files in a specified folder and then allowing users to search for words in those files.

## Table of Contents

### ~ Features
### ~ Technologies Used
### ~ Project Structure
### ~ Class Descriptions
### ~ How to Run
### ~ Contributing

## Features
**File Indexing:** Indexes text files from a specified folder, storing the frequency of each word in each file.

**Search Functionality:** Allows users to search for words and displays the relevant files sorted by word frequency.

**View Indexed File Content:** Users can view the content of indexed files directly.

**nteractive Menu:** Provides a simple menu interface for users to navigate through different options.

## Technologies Used
**Python:** The project is written entirely in Python, utilizing core libraries such as os and re for file management and regular expressions.

## Project Structure
**search_engine.py:** Contains the core functionality for the search engine, including indexing files, searching for words, and displaying results.

**search_engine_utils.py:** Provides the user interface and manages the interaction with the BasicSearchEngine class.

**WordInfo:** A helper class that stores information about a word’s occurrence in a file, including the file name and count.

## Class Descriptions
**BasicSearchEngine:**

Manages file indexing and search functionality.
Uses a dictionary to store indexed words and their associated WordInfo objects.
**WordInfo:**

Represents the frequency of a word in a specific file.
Contains attributes for the file name and word count.
## How to Run
### Clone the Repository:
**git clone https://github.com/your-username/basic-search-engine.git
cd basic-search-engine**
