# Project: Git Basics

**DUE:** Wednesday, Sept. 18, Noon.

This project is worth **ten (10) points.**

You will need to have a [GitHub](https://github.com) account to complete this assignment.

Because some aspects of this project involve work with a remote repository (which will be covered in a future class), those details have been provided. You are responsible for properly executing the commands on your computer to branch, add and commit.

## Instructions

1. Install `git` on your computer. Configure the software as shown in class (`user.name`, `user.email`, `core.editor`). So you do not have to type in a username/password every time you push your work to GitHub, follow the steps in ["Caching your GitHub password in Git"](https://help.github.com/en/articles/caching-your-github-password-in-git).

2. Fork this repository. You will find the "fork" button on the right, just below the navigation bar. "Forking a repository" creates a copy of the repo in your GitHub account. **Moving forward, use the version in *your* account.** If you use the repository in `umiami-front-end` you will be unable to push changes.

3. Switch to the repository in your account. Click the green "Clone or Download" button, then click the clipboard icon next to the URL of the repository's location. The URL should be something similar to: `https://github.com/your-username/git-basics-project.git`.

4. Using the command line, navigate to the directory on your computer where you would like to work. This may be your home folder or another directory -- choose what is comfortable for you. Type `git clone` followed by a space and the URL you copied from GitHub. Hit enter. This will download a copy of the repository to your computer.

5. Change the directory you just cloned.

6. On the `master` branch of this repository, remove the `README.md` file. Commit this change.

7. Create a new branch called `fix-typo`. Fix the typo in `index.html` (it is in the `h2`). Commit this change.

8. Using the `fix-typo` branch as the basis, create another new branch called `update-web-site`.

9. Within the `update-web-site` branch, you will make changes to the web site. In `index.html`, add a footer tag. Within the footer, add copyright information. Add a bit of text which reads "Last updated:" and the date. In the style sheet, change the font so it uses one from Google Fonts.

10. When finished, commit these changes together in a single commit.

11. Push all three branches (`master`, `fix-typo`, `update-web-site`) to GitHub using the following command: `git push origin --all`. Check on GitHub.com to see that all the branches are there.

12. Email Prof. Brown the link to your repo no later than Noon on Wednesday, Sept. 18.


## Grading

Projects submitted past the due date will receive a zero (0).

Submissions will receive deductions for any missed steps as well as the following:

- Incorrect git configuration.
- Poor commit messages.


## Warning

It is worth noting, I am aware this exercise can be completed with the use of a graphical user interface application (i.e. GitHub Desktop). Use of such an application on this assignment will be considered cheating.

If at any point during the semester it is determined the work has been submitted inappropriately, the assignment will be retroactively changed to a zero (0) and further penalties as specified in the syllabus will apply.

**Good luck!**
