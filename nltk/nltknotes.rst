How the poster gets laid out::

  +-------------------+
  |        {T}        |
  |-------------------|
  |        {I}        |
  |    {1}     {2}    |
  |                   |
  | {3}    {4}    {5} |
  |-------------------|
  |        {F}        |
  +-------------------+

  {T}: Title
  {F}: Footer

{I} NLTK
--------

NLTK is a library for parsing and understanding natural language with Python.

{2} mail_scrape
---------------

the task: take a few thousand emails and try to figure out what they look like

the flow:

#. Move raw data from Access DB to CSV
#. Load data from CSV
#. <NLTK magic goes here>
#. Print out interesting information.

{4} Magic
---------

#. Tokenizing
   The first step is to take a block of text and split it into atomic tokens of words
#. Tagging
   These words can then be tagged by their part of speech.
#. Parsing
   These tagged tokens can be run through any number of NLTK functions to extract meaning
#. Classifying
   Take the parsed tokens and run them through a classifier to get deeper understanding of the text
#. Understanding
   Take the information from NLTK and extract the most useful bits for display to the user.
