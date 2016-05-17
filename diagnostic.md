![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

# Unix/CLI Diagnostic

## Challenge

Carry out all of the following tasks using _only the command line_! As is
usually the case, you're welcome to use any resource you can find (except
another student, of course) to reach your answer.

## Navigating the Filesystem

Complete each of following steps, **in order** :

1.  Create a new directory called `cli-diagnostic` inside the root directory of
this repository (`unix-cli-diagnostic`).

2.  Create a new file inside `cli-diagnostic` called `rhyme.txt`.

3.  Open `rhyme.txt` using Atom (via the terminal) and add the following text:

 "The rain in Spain falls mainly in the plain."

 Once you've done this, save the file and quit.

4.  Make a directory inside `cli-dliagnostic` called `temp`.
Inside it, create a new blank file called `temp.md`.

5.  Navigate back up to `cli-diagnostic`, and delete the `temp` directory (with
`temp.md` inside of it). Use `ls` to show the contents of `cli-diagnostic`
- was `temp` deleted?

<!-- Answer Starts Here -->
Yes. `temp` was deleted.

<!-- Answer Ends Here -->

## Absolute and Relative Paths

Open up this file in Atom, and write your answers below (where indicated).

1.  Is `/Users/blah_blah/Desktop` a relative path or an absolute path?
How do you know?

 <!-- Answer Starts Here -->
This is at least an absolute path because it starts at /, the root directory
(which contains my Users directory).

However, if we are in the root directory, then it is also the relative path
because then those would be the same (I think). I am not sure if that counts.

<!-- Answer Ends Here -->

2.  Suppose that we're working on a project, and we want to use a font that's
being hosted somewhere on the internet.
Would we use an absolute or relative path to refer to it? Why?

 <!-- Answer Starts Here -->
We would use an absolute path, including the URI because something on the
internet is not in a subdirectory of my current working directory. The computer
needs to know where to find the item on the internet.
 <!-- Answer Ends Here -->

3.  Now suppose that we have an image file living inside our project.
Would we refer to it with an absolute or relative path? Why?

 <!-- Answer Starts Here -->
We can use a relative path for this because it is in a subdirectory.
 <!-- Answer Ends Here -->

<hr>

You're done! Refer back to README.md.
