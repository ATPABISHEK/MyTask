# NEWS ARTICLE API
This project contains HTTP JSON API for news article
# Functionalities of this API:
## Create an article:
 Should be a POST request\
 Use JSON request body\
 URL to update articles ‘/articles’
## Get an article using id:
 Should be a GET request\
 Id should be in the url parameter\
 URL should be ‘/articles/<id here>’
## List all articles:
 Should be a GET request\
 URL to get articles ‘/articles’
## Search for an Article (search in title, subtitle, content):
 Should be a GET request\
 Search term should be in the query parameter with key ‘q’\
 URL should be ‘/articles/search?q=<search term here>’
 
# POST request for articles
 1. This should be post request\
 1. request should have body data as type JSON\
 1. each JSON should have following format:\
    1. {\
    1.  "title":\<article title as string\>,\
    1.  "subtitle":\<article subtitle as string\>,\
    1.  "content":\<article content as string\>\
    1. }\
 1. key names should not be changed and also they are case sensitive
