# Automatic Punctuation
I'm not sure where I got this idea, but I think it's a pretty neat way to learn about LSTMs.

This is my thought process when I approached the problem.

I first have a corpus of text in which I eliminate all punctuation (including spaces).

My input vector is the individual characters of the corpus, and my output vector is a list of all the unique punctuation as well as one extra dimension for "no punctuation."

Let's see how this works out.
