# Achieve Automator

Automatically make PDFs from Achieve HW Questions.

## Installation

Clone the repo and install all the requirements using

```bash
pip install -r requirements.txt
```

## Usage
 - Make sure you are using Google Chrome. Download and install Selenium Webdriver based on your Google Chrome Version from [here](https://chromedriver.chromium.org/downloads)
 - Set the path in the program.
 - Run the program using `python main_docx.py` to generate a WORD Document (**PREFERRED**).
 - Run the program using `python main_pdf.py` to generate a PDF Document.
 - The program will automatically open and log into Achieve.
 - Open any Homework on the website, come back to the program, and give a name for it. The file will be saved accordingly. For example, if you input the name as `HW1`, then the file will be saved as `HW1.pdf`.
 - If you wish to save it in a folder, make a new folder in the root directory and enter the `directory_name/doc_name` for the Quiz Name. For example, if you had a folder called *MyDocs* and wanted to save *HW16* inside it, enter `MyDocs/HW16` as the name of the Quiz on the CLI. 
 - After giving a name, **make sure to open the website back. Else this will not work. The website needs to be in the foreground. The script can run in the background.**
 - By default, the program only logs the correct answers on the PDF (Bug Fixed). 
 - If you want to see all the mistakes you made in the PDF as well, then enable the `error_log` flag on top.
 - If your internet is slow and is not loading the images on time, try increasing the time limit on the top of the program.

## License
[MIT](https://choosealicense.com/licenses/mit/)
