# Motivation
Most modern tools have spellchecking features but don't come with words for none english languages 
or the supplied list of words is limited or incomplete.


# File types and syntax
Each list of words is stored in a `.dic` file.
The file contains one word on each line followed by a newline `\n` stored in `utf-8` text format.

To have the file well organized keep the lines sorted in alphabetical order ignoring case.


# Content
Every proper variation of a word is accepted including common acronyms. 
Abbreviations are allowed as well.
Names of continents and countries are included among the common words.
Names of persons, cities etc are not included in the common list of words.


# Organization
```
<root>
 + <language name in english>
   + common
   + technical
     + IT
     + <field of study>
 
```

