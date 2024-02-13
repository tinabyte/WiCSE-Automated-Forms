# WiCSE-Automated-Forms

## Dependencies
Download Chrome Driver: 
https://chromedriver.chromium.org/downloads

Download Selenium
Mac: Brew install selenium
or try: pip install selenium

## How to use the python files

Modify the following code in the file

```python
str = """

Event Title Name

Date: Jan, Feb, March, April, May... shortened month names -> ex: Jan 15

Time: #PM - #AM

Location: Any location here

Details: Details of the events here

Attendees: #
"""

myEmail = 'yourEmail@mail.com'

myName = 'Your Name'

path_to_chromedriver = 'the absolute path to your chrome driver'
```

Here is an example I use, make sure to follow format in order for it to run