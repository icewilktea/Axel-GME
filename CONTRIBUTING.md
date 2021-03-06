# Contribution Guidelines

There are some guildelines which everyone should follow while contributing to this opensource project. While working in large teams, it is necessary to follow these steps to avoid any conflicts in the code and continue a smooth flow of collaboration amongst the developers.

## Please follow these steps if you wish to contribute to the project:

1. Go through the Issues tab to see if, what you want is already in discussion.

2. Open a new issue if you do not find what you need. Describe the bug, feature request, problems, additions you might want or anything clearly in the Issue message.

3. Mention in the Issues tab that you want to work on it.

4. Wait for the approval from the maintainers of this project before starting to work on it.

5. Create a pull request after making the changes and mention the issue number that your pull request is related to.

6. Make the required changes if the reviewer asks for them. 

7. That's it! Your pull request will be merged once everything seems okay.

**Watch this video if you are new to GitHub - [YouTube Link](https://youtu.be/HbSjyU2vf6Y)**

## 1. Fork the repository

First step is to fork this repository (seanshin2647/Axel-GME) to your GitHub account. You can do this by clicking on the fork button provided in the top right corner of the repo page. 

Also, star and watch the repository to receive all the updates directly to your mail.

**How to fork a repository? - [YouTube Link](https://youtu.be/HbSjyU2vf6Y?t=101)**

## 2. Clone the forked repository to your system

Clone the repository that you just forked into your account.
Be careful to clone the forked repo (your-username/Axel-GME) and not the main repo (seanshin2647/Axel-GME) as making direct changes to the main repo will result in conflict of code and lack of co-ordination as we proceed further.

The forked repository will have your username in the top left corner and the clone link will also contain your username (https://github.com/your-username/Axel-GME.git).

**How to clone a forked repo? - [YouTube Link](https://youtu.be/HbSjyU2vf6Y?t=134)**

## 3. Add the main repository as remote upstream

Now, you have the repository on your system and you are ready to make changes. But what if someone else changes the same thing that you just did?

To avoid any conflicts, you need to pull all the changes from the main repository. 

So, after cloning the forked repository (your-username/skill-board) to your system, use the command `git remote add upstream https://github.com/seanshin2647/Axel-GME` to point to the main repository. You only need to do this once.

Now, after making any changes to your project on the system, follow these simple steps to push your work to the repository:

`git add .`

`git commit -m "Commit Message"`

`git pull upstream master` *This command checks for any conflicts with the main repo. Go through the conflicts and make changes, if required.*

`git push`

When you write your commit message, make sure to write it in a way that will fit into the following format, "This commit is intended to do X" (X is your commit message). Do not end it with a period.

**How to set up a remote repository - [YouTube Link](https://youtu.be/-zvHQXnBO6c)**

## 4. Create a pull request

After pushing the changes to your forked repository (your-username/Axel-GME), all you have to do is create a new pull request from your account by simply clicking on the *Pull Request* button.

> NOTE:
> If you are some commits behind of Axel-GME:master then you need to first git pull upstream master from the system, push it to your forked repository and then create the Pull Request.

Give a detailed and useful explaination of what you did in the comments of pull requests and someone from the maintainers or team leads will review the code and accept the pull request or ask you to change some things before merging it.

**How to create a pull request? - [YouTube Link](https://youtu.be/HbSjyU2vf6Y?t=297)**
