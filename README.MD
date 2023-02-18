# Practice Repository


## Main Flow

<img src="sources/git_flow.svg">

After cloning repository locally all new features starts from <code>develop</code> branch.

1 - For creating new feature branch please use the next command: </br>
<code>git checkout -b feature/feature_name</code>

2 - After that when you have added changes in your local feature branch you need to commit you changes with:</br> 
<code>git commit -m "Message text"</code>

3 - Then, you need to push your changes to remote:</br>
<code>git push origin feature_name</code>

4 - Create a PR and assign any developer to review it.

5 - Do the requested changes, if necessary, until approval

6 - Merge into <code>develop</code> and delete your feature branch

7 - When you're ready for release, you need to create PR for merging <code>develop</code> branch into <code>release</code> branch.

8 - The same steps you can use with merge from <code>release</code> into <code>main</code> branch.

9 - For hotfixes create <code>hotfix</code> branch from <code>main</code> branch:</br>

<code>git checkout -b hotfix</code>

10 - After changes commit and push in remote <code>hotfix</code> branch

11 - Create PR for merging changes in <code>main</code> branch and <code>develop</code> branch separately.

Thanks