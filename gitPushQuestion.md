Can I push to GitHub IF the repo was created in cmd?

I made a file
    echo "#training-joe" >> README.md
Then
    git init
    git add README.md
    git commit -m "first terminal commit"
 Error is git push.
    git push 


echo "#training-joe" >> helpme1.md
echo "#training-joe" >> pikachoo.md



(base) josephcagney@josephs-mbp training % echo "#training-joe" >> README.md

(base) josephcagney@josephs-mbp training % ls
README.md

(base) josephcagney@josephs-mbp training % git init
Reinitialized existing Git repository in /Users/josephcagney/Desktop/Study/LumifyCFSD/training/.git/
(base) josephcagney@josephs-mbp training % git add README.md
(base) josephcagney@josephs-mbp training % git commit -m "first terminal commit"

[main (root-commit) a0ea68c] first terminal commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

(base) josephcagney@josephs-mbp training % git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>
Git remote add origin [url goes here]
git remote add origin 
and then push using the remote name


https://github.com/joecags/library.git

    git push <name>


git mv -v <> <>