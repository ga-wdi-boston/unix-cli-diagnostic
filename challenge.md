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

 This is an absolute path as evidenced by the highly specific file path.  A relative path would look more like "cd ..".

2. Suppose that we're working on a project, and we want to use a font that's being hosted somewhere on the internet. Would we use an absolute or relative path to refer to it? Why?

 You would use an absolute path because the font is not on your computer or your local server.  URLs need to be an absolute path such as what you might find on Google Font.

3. Now suppose that we have an image file living inside our project. Would we refer to it with an absolute or relative path? Why?

 <!-- Answer Starts Here -->
If the image is one from your computer, you can use a relative path.  If the image is hosted online, you would need an absolute path.  
 <!-- Answer Ends Here -->

<hr>

You're done! Refer back to README.md.
