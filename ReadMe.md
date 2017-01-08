#Multi WP Blog Search

This is a simple experiment/test searching across multiple WordPress blogs.

[Multi WP Blog search](http://git.johnj.info/wp-sites-search/index.html)

It uses the [WordPress REST API](http://v2.wp-api.org/ "WP REST API v2 Documentation"). I guess you could use rss too as WordPress seems to provide feeds for searches. 

I've no idea if this is useful or not, google also does multi site searches. I guess it could be used to provide a search across multiple WordPress blog in one place. 

you can kick off a search on the page by adding a hash & the search term to the url:

`http://git.johnj.info/wp-sites-search/#twitter`

[http://git.johnj.info/wp-sites-search/#twitter](http://git.johnj.info/wp-sites-search/#twitter)

## Notes

BLOGURL/wp-json/wp/v2/posts/?search=needle&per_page=10

The REST API became available around wp 4.7

I am not sue I understand the x-domain and mixed content stuff



