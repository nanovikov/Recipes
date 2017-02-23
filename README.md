# Recipes

The goal of this repository is to track the evolution of recipes over time.

# Git
_A free open-source version control system_

##Git configuration

	git config --global user.name "username"
	git config --global user.email "myemail@email.com"
	git config --global color.ui "auto"
	git config --global core.editor "vim"

	git config --list

##Working with a local repo

	mkdir localrepo
	cd localrepo
	git init

	git remote add origin URL
	git push origin master

##Clone github repo
	git clone URL
	git add .
	git commit -m "message of changes"
	git pull
	git push

## Proxy settings
	git config --global http.proxy http://user:password@proxy.url
	git config --global --unset http.proxy

# Markdown language

# # First Level Header

## ## Second Level Header

### ### Third Level Header

> blockquote `>`

*italics*
	*italics*

**bold**
	**bold**

~~crossed out~~
	~~crossed out~~

[Testlink](https://github.com/nanovikov/Recipes/edit/master/README.md)

	[Testlink](https://github.com/nanovikov/Recipes/edit/master/README.md)

[Testlink2][1]
[1]: https://github.com/nanovikov/Recipes/edit/master/README.md

	[Testlink2][1]
	[1]: https://github.com/nanovikov/Recipes/edit/master/README.md

![alt text](cats.png)

	![alt text](cats.png)

First Header | Second Header
-------------|--------------
my | table
is | awesome


## Emojicode
:joy:
	:joy:
