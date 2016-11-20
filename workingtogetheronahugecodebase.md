# Working together on a huge codebase 

[Laura Lowenthal](https://twitter.com/laulowen)

## Size
- 3 billion lines of code
- 75k commits by humans
- approx. 250k commits by automated tools

## General 

### Monolithic Model
- trunk based development
- branches for releases

### Advantages
- avoid dependency hell
- everybody has all the code

### Tools
- piper: The repository; chrome, google drive, etc. Everything is there.
	- sync changes
	- write code
	- code review
	- commit
- tool based code review
- clients in the cloud
	The whole workspace of every developer is cloud based
	- code analysis
	- editing
	- collaborating
- explore
	searching and navigating through the code is also cloud base
	- searching for reg-ex-patterns, class names, etc. 
	- ctrl + click etc. works as expected
	- looks more and more like an ide --> syntax highlighting etc.
- pre and post commit checks keep the trunk in a working state

## Opinions and experiences
- It's okay: Not as unmanagable as you would think
- agility and release cycles are different betweend different teams

### Code Reviews keep you sane
- code review is built in to the repository commands.
- reviews usually take several iterations. 
- spread knowledge
- sometimes review is like an fyi
- everybody can review
- looks good to me + owners approval = merge
- each team is responsible for the quality of it's work
- author chooses reviewers

### The joys of a huge codebase and team
- lots of knowledge
- automated tests and reviews keep standards high

### the struggle
- keeping things performant at this scale is hard
- there are teams who will work full-time on optimizing for everybody. BUT: small improvements for every developer will be a huge improvement. 

### Wrap Up
If you like a process, you have to automate it. 

### Misc
- It's possible to code on a 'regular' ide.
- cherry picking from trunk to release branches is usually for priority bug fixes
- 'it depends' is the ultimate truth ;)

