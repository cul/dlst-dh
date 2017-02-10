---
layout: project
title: "Roget Tools"
description: "A Python library for tracking broad semantic categories through bodies of text using the top-down hierarchical structure of Peter Mark Roget's Thesaurus"
link: "https://github.com/prpole/roget-tools"
author: Alex Gil
people:
- Phillip R. Polefrone
---

Following Klingenstein, Hitchcock, and DeDeo 2014)'s work on the "Old Bailey" records, Roget Tools is a Python library for tracking broad semantic categories through bodies of text using the top-down hierarchical structure of Peter Mark Roget's Thesaurus. These tools were derived from the 1911 index to and full text of the Thesaurus available from Project Gutenberg and were generated using 1. automated regular expression text extraction on the index and 2. reconstruction of the hierarchy represented by the headings of the full 1911 edition. This hierarchy is a comprehensive and unbroken network encompassing all of Roget's original thesaurus categories, and importing it into a Python-readable format allows an integration of network analysis techniques into the analysis of textual corpora.

With this integration in mind, the library opens up several methods of automated textual analysis. First, it enables Python-readable categorization of individual words at different levels of abstraction (i.e., specificity of semantic categorization). It also allows the user to return the full hierarchical path of all a given word's categories to the top of Roget's taxonomy, simultaneously measuring the path length. In addition to being applicable to individual words, both of these methods can be automatically applied to large samples of text, replacing words with their semantic categories. Roget Tools can also return the distance (in network edges) between any two words in the Thesaurus or any two nodes in the hierarchy. (See Jarmasz and Szpakowicz (2012) on the relevance of this measure.) Finally, given a text---be it a list of randomly selected words, a portion of a literary text, or part of the output from a topic modeling algorithm---the Roget tools can return the node or nodes that most accurately represent that text's semantic character; this representativeness is measured as the minimum average distance in edges from each word in the list to the selected node.