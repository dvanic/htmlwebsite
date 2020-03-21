# Building this blog
For the last ~2 years, I ran [www.daryavanichkina.com](www.daryavanichkina.com) with a custom Wordpress + MediaWiki install, which together gave me excellent control over content and presentation (albeit within available Wordpress templates) and very, very sophisticated wiki tools. 

There were problems, though, most notably:

- the necessity to maintain and regularly update Wordpress and its plugins
- the rather tedious and buggy process of backing up Wordpress and MediaWiki databases
- the slow loading speeds that I experienced, given that the site was content-rich, I was hosting it on HostGator, the servers of which are in the US, which meant it took forever to load from Australia
- finally, I know WordPress isn't secure, and while I feel that I'm too small a fish to be interesting for an attacker, the rational side of my brain knows that this isn't really a good point of view (I've always been a "better safe than sorry" kind of person, so it didn't make sense to forgo this attitude online).

I was attracted by the opportunity to host everything on github pages (I'm a PhD student, so any chance to save $$$ is useful), and the simplicity and beauty of blogging with something as concise and clean as jekyll - especially when I saw [this website](http://seananderson.ca/ "http://seananderson.ca/"), which was promptly bookmarked as "BeautifulWebsite".

And thus began 2 weeks of googling, scouring blog posts and StackOverflow, debugging and learning a whole bunch of stuff in the process.

The first blog post I found with details on how to configure a Jekyll site was [this one](http://www.smashingmagazine.com/2014/08/01/build-blog-jekyll-github-pages/ "http://www.smashingmagazine.com/2014/08/01/build-blog-jekyll-github-pages/"), where you fork a pre-built jekyll package called Jekyll Now. I set it up to the point of being able to run on [www.dvanic.github.io] (www.dvanic.github.io "www.dvanic.github.io"), and serving it up locally on my machine. The other great thing about this post is that it features a link to [http://prose.io/](http://prose.io/ "prose"), a nice interface to edit and commit to Github repos from the browser; I've got several computers, and I want to be able to edit blog posts on all of them, including Windows boxes where I don't have git set up.

After feeling a bit more comfortable with Jekyll, its directory structure and logic, I started looking for themes. From the outset, I knew I wanted to start with a pre-built [theme](http://jekyllthemes.org/ "http://jekyllthemes.org/") for my site and then customize it, since I'm not a designer, and, frankly speaking, I've got little interest in spending time musing over colours, fonts, and golden ratios. After forking a bunch of repositories, and playing with them, I ended up going with [Lanyon](http://lanyon.getpoole.com/ "http://lanyon.getpoole.com/"), a theme built on top of [Poole](http://getpoole.com/ "http://getpoole.com/"). 

Josua Lande has written a [wonderful post](http://joshualande.com/jekyll-github-pages-poole/ "http://joshualande.com/jekyll-github-pages-poole/") on configuring his blog with Lanyon, and that was the next resource I used. 




http://joshualande.com/jekyll-github-pages-poole/ 