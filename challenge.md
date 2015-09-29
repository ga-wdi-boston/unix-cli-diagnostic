![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

## Challenge

Carry out all of the following tasks using _only the command line_! As is usually the case, you're welcome to use any resource you can find (except another student, of course) to reach your answer.

<hr>

## Navigating the Filesystem

Complete each of following steps, **in order** :

1. Create a new directory called `quiz` inside the root directory of this repository (`cli-08-assessment`).

2. Create a new file inside `quiz` called `rhyme.txt`.

3. Open `rhyme.txt` using Sublime (via the terminal) and add the following text:

 "The rain in Spain falls mainly in the plain."

 Once you've done this, save the file and quit.

4. Make a directory inside `quiz` called `temp`. Inside it, create a new blank file called `temp.md`.

5. Navigate back up to `quiz`, and delete the `temp` directory (with `temp.md` inside of it).
Use `ls` to show the contents of `quiz` - was `temp` deleted?

## Absolute and Relative Paths

Open up this file in your text editor, and write your answers below (where indicated).

1. Is `/Users/blah_blah/Desktop` a relative path or an absolute path? How do you know?

 <!-- Answer Starts Here -->
 It is an absolute path because it refers to the location from the root directory of the computer. The root directory is shown by the "/" before "Users".
 <!-- Answer Ends Here -->

2. Suppose that we're working on a project, and we want to use a font that's being hosted somewhere on the internet. Would we use an absolute or relative path to refer to it? Why?

 <!-- Answer Starts Here -->
 We would use a absolute path because we would need to reference the exact location of the font we want to use. This would most likely be a URL which specifies an exact location on the web.
 <!-- Answer Ends Here -->

3. Now suppose that we have an image file living inside our project. Would we refer to it with an absolute or relative path? Why?

 <!-- Answer Starts Here -->
 We would refer to it with a relative path because we would refer to it in terms of the current directory which would be the project we are working on. There would be no need to refer to the file from the root of the computer. It is much easier and makes more sense to refer to it with a relative path.
 <!-- Answer Ends Here -->

<hr>

You're done! Refer back to README.md.
