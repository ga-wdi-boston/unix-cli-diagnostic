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

 <!--Answer starts here-->
 red

 <!-- Answer Ends Here -->

6. Do `git add <file_name>`  to stage your changes.  Do `git status` again to see the newly staged file.  What color is the file name now?

 <!--Answer starts here-->new file: cli-diagnostic/rhyme.txt and cli-diagnostic/temp/temp.md are both green.
 modified: diagnostic.md is red.-->

 <!--Answer ends here-->

7. Let's commit these changes with `git commit <file_name>` and the commit message of `add temp.md and associated folders`.

8. Navigate back up to `cli-diagnostic`, and delete the `temp` directory (with `temp.md` inside of it). Use `ls` to show the contents of `cli-diagnostic` - was `temp` deleted?

<!-- Answer Starts Here -->

<!-- Answer Ends Here -->

9.  Let's commit our changes, Do  `git status` to view your changes.  Do `git add <file_name>`  to stage your changes.  Commit these changes with `git commit <file_name>` and the commit message of `remove temp folder`.

## Absolute and Relative Paths

1. Is `/Users/blah_blah/Desktop` a relative path or an absolute path? How do you know?

 <!--Answer starts here-->It's an absolute path because it starts at the root/ gives the full path as opposed to a path relative to where I am.

 <!-- Answer Ends Here -->

 2. Given:
```sh
~/project
├── css
├── data
├── img
├── js
└── planning
```

If we are in the `project` directory and use `cd planning`, is a relative or absolute path being referenced? How do you know?

 <!-- Answer starts here -->>It's an absolute path because it specifies the protocol and shows the computer where to go regardless of what page I'm on right now (for example, if I'm on facebook.com and I use the link above, the computer will not assume that the link is a part of Facebook.)

 <!-- Answer Ends Here -->

3. Now suppose that we have an image file living inside our project. Would we refer to it with an absolute or relative path? Why?

 <!-- Answer Starts Here -->
We would refer to it with a relative path, because it's in the same project and it's shorter/more efficient to use a relative path rather than start at the beginning and work our way back to the image file.
 <!-- Answer Ends Here -->

<hr>

You're done! Refer back to README.md.
