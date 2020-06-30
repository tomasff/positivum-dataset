# Positivum news articles dataset

This dataset consits of 27317 news articles headlines which were collected via RSS feeds and
automatically classified with a `Positive/Neutral` or `Negative` sentiment when the
[Positivum](https://github.com/tomasff/positivum) project was available online.
More information about how the articles are collected is available in the repository [here](https://github.com/tomasff/positivum).

CSV header explanation:
* `title` - headline provided by the publisher
* `url` - URL of the article (which may no longer be used by the publisher)
* `date` - date of publication
* `classication` - sentiment classification (1 -> Positive/neutral, 0 -> Negative)
* `publisher` - author/publisher of the article

In this dataset, an article with a negative sentiment means that its
headline might be related to controversy, sadness, hate, violence, discrimination, etc.

Each article's classification was automatic and does not represent my views.

## Legal
News article's headlines marked as published by:
* "BBC" belong to [© BBC](https://www.bbc.co.uk/)
* "The Guardian" belong to [© The Guardian](https://www.theguardian.com/)
* "CNN" belong to [© CNN](https://edition.cnn.com/)

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Dataset" property="dct:title" rel="dct:type">Positivum News Articles Dataset</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://tomff.com" property="cc:attributionName" rel="cc:attributionURL">Tomás F.</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.