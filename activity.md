# Challenge!

1. **Install Python:** The first thing you will need for the challenge is to download Python. The easiest way to do it is to download [Anaconda](https://www.continuum.io/downloads). It's free.


2. **Install NLTK:** Once you've installed the suite of tools that come with Anaconda \(which includes the [Jupyter Notebook](http://jupyter.org/)\), follow these [instructions](http://www.nltk.org/install.html) to install NLTK. Next, open the Jupyter Notebook on your machine and you are already to attempt the challenge.


> The learning objectives and cheat sheet are written in code. Don't panic. You'll notice that everything after a \# is written in plain, normal English \(in fact, you may even be able to guess what some of the Python commands, such as 'import', do\).

## Learning objectives

```python
import nltk #import nltk into the Jupyter Notebook

nltk.download() #download the nltk data into the Notebook

from nltk.book import * #import the example corpora from nltk

text2 #what a variable is and how to "call" one

text2.concordance("any_word") #show every instance of a word in context. 

text2.collocations() #most common words that appear repeatedly together

#Use text5, text7 and text8. Call the text, then investigate the use of gendered language in the texts e.g. he, she, women, lady, man, etc...
```

* Hashtags are used in Python to write comments to yourself and others who might read your code. They do not affect the instructions that the computer receives and are used to remind you or explain to another person what your code is meant to achieve.


* Absorb the learning objectives above and observe the relationship between code and the comment following the hash. When you feel sufficiently enlightened, move on to the challenge proper.

#### BONUS!!

```python
text1.similar("any_word") #words distributed similarly in the text
text1.count("any_word") #counts occurrences of word
text1.common_contexts(["this_word", "that_word"]) #common contexts of words
```

#### TIPS

* press "Tab" while typing a command to auto-complete
* press "Shift" + "Enter" to run your line of code



