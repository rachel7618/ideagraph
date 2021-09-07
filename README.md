# ideagraph

The goal of this project is to implement the IdeaGraph algorithm for chance discovery (Wang et al., 2014).

The tweet dataset is not provided;
A stopword.txt file is created based on common stopwords and some climate-change-related words, as my project focused on climate change topics.

## GetTweets - Keyword.ipynb
It utilized code snscrape-python-wrapper from @MartinBeckUT

## LDA Model.ipynb
LDA Model was modified on my classmate Pournemat's code.

I added more filters to apply on tweets: emails, hashtags, numbers, and twitter user names.

## IdeaGraph.ipynb
IdeaGraph algorithm is bulit based on Wang et al.(2014).

**Visualization**

You need to install a copy of Graphviz (http://www.graphviz.org) to visualize IdeaGraph.

Easier way to do so is to copy and paste dot file here (https://visjs.github.io/vis-network/examples/network/data/dotLanguage/dotPlayground.html)

## Reference:
Beck, M. 2021, February 18. How to Scrape Tweets With snscrape. Medium. https://betterprogramming.pub/how-to-scrape-tweets-with-snscrape-90124ed006af.

Pournemat, M., & Weiss, M. 2021. Identifying business opportunities using topic modeling and chance discovery, 11.

Wang, H., Ohsawa, Y., Lv, P., Hu, X., & Xu, F. 2014. IdeaGraph: Turning Data into Human Insights for Collective Intelligence. In F. Sun, T. Li, & H. Li (Eds.), Foundations and Applications of Intelligent Systems, vol. 213: 33–44. Berlin, Heidelberg: Springer Berlin Heidelberg.
