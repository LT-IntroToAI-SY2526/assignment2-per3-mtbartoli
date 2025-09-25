# Assignment 2 - Write UP

## Description
This assignment is about learning and applying the while loop and iterating through multiple lists at a time.  We also will discuss how we match things in chatbots in order to extract what a user is trying to find.  Next assignment we will work with data bases and how we can extract information from them.

## What to complete
1. Go through the notes.py file w/ Mr. Berg
2. Complete `a2.py`, Mr. Berg will walk everyone through the process
3. Make sure you pass all asserts in `a2.py`
4. Complete the reflection problems below
5. Push your code to github for grading

## Reflection Questions
1. What was difficult for you while completing the match function?

The % wildcard was confusing at first because it can match zero or more words and it depends on what the next word is


2. Explain how you could use the match function for extracting information from a movie database.

with patterns and the match function you can extract the movie name or details. Such as

movie_entry = ["The", "Godfather", "1972", "Crime", "Drama", "Francis", "Ford", "Coppola"]

ectracting the directors name:

pattern = ["%", "_", "_", "Coppola"]
match(pattern, movie_entry)
returns Fancis, Ford

"%" = match any sequence "_" = a word