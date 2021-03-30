0x03. Git
=========

** Foundations - 0-Day ― 0-Day

** By Guillaume, CTO at Holberton School

** Weight: 1

** Project over - took place from 06-01-2020 to 06-03-2020 - you're done with 100% of tasks.

** QA review fully automated.

#### In a nutshell…

-   **Auto QA review:** 10.0/20 mandatory & 1.0/11 optional
-   **Altogether:**  **54.55%**
    -   Mandatory: 50.0%
    -   Optional: 9.09%
    -   Calculation:  50.0% + (50.0% \* 9.09%)  == **54.55%**

Concepts
--------

*For this project, students are expected to look at these concepts:*

-   [Source code management](https://intranet.hbtn.io/concepts/22)
-   [Git and Github cheat sheet - Everything in less than 30 seconds](https://intranet.hbtn.io/concepts/57)
-   [The Framework](https://intranet.hbtn.io/concepts/75)
-   [Approaching a Project](https://intranet.hbtn.io/concepts/350)

Resources
---------

**Read or watch:**

-   [Resources to learn Git](https://intranet.hbtn.io/rltoken/R0sxgBfnnSyXN2raCOn3ZQ "Resources to learn Git")
-   [About READMEs](https://intranet.hbtn.io/rltoken/ZtuIDV8FbDiphUjJ9b-IZw "About READMEs")
-   [How to write a Git commit message](https://intranet.hbtn.io/rltoken/AvIbO7uXT9-BiWgXIhszDg "How to write a Git commit message")

**Resources for advanced tasks** (Read only after finishing the mandatory tasks):

-   [Learning branching](https://intranet.hbtn.io/rltoken/514Jj2WL9uL6wOyOYWejdA "Learning branching")
-   [Effective pull requests and other good practices for teams using GitHub](https://intranet.hbtn.io/rltoken/ZUE0eoAWDKadJd4QCQkzQg "Effective pull requests and other good practices for teams using GitHub")

Learning Objectives
-------------------

At the end of this project, you are expected to be able to [explain to anyone](https://intranet.hbtn.io/rltoken/y5shhsnWv3y_T_pB4vh_Tw "explain to anyone"), **without the help of Google**:

### General

-   What is source code management
-   What is Git
-   What is GitHub
-   What is the difference between Git and GitHub
-   How to create a repository
-   What is a README
-   How to write good READMEs
-   How to commit
-   How to write helpful commit messages
-   How to push code
-   How to pull updates
-   How to create a branch
-   How to merge branches
-   How to work as collaborators on a project
-   Which files should and which files should not appear in your repo

Requirements
------------

### General

-   A `README.md` file at the root of the `holbertonschool-zero_day` repo, containing a description of the repository
-   A `README.md` file, at the root of the folder of *this* project (i.e. `0x03-git`), describing what this project is about
-   **Do not use GitHub’s web UI**, but the command line to perform the exercise (except for operations that can not possibly be done any other way than through the web UI). You won’t be able to perform many of the task requirements on the web UI, and you should start getting used to the command line for simple tasks because many complex tasks can only be done via the command line.
-   Your answer files should only contain the command, and nothing else

More Info
---------

### Install `git`

If `git` is not already installed on your terminal:

    $ sudo apt-get update
    $ sudo apt-get upgrade
    $ sudo apt-get install git

### Basic usage

At the end of this project you should be able to reproduce and understand these command lines:

    $ git clone <repo>
    $ touch test
    $ git add test
    $ git commit -m "Initial commit"
    $ git push origin main

Quiz questions
--------------

Show

#### Question \#0

You have the following files in your project directory:

    julien@ubuntu:/tmp/git_project$ ls
    0-test  0-test~ #0-test# file1  file2

You’ve edited `0-test` and you want to add it to your GitHub repo. What is the correct command to add **only** `0-test`?

-   `git add .`

-   `git add -N 0-test`

-   `git add 0-test`

#### Tips:

You should learn what each of these commands would actually do if you were to execute them!

#### Question \#1

What command can you use to see what changes have been staged, which haven’t, and which files aren’t being tracked by Git?

-   `git init`

-   `git status`

-   `git checkout`

Tasks
-----

### 0. Repo-session

mandatory

Score: 100.00% (Checks completed: 100.00%)

Create a new directory called `0x03-git` in your `holbertonschool-zero_day` repo. Make sure you include a `README.md` in your directory.

**Repo:**

-   GitHub repository: `holbertonschool-zero_day`

** ** ** Done?!

Help

×

#### Students who are done with "0. Repo-session"

Check your code

×

#### Correction of "0. Repo-session"

Start a new test

[![Checker whm pre malala](./Project_%200x03.%20Git%20_%20Holberton%20Intranet_files/checker_whm_pre_malala-e9e81a71e41301c49c8e1a9ae8ef40471ee7d664bdb9089fb229a6cc035bec0d.png)](https://twitter.com/hashtag/HbtnWomensHistoryMonth)

[![Checker whm post womens history month](./Project_%200x03.%20Git%20_%20Holberton%20Intranet_files/checker_whm_post_womens_history_month-618fe8a6d6d64b25389b52d869911e91d8800af725550de35d77bfb29bff2056.png)](https://twitter.com/hashtag/HbtnWomensHistoryMonth)

**

** Requirement success

** Requirement fail

** Code success

** Code fail

** Efficiency success

** Efficiency fail

** Text answer success

** Text answer fail

QA Review

×

#### 0. Repo-session

### 1. Coding fury road

mandatory

Score: 100.00% (Checks completed: 100.00%)

For the moment we have an empty project directory containing only a `README.md`. It’s time to code!

-   Create these directories at the root of your project: `bash`, `c`, `js`
-   Create these empty files:
    -   `c/c_is_fun.c`
    -   `js/main.js`
    -   `js/index.js`
-   Create a file `bash/holberton` with these two lines inside: `#!/bin/bash` and `echo "Holberton"`
-   Create a file `bash/school` with these two lines inside: `#!/bin/bash` and `echo "School"`
-   Add all these new files to git
-   Commit your changes (message: “Starting to code today, so cool”) and push to the remote server

**Repo:**

-   GitHub repository: `holbertonschool-zero_day`
-   Directory: `0x03-git`
-   File: `bash/holberton, bash/school, c/c_is_fun.c, js/main.js, js/index.js`

** ** ** Done?!

Help

×

#### Students who are done with "1. Coding fury road"

Check your code

×

#### Correction of "1. Coding fury road"

Start a new test

[![Checker whm pre malala](./Project_%200x03.%20Git%20_%20Holberton%20Intranet_files/checker_whm_pre_malala-e9e81a71e41301c49c8e1a9ae8ef40471ee7d664bdb9089fb229a6cc035bec0d.png)](https://twitter.com/hashtag/HbtnWomensHistoryMonth)

[![Checker whm post womens history month](./Project_%200x03.%20Git%20_%20Holberton%20Intranet_files/checker_whm_post_womens_history_month-618fe8a6d6d64b25389b52d869911e91d8800af725550de35d77bfb29bff2056.png)](https://twitter.com/hashtag/HbtnWomensHistoryMonth)

**

** Requirement success

** Requirement fail

** Code success

** Code fail

** Efficiency success

** Efficiency fail

** Text answer success

** Text answer fail

QA Review

×

#### 1. Coding fury road

### 2. Collaboration is the base of a company

mandatory

Score: 0.00% (Checks completed: 0.00%)

A branch is like a copy of your project. It’s used mainly for:

-   adding a feature in development
-   collaborating on the same project with other developers
-   not breaking your entire repository
-   not upsetting your co-workers

The purpose of a branch is to isolate your work from the main code base of your project and/or from your co-workers’ work.

For this project, create a branch `update_script` and in this branch:

-   Create an empty file named `bash/98`
-   Update `bash/holberton` by replacing `echo "Holberton"` with `echo "Holberton School"`
-   Update `bash/school` by replacing `echo "School"` with `echo "The school is open!"`
-   Add and commit these changes (message: “My personal work”)
-   Push this new branch [Tips](https://intranet.hbtn.io/rltoken/s_Det7cYJiyRZDlbZgQmeA "Tips")

Perfect! You did an amazing update in your project and it’s isolated correctly from the **main** branch.

Ho wait, your manager needs a quick fix in your project and it needs to be deployed now:

-   Change branch to `main`
-   Update the file `bash/holberton` by replacing `echo "Holberton"` with `echo "Holberton School is so cool!"`
-   Delete the directory `js`
-   Commit your changes (message: “Hot fix”) and push to the origin

Ouf, hot fix is done!

**Repo:**

-   GitHub repository: `holbertonschool-zero_day`
-   Directory: `0x03-git`
-   File: `bash/holberton, bash/school, bash/98`

** ** ** Done?!

Help

×

#### Students who are done with "2. Collaboration is the base of a company"

Check your code

×

#### Correction of "2. Collaboration is the base of a company"

Start a new test

[![Checker whm pre malala](./Project_%200x03.%20Git%20_%20Holberton%20Intranet_files/checker_whm_pre_malala-e9e81a71e41301c49c8e1a9ae8ef40471ee7d664bdb9089fb229a6cc035bec0d.png)](https://twitter.com/hashtag/HbtnWomensHistoryMonth)

[![Checker whm post womens history month](./Project_%200x03.%20Git%20_%20Holberton%20Intranet_files/checker_whm_post_womens_history_month-618fe8a6d6d64b25389b52d869911e91d8800af725550de35d77bfb29bff2056.png)](https://twitter.com/hashtag/HbtnWomensHistoryMonth)

**

** Requirement success

** Requirement fail

** Code success

** Code fail

** Efficiency success

** Efficiency fail

** Text answer success

** Text answer fail

Ask a new correction : in progress...: an error occured

QA Review

×

#### 2. Collaboration is the base of a company

### 3. Collaboration: be up to date

mandatory

Score: 0.00% (Checks completed: 0.00%)

Of course, you can also work on the same branch as your co-workers and it’s best if you keep up to date with their changes.

For this task – **and only for this task** – please update your file `README.md` in the main branch from GitHub.com. It’s the **only time** you are allowed to update and commit from GitHub interface.

After you have done that, in your terminal:

-   Get all changes of the main branch locally (i.e. your `README.md` file will be updated)
-   Create a new file `up_to_date` at the root of your directory and in it, write the git command line used
-   Add `up_to_date` to git, commit (message: “How to be up to date in git”), and push to the origin

**Repo:**

-   GitHub repository: `holbertonschool-zero_day`
-   Directory: `0x03-git`
-   File: `README.md, up_to_date`

** ** ** Done?!

Help

×

#### Students who are done with "3. Collaboration: be up to date"

Check your code

×

#### Correction of "3. Collaboration: be up to date"

Start a new test

[![Checker whm pre malala](./Project_%200x03.%20Git%20_%20Holberton%20Intranet_files/checker_whm_pre_malala-e9e81a71e41301c49c8e1a9ae8ef40471ee7d664bdb9089fb229a6cc035bec0d.png)](https://twitter.com/hashtag/HbtnWomensHistoryMonth)

[![Checker whm post womens history month](./Project_%200x03.%20Git%20_%20Holberton%20Intranet_files/checker_whm_post_womens_history_month-618fe8a6d6d64b25389b52d869911e91d8800af725550de35d77bfb29bff2056.png)](https://twitter.com/hashtag/HbtnWomensHistoryMonth)

**

** Requirement success

** Requirement fail

** Code success

** Code fail

** Efficiency success

** Efficiency fail

** Text answer success

** Text answer fail

Ask a new correction : in progress...: an error occured

QA Review

×

#### 3. Collaboration: be up to date

### 4. HAAA what did you do???

\#advanced

Score: 16.67% (Checks completed: 16.67%)

Collaboration is cool, but not really when you update the same file at the same time…

To illustrate that, please merge the branch `update_script` to `main`: “Cool, all my changes will be now part of the main branch, ready to be deployed!”

**HHHHHHHAAAAAAAA**

    CONFLICT (content): Merge conflict in bash/holberton

As you can see, you have conflicts between two branches on the same file.

Your goal now is to resolve conflicts by using the version of the branch `update_script`, and push the result to the origin.

At the end, you should have all your work from the branch `update_script` (new file and two updated files) and all latest `main` commits (new files, delete folder, etc.), *without* conflicts.

**Repo:**

-   GitHub repository: `holbertonschool-zero_day`
-   Directory: `0x03-git`

** ** ** Done?!

Help

×

#### Students who are done with "4. HAAA what did you do???"

Check your code

×

#### Correction of "4. HAAA what did you do???"

Start a new test

[![Checker whm pre malala](./Project_%200x03.%20Git%20_%20Holberton%20Intranet_files/checker_whm_pre_malala-e9e81a71e41301c49c8e1a9ae8ef40471ee7d664bdb9089fb229a6cc035bec0d.png)](https://twitter.com/hashtag/HbtnWomensHistoryMonth)

[![Checker whm post womens history month](./Project_%200x03.%20Git%20_%20Holberton%20Intranet_files/checker_whm_post_womens_history_month-618fe8a6d6d64b25389b52d869911e91d8800af725550de35d77bfb29bff2056.png)](https://twitter.com/hashtag/HbtnWomensHistoryMonth)

**

** Requirement success

** Requirement fail

** Code success

** Code fail

** Efficiency success

** Efficiency fail

** Text answer success

** Text answer fail

Ask a new correction : in progress...: an error occured

QA Review

×

#### 4. HAAA what did you do???

### 5. Never push too much

\#advanced

Score: 0.00% (Checks completed: 0.00%)

Create a `.gitignore` file and define a rule to never push `~` files (generated by Emacs). [Tips](https://intranet.hbtn.io/rltoken/0ANsyvhObT_TYAToY8-lbA "Tips")

**Repo:**

-   GitHub repository: `holbertonschool-zero_day`
-   Directory: `0x03-git`
-   File: `.gitignore`

** ** ** Done?!

Help

×

#### Students who are done with "5. Never push too much"

Check your code

×

#### Correction of "5. Never push too much"

Start a new test

[![Checker whm pre malala](./Project_%200x03.%20Git%20_%20Holberton%20Intranet_files/checker_whm_pre_malala-e9e81a71e41301c49c8e1a9ae8ef40471ee7d664bdb9089fb229a6cc035bec0d.png)](https://twitter.com/hashtag/HbtnWomensHistoryMonth)

[![Checker whm post womens history month](./Project_%200x03.%20Git%20_%20Holberton%20Intranet_files/checker_whm_post_womens_history_month-618fe8a6d6d64b25389b52d869911e91d8800af725550de35d77bfb29bff2056.png)](https://twitter.com/hashtag/HbtnWomensHistoryMonth)

**

** Requirement success

** Requirement fail

** Code success

** Code fail

** Efficiency success

** Efficiency fail

** Text answer success

** Text answer fail

Ask a new correction : in progress...: an error occured

QA Review

×

#### 5. Never push too much

Copyright © 2021 Holberton School. All rights reserved.

** **

×

#### Video streaming

**

×

#### Markdown Guide

#### Emphasis

    **bold**
    *italics*
    ~~strikethrough~~

#### Headers

    # Big header
    ## Medium header
    ### Small header
    #### Tiny header

#### Lists

    * Generic list item
    * Generic list item
    * Generic list item

    1. Numbered list item
    2. Numbered list item
    3. Numbered list item

#### Links

    [Text to display](http://www.example.com)

#### Quotes

    > This is a quote.
    > It can span multiple lines!

#### Images

CSS style available: `width, height, opacity`

    ![](http://www.example.com/image.jpg)
    ![](http://www.example.com/image.jpg | width: 200px)
    ![](http://www.example.com/image.jpg | height: 124px | width: 80px | opacity: 0.6)

#### Tables

    | Column 1 | Column 2 | Column 3 |
    | -------- | -------- | -------- |
    | John     | Doe      | Male     |
    | Mary     | Smith    | Female   |

    Or without aligning the columns...

    | Column 1 | Column 2 | Column 3 |
    | -------- | -------- | -------- |
    | John | Doe | Male |
    | Mary | Smith | Female |

#### Displaying code

    `var example = "hello!";`

    Or spanning multiple lines...

    ```
    var example = "hello!";
    alert(example);
    ```
