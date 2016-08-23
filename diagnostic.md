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

4. Make a directory inside `cli-dliagnostic` called `temp`. Inside it, create a new blank file called `temp.md`.

5. Navigate back up to `cli-diagnostic`, and delete the `temp` directory (with `temp.md` inside of it). Use `ls` to show the contents of `cli-diagnostic` - was `temp` deleted?

6.) Navigate back up to `unix-cli-diagnostic` directory.

## Absolute and Relative Paths

Using Atom, open up `diagnostic.md` and write your answers below (where indicated).

1. Is `/Users/blah_blah/Desktop` a relative path or an absolute path? How do you know?

 <!-- Answer Starts Here -->
This is an absolute path. /Users/blah_blah is the root directory, which is explicitly specified here.
 <!-- Answer Ends Here -->

2. Suppose that we're working on a project, and we want to use a font that's being hosted somewhere on the internet. Would we use an absolute or relative path to refer to it? Why?

 <!-- Answer Starts Here -->
An absolute path—you always have to use an absolute path to get to resources hosted online that aren't using the same domain name as your project. Relative paths only help locate resources that have a location that's relative (within the same "family" of folders/locations) to the current resource/file.
 <!-- Answer Ends Here -->

3. Now suppose that we have an image file living inside our project. Would we refer to it with an absolute or relative path? Why?

 <!-- Answer Starts Here -->
You could use either. Absolute paths are more clear, but relative paths might be helpful (for example, if you're developing locally and pushing to a live server, the absolute path on your localhost wouldn't work in production.)
 <!-- Answer Ends Here -->

<hr>

You're done! Refer back to README.md.
