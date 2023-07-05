# words-to-sentence
/n Welcome to my first original mid-sized project. I hope I'm not biting off more than I can chew./n

When this program is executed, the user will be asked to provide three of their 'favourite' verb, noun, and adjective.
These three words will need to be separate by a comma (and, a space).
Conditions will be set on the words such that they can be added to a sentence and make sense.
At time of writing, I'm not sure if I will cheap out and simply put length requirements on the words, or if I will add additionals.

This project will have a few phases. This version will simply accept a noun, verb, and adjective in order, and have a dictionary of potential sentence structures (## How will I create many many sentence structures?) which the three words fit into.


Potential future requirements on the words include:
    a) Must be a proper English word ##contrast with dictionary?
    b) Lose the requirement for a noun, verb, and adjective
        Alternately, just add a check/proof of noun/verb/adjective?
    c) Others?

Potential future structure, function of this program:
    a) NLP to evaluate words and create sentences
    b) Random mixing, correcting of inputted words
    c) Enforced criteria

I'll approach this project with this strategy:

USER INPUT CODE 
    1. I will request input from the user.
    2. I will split, clean up, and check the words.

SENTENCE FORMATTING CODE
    1. Create a dictionary (## as above, how?) containing various random sentences, with open spots for the noun, verb, and adjective.
    2. Create a function to randomly pre-select one of the sentence structures, each time this program is run (## or maybe, every time three words are inputted? Should this program run continuously until terminated?)

ASSEMBLING THE NEW SENTENCES
    1. Create function to insert the user-inputted words into the pre-selected sentence structure.
        1.a) Map the words to their type (i.e., user's noun goes to the noun spot)
