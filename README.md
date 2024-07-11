# LinguaDoc 🐍🤖📄

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.11-blue.svg)
![PySide6](https://img.shields.io/badge/PySide6-6.7.2-green.svg)
![Python](https://img.shields.io/badge/pydocx-0.9.10-red.svg)


LinguaDoc is a Python-based desktop application built using PySide6 and BasicLingua. The application provides translation functionalities and document generation features with a focus on efficient async operations.

## Features ⚓

- **GUI**: Utilize `PySide6` for the graphical user interface.
- **Translation Functionalities**: Utilize `BasicLingua` for language translation.
- **Document Generation**: Generate documents efficiently with `pydocx`.
- **Concurrent execution**: Perform tasks asynchronously for better performance with `threading`.


## Table of Contents

- [How LinguaDoc works](#how-linguadoc-works)
- [Installation](#installation)
- [Usage](#usage)
- [Snapshots of the application](#snapshots-of-the-application)
- [Contributions](#contributions)

## How LinguaDoc works
By clicking on the Text Translation, users are taken to a page where they can input the API key required for initializing the BasicLingua library . This key is essential for accessing and utilizing the library's feature of Text Translation. Upon accessing the page, users are prompted to obtain an API key from [here](https://aistudio.google.com/app/apikey) for the initialization of the BasicLingua library.

## Installation
The application has been bundled into a setup file, allowing you to install and run it locally without needing to have Python installed on your machine. This ensures that our non-coder friends can also use the application with ease.

You can download the setup file from the following link:

[Download Setup File](https://mega.nz/file/qNE3kBDQ#Gc5uFAxA4o-Nk96WDkebOk4aUWR4JtIuguYlrQpMeus)

### Prerequisites

- Python 3.11
- pip (Python package installer)

### Steps

1. **Clone the repository**:

    ```sh
    git clone https://github.com/yourusername/LinguaDoc.git
    cd LinguaDoc
    ```

2. **Create and activate a virtual environment** (optional but recommended):

    ```sh
    python -m venv venv
    cd venv\Scripts\activate
    ```

3. **Install the required packages**:

    ```sh
    pip install -r requirements.txt
    ```

## Usage
**Run the application**:
        
```sh
python LinguaDoc.py
```
    
## Snapshots of the application
    
<p align="center">
      <img src="Images/Screenshot (282).png" width="400">
      <img src="Images/Screenshot (283).png" width="400">
</p>

## Contributions
We are excited to receive contributions! Please refer to our [CONTRIBUTIONS.md](https://github.com/Minty-cyber/LinguaDoc/blob/main/CONTRIBUTIONS.md) for comprehensive steps on submitting pull requests to the project.
   
