Title: Code Challenge 05 - Twitter data analysis Part 2: how similar are two tweeters?
Date: 2017-02-06 00:01
Category: Challenges
Tags: codechallenges, learning, twitterapi, Twitter, NLP, similarity, Gensim
Slug: codechallenge05
Authors: PyBites
Summary: A new week, more coding! In Part 2 of our Twitter data analysis we challenge you to find out how similar two tweeters are ...
cover: images/featured/pybites-code-challenges.png

> This week, each one of you has a homework assignment ... - Tyler Durden (Fight club)

### Birds of a feather 

A new week, more coding! In Part 2 of our Twitter data analysis we challenge you to find out how similar two tweeters are ...

### Challenge

* Make a script that receives two command line args: user1 and user2

		$ similar_tweeters.py bbelderbos pybites
		# ... some index of similarity ...

* Get the last n tweets of these users. You can use the code of [Part 1](https://github.com/pybites/challenges/blob/solutions/04/usertweets.py).

* Tokenize the words in the tweets, filtering out stop words and irrelevant Twitter characters (e.g. @, RT, #).

* Extract the main subjects the users tweet about. You could use [Gensim](https://radimrehurek.com/gensim/), an NLP package for Topic Modeling, which supports [LDA](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation):
	
	> In natural language processing, latent Dirichlet allocation (LDA) is a generative statistical model that allows sets of observations to be explained by unobserved groups that explain why some parts of the data are similar. 

	However feel free to take your own approach! We are dropping the template and requirements.txt for this challenge, we'd love to see different approaches to this problem ...

### Stay in sync with PyBites challenges repo

Start coding by [forking our challenges repo](https://github.com/pybites/challenges):

    $ git clone https://github.com/pybites/challenges

If you already forked it [sync it](https://help.github.com/articles/syncing-a-fork/):

    # assuming using ssh key
    $ git remote add upstream git@github.com:pybites/challenges.git 
    $ git fetch upstream
    # if not on master: 
    $ git checkout master 
    $ git merge upstream/master
	# ... no template for this challenge ...

### Good luck!

Remember: there is no best solution, only learning more Python.

Enjoy and we're looking forward reviewing our and your solutions on Friday.

Have fun!

---

### About PyBites Code Challenges

More background in our [first challenge article](http://pybit.es/codechallenge01.html).
