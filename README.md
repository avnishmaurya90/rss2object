# rss2object
Converts a RSS feed URL into JSON format.

It covers all tags listed under RSS Feed including required and optional too.

var converter = require('rss2object);

converter.url2Object(rssUrl, function(err, json){
console.log(json);
});


