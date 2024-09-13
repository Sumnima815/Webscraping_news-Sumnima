# Automated E-Paper PDF Downloader

This project automates the process of downloading PDF files from a newspaper website using Selenium WebDriver. It opens the e-paper site, finds the available PDF links, opens them in new tabs, and downloads them to a specified directory.

## Table of Contents

- Features
- Installation
- Usage
- Issues
  
## Features

- Automatically navigates to the specified newspaper e-paper website.
- Finds and opens PDF links in new tabs.
- Downloads PDFs to a specified folder.
- Handles errors like missing elements or timeouts during the download process.


  

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/epaper-downloader.git

2. Installing the necessary Python dependencies:

   pip install selenium

3. ChromeDriver must be installed initallay and has to be added to systems path.

4. Setting up the folder where the downloaded pdf will bw stored.

## Usage 
To run the script:

Open the notebook or convert it to a Python script.
Call the job() function to start the automation:

job()

The PDFs will be downloaded to the NewsToday folder in current working directory.

## Issues
Common issues that may arise:

ChromeDriver version mismatch: Ensure that the ChromeDriver version matches your installed Chrome browser version.

Timeouts: If the website is slow, you may need to increase the waiting time for elements to load.




   
