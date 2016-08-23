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
That is an absolute path because it references '/Users/blah_blah/', which
represents the root directory.
 <!-- Answer Ends Here -->

2. Suppose that we're working on a project, and we want to use a font that's being hosted somewhere on the internet. Would we use an absolute or relative path to refer to it? Why?

 <!-- Answer Starts Here -->
Assuming that image is being hosted on another website, you would need to use an
absolute path. The computer will not know which website is hosting the font, so
the path would have to first specify the domain, which makes it an absolute
path.
 <!-- Answer Ends Here -->

3. Now suppose that we have an image file living inside our project. Would we refer to it with an absolute or relative path? Why?

 <!-- Answer Starts Here -->
You could use either. If your image file lives very close to your html file, it
can be easier and cleaner to use a relative path. If it does not live very close
to the html file, it may be better to use an absolute path to avoid a confusing
relative path with many steps.
 <!-- Answer Ends Here -->

<hr>

You're done! Refer back to README.md.
