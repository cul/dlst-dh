---
layout: project
title: Macro-Etymological Analyzer
description: A command-line application computing the proportion of origin languages for all the words of a given text, helping quantify stylistic properties that are potentially revealing about the text and its rhetorical modes.
link: "http://jonathanreeve.github.io/macro-etym/"
img: macro-etymological.jpeg
author: Alex Gil
people:
- Jonathan Reeve
teams:
- Group for Experimental Methods in the Humanities
---

The English language has continually borrowed from foreign languages—close to 30% of modern English words are descended from French, and another 30% are from Latin. These words are often concentrated in semantic frames associated with their origin languages—legal vocabulary contains a preponderance of words of French origin, and the vocabulary of the natural sciences contains many words of Latin and Greek origin. The etymology of words in a text, therefore, may be suggestive of its context, genre, or its level of discourse. Should a writer choose the Latinate term “masticate” over the Anglo-Saxon term “chew,” for instance, one might assume a scientific context or a high level of discursive formality. By computing the proportion of origin languages for all the words of a given text, we may quantify stylistic properties that are potentially revealing about the text and its rhetorical modes. [The Macro-Etymological Analyzer](http://jonathanreeve.github.io/macro-etym/) is a Python command-line application written by Jonathan Reeve that serves this purpose. The program will run a frequency analysis on your text, look up each word using the Etymological WordNet, then tally the words according to origin language family.
