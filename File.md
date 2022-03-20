# Commit 0
git init
git add File.md
git commit -m "Commit 0"
# Commit 3
## Getting a list of commit hashes so I know what commit 0 was. Commit 0 hash first 4 chars: f4f3.
git log
git branch bug-fix f4f3
git checkout bug-fix
git add .
git commit -m "Commit 3"