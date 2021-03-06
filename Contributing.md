# Idea Lab💡

***Collaborative space for developers, designers and artists to share and work with their ideas.***

---

🎉***First off, thanks for taking the time out of your schedule and deciding to contribute here!*** 👍

* This repository is open for all contributions, and is accepting contributions under under [DWOC (Devscript Winter of Code)](https://devscript.tech/) by [Devscript, India](https://devscript.tech/woc/). Any kind of updation, addition, modification and other valuable contributions are welcome.

* In case you're new to open source and contributing, be sure to read about [GitHub](https://guides.github.com/activities/hello-world/#:~:text=GitHub%20is%20a%20code%20hosting,%2C%20commits%2C%20and%20Pull%20Requests.), [GitHub Guide](https://guides.github.com/), [GitHub Open Source](https://github.com/open-source), and you are encouraged to check [OpenSource Guide](http://opensource.guide/).

* Please feel free to open new issues and pull requests, wherever needed.

* Every contribution counts, and will go a long way towards betterment of the code and/or its related files.

## Assistance to get started:page_facing_up:

If you're new to contributing and have no idea about working with repositories, be sure to check [GitHub docs to getting started](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github) from GitHub may also be helpful to refer.

## Essential Guidelines for contribution against Devscript Winter of Code::bookmark_tabs:

Before you start off with the contribution, 

:bulb: Be sure to look into, and adhere to these points: 

* First comment on the opened issues on which you want to work as "Can I take up the work ?","I would like to work on this!",etc.:loudspeaker:

* Wait for ***approval***. After it's assigned to you then move on further, fork the repository and clone it (if haven't yet done) and start your work according to the guidelines given in the [README.md](https://github.com/bhavesh1129/idea-lab/blob/main/README.md) of repository.

## Steps to Contribute in GitHub Repository:pushpin:

***If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git/).***

### 1. Fork this repository 🚀

* Fork this repository by clicking on the fork button on the top of this page.
<p align="center">
    <img src="https://raw.githubusercontent.com/bhavesh1129/orphan_support-php/main/assets/img/fork.png"/>
  </a>
 
* This will create a copy of this repository in your account.

### 2. Clone the repository 🏁
 
* Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

* After cloning the repository, please read and understand what the existing code or document is meant for, before overwriting it with your changes. If you're unsure about any part, feel free to ask it in discussions, and we'd be happy to help.
<p align="center">
    <img src="https://github.com/bhavesh1129/idea-lab/blob/main/Contributing%20File%20Images/clone.png">
  </a>
 
* Open a terminal and run the following git command:

```
git clone "https://github.com/bhavesh1129/idea-lab.git"
```

### 3. Navigate to the project directory.⚓

* Change to the repository directory on your computer (if you are not already there):

```
cd Idea Lab
```
<p align="center">
    <img src="https://github.com/bhavesh1129/idea-lab/blob/main/Contributing%20File%20Images/cd.PNG">
  </a>
  
### 4.Install dependencies by running this command on terminal (Make sure node package manager is installed, if not, get it from [here](https://nodejs.org/en/download/package-manager/)):point_left:

```npm install```

### 5.Start the project on Localhost:woman_technologist:

```npm start```

### 6. Add a reference to the original repository.:ledger:

```
git remote add upstream https://github.com/bhavesh1129/idea-lab.git (URL of the repository)
```

<p align="center">
    <img src="https://github.com/bhavesh1129/idea-lab/blob/main/Contributing%20File%20Images/remote.PNG">
  </a>
  
### 7. See latest changes to the repository using following command::arrow_left:

```
git remote -v
```

<p align="center">
    <img src="https://github.com/bhavesh1129/idea-lab/blob/main/Contributing%20File%20Images/remote%20v.PNG">
  </a>
  
### 8. Now create a branch using::dna:

```
git checkout -b <your-new-branch-name>
```

<p align="center">
    <img src="https://github.com/bhavesh1129/idea-lab/blob/main/Contributing%20File%20Images/checkout.PNG">
  </a>
  
### 9. Take a pull from the upstream repository to your master branch to keep it at par with the main project.:arrow_up:

```
git pull upstream master
```

<p align="center">
    <img src="https://github.com/bhavesh1129/idea-lab/blob/main/Contributing%20File%20Images/pull.PNG">
  </a>
  

### 10. Make necessary changes🚏

* Do the necessary changes.

* If you go to the project directory and execute the command `git status`, you'll see there are changes.

