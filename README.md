# Bookmarklet

Bookmarklet is a collection of practical bookmarklets, which enables quick access by simply dragging and dropping it to the bookmark bar.

## Backlink Checker

Use Ahrefs' backlink checker tool to query the backlinks of the current page.

[ahrefs backlink-checker](javascript:(function(){    var url=location.href;    var url=url.replace(/^(http|https):\/\//i,'');    window.open('https://ahrefs.com/backlink-checker/?input=%27+encodeURIComponent(url))})();)