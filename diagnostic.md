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

 <!-- Answer Ends Here -->

6. Do `git add <file_name>`  to stage your changes.  Do `git status` again to see the newly staged file.  What color is the file name now?

 <!-- Answer Starts Here -->

 <!-- Answer Ends Here -->

7. Let's commit these changes with `git commit <file_name>` and the commit message of `add temp.md and associated folders`.

8. Navigate back up to `cli-diagnostic`, and delete the `temp` directory (with `temp.md` inside of it). Use `ls` to show the contents of `cli-diagnostic` - was `temp` deleted?

<!-- Answer Starts Here -->

<!-- Answer Ends Here -->

9.  Let's commit our changes, Do  `git status` to view your changes.  Do `git add <file_name>`  to stage your changes.  Commit these changes with `git commit <file_name>` and the commit message of `remove temp folder`.

## Absolute and Relative Paths

1. Is `/Users/blah_blah/Desktop` a relative path or an absolute path? How do you know?

 <!-- Answer Starts Here -->
The path listed above is a relative path because it tells you exactly where to go from the Home directory. It gives a direct route, avoiding online URLs that may change over time and therefore lose the information they linked to.



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

 <!-- Answer Starts Here -->
We would use an absoulte path because that's where the font is being hosted by the server. It similar to the argument made in class: any photo hosted by google isnt going anywhere, we'll be able to link to it as long is its being hosted.
 <!-- Answer Ends Here -->

3. Now suppose that we have an image file living inside our project. Would we refer to it with an absolute or relative path? Why?

 <!-- Answer Starts Here -->
Depends on the situation, both have different stengths and weaknesses. For example: If we are working with others, it should have an absoulte path so that eveyone can access the files individually and not have to rely on one person to host them in a certain location. 
 <!-- Answer Ends Here -->

<hr>

You're done! Refer back to README.md.
