# pytrends.py #

pytrends.py is an extension module for feeding trendy words in the world. It will collect them from resources automatically and provide the words what you want.

# You need the other modules for it #

[BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/)

# Rework Order #

**Output format
  * 1 sentence (1 trend) is joined by " " or "-"** Resources
  * For a moment, it is only Google Trends. We need more and more...


# Sample #

```
$ python
>>> import pytrends
>>> list = pytrends.get_words()
>>> list
[u'best', u'actress', u'winner', u'2010', u'sunan', .... ]
>>>
```