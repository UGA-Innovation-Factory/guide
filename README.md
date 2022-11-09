# Innovation Factory Guide
This repository serves as a guide for the UGA Innovation Factory Sensors team to navigate their projects throughout the school year. It consists of best practices, examples, and setup information. This repository will be continually updated so please watch and star this in order to be notified of any changes.

## Getting Started
Before we can get started with our projects, we must ensure that our workspace is configured correctly and all the necessary tools are installed. I do understand that this is a significant amount of information and tasks to complete, but everything here is immensely beneficial, not only for the Innovation Factory, but as well as for your career.

Steps:
1. Sign up for [Github Student Developer Pack](https://education.github.com/pack). It's free with your UGA email. (May take a few days to verify)
2. Install [Python 3 here](https://realpython.com/installing-python/)
3. Through [Github Student Developer Pack](https://education.github.com/pack), you are given access to all Jetbrains IDE compilers for free. As a result, we will be using and installing [PyCharm here](https://www.jetbrains.com/student/?authMethod=github). In order for this to work, you must have already signed up for Github Student Developer Pack.
4. Install [Github Desktop](https://desktop.github.com/).
5. If you are not familiar with Python at all, I advise you go through [this Youtube Tutorial](https://www.youtube.com/watch?v=_uQrJ0TkZlc). It does take a while, but by the end of it, you will have become somewhat of an expert on Python.

That's it! You are done for now!


## What is Github and how do I use it with Github Desktop?
Have you ever wondered how developers manage and collaborate on a project? Through Github, teams of developers are able to store, manage, and collaborate on their projects through different stages of development. This is important to us at the Innovation Factory as Github will help you keep track of your project and will allow the leadership to assist in any issues.

Steps:
1. Please follow [this guide](https://docs.github.com/en/get-started/quickstart/hello-world) to create your first example repository.
2. Link your Github to your Pycharm IDE with [this guide](https://www.jetbrains.com/help/pycharm/github.html). What this allows you to do is pull, commit, push, and fetch code through the IDE. TLDR: version control with the IDE.
3. Read and understand how to use Github Desktop [with this guide](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/overview/getting-started-with-github-desktop).


An additional resource I would like everyone to read is [this article discussing better Github Commits](https://www.freecodecamp.org/news/how-to-write-better-git-commit-messages/#:~:text=The%20commit%20type%20subject%20line,of%20the%20subject%20line%20description).


TLDR:
* feat – a new feature is introduced with the changes
* fix – a bug fix has occurred
* chore – changes that do not relate to a fix or feature and don't modify src or test files (for example updating dependencies)
* refactor – refactored code that neither fixes a bug nor adds a feature
* docs – updates to documentation such as a the README or other markdown files
* style – changes that do not affect the meaning of the code, likely related to code formatting such as white-space, missing semi-colons, and so on.
* test – including new or correcting previous tests
* perf – performance improvements
* ci – continuous integration related
* build – changes that affect the build system or external dependencies
* revert – reverts a previous commit

Example Commit:
```
fix: fix foo to enable bar

This fixes the broken behavior of the component by doing xyz. 

BREAKING CHANGE
Before this fix foo wasn't enabled at all, behavior changes from <old> to <new>

Closes D2IQ-12345
```

## Creating Your Project
This section is a little different as it covers your actual project vs the sample one above. We will be using microPython, ROS, and an ESP32 to manage our sensors.

1. Create your repository in the [Innovation-Factory/Sensors](https://github.com/orgs/UGA-Innovation-Factory/teams/sensors) team. Name it IF2022-SensorName-Sensor. Ex: IF2022-Force-Sensor.
2. [Follow this guide to setup microPython on your ESP32](https://docs.micropython.org/en/latest/esp32/tutorial/intro.html).
3. [Install the Pycharm ROS Plugin](https://plugins.jetbrains.com/plugin/11235-ros-support).

## Preliminary Project - Start on 11/10/2022
The first project you guys will create will be hosted through the Jetson Nano and will be written in Python.

- [ ] Login to the Nano and open up the terminal (Ask Jeff or leadership for password)
- [ ] [Install Python 3](https://automaticaddison.com/how-to-write-a-python-program-for-nvidia-jetson-nano/)
- [ ] [Copy the build_opencv.sh shell script to nano with emacs or nvim](https://github.com/mdegans/nano_build_opencv)
- [ ] Once copied, run ./build_opencv.sh (if you get permissions error: `chmod +x ./build_opencv.sh` and then run it again)

### This guide is incomplete: please check back soon!
