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

Answer: yes, `temp` was deleted.

## Absolute and Relative Paths

Using Atom, open up `diagnostic.md` and write your answers below (where indicated).

1. Is `/Users/blah_blah/Desktop` a relative path or an absolute path? How do you know?

 <!-- Answer Starts Here -->
 It's an absolute path because it references the root directory, which is the highest directory that can be referenced.

 <!-- Answer Ends Here -->

2. Suppose that we're working on a project, and we want to use a font that's being hosted somewhere on the internet. Would we use an absolute or relative path to refer to it? Why?

 <!-- Answer Starts Here -->
Again, we would use an absolute path, otherwise the computer wouldn't know where to look, so to speak, unless the image were already in the same general place as where the rest of the code were being hosted. For our purposes, if I pulled an image from http://www.example.com/pictures/cats for a web page at http://www.mysite.com/animals/ , the path the image is from would have to be absolute as the computer would need to be told where to grab the original image from.
 <!-- Answer Ends Here -->

3. Now suppose that we have an image file living inside our project. Would we refer to it with an absolute or relative path? Why?

 <!-- Answer Starts Here -->
 We would use a relative path to refer to it as its already inside of our project. Using the example from above, if the image were already at http://www.mysite.com/animals/cats and I wanted to pull it for http://www.mysite.com/animals/pets, all I'd only have to include a relative path to </cats> {whatever the correct syntax would be} as the computer would then infer that it's already looking in http://www.mysite.com/animals and all we'd need to do would be to specify the relative path, where it differs from where we're putting the image we want. 

 <!-- Answer Ends Here -->

<hr>

You're done! Refer back to README.md.
