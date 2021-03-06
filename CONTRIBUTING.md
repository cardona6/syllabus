# Contributing

Before starting, please read the following general guidelines and [Checklist for a lesson](https://github.com/Code-Your-Future/syllabus/issues/9). Participate in the discussion if you'd like.

There are [discussions](https://github.com/Code-Your-Future/syllabus/issues) about each module and every class in a module, make sure to go through them (or add a new issue/discussion point).

To contribute to the Code Your Future syllabus, fork and open a pull request to
[this repository](https://github.com/code-your-future/syllabus), or contribute directly to **London** or **Scotland** branches of the syllabus. (Contributions to **master** are strictly through approved Pull Requests, even for administrators of the repo)

While **master** is the blueprint of our syllabus, we have two branches for specific classes (**London** and **Scotland** currently) to allow the teams to adapt to their classes' needs, and also update their syllabus versions to reflect how the class goes.

We should also update the classes' branches with **master** regularly (and vice versa) to keep our master blueprint relevant and up to date for future classes.

## Publish the Gitbook

A Gitbook for each branch is published automatically on each push:

- master - https://code-your-future.github.io/syllabus-master/
- London - https://code-your-future.github.io/syllabus-london/
- Scotland - https://code-your-future.github.io/syllabus-scotland/

Mentors should point the students to the individual classes on Github (not the gitbook links) to allow them to get familiar with Git and Github, and to focus on the individual class. Also Point them to the version on your branch.

For your convenience, you can run Gitbook locally

Install the [GitBook](https://github.com/GitbookIO/gitbook) CLI:
```bash
npm install -g gitbook-cli
```

Install gitbook plugins for this project, if not already installed:
```bash
gitbook install
```

Run the gitbook server which will autoupdate as you change the contents
```
gitbook serve
open http://localhost:4000
```

## Add new modules or lessons

The repo is stuctured as `module-name\lesson-number` - add your content in the correct file.

If you've added a new file, then Add it as new entry in [SUMMARY.md](https://github.com/Code-Your-Future/syllabus/blob/master/SUMMARY.md).
If the module contains many individual markdown files, add them as nested bullets under the main README.

## A Lesson template
Please check the [lesson template](lesson-template.md) and use it as a starting point for your new lessons.

Each lesson should follow that format - starting with **what we will learn today** then **class contents**, **homework** and **preparation for next class**.

The class contents and homework should follow these general guidelines - [Checklist for a lesson](https://github.com/Code-Your-Future/syllabus/issues/9)

Some of the most important guidelines are:
- Focus on exercises in the class rather than presentations or long explanations
- Prefer pointers to good documentation over explaining everything in the lesson itself
- The homework should be relevant, get harder gradually with an (optional) stretch goal for more advanced students.
