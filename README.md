# Recipes

The goal of this repository is to track the evolution of recipes over time.

## Git
_A free open-source version control system_

###Git configuration

	git config --global user.name "username"
	git config --global user.email "myemail@email.com"
	git config --global color.ui "auto"
	git config --global core.editor "vim"

	git config --list

**Create a repo on the local server**
git init

**Link local repo to github repo**
git remote add origin URL
git push origin master

**Clone github repo to local server**
git clone URL

**Proxy**
git config --global http.proxy http://user:password@proxy.url
git config --global --unset http.proxy

**Updating local repo**
git add .
git commit -m "message"

**Updating remote repo**
git push

# Markdown language

# # First Level Header

## ## Second Level Header

### ### Third Level Header

> > blockquote
> continued
> and continued

*some emphasis*
_some other emphasis_
**more emphasis**
__italics__

[Testlink](https://github.com/nanovikov/Recipes/edit/master/README.md)

[Testlint][1]

[1]: https://github.com/nanovikov/Recipes/edit/master/README.md

![alt text](path-to-image)



 
