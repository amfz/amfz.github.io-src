Title: First Post
Date: 2017-04-04 21:10
Category: Admin

This is my first Pelican post.
  

####Tutorials/documentation used:
  *  [Pelican quickstart](http://docs.getpelican.com/en/3.6.3/quickstart.html)
  *  [Make a Github Pages blog with Pelican, _Fedora Magazine_](https://fedoramagazine.org/make-github-pages-blog-with-pelican/)
  *  [Creating a Github Pages Website with Pelican, Pedro Rodriguez](https://pedrorodriguez.io/blog/2015/09/15/github-website-with-pelican/)
  *  [How to use Pelican on github pages, Josef Jezek](https://gist.github.com/josefjezek/6053301)
  * [Migrating to Github Pages Using Pelican, Amy Hanlon](http://mathamy.com/migrating-to-github-pages-using-pelican.html)
  

####Misc notes on installation:
*  created an environment with [conda](https://conda.io/docs/using/envs.html) rather than virtualenv
*  `activate` works in cmd.exe, but not Powershell
*  `ghp-import -b master output` did not work
*  alternative workflow to publish:
  1. From the main project folder, gh-pages branch: `pelican content -o output -s publishconf.py`
  2. `cd output`
  3. `git add --all`
  4. `git commit -m "commit message"`
  5. `git push origin master`
  

####quickstart options used:
* Where do you want to create your new web site? [.]
* What will be the title of this web site? am
* Who will be the author of this web site? AM
* What will be the default language of this web site? [English]
* Do you want to specify a URL prefix? e.g., http://example.com   (Y/n) y
* What is your URL prefix? (see above example; no trailing slash) https://amfz.github.io
* Do you want to enable article pagination? (Y/n) y
* How many articles per page do you want? [10]
* What is your time zone? [Europe/Paris] America/New_York
* Do you want to generate a Fabfile/Makefile to automate generation and publishing? (Y/n) y
* Do you want an auto-reload & simpleHTTP script to assist with theme and site development? (Y/n) y
* Do you want to upload your website using FTP? (y/N) n
* Do you want to upload your website using SSH? (y/N) n
* Do you want to upload your website using Dropbox? (y/N) n
* Do you want to upload your website using S3? (y/N) n
* Do you want to upload your website using Rackspace Cloud Files? (y/N) n
* Do you want to upload your website using GitHub Pages? (y/N) y
* Is this your personal page (username.github.io)? (y/N) y