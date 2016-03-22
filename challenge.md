![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

## Challenge

Carry out all of the following tasks using _only the command line_! As is usually the case, you're welcome to use any resource you can find (except another student, of course) to reach your answer.

## Navigating the Filesystem

Complete each of following steps, **in order** :

1. Create a new directory called `cli-diagnostic` inside the root directory of this repository (`unix-cli-diagnostic`).

2. Create a new file inside `cli-diagnostic` called `rhyme.txt`.

3. Open `rhyme.txt` using Atom (via the terminal) and add the following text:

 "The rain in Spain falls mainly in the plain."

 Once you've done this, save the file and quit.

4. Make a directory inside `cli-dliagnostic` called `temp`. Inside it, create a new blank file called `temp.md`.

5. Navigate back up to `cli-diagnostic`, and delete the `temp` directory (with `temp.md` inside of it).
Use `ls` to show the contents of `cli-diagnostic` - was `temp` deleted?

## Absolute and Relative Paths

Open up this file in Atom, and write your answers below (where indicated).

1. Is `/Users/blah_blah/Desktop` a relative path or an absolute path? How do you know?

Absolute.

Starts with a frontslash, "/", the root of the file system.

2. Suppose that we're working on a project, and we want to use a font that's being hosted somewhere on the internet. Would we use an absolute or relative path to refer to it? Why?

Assuming this means that the project is local and the font remote, we would want an absolute path.

Since the font is in a file system on a different computer/server/host, we have to point our project/system to it.
For instance, I wouldn't address a letter to someone with just their name and a street address without
putting the state and zip code.

3. Now suppose that we have an image file living inside our project. Would we refer to it with an absolute or relative path? Why?

You could use either, but it might be easier to use a relative path.

Since the image file is in the same project, you don't have to add as much detail.
Is this situation analogous? I could ask a friend in the same city to take a package to a specific house number and street, and they would know I'm referring to the same city, therefore, I don't have to provide as much detail.

<hr>

You're done! Refer back to README.md.
