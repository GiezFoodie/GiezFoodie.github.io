# Requirements

Having jekyll, bundle and git installed

# Download your folder locally

> git clone git@github.com:GiezFoodie/GiezFoodie.github.io.git

And finally to get in the folder from the command line:
> cd GiezFoodie.github.io.git 

# Run it locally:

From within the folder:
> bundle install
> bundle exec jekyll serve

If you see anyerror in the second line please say, it should end up running a website on http://127.0.0.1:4000/ .

You can now visit that page in your browser.

# Updating your website on the remote server
- git add *files* (or . for all)
> git add .
> git commit -m "message name"
> git push origin master

The third line might ask your for username and password, however we sent up a ssh key on your home computer.

# File locations:

## main home page:
> index.md
Just find and replace!