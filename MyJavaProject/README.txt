Creating an Eclipse Project in Eclipse

GITHUB.COM
https://github.com/new
SoftDevJohn/MyGitEclipse
(*) Public
[*] Initialize this repository with a README
Create Repository
Clone or Download
https://github.com/SoftDevJohn/MyGitEclipse.git

Eclipse
1) Tell Eclipse about the Git Repository
Window>Perspective>Open Perspective>Other>Git>Open
Clone a Git Repository and add the clone to this view>
URI: https://github.com/SoftDevJohn/MyGitEclipse.git
>Next>Next
Directory: C:\Users\John\JavaTestProjects\MyGitEclipse
>Finish
{MyGitEclipse appears in the Git Repositories window}

Next Create the actual Java Project
File>New>Project>Java>Java Project
>Next
Project Name: MyGitProject>
Location: C:\Users\eclipse-workspace\MyGitProject
Finish
{
This creates MyGitProject with the following sub-directories:
.settngs
.classpath#.project
}
Select MyGitProject>RC>Team>Commit
Copy the files from "Unstaged changes" to "Stages changes"
>Commit and Push
