README
======

Quickstart
----------

I know you're impatient. So am I. Here you go!

### Get the Code

Either ownload the current version from [github][gitdl] or [bitbucket][hgdl] or you check out the source code from [bitbucket][hg] or [github][git].

#### hg

	hg clone https://bitbucket.org/bobschi/html5-jekyll-template

#### git

	git clone git://github.com/bobschi/html5-jekyll-template.git
	
#### Run it

Now just navigate to the new directory in the shell of your choice, and execute jekyll.

	cd html5-jekyll-template
	jekyll

Now start work! ;)

Why?
----

Some of you may now my [HTML5-Boilerplate-Jekyll-Template][html5jbp] which was, like it's name, hastely thrown together when I wanted to get my [blog][] up and running. It was quick and dirty. And it didn't really work out all too well for me. I never learned how to use the included tools. Looking at the code was a great learning opportunity, but it was simply too much for me. I never liked using tools like SASS oder LESS, and there were too many assumptions included about what I was going to use (jQuery, Google Analytics, etc.). By no means HTML5Boilerplate is bad. It is a great community effort. It is a great tool if you know how to use it. But it is not what I need. It is a swiss army knife, when all that I needed was a hammer.

What?
-----

This is a starting point, with some basic templates and code in place to make your life easier. HTML5 and CSS3 compliant, as there's not much that could create trouble. Mind you: This is a *starting point*. You will have to add to it. I will share another version of this soon, which will include Foundation, #grid and Disqus, as I have decided to redesign my blog using those tools.

License
-------

Shared under [The Unlicense][unlicense]. See `LICENSE.md`. Basically, do whatever you want with it. Have fun. Share. Create. Be awesome.

Thanks
------

A special thanks to [Markus "Cypher" Prinz][Cypher] who brought me to Jekyll and Github Pages in the first place.

A shout out to Vito Botta for his blog post [Migrating from Wordpress to Jekyll - Part 2: **Everything** you need to know about Jekyll][migratewpjekyll] -- I've found some pretty helpful  hints in there.

Thank you [Paul Irish][paulirish] and the numerous commiters to the [HTML5 Boilerplate][boilerplate] project on [github][boilerplaterepomem] -- you guys are awesome.

Another shoutout to [Jacques Fortier][jqf] for his [postmore][] plugin!

Find Your Way Around
--------------------

Those are the basic folders you will normally set up for jekyll, your basic page and your posts and content, and some of the basic resources you will need.

	+-- _includes
	|   `-- FILLME
	+-- _layouts
	|   |-- default.html
	|   `-- post.html
	+-- _plugins
	|	|-- FILLME
	|   `-- README.md
	+-- _posts
	|   |-- 1970-1-1-hello-world.md
	|   |-- 1971-1-1-hello-world.md
	|   |-- 1972-1-1-hello-world.md
	|   |-- 1973-1-1-hello-world.md
	+-- _site
	+-- css
	|	`-- style.css
	+-- js
	|	`-- FILLME
	|-- _config.yml
	|-- about.md
	|-- atom.xml
	|-- CNAME
	|-- index.html
	`-- rss.xml

Some of the files are still missing. They will be added shortly.

Libraries Used
--------------

- [html5shiv][] -- [MIT][] or [GPL][] Version 2 licenses
- [postmore][] -- by Jacques Fortier

[html5shiv]:			http://code.google.com/p/html5shiv/
[html5jbp]:				https://github.com/bobschi/HTML5-Boilerplate-Jekyll-Template
[blog]:					http://lebobs.ch/
[hg]:					https://bitbucket.org/bobschi/html5-jekyll-template
[hgdl]:					https://bitbucket.org/bobschi/html5-jekyll-template/downloads
[git]:					https://github.com/bobschi/html5-jekyll-template
[gitdl]:				https://github.com/bobschi/html5-jekyll-template/downloads
[postmore]:				http://www.jacquesf.com/2011/03/creating-excerpts-in-jekyll-with-wordpress-style-more-html-comments/
[cypher]: 				http://nuclearsquid.com/
[paulirish]: 			http://paulirish.com/
[andyclarke]: 			http://stuffandnonsense.co.uk/
[boilerplaterepomem]: 	https://github.com/paulirish/html5-boilerplate/network/members
[boilerplate]: 			http://html5boilerplate.com/
[migratewpjekyll]: 		http://vitobotta.com/how-to-migrate-from-wordpress-to-jekyll/
[unlicense]: 			http://unlicense.org/
[mit]: 					http://opensource.org/licenses/mit-license.php
[bsd]: 					http://www.opensource.org/licenses/bsd-license.php
[gpl]: 					http://www.gnu.org/licenses/gpl.html
[jqf]:					http://www.jacquesf.com/
[postmore]:				http://www.jacquesf.com/2011/03/creating-excerpts-in-jekyll-with-wordpress-style-more-html-comments/