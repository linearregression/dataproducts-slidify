---
title       : Simple text sentiment analysis
subtitle    : Opionionated
author      : Ling Long WeWa
job         : Sentiment Analyst
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
logo        : []
---

## Problem

A simple app that performs simple sentiment analysis for text. User enter their text for analysis. A positive number is a postive sentiment. Number magnitude denoted the degree.
Mechanism is to match words form sentence against bags of prelablled words that indicates postive and negative sentiments.
Prelabbled sentiment words found http://www.cs.uic.edu/~liub/FBS/opinion-lexicon-English.rar.

---

## Proposed Solution

User enter a sentence. The sentence is tokenised inwot list of words forming a word vector. This vector then matches against the "positive sentiment" word vector and negative word vectors from the prelabelled dataset.

----
# Sentiment Score

Score is count as how many words found from positive sentiment grup and how many not found from negative sentiment group.

---

## Submitted Solution

So to find out sentiment for text "I love you", enter the text I love you,
in Sample Text box. Then a score will shows on righ hand side.


---
## Application

This can be used to help identify public opionin on branding. Sentiment analysis can be used on Tweets.

## Thanks you.


