# Activity
The learning objectives and cheat sheet are written in code. Do not panic and do not be intimidated. You'll notice that everything after a # is written in plain, normal English (in fact, you may even be able to guess what some of the Python commands, such as 'import' do). Hashtags are used in Python to write comments to yourself and others who might read your code. They do not effect the instructions that the computer receives and are used to remind you or explain to another what your code is meant to achieve. Contrary to popular myths perpetrated by Hollywood films, code does not fly off the fingers of talented techies. It's a slow, often collaborative process. Absorb the learning objectives below and observe the relationship between code and the comment following the hash. When you feel sufficiently enlightened, move on to the challenge proper.      
##Learning objectives for challenge!
```python
import nltk #import nltk into the Jupyter Notebook

from nltk.book import * #import the example corpora from nltk

text2 #what a variable is and how to "call" one

text2.concordance("any_word") #show every instance of a word in context

text2.collocations() #most common words that appear repeatedly together
```

####BONUS!!
```python
text1.similar("any_word") #words distributed similarly in the text
text1.count("any_word") #counts occurrences of word
text1.common_contexts(["this_word", "that_word"]) #common contexts of words
```
####TIPS
- press "Tab" while typing a command to auto-complete
- press "Shift" + "Enter" to run your line of code
