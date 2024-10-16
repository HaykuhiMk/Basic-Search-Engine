# Basic Search Engine with GUI

This project is a Python-based Basic Search Engine that provides functionality for indexing and searching through text files. It includes a graphical user interface (GUI) built with the Tkinter library, which allows users to easily interact with the search engine through an intuitive and simple interface. The project is divided into two main components: the search engine logic implemented in Python (search_engine.py) and the graphical interface (search_engine_GUI.py).

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Indexing:** Efficiently indexes all `.txt` files within a selected directory, tracking word occurrences in each file.
- **Search Functionality:** Allows users to search for multiple words simultaneously and retrieves relevant files sorted by relevance.
- **Graphical User Interface (GUI):** Built with Tkinter, providing an intuitive and responsive user experience.
- **View File Content:** Users can view the full content of any indexed file directly within the application.
- **Real-time Feedback:** Displays indexing progress and search status updates to keep users informed.

## Demo

![Search Engine GUI Screenshot](screenshots/gui_screenshot.png)

*Screenshot of the Basic Search Engine GUI showcasing the indexing and search functionalities.*

## Project Structure
- **search_engine.py:** This file contains the core logic for the search engine. It includes the BasicSearchEngine class, which handles file indexing and searching, and the WordInfo class, which stores information about occurrences of words in files. Users can search for keywords, and the search engine will return the text files where the words are found, along with a relevance score based on the number of occurrences.

- **search_engine_GUI.py:** This file contains the GUI implementation using Tkinter. The graphical interface allows users to easily index files, perform searches, and view the content of indexed files. It also provides options for full-screen mode and has interactive widgets for selecting files and displaying results.

## Installation

### Prerequisites

- **Python 3.7 or higher**: Ensure that Python is installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

### Clone the Repository

```bash
git clone https://github.com/HaykuhiMk/Basic-Search-Engine.git
cd basic-search-engine```

### Install Dependencies
The project uses standard Python libraries, so no additional installations are required. However, it's recommended to use a virtual environment.


