# Introduction
Description of the project

# Pseudocode
Put pseudocode in this box:

```
Some pseudocode here
```

# Successes
Description of the team's learning points

# Struggles
One of the struggles our team faced occurred when writing the `get_next_word()` function. Our initial plan was to have the function calculate all the probabilities, and then find the highest probability. It was originally going to choose the word with the highest probability as the next word, and randomize it if it was a tie. This became a problem when running the `generate_random_text()` function because certain phrases (Black fish, Blue fish, Black fish, Blue fish...) were getting stuck in a repeating loop since the same word was picked every time. We ultimately changed the function to select the next word randomly, weighing the probabilities, rather than always choosing the most likely next word. This gave lower probability words a chance of being selected, which resolved the infinite loop problem.

# Personal Reflections
## Group Leader
Group leader's reflection on the project

## Other member
Abby - I found this project to be very interesting and informative. I have no experience with these models, and especially after being sick during the lecture, I had a lot of ground to cover to feel okay working on these functions. I found the structures used for Markov models to be very interesting, with dicts of dicts, etc. It was difficult for me to understand the key-value pairs and lists needed for the generation of random text in the beginning, but after looking at what the function inputs needed to be, it made more sense. I was also confused by the seed=42 for a little while and had to ask Claude why 42 in order to understand that the random number gen seed just ensures the ability to reproduce data. 

# Generative AI Appendix
Claude was used to identify the use of the seed in the generate and next word functions. I asked, 'In the context of a Markov model, what is the function of a seed, and does the number have any significance? I learned that it is just to maintain randomness while keeping the ability to reproduce results.