* Add those changes to the branch you just created using the `git add` command:
```
git add .
```
<p align="center">
    <img src="https://github.com/bhavesh1129/idea-lab/blob/main/Contributing%20File%20Images/add.PNG">
  </a>


### 11. Now Commit those changes::fountain_pen:

```
git commit -m "(Add your message here)"
```
<p align="center">
    <img src="https://github.com/bhavesh1129/idea-lab/blob/main/Contributing%20File%20Images/commit.PNG">
  </a>

### 12. Push changes to GitHub 🪂

* Push your changes using:

```
git push origin <branch-name>
```

<p align="center">
    <img src="https://github.com/bhavesh1129/idea-lab/blob/main/Contributing%20File%20Images/push.PNG">
  </a>

### 13. Submit your changes for review 🚩

* If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<p align="center">
    <img src="https://raw.githubusercontent.com/bhavesh1129/orphan_support-php/main/assets/img/compare.png">
  </a>

* Now submit the pull request.

<p align="center">
    <img src="https://raw.githubusercontent.com/bhavesh1129/orphan_support-php/main/assets/img/pullrequest.png">
  </a>

* Soon we will be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.
---

## More Contribution Guidelines :guard::page_with_curl:

 1. Issues will be assigned on a first come first serve basis.
 2. Maximum two active issues can be assigned to a single individual.
 3. Mention the essential details, like programmming language you want to work in, while asking for issues.
 4. Make a separate branch for each issue, and use appropriate branch names for the same.
 5. Write clean and easy to understand code. Avoid copy pasting code, we're strictly against plagiarism! 
 6. Provide comments wherever necessary.
 7. Add a README.md to the folders included, explaining the working of the script.
 8. Add an appropriate screenshot of output or demo in the README.
 9. Add a "requirements.txt" file that enlists the program requirements, in case dependencies are required.
10. Perform a self-review before submitting the PR and wait for the mentors to review it and merge.

### :ribbon: **Please go through the following essential steps for successfully submitting a Pull Request here:** :rocket:

1. Star :star: (Optional, will help you stay up-to-date about the later changes in the base repository) and Fork this repository. :checkered_flag:

2. Clone it :globe_with_meridians: using command `git clone <Your_Forked_Repo_URL_Here>` in your CLI. This will download and save a folder for your existing repository, locally in your machine.

3. Switch to a branch using `git checkout -b <branchName>`, in which you are required to work (usually it is 'main' or 'master', but for our cases, it'll be "dev_username". In place of username, mention your GitHub username). Remember, do not directly checkout from 'master' branch of your forked repository.

4. Check existing files, and make your desired updations.

5. Open a command prompt/terminal :man_technologist: in the same directory and enter `git add .` or `git add -A`. This adds all the files for tracking and will be including them in the next commit.

6. Commit your changes :memo: with `git commit -m "<Your One-Liner Commit Message>"`. In place of message, put a valuable and meaningful message so that it is easier for us to understand the changes you have done. This commits your changes locally.

7. Use `git pull -u` or `git pull --set-upstream origin <branchName>` (The `-u` or `--set-upstream` flag only needs to be used in the first time. For later use, `git pull` can be used without any additional flags). This pulls any further changes from the server and ensures that the local branch is again up-to-date with the remote server. 

8. Push your changes :arrow_up: to remote server using `git push` or `git push origin <branchName>`. This pushes your changes to the repository.

After following these steps in Git CLI (in order), you'll need to go to your GitHub repository in the website to initiate a new Pull Request. Now create a pull request by comparing 'dev_username' branch of your forked repository with 'master' branch of this upstream repository. :confetti_ball:

***:trophy: After this, project leaders and mentors will review the changes and will merge your PR if they are found good, otherwise we will suggest the required changes.***

## Style Guides for Git Commit Messages:memo:

#### Here's a list of some good to have points, that can add more value to your contribution logs.

- Use the present tense (example: "Add feature" and not "Added feature")
- Use the imperative mood (example: "Move item to...", instead of "Moves item to...")
- Limit the first line (also called subject line) to 50 characters or less
- Capitalize the subject line
- Separate subject from body with a blank line
- Do not end the subject line with a period
- Wrap the body at 72 characters
- Use the body to explain what, why, vs, and how
- Reference issues and pull requests liberally after the first line

For more detailed reference to the above points, refer here: [https://chris.beams.io/posts/git-commit/].


### So, what are you waiting for? Begin contributing now! :fire: :rocket:

#### All the Best!🥇


