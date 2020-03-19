# NLP as a rest API

This a natural language processing Rest API that takes two string inputs from a user

and then uses the spacy NLP module for calculating the similarity between 2 strings with a rating from 0 to 1.

A user registers by entering a username and password. The user can now login and enter two strings. 

The user is then returned a json with the resultant similarity calculated using the spacy natural language processing 

module. Each time the user calculates a similarity a token is taken from him. If the user wants more tokens, he must

refill them
