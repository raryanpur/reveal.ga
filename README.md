reveal.ga
=========

This is a skeleton for your GA slides with a few extras to make managing everything simple.

* Use rake tasks to start and stop your local grunt server and redirect its output
* Use a rake task to point your local reveal.js server at a particular lesson folder.

###Moving Between Lessons

Run ```rake point_to[lesson]```, where "lesson" is the number of the lesson directory you want to view. This will update a symlink in the reveal.js directory to point to your slides.

```rake point_to[2]``` 

Will point reveal.js at your 02_Variables_Conditionals directory and its corresponding slides.

###Starting/Stopping Grunt
Run ```rake g:serve``` to start the grunt server which runs reveal.js (you may have to do a one-time ```npm install``` upon downloading the skeleton). 

```rake g:stop``` will stop the grunt server. As it stands now, because I'm lazy, this will blow away every grunt server you have running. If you run many of these, sorry about that. 

###Contributions welcome!
