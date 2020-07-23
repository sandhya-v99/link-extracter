# link-extracter

This is a set of programs that emulate some of the functions of a Search engine. They
store their data in a SQLITE3 database named &#39;spider.sqlite&#39;. This file can be removed at
any time to restart the Process.

This program crawls a web site and pulls a series of pages into the Database, recording
the links between pages.

In this program, we crawl a website and retrieve specified number of pages. If you
restart the program again and tell it to crawl more pages, it will not re-crawl any pages
already in the database. Upon restart it goes to a random non-crawled page and starts
there. So each successive run of spider.py is additive.
 
