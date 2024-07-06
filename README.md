# TUTORIAL #

A React Single Page Application for displaying an interactive tutorial.

The project is designed to be deployed to GitHub pages. It imports plain HTML tutorials into an iframe, and provides a Kanban simulator component, which you must interact in order to progress through any given tutorial.

[Demo](https://MERNCraft.github.io/tutorial)

The SPA displays:

* A list of available tutorials (itself read in from a JSON file)
* A vertical menu bar which collapses to a hamburger icon if the viewport is narrow
* Code blocks with syntax highlighting and line-numbering
* Screenshots 
* A variety of collapsible "aside" elements, for tips, warnings TLDR explanations, and other extra content
* A Kanban-style project management board, to encourage you to imagine your own solutions to the issues to be treated before checking out the suggested technique.

You can choose to read the content in one continuous page, or to divide it into bookmarkable sections. When you print out the tutorial, screen-only elements will not be printed.
