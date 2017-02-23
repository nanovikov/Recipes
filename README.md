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

	Use 'tab' or triple backticks to show code

> `>` makes a blockquote

*italics* by `*italics*`

**bold** by `**bold**`

~~crossed out~~ by `~~crossed out~~`

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
:joy: by `:joy:`

## Nested lists

1. Start the list
  1. indent by 2 spaces
  2. each time
    * then by 2 more spaces
2. Then continue with the original list
3. And you have yourself a nested list
  * isn't that
    * very cool?
4. If you want to add comments, add two spaces here
 And one here. :wink:

```
1. Start the list
  1. indent by 2 spaces
  2. each time
    * then by 2 more spaces
2. Then continue with the original list
3. And you have yourself a nested list
  * isn't that
    * very cool?
4. If you want to add comments, add two spaces here  
 And one here :wink:
```

## Task lists

```
- [x] task 1
- [ ] task 2
- [ ] task 3
```

## Paragraphs

To type a paragraph  
Like this  
Add two spaces  
At the end of each line

Otherwise your paragraph will look like this: 
To type a paragraph
Like this
Add two spaces
At the end of each line
