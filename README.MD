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
 - Run the program using `python main.py`
 - The program will automatically open and log into Achieve.
 - Open any Homework on the website, come back to the program, and give a name for it. The file will be saved accordingly. For example, if you input the name as `HW1`, then the file will be saved as `HW1.pdf`.
 - After giving a name, **make sure to open the website back. Else this will not work. The website needs to be in the foreground. The script can run in the background.**
 - By default, the program only logs the correct answers on the PDF (Bug Fixed). 
 - If you want to see all the mistakes you made in the PDF as well, then enable the `error_log` flag on top.
 - If your internet is slow and is not loading the images on time, try increasing the time limit on the top of the program.

## License
[MIT](https://choosealicense.com/licenses/mit/)
