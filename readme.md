# Starter Website for Github Pages
slides for presentation: https://docs.google.com/presentation/d/1XQk0PowKr5jEQ2xt8mX3AZXXXWsJWy42cn3Hl1Lo7UA/edit#slide=id.g1446063bce0_1_68

# Before you begin

I recommend developing your website on a laptop so that you can view your website locally before you push it to the actual world wide web. To do this, you’ll need git to allow uploading your code to github and ruby and Jekyll to allow serving your code to your local web browser.

- git (mac) <https://sourceforge.net/projects/git-osx-installer/> (windows) <https://git-scm.com/download/windows>
- ruby <https://www.ruby-lang.org/en/documentation/installation/#installers>
- Jekyll <https://jekyllrb.com/>

# View website locally

1. open terminal
2. navigate to your website's folder like
```cd ~/Documents/Website/shanadeane.com```
3. run
```bundle exec jekyll serve -l```
4. open web browser! http://127.0.0.1:4000/


# How to format posts with Markdown

https://www.markdownguide.org/cheat-sheet/


# How to save and upload website

1. Edit website and save files
2. Open terminal
3. ```git add . && git commit -m "my work"``` where _my work_ is a breif description of what you changed
4. ```git push```
5. Wait 60 seconds and check your website!

# Edit HTML and CSS
First, you should have a basic understanding of HTML and CSS
https://www.w3schools.com/html/
https://www.w3schools.com/css/

Next, you can use this tutorial to guide you through how to override the Jekyll theme defaults by copying the `_includes`, `_head`, etc directories into your repo where you can then edit them and have them be used when your site is served by the `bundle exec jekyll serve -l` command.
