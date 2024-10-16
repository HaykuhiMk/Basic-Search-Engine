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

- **Indexing:** The search engine can index all text files (.txt) within a selected folder. When files are indexed, the search engine reads the content, extracts individual words, and keeps track of their occurrence counts. Each word is stored in a dictionary with the file name and count information, allowing for quick and efficient searches.
- **Search Functionality:** The search engine allows users to input a search query consisting of one or more words. It performs a search on the indexed files and returns results showing the number of matches for each file. The results are displayed in order of relevance (files with the highest number of occurrences are shown first).
- **Graphical User Interface (GUI):** Built with Tkinter, providing an intuitive and responsive user experience. The graphical interface runs in full-screen mode by default but can be toggled using the Esc key. The GUI provides several widgets such as buttons, input fields, and text areas that allow the user to perform tasks like indexing files, searching, and viewing results in a user-friendly way.
- **View File Content:** The GUI also provides a feature where users can select an indexed file and view its content. This makes it easy for users to see the full text of files that match their search query, all from within the same interface.
- **Real-time Feedback:** Displays indexing progress and search status updates to keep users informed.
- **Error Handling and User Feedback:** The project includes robust error handling for scenarios such as invalid folder paths, non-existent files, and other common issues. It provides clear messages to the user when issues occur and ensures a smooth experience by giving feedback for each action performed (e.g., when files are successfully indexed or when no search results are found).

## Demo

![Search Engine GUI Screenshot](screenshots/gui_screenshot.png)

*Screenshot of the Basic Search Engine GUI showcasing the indexing and search functionalities.*

## Project Structure
- **search_engine.py:** This file contains the core logic for the search engine. It includes the BasicSearchEngine class, which handles file indexing and searching, and the WordInfo class, which stores information about occurrences of words in files. Users can search for keywords, and the search engine will return the text files where the words are found, along with a relevance score based on the number of occurrences.

- **search_engine_GUI.py:** This file contains the GUI implementation using Tkinter. The graphical interface allows users to easily index files, perform searches, and view the content of indexed files. It also provides options for full-screen mode and has interactive widgets for selecting files and displaying results.

## Usage

### Requirements
To run this project, ensure you have the following:

- Python 3.6+
- Tkinter (Comes pre-installed with most Python distributions)


Install any additional dependencies by running:

```pip install -r requirements.txt```

### Running the Search Engine
1. Clone the Repository:
  ```git clone https://github.com/HaykuhiMk/Basic-Search-Engine.git```

  ```cd ./Basic-Search-Engine/GUI-version```

3. Run the GUI:
   
  ```python3 main.py```



### Install Dependencies
The project uses standard Python libraries, so no additional installations are required. However, it's recommended to use a virtual environment.




