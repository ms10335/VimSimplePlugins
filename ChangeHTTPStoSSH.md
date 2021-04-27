First check if there is a remote in your repository and its name using:
git remote
if there is one, let's assume it's origin
Check the url of that remote, with:
git remote get-url origin
if it was an http address , then change it to an ssh url using the following cmd:
git remote set-url origin git@github.com:username/repository-name
