# git

// create a new repository
# git init	

// checkout a repository
# git clone /path/to/repository
# git clone username@host:/path/to/repository

// Add
# git add <filename>
# git add *

// Commit
# git commit -m "Commit message"

// Push changes
# git push origin master

// Link to the repository
# git remote add origin <server>

// Delete file
# rm arq1.txt
# git rm --cache arq1.txt
# git push origin master

// Save password
// Set git to use the credential memory cache
# git config --global credential.helper cache
# git config --global user.name "your username"
# git config --global user.password "your password"
