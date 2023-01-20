# Contributing to ROS 2 turtlebot 3 navigation docker

Please inform the maintainer as early as possible about your planned
feature developments, extensions, or bugfixes that you are working on.
An easy way is to open an issue or a pull request in which you explain
what you are trying to do.

## Pull Requests

The preferred way to contribute to **ROS 2 turtlebot 3 navigation docker** is to fork the main repository on Gitlab, then submit a "pull request"
(PR):

1. Fork the [project repository](git@github.com:brean/ros2-turtlebot3-remote-pc-docker.git):
   click on the 'Fork' button near the top of the page. This creates a copy of
   the code under your account on the Gitlab server.

3. Clone this copy to your local disk:

        $ git clone git@github.com:YourLogin/ros2-turtlebot3-remote-pc-docker.git

4. Create a branch to hold your changes:

        $ git checkout -b my-feature

    and start making changes. Never work in the ``main`` branch!

5. Work on this copy, on your computer, using Git to do the version
   control. When you're done editing, do::

        $ git add modified_files
        $ git commit

    to record your changes in Git, then push them to Gitlab with::

       $ git push -u origin my-feature

Finally, go to the web page of your fork of the repo,
and click 'Pull request' to send your changes to the maintainers for review.

## Merge Policy

Summary: maintainer can push minor changes directly, pull request + 1 reviewer for everything else.

* Usually it is not possible to push directly to the `main` branch of this repository for anyone. Only tiny changes, urgent bugfixes, and maintenance commits can be pushed directly to the `main` branch by the maintainer without a review. "Tiny" means backwards compatibility is mandatory and all tests must succeed. No new feature must be added.

* Developers have to submit pull requests. Those will be reviewed by at least one other developer and merged by the maintainer. New features must be documented and tested. Breaking changes must be discussed and announced in advance with deprecation warnings.

* New features should be documented in the [README.md](README.md) file or in new markdown-documents describing how to use them.

## Project Roadmap

Check the [Issue Tracker](https://github.com/brean/ros2-turtlebot3-remote-pc-docker/issues) for roadmap planning. 