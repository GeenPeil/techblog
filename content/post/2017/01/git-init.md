+++
date = "2017-01-17T12:00:00+01:00"
title = "git init"
author = "Geert-Johan Riemer"
+++

`git init`, regularly marks the start of a new project. This project is not different when it comes to git and yesterday the [first commit](https://github.com/GeenPeil/stem/commit/e55e07e8ba676099fb3d643a224a31d5983c639d) was pushed to GitHub.

One might wonder why we didn't start earlier with development. The party was announced on the 5th of December, so why wait? Well the answer is pretty simple: we first focused on the functional design of it all. We will share this functional design in a separate post at a later time. For now, lets show some basic tech details.

<!--more-->
 
#### Simple overview of components
 
This projects consists of 4 main components:

- `db`: The central database.
- `rutte`: The back-end program exposing REST API's for two front-ends:
- `arib`: The front-end for party members (member self-service, voting and discussion).
- `opstelten`: The front-end for GeenPeil HQ personnel.

If you have seen the [previous GeenPeil project](https://github.com/GeenPeil/teken), you will recognize a trend with component names.

![Simple overview of components](/images/git-init-tech-overview.png)

This is of course a very simplistic overview. It will be updated as the project progresses.

#### I would like to participate

Awesome! First of all, make sure you have access to the project and communication channels. Please mail me at `geertjohan@geenpeil.nl` and explain what your skills are and how you would like to contribute. I'll get back to you as soon as possible.

Once you're added to the developers team, go to [Projects](https://github.com/GeenPeil/stem/projects) to find yourself a suiting task to complete. Make sure the task is in a "TODO" column and not already assigned.

Once you've found a task you are willing to take on it's important to assign yourself to this task so we know you are working on it and move it to the "In Progress" column. Create a fork of the repository. Create a new branch on your fork and push your masterpiece. Once complete, back to GitHub to create a pull request. 

After someone else reviewed/approved your code it will be merged back into the master branch.

If you are unable to or have no time to complete a task which you assigned to yourself be sure to put it back into the "TODO" list so someone else can pick it up. Perhaps you can add a comment pointing to a work-in-progress branch someone else can adopt.

Checkout the complete repository at [github.com/GeenPeil/stem](https://github.com/GeenPeil/stem).