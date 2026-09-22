# Introduction


# Pseudocode
Put pseudocode in this box:

```
Some pseudocode here
```

# Successes
Description of the team's learning points

# Struggles
One of the struggles our team faced occurred when writing the get_next_word() function. Our initial plan was to have the function calculate all the probabilities, and then find the highest probability. It was originally going to choose the word with the highest probability as the next word, and randomize it if it was a tie. This became a problem when running the generate_random_text() function because certain phrases ("Black fish, Blue fish, Black fish, Blue fish...") were getting stuck in a repeating loop since the same word was picked every time. We ultimately changed the function to select the next word randomly, weighting the probabilities, rather than always choosing the most likely next word. This gave lower probability words a chance of being selected, which resolved the infinite loop problem.

# Personal Reflections
## Group Leader
Group leader's reflection on the project

## Other member
Other members' reflections on the project

# Generative AI Appendix
As per the syllabus
