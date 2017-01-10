![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

# Unix/CLI Diagnostic

## Challenge

Carry out all of the following tasks using _only the command line_! As is
usually the case, you're welcome to use any resource you can find (except
another student, of course) to reach your answer.

## Navigating the Filesystem

Complete each of following steps, **in order** :

1. Create a new directory called `cli-diagnostic` inside the root directory of
this repository (`unix-cli-diagnostic`).

2. Create a new file inside `cli-diagnostic` called `rhyme.txt`.

3. Open `rhyme.txt` using Atom (via the terminal) and add the following text:

 "The rain in Spain falls mainly in the plain."

 Once you've done this, save the file and quit.

4. Make a directory inside `cli-diagnostic` called `temp`. Inside it, create a new blank file called `temp.md`.

Navigate back up to `unix-cli-diagnostic` directory.
Using Atom, open up `diagnostic.md` and write your answers below (where indicated).

5. Great Work!  Back in the terminal, do  `git status` to view your changes.  What color is the file name?

 <!-- Answer Starts Here -->
    cli-diagnostic/ is red
 <!-- Answer Ends Here -->

6. Do `git add <file_name>`  to stage your changes.  Do `git status` again to see the newly staged file.  What color is the file name now?

 <!-- Answer Starts Here -->
  green
 <!-- Answer Ends Here -->

7. Let's commit these changes with `git commit <file_name>` and the commit message of `add temp.md and associated folders`.

8. Navigate back up to `cli-diagnostic`, and delete the `temp` directory (with `temp.md` inside of it). Use `ls` to show the contents of `cli-diagnostic` - was `temp` deleted?

9.  Let's commit our changes, Do  `git status` to view your changes.  Do `git add <file_name>`  to stage your changes.  Commit these changes with `git commit <file_name>` and the commit message of `remove temp folder`.

## Absolute and Relative Paths

1. Is `/Users/blah_blah/Desktop` a relative path or an absolute path? How do you know?

 <!-- Answer Starts Here -->
 It is an absolute path because it starts at Users, which is the root directory. This is the full location of where Desktop is found.

 <!-- Answer Ends Here -->

 2. Suppose that we're working on a project, and we want to use a font that's being hosted on Google at `https://fonts.googleapis.com/css?family=Open+Sans`. Is that an absolute or relative path to refer to it? Why?

 <!-- Answer Starts Here -->
  I believe this is an absolute path, because I see nothing in this site that does not go back to the root of the site. The https: is the beginning of the path of a wbesite. 
 <!-- Answer Ends Here -->

3. Now suppose that we have an image file living inside our project. Would we refer to it with an absolute or relative path? Why?

 <!-- Answer Starts Here -->
We can use a relative path in that case, because we are already inside the project and don't need to refer to the entire directory when giving the location of the image file.
 <!-- Answer Ends Here -->

<hr>

You're done! Refer back to README.md.
