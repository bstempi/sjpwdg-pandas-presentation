Intro
=====

This is a presentation that I put together for the [South Jersey Python and Web Dev Group](https://www.meetup.com/South-Jersey-Python-User-Group/) to introduce Pandas.

Structure
---------

This section describes the files that are included in this presentation.

### Slide Deck

The slides are stored in `pandas-karate.md`.  I used a program called [Deckset](https://www.decksetapp.com/) to render the presentation.

Any and all images that appear in this repo are part of the slide deck.

### Example Notebooks

I've included several notebooks that are referenced in the slides.  During the presentation, I will be running Jupyter Lab in order to host these notebooks so that people can access them.

In order to install Jupyter Labs, Pandas, and the other supporting libraries, simply run `pip3 install -r requirements.txt`.  This project assumes you have Python 3 installed.

### Example Data

`new-jersey-crime.csv` was taken from the FBI UCR dataset.  In this case, we got data for [New Jersey by city](https://ucr.fbi.gov/crime-in-the-u.s/2016/crime-in-the-u.s.-2016/tables/table-6/table-6-state-cuts/new-jersey.xls).  I've adapted the spreadsheet to remove some of the labels and exported it as a CSV file for ease of use.