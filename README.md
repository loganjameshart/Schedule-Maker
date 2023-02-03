# Schedule Maker
Scrapes an inputted link relevant to my work to create a Word document of upcoming events.

## How It's Made:

Python Standard Library. External Python libraries: python-docx, beautifulsoup4, pysimplegui, requests.

This was made to automate a bunch of link clicking, copy/pasting, and formatting to create a weekly schedule document. Even though the GUI takes any link as input, the program was written to scrape a very particular webpage from my work which displays a weekly schedule.

## Things I'd change

This was my first big use of BS4, so I'm sure there are more elegant ways of parsing than I used. A lot of decisions, however, were made to account for the "soup" that is the webpage's HTML layout.

