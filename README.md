Title: "SRT411A0" 

Author: "Ivan (Avaplex)"

Name: "Ali Reza Abedzadeh""

Date: '2018-02-15'

GitHub Documents
This is an R Markdown format used for publishing markdown documents to GitHub. The R MarkDown File Generated for Github which include the result automatically is available at same repository “SRT411A0.md” https://github.com/avaplex/srt411/blob/master/SRT411A0.md
PDF File and HTML file also Available in this repository to Download

https://github.com/avaplex/srt411/blob/master/SRT411A0.pdf
https://github.com/avaplex/srt411/blob/master/SRT411A0.html

Note: HTML File should be download and open locally through your browser , you can only view the source inside the GitHub
This is an assignment from SRT411 which is for Introduction to R and Github. This assignment is base on the todo labs from PDF file named A very short introduction to R which can be download from https://cran.r-project.org/doc/contrib/Torfs+Brauer-Short-R-Intro.pdf

•	Install the knitr with R Markdown in RTUDIO
	install.packages("rmarkdown")

•	Install miktex 

•	Download and Install pandoc

•	Download and Install GitHub Git-2.16.1.4-64-bit.exe

•	Download and install git through  this link

	https://git-scm.com/downloads
	Git can also be downloaded from:
	https://github.com/git-for-windows/git/releases/
	Or any version that is suitable for your platform

•	Set up your git email by typing git config --global user.email YOUR_EMAIL. Replace YOUR_EMAIL with an email account.

•	Set up your git name by typing git config --global user.name YOUR_NAME. Replace YOUR_NAME with your full name, like John Smith.

•	Setup a Github account and a new repository using same Email
	$https://github.com/join

•	Create an SSH key in GitBash ( on you computer)
	$ssh-keygen -t rsa -b 4096 -C your_email@example.com

•	Choose a Path and Pass phrase if necessary or just press enter to accept default
	Ensure the ssh-agent is running: eval $(ssh-agent -s)

•	Add SSH Private key to your agent
	$ssh-add ~/.ssh/id_rsa

You can see and read about adding the SSH key to your GitHub account using this link:
https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/

•	Copies the contents of the id_rsa.pub file to your clipboard
	$clip < ~/.ssh/id_rsa.pub

Follow these steps in your github account
In the upper-right corner of any page, click your profile photo, then click Settings.
In the user settings sidebar, click SSH and GPG keys
Click New SSH key or Add SSH key
In the "Title" field, add a descriptive label for the new key. For example, if you're using a personal Mac, you might call this key "Personal MacBook Air".
Paste your ssh key
Click Add SSH key. 
If prompted, confirm your GitHub password.
Source for this steps:
https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/

•	Creating a repository
	$MKDIR <Folder>
	$CD <folder>
	$git init

•	To add a readme file for your git: $git add README.md
	check the git status: $git status
	When you make changes you can commit it using: $git commit -m "Initial version"
	to add all your file to git use: $git add .
	to commit a file: $git commit -m "Update README.md"

	to push a file / files to github
	$ git remote add origin
	$ git@github.com:YOUR_GITHUB_USERNAME/YOUR_GIT_REPO_NAME.git
	$ git push -u origin master

•	 (more info available here ) https://www.dataquest.io/blog/how-to-share-data-science-portfolio/

•	Now you have everything to do this project

•	Create a new .Rmd  file in your RStudio and answer the TODO sections in https://cran.r-project.org/doc/contrib/Torfs+Brauer-Short-R-Intro.pdf

Document , and the generate your RMD, MD, Write your Readme, and Generate your PDF or even World Document (As you see in follow) or HTML from your file



resources for this poroject:
https://rmarkdown.rstudio.com/
https://git-scm.com/downloads
https://nicercode.github.io/guides/reports/
http://kbroman.org/knitr_knutshell/pages/markdown.html
http://kbroman.org/knitr_knutshell/pages/Rmarkdown.html
https://cran.r-project.org/doc/contrib/Torfs+Brauer-Short-R-Intro.pdf
https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/
https://www.dataquest.io/blog/how-to-share-data-science-portfolio/
https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf
https://cran.r-project.org/doc/contrib/Torfs+Brauer-Short-R-Intro.pdf
