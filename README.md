# security-data-sources

The crawler is part of a project for analyzing security data sources. We only download and save the article in our database if a valid CVE identifier is contained in the content of the article.

The real project is on https://git.uibk.ac.at/c7031099/security_data_sources and is private.
This README is merely intended to give information about the crawler.

## Settings
* Politeness delay: Generally we use a politeness delay of 20 seconds unless you have another Crawl-Delay set in your `robots.txt`.
* Underlying implementation: `Crawler4j` (https://github.com/yasserg/crawler4j)
* Crawl binary content: off
* Filter: css|js|bmp|gif|jpe?g|png|tiff?|mid|mp2|mp3|mp4|wav|avi|mov|mpeg|ram|m4v|pdf|rm|smil|wmv|swf|wma|zip|rar|gz

## Contact

If there are any problems then please contact me in the following way:

* E-Mail: thomas[dot]tschol(at)student[dot]uibk[dot]ac[dot]at
