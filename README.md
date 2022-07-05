# Organizing Your Work for this Course

## Learning Goals

- Configure a directory for storing lessons
- Understand the relationship between navigating directories in the terminal and
  navigating directories in a graphical user interface like Finder
- Practice common terminal commands such as `pwd`, `ls`, `mkdir`, and `cd`

## Instructions

From now on, you'll be executing code on your own computer. For each and every
lab, you'll be copying the code to your computer using
[Git](https://git-scm.com). You will then be able to run and test your code in
your terminal, and submit your work using the learn-co gem.

## MacOS: Setting Up Your Directory Structure

For Mac users, follow along with this video:

<iframe width="640" height="480" src="https://www.youtube.com/embed/_zeNHyW9gvw" frameborder="0" allowfullscreen></iframe>

## WSL: Setting Up Your Directory Structure

For Windows users, follow along with this video:

<iframe width="640" height="480" src="https://www.youtube.com/embed/EwLe9M4xZlk" frameborder="0" allowfullscreen></iframe>

## Creating Folders to Organize Your Work

- Go to your terminal and navigate to your home directory by typing `cd ~`.
- Navigate into the `Development` folder with `cd Development` (if you don't
  have a `Development` folder yet, you can create it with `mkdir Development`,
  then `cd` into it).
- Create a directory for all your assignments by typing `mkdir code`.
- Navigate into this folder with `cd code`.
- In here, create a directory for Software Engineering Prep with
  `mkdir se-prep`.

You'll be going through multiple phases in this course, so it may be helpful
to go one step further and also create folders for phases 1 through 5 within
`code`. When making the phase folders use a `-` between words. For example,
the phase 1 folder should be named `phase-1`.

Having a specific place for your work will make it easier to find if you ever
need to look back at an earlier project. It'll also keep the rest of your
computer's folders clear of random code.

## Terminal Command Reference

Here's a quick reference of the terminal commands used in these videos. For
more, check out this awesome [cheatsheet].

| Command      | Description                                                |
| ------------ | ---------------------------------------------------------- |
| ls           | List all files and folders in the current directory        |
| ls -a        | List all files and folders, including hidden files         |
| mkdir [name] | Make a new directory with the given [name]                 |
| cd [folder]  | Change directories to the given [folder]                   |
| cd ..        | Change directories to the parent directory                 |
| cd ~         | Change directories to the home directory                   |
| pwd          | Print the full path of the current working directory       |
| explorer.exe | (Windows) Open the File Explorer to the current directory  |
| open .       | (Mac) Open the Finder application to the current directory |

## Resources

- [Terminal Commands Cheatsheet][cheatsheet]

[cheatsheet]: https://github.com/0nn0/terminal-mac-cheatsheet
