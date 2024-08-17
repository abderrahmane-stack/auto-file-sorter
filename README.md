# Auto File Sorter

## Overview
`Auto File Sorter` is a Python script that automates the process of organizing files in a specified directory. It categorizes files into folders based on their file extensions (e.g., Documents, Images, Videos), making file management easier and more efficient.

## Features
- Automatically creates folders for different file categories (Documents, Images, Videos, etc.).
- Moves files into their respective folders based on file extension.
- Easy to customize by adding or modifying file types and categories.

## How It Works
1. Specify the directory you want to sort in the script.
2. The script will automatically create folders based on predefined categories.
3. Files in the directory will be moved to the appropriate folder based on their file extensions.

## File Categories
The following file categories and extensions are supported by default:

- **Documents**: `.pdf`, `.docx`, `.txt`, `.xlsx`
- **Images**: `.jpg`, `.jpeg`, `.png`, `.gif`
- **Videos**: `.mp4`, `.mkv`, `.avi`
- **Music**: `.mp3`, `.wav`
- **Archives**: `.zip`, `.rar`, `.tar`

You can easily customize these categories and extensions to suit your needs.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/abderrahmane-stack/auto-file-sorter.git

2.Navigate to the project directory:

  ```bash
  cd auto-file-sorter
```
### Usage
 1.Open the script file_sorter.py.
 2.Modify the directory variable to the path of the directory you want to sort.
 3.Run the script:
 ```bash
 python file_sorter.py
```
## Customization
To add or modify file categories and extensions, edit the file_types dictionary in the script. You can add more categories and specify additional extensions to suit your needs.
 ```
file_types = {
    'Documents': ['.pdf', '.docx', '.txt', '.xlsx'],
    'Images': ['.jpg', '.jpeg', '.png', '.gif'],
    'Videos': ['.mp4', '.mkv', '.avi'],
    # Add more categories here
}
```
Contribution
Feel free to fork this repository and contribute by submitting pull requests. Any suggestions or improvements are welcome!
