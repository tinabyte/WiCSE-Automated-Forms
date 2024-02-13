# WiCSE-Automated-Forms

## Dependencies
Download Chrome Driver: 
https://chromedriver.chromium.org/downloads

Download Selenium
Mac: Brew install selenium

Windows: pip install selenium

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

```python

str = """
Data Science Workshop Classification

Date: Feb 13

Time: 4PM - 5PM

Location: Matherly 0018 

Details: Rida will covering Classification. I’ll be going over the concept as well as having live coding for the attendees to work on

Attendees: 30
"""

```

## Other things to note
(These files are messy, sorry in advance 😭)
How to use, download the files, and run it specfic to your needs. For example, if you want to make a room reservation. Download roomReservationForm.py and replace the str, email, and chromeDriver location and run the file. 

For the postRequest, you must input the AM and PM, and instagram caption manually... I couldn't get emojis to work 💔

The submit button is commented out, but if you feel confident enough that the code works to your intent, uncomment it out and it will auto submit. (room reservation)