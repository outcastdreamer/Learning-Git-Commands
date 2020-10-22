<h1 align="center"> GIT COMMANDS FOR HACKTOBERFEST</h1>
<hr> 

This repository was created for my session on Opensource, Git & Github
held via Developer Student Club REVA for Hacktoberfest event.

<hr>

Note : 
-> "#" refers as comment (don't include it in the cmd command)			
-> keyword refers to origin or whatever you have used for storing remote git link of your repo.

<hr>

<pre>			
			<b>GLOBAL CONFIG LEVEL (One time setup)</b>

1. git config --global user.name "username"
2. git config --global user.email "email@email.com"
<hr>

			<b>PROJECT LEVEL  (Everytime a new project is made)</b>

3. open cmd in the current folder
4. git init
5. git remote add keyword &lt;link&gt;

Note : Make sure that a new github repository has been made as well for this process.
<hr>

			<b>UPDATION LEVEL (Every time you make changes to your code)</b>

6 a.) git add .                          #add all files in the current working directory
	or
   b.) git add &lt;filename&gt;         #only add a specific file (not all files)
7. git status
8. git commit -m "message"        #Message can be different such as "removed bugs", etc
9. git push -u keyword master   #main (check what shows under git commit)

<hr>

			<b>ADDITIONAL COMMANDS</b>

10. git remote -v
11. git rm &lt;filename&gt; 
#Removes file that was added via git add for tracking

<hr>
			<b>For Forking other user's project</b>
			
12. Click on "fork" from their repo.			
13. git clone &lt;link&gt;             
#Of your cloned repo on your personal account

14. Make your changes to the files and send pull request

#The pull request will be added by the Repo/Main Project owner if they find
#find it beneficial to their project (removed bugs or added feature)

<hr>
		
			<b>For syncing other people's work/code which you merged from their project via forking</b>

15. git pull keyword master    

<hr>

			<b>Merging with main project (One time set up)</b>

16. Add the remote, call it "upstream":

17. git remote add upstream https://github.com/whoever/whatever.git

<hr>

			<b>Merging with main project (After One time set up is done)</b>

# Fetch all the branches of that remote into remote-tracking branches,
# such as upstream/master:

18. git pull upstream master 

# Make sure that you're on your master branch:

19. git checkout master

# Rewrite your master branch so that any commits of yours that
# aren't already in upstream/master are replayed on top of that
# other branch:

20. git rebase upstream/master  #To resolve any conflicts or clashes

<hr>

			<b>Pushing the main forked project to your personal forked project</b> 
			
21. git push -f keyword master   
#-f stands for force, in case git push keyword master doesn't work

<hr>

</pre>
   


  