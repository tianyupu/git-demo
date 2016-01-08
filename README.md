# git-demo

A simple repository for demoing the basics of git.

## What is git?

git is a version control system. It saves snapshots of your files as you
work on your project, giving you the ability to wind back to a particular
point in time.

## Why do we care?

If you've ever worked on something by yourself and created a copy of a file
just so you can keep working on the file (with the copy as a backup), and
ended up with a lot of files this way, git can help you manage these multiple
copies in a cleaner way, without all of these files scattered all over the
place.

If you've ever worked on a group project, be it a coding or other kind of
project, you'll have found that coordinating what versions of various files
people have is a large challenge. Maybe Alice is working on part 1 and Bob
on part 2, and then they have to email each other their work, and somehow
combine it together, while Charlie has decided that Bob's part needs to be
rewritten. At this point, how does any of them know who's got the most up-to-date
version of everything? git lets you collaborate much easier in teams, in a
central place, where you can also see the history of changes by everyone
in your team.

## Is it hard to learn?

No. There are a few basic commands that enable you to do most of what you
need day-to-day. Many other commands have specialised purposes and are not
necessary to know for a first-time user.

Also, there are numerous GUI clients for various operating systems. These
simplify the interactions with git and provide a way of visualising the
changes in the project.

## Basic terminology

* commit: a "snapshot" in time of all of the files in the repository. Has
an author, date and time, and a message written by the author describing
the change and the reasons behind it
* branch: a "version" of the repository at a particular point in time.
Two branches can't have the same name. The `master` branch is the main branch
of any git repository. This branch should always be 100% working. We nearly
always create branches from `master`. To begin with, our branch will be identical
to `master` but as we make changes, it will begin to look more and more different.
Having our own branch means we can keep working on stuff while `master` changes.
When we're happy for our work to go into `master`, we create a pull request.
* pull request: a way of telling the maintainers of a repository, "Hey, I've
done a bunch of changes and think they would be good if they were in the
master branch. Please take a look and leave comments?" It's a good way to
review code before it becomes part of the master branch, which impacts
any developer that goes on to work with the code!

## What are the typical steps that we'll use when developing features?

1. Create a branch from master
1. Make changes to files in this branch
1. Commit changes
1. Push commits to the corresponding branch on GitHub
1. When finished with the feature, open a pull request on GitHub
1. Merge the pull request while a tutor is present

# License

MIT
