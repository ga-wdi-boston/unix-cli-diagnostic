![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

## Challenge

Carry out all of the following tasks using _only the command line_! As is usually the case, you're welcome to use any resource you can find (except another student, of course) to reach your answer.

<hr>

## Navigating the Filesystem

Complete each of following steps, **in order** :

1. Create a new directory called `quiz` inside the root directory of this repository (`cli-08-assessment`).
Done
2. Create a new file inside `quiz` called `rhyme.txt`.
Done
3. Open `rhyme.txt` using Sublime (via the terminal) and add the following text:
Done
 "The rain in Spain falls mainly in the plain."
Done
 Once you've done this, save the file and quit.
Done
4. Make a directory inside `quiz` called `temp`. Inside it, create a new blank file called `temp.md`.
Done
5. Navigate back up to `quiz`, and delete the `temp` directory (with `temp.md` inside of it).
Use `ls` to show the contents of `quiz` - was `temp` deleted?
With rm -rf, yes
## Absolute and Relative Paths

Open up this file in your text editor, and write your answers below (where indicated).

1. Is `/Users/blah_blah/Desktop` a relative path or an absolute path? How do you know?

Relative path. It's because the path is specified relative to my current location in the directory.

2. Suppose that we're working on a project, and we want to use a font that's being hosted somewhere on the internet. Would we use an absolute or relative path to refer to it? Why?
An absolute path because all web addresses are unique, and thus absolute.


3. Now suppose that we have an image file living inside our project. Would we refer to it with an absolute or relative path? Why?

With a relative path because we are inside the project folder and you only need
to access the file by specifying relative to where in the directory you are.

You're done! Refer back to README.md.
