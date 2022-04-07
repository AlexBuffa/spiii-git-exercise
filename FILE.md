git init <br>
[edit FILE.md] (master)<br>
git add FILE.md (master)<br>
git commit -m "Initial commit" (master)<br>
git branch bug-fix (master)<br>
[edit FILE.md] (master)<br>
git add FILE.md (master)<br>
git commit -m "commit 1" (master)<br>
[edit FILE.md] (master)<br>
git add FILE.md (master)<br>
git commit -m "commit 2" (master)<br>
git checkout bug-fix (master)<br>
[edit FILE.md] (bug-fix)<br>
git add FILE.md (bug-fix)<br>
git commit -m "commit 3" (bug-fix)<br>
[edit FILE.md] (bug-fix)<br>
git add FILE.md (bug-fix)<br>
git commit -m "commit 4" (bug-fix)<br>
git branch bug-fix-experimental (bug-fix)<br>
git merge master (bug-fix)<br>
[edit FILE.md, fix conflict] (bug-fix)<br>
git add FILE.md (bug-fix)<br>
git commit -m "commit 5" (bug-fix)<br>
[edit FILE.md] (bug-fix)<br>
git add FILE.md (bug-fix)<br>
git commit -m "commit 6" (bug-fix)<br>
git checkout bug-fix-experimental (bug-fix)<br>
[edit FILE.md] (bug-fix-experimental)<br>
git add FILE.md (bug-fix-experimental)<br>
git commit -m "commit 7" (bug-fix-experimental)<br>
[edit FILE.md] (bug-fix-experimental)<br>
git add FILE.md (bug-fix-experimental)<br>
git commit -m "commit 8" (bug-fix-experimental)<br>
[edit FILE.md] (bug-fix-experimental)<br>
git add FILE.md (bug-fix-experimental)<br>
git commit -m "commit 9" (bug-fix-experimental)<br>
git checkout master (bug-fix-experimental)<br>
[edit FILE.md] (master)<br>
git add FILE.md (master)<br>
git commit -m "commit 10" (master)<br>
[edit FILE.md] (bug-fix)<br>
git add FILE.md (bug-fix)<br>
git commit -m "commit 11" (bug-fix)<br>
[edit FILE.md] (bug-fix)<br>
git add FILE.md (bug-fix)<br>
git commit -m "commit 12" (bug-fix)<br>
git checkout master (bug-fix)<br>
git merge bug-fix (master)<br>
[edit FILE.md, fix conflict] (master)<br>
git add FILE.md (master)<br>
git commit -m "commit 13" (master)<br>
[edit FILE.md] (master)<br>
git add FILE.md commits.png (master)<br>
git commit -m "commit 14" (master)<br>
