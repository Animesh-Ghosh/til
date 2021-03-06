# TIL

> Today I Learned

A collection of concise write-ups on small things I learn across a variety of 
languages and technologies.

_6 TILs and counting..._

## Categories
* [C++](#C++)
* [Docker](#Docker)
* [Drupalcamp-delhi-2019](#DrupalCamp-Delhi-2019)
* [Makefile](#Makefile)
* [Qbasic](#QBasic)

---

### C++

- [Everything I know is wrong.](C++/Everything-I-know-is-wrong.md)

### Docker

- [The Thing with Docker Desktop](Docker/The-Thing-with-Docker-Desktop.md)

### Drupalcamp-delhi-2019

- [DrupalCamp Delhi 2019](DrupalCamp-Delhi-2019/DrupalCamp-Delhi-2019.md)

### Makefile

- [First program using Make.](Makefile/First-program-using-Make.md)
- [Makefiles exist.](Makefile/Makefiles-exist.md)

### Qbasic

- [I used to do QBasic.](QBasic/I-used-to-do-QBasic.md)

---

## Usage

Steps to follow:

1. Create directories for specific topics. For example if you solve a problem on 
	*HackerRank* create a directory named `Competitive Programming` or if you 
	learned something new in JavaScript, create a directory for the same.

	Some recommended categories:

	- Data Structures & Algorithms
	- Meet-ups
	- C++/JavaScript/Python
	- HTML/CSS
	- Git/Version Control
	- Machine Learning

2. Inside those directories create a [`Markdown`](https://www.markdownguide.org/basic-syntax/) 
	file with your title for example `Variables-in-JavaScript.md`, 
	`Create_React_App.md` etc. Make sure that the markdown file has a title. 
	Spaces in titles are _not_ recommended since different services render 
	markdown differently.

3. Every Markdown TIL file should start with a `#` i.e h1 heading.

4. Run `python createTIL.py` to auto-generate the new README file for you 
	
	OR
	
	If you are using git, you can install this script as a pre-commit git hook so 
	that it is autogenerated on each commit. Use the following command:

	`cd .git/hooks/ && ln -s ../../createtil.py pre-commit && cd -`
 
5. Once satisfied push your changes.

## About

Original Idea/Work [thoughtbot/til](https://github.com/thoughtbot/til).

## Other TIL Collections

* [Today I Learned by Hashrocket](https://til.hashrocket.com)
* [jwworth/til](https://github.com/jwworth/til)
* [thoughtbot/til](https://github.com/thoughtbot/til)