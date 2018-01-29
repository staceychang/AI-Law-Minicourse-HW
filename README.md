# AI-Law-Minicourse-HW

**Homework**

_I. Supreme Court Topic Modeling_
1. Step one: Beautiful soup grabber is being used to create a data structure so that commands can be applied to the data. This first step is using beautiful soup grabber to pull URLs from the site. 
2. Step two: The code is searching for searchable-content that will be added to the table; the three (test, test2, test3) are combined in full_project to create a pickle file, which is named pull_proj_preproc.pickle.
3. Step three: Stop words are being generated; the code is told that certain words are to be ignored because they are common, state names, or are female/male names. The STOPLIST at the bottom combines all the lists of homespum/names. The stoplist is applied.
4. Step four: SKlearn is being imported to be applied on the pickled full_proj. The code is given a number of topics and topic words (set at 30) with features of a maximum and minimum df. 
5. Step five: the nmf_mod is given factors such as the number of topics, features, and top words.
