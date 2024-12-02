# Run the following commands to ensure Git is still properly configured:
#	1.	Check the remote connections:
git remote -v

# The output should still list origin and upstream.
# 2.	Run a Git status check:
git status

# This ensures Git recognizes the repository in its new location
# Step: Test the Syncing
# 	1.	Fetch updates from the upstream repository:

git fetch upstream


# 	2.	Merge upstream changes into your local branch:

git merge upstream/main


# 	3.	Push changes to your fork:
# If you’ve made changes locally and want to push them to your fork:

git push origin main

# 	•	Use git log to check the commit history and ensure the merge commit is included:
git log --oneline