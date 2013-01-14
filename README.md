twar
====

A very stupid command line tool for archiving the tweets in a Twitter
search result. Twitter search results live for a week or so, and are highly
volatile. Results are stored as line-oriented JSON (each line is a
complete JSON document), and is exactly what is received from the Twitter API. 

How To Use
----------

1. pip install -r requirements.txt
1. cp config.py.example config.py
1. add twitter api credentials to config.py
1. ./archive.py aaronsw
1. cat aaronsw.json
1. :-(


