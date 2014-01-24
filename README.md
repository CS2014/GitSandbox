Simple Git Tutorial


git clone SERVER_LINK_GITHUB
	- copy the repository to your local machine.
-- 

git pull
	- Gets the changes from the server and attempts to merge them with any local changes
git push
	- Pushes any commits you have made locally to server
git commit -a -m "COMMIT MESSAGE"
	- Commit any changes LOCALLY. Any changes made after this and the git push will not be tracked on the server
git add .
	- Add any new files you've created to tracking. You'll need to commit afterwards

--

git status
	- Shows the LOCAL status of your git repo. Let's you know if you've got uncommitted changes or un-added files
git log
	- Shows a list of changes made on the server.

--


How to add a new changes to be tracked:
1. pull changes from the server. 	git pull
2. Commit your changes locally. 	git commit -a -m "I made changes!"
3. Push these changes to remote 	git push

How to add a new files to be tracked:
1. pull changes from the server. 	git pull
2. Add the new file to be tracked	git add .
3. Commit your changes locally. 	git commit -a -m "I made changes!"
4. Push these changes to remote 	git push