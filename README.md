# NYT Article Grabber

Simple Python script that returns unicode plain-text from The New York Times. I have no clue how it contributes towards your monthly free article count. I didn't really think about that. Also, sometimes it doesn't work.

# Example
```python
import nyt

print(nyt.get_article_text("http://www.nytimes.com/2015/05/24/world/middleeast/with-victories-isis-dispels-hope-of-a-swift-decline.html?hp&action=click&pgtype=Homepage&module=first-column-region&region=top-news&WT.nav=top-news").encode('ascii', 'ignore'))
```

# Requirements
* Python 2.7+
* [requests](https://github.com/kennethreitz/requests)
* [BeautifulSoup4](http://www.crummy.com/software/BeautifulSoup/)

*Made at CodeDay San Francisco 2015*