# Intro to Programming Concepts

**Presented by [Girl Develop It, Dayton](http://gdidayton.com)**
Much Love to, Forked from [gdiboulder](https://github.com/gdiboulder).


## How to used these slides

The slides are built with [reveal.js](https://github.com/hakimel/reveal.js/) with the markdown, highlight and note plugins active.

Option 1 : Use the hosted slides


Resource|URL
---|---
Slides|[http://gdidayton.com/intro-to-programming-concepts/#/](https://gdidayton.github.io/into-to-programming-concepts/#/)


Option 2 : Get the slides on your machine (requires use of a terminal and node to be installed)

Follow the steps below to Fork and Clone this repo. Then navigate to the folder containing the slide and run the node start command. 
```ApacheConf
$ cd gdi-dayton-intro-programming-concepts
# Changes the active directory in the prompt to the newly cloned "gdi-dayton-intro-programming-concepts" directory
$ npm start
# runs the grunt server that will load the slides at localhost:8000/
```


## How to update these slides

### 1. Fork this Repo

To fork this project, click the "Fork" button in the GitHub.com repository.

![Forking a repo](images/Bootcamp-Fork.png)

### 2. Clone your fork

You've successfully forked the **gdi-dayton-intro-programming-concepts** repository,
but so far it only exists on GitHub. To be able to work on the project, you will need to clone it to your local machine.

Run the following in your terminal:
```
$ git clone https://github.com/username/gdi-dayton-intro-programming-concepts.git
# Clones your fork of the repository into the current directory in termina
```

### 3. Configure remotes
When a repository is cloned, it has a default remote called origin that points to
your fork on GitHub, not the original repository it was forked from. To keep
track of the original repository, you need to add another remote named upstream:

Run the following in your terminal:
```ApacheConf
$ cd gdi-dayton-intro-programming-concepts
# Changes the active directory in the prompt to the newly cloned "gdi-dayton-intro-programming-concepts" directory
$ git remote add upstream https://github.com/gdidayton/gdi-dayton-intro-programming-concepts.git
# Assigns the original repository to a remote called "upstream"
$ git fetch upstream
# Pulls in changes not present in your local repository, without modifying your files
```

## You're ready to make changes! 
### WE accept PRS

When you're ready, commit and push your changes to your repo. 

Don't forget to do a pull request on the upstream repo so we can merge your changes in!

## Questions?
E-mail us: [dayton@girldevelopit.com](mailto:dayton@girldevelopit.com)

Tweet at us: [@gdidayton](http://twitter.com/gdidayton)
