# Commands

---

1. Create repo in GitHub
2. Create local repo with `git init`
3. Create README, add file: `git add README.md`
4. Create main/production branch: `git branch -M production`
5. Add remote origin: `git remote add origin https://github.com/mkm29/pg-do-git-branching-model.git`
6. Push to remote repo: `git push -u origin production`
7. Create HotFix branch: `git checkout -b HotFix`
8. Create Integration branch: `git checkout -b Integration`
9. `git checkout -b Feature1`
10. `git checkout -b Feature2`
11. `git checkout Feature2`
12. `touch main.py`
13. `git add main.py`
14. Add some code to `main.py`
15. `git commit -m 'Added main.py'`
16. `git push --set-upstream origin Feature2`
17. `git checkout Integration`
18. `git merge Feature2`
19. `git branch -d Feature2`
20. `git checkout Feature1`
21. `touch logging.py`
22. Add some code to `logging.py`
23. `git add logging.py`
24. `git commit -m 'Added file for basic logging`
25. `git push --set-upstream origin Feature1`
26. `git checkout Integration`
27. `git checkout Feature1`
28. `touch auth.py`
29. Add some code to `auth.py`
30. `git add auth.py`
31. `git commit -m 'Added JWT auth file'`
32. `git checkout Integration`
33. `git merge Feature1`
34. `git checkout HotFix`
35. `git merge Feature1`
36. `git checkout production `
37. `git merge Feature1`
38. Resolve merge conflict
39. `git branch -d Feature1`
40. `git checkout HotFix`
41. Change logger type in `logging.py`
42. `git add logging.py`
43. `git push --set-upstream origin HotFix`
44. `git checkout production`
45. `git merge HotFix`
46. `git checkout Integration`
47. `git merge HotFix`
