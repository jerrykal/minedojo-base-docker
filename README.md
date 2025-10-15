# MineDojo Base Docker Image

This is the base Docker image for MineDojo projects, built on top of [MineDojo/egl-docker](https://github.com/MineDojo/egl-docker).

It installs all system-level dependencies required by MineDojo, while leaving project-level dependencies (such as conda environments and the MineDojo Python package) to be installed separately within each project.
