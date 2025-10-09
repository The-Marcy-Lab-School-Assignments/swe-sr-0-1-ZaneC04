# Technical Writing Assignment

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

A good technical explanation often uses a metaphor to help others understand a complex concept. Choose a metaphor to represent a Git commit. 

In a few brief paragraphs, use your chosen metaphor to explain:
* What a commit is
* How a commit is created (include the command-line syntax)
* Why commits are useful in version control.
* Why it is important to write descriptive clear messages in team settings.

### Response 1

An important aspect of working on a program with others is organization. One of the ways that programmers are able to organize their code in a understandable  way is by using Git to create "commits" of their code. A way we can think about using commits is by thinking of the layers of a cake. 
 
Git is a software that programmers can download and
allows them to be able to control the different versions of their program. Git is our kitchen, and has all the ingredients and appliances available to be able to make our cake and the layers of it. 

Commit is one of the commands that Git allows us to use, but it is not the first we use to commit our code. For our cake layers, we'd have to combine our ingredients before decorating. Our "baking" here is us doing 

```

git add [filename]    # stages one file
git add -A            # stages all our files

```
in our command terminal, which adds our files to the "staging area". This is where we can then commit our code using Git. Think of this as baking our cakes, as we cannot eat just the uncooked batter. After baking, we are able to start decorating our cake layers for our finished cake. 

Next, now that we have added our code to the staging area, we are able to then commit our code. We are able to then do 

```
git commit                  # commiting without a message 
git commit -m '[message]'   # committing with a message
```

in our terminal. This commits our code outside of our machines, and uploads it to GitHub. This is extremely important for our "version control". Think of our cake layers again, what if one of our cake layers was burnt? Commits are able to control our versions of code, and see if they're fit to be in the final product of our program. Similarly, we need to check if all the layers of our cake are baked well, and can then be decorated.

Before we decorate though, we need to understand what flavor of cake we are decorating, or even the color of icing we're supposed to use. In our commit commands above, you can commit your code with or without a comment attached. It is not recommended to commit without a message, as it is important to programmers to know what was done in this commit, and why. What if this cake layer was red velvet and needed to be under the layer of chocolate? Communication is important, and this is the same for programmers working together on a program.