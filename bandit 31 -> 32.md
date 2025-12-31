# Bandit level 31 -> 32

## Objective  
To retrieve the password from a Git repository by pushing a required file.

## Commands Used  
git clone ssh://bandit31-git@bandit.labs.overthewire.org:2220/home/bandit31-git/repo  
cd repo  
cat README.md  
echo "May I come in?" > key.txt  
git add -f key.txt  
git commit -m "Add key.txt"  
git push

## Explanation  
First, the Git repository was cloned and the README file was checked.  
The README explained that certain files were blocked using .gitignore.  
A file named key.txt was created with the required content.  
The file was force-added using git add -f to bypass .gitignore.  
After committing the file, it was pushed to the remote repository.  
The password was shown after the push was completed.

## Outcomes  
Learned how to force-add ignored files and push them to a remote repository.  
flag: 3O9RfhqyAIVBEZpVb6LYStshZoqoSx5K
