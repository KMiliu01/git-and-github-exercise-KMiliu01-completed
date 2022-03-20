# Commit 0
git init <br>
git add File.md <br>
git commit -m "Commit 0" <br>
# Commit 1
git add . <br>
git commit -m "Commit 1" <br>
# Commit 2
git add . <br>
git commit -m "Commit 2" <br>
# Commit 3
## Getting a list of commit hashes so I know what commit 0 was. Commit 0 hash first 4 chars: f4f3.
git log <br>
git branch bug-fix f4f3 <br>
git checkout bug-fix <br>
git add . <br>
git commit -m "Commit 3" <br>
# Commit 4
git add . <br>
git commit -m "Commit 4" <br>
# Commit 5
git merge master <br>
git add . <br>
git commit -m "Commit 5 - merge - conflicts solved" <br>
# Commit 6
git add . <br>
git commit -m "Commit 6" <br>
# Commit 7
## Getting hash of Commit 4 (eef6) and branching from it.
git log <br>
git checkout -b bug-fix-experimental eef6 <br>
git add . <br>
git commit -m "Commit 7" <br>
# Commit 8
git add . <br>
git commit -m "Commit 8" <br>
# Commit 9
git add . <br>
git commit -m "Commit 9" <br>
# Commit 10
git checkout master <br>
git add . <br>
git commit -m "Commit 10" <br>
# Commit 11
git checkout bug-fix <br>
git merge bug-fix-experimental <br>
git add . <br>
git commit -m "Commit 11 - merge - conflicts solved" <br>
# Commit 12
git add . <br>
git commit -m "Commit 12" <br>
# Commit 13
git checkout master <br>
git merge bug-fix <br>
git add . <br>
git commit -m "Commit 13 - merge - conflicts solved" <br>
# Commit 14
![inline](git-graph.jpg) <br>
git add . <br>
git commit -m "Commit 14 - add image" <br>