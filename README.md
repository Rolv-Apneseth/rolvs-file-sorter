# file-sorter

Program with a gui which allows you to sort a chosen folder by file type or by date into automatically generated folders, and then also undo the folders if necessary.

## What I learned

- File i/o
- Building GUI's using tkinter
- Error handling
- Use of OOP
- Combined use of the datetime and os modules for sorting files based on the time since it was modified

## Installation

1. Requires python 3.6+ to run. Python can be installed from [here](https://www.python.org/downloads/)
2. To download, click on 'Code' to the top right, then download as a zip file. You can unzip using your preferred program.
   - You can also clone the repository using: `git clone https://github.com/Rolv-Apneseth/file-sorter.git`
3. Install the requirements for the program.
   - In your terminal, navigate to the cloned directory and run: `python3 -m pip install -r requirements.txt`
4. To run the actual program, navigate further into the file-sorter folder and run: `python3 main.py`

## Usage

1. Select which folder you would like sorted (or unsorted if it is already sorted). To do this, click on Select a folder to open a filedialog menu.
2. Select a sort type by clicking on the sort type dropdown.
   - File Type sorts files into folders based on their file types i.e. all image files into one folder, executables into another etc.
   - Date will sort files into the folder structure of Year/Month which it was last changed in
   - If date is selected, you will also be prompted to write the earliest year you want a folder for. Please note that this can therefore create an excessive amount of folders.
3. Click on sort files to execute the script

To undo the created folders and move the files back into the chosen sort folder, simply click on the Reset folder button (but make sure that the exact same options, such as sort type, are still selected).
