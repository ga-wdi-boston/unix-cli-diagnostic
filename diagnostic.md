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

 <This is an absolute path since the reference to it is the same from anywhere on my computer. >

2. Suppose that we're working on a project, and we want to use a font that's being hosted somewhere on the internet. Would we use an absolute or relative path to refer to it? Why?

 <We would use an abolute path to reference this font, as a relative path may not be adequate for users on other computers, and the font is not stored within a directory relative to the files on the page I'm building.>

3. Now suppose that we have an image file living inside our project. Would we refer to it with an absolute or relative path? Why?

 <Assuming there is no conflicts from the host, we would refer to this using a relative path as it shares storage and local directories with the files for the project such as our html and css.>

<hr>

You're done! Refer back to README.md.
