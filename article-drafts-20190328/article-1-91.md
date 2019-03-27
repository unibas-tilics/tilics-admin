# Bayes Theorem: Updating Prior Beliefs With Data
One might argue that the standard reasoning process in our brains consists of two basic elements: 
The initial belief we have about a topic and the step of updating of this belief when we observe something new.
For example, we at first expect a deck of cards to be fair when playing a game of poker.
But after observing two straight flushes in a row, it is natural to believe that a fair deck is very improbable.

This basic notion of updating beliefs is mathematically formalized in the so-called Bayes' Theorem,
where the prior probabilities are updated to the 'posterior' probability when observing new evidence.
The theorem forms the basis of a wide range of methods in Statistics and Machine Learning 
and allows incorporating prior knowledge into models instead of only basing it on data.
We can for example include the notion that faces are rather symmetrical for face recognition, which ultimately allows us to train the model with fewer data.

However, if enough data that contradicts this assumption is observed, the model will still be able to ignore this potentially incorrect prior assumption.

## Optional
So even if we initially believe Computer Science to be about fixing Computers, learning more about it will surely change that.


##Author
Fabricio Arend Torres, 27-03-2019
