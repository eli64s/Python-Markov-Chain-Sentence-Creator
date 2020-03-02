# Python Markov Model Sentence Generator 
This notebook generates random sentences using a Markov chain stochastic model. This model takes one user-defined vocabulary word input and then generates its synonyms using the Natural Language Toolkit module. The training data for this model is a collection of example sentences (sentences are composed of the synonyms or user-defined word) obtained from a vocabulary API.

This notebook can be divided into four sections:
- One user-defined vocabulary word input, used to generate synonyms via the Natural Language Toolkit module
- The training data is created, collecting sentences composed of the input word's synonyms from a vocabulary API 
- The training data is fed to the Markov chain model function
- Random sentences are generated

I hope to improve this model over time by refining the data inputs for the model, and eventually look to include this script as a module in my [Vocabulary Flashcard Web-Application](https://github.com/eli64s/Django-Flashcard-Web-App). Feel free to ask questions and suggest areas of improvement!
