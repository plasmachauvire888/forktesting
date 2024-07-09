# forktesting
Test how forks works



1. Create repo => https://github.com/plasmachauvire8/forktesting
2. Push on it
3. Fork repo on git using Fork button => https://github.com/plasmachauvire888/forktesting
4. Push to new repo (forked version)
5. Push to original repo

Then, to rebase on orginal :
On forked version, run : 

```bash

git remote add upstream https://github.com/plasmachauvire8/forktesting
git fetch upstream
git rebase upstream/master
-- resolve conflicts
git push origin master --force
```

