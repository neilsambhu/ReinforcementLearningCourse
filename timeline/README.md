# Reinforcement Learning
12/9/2023 9:32 PM: source: `https://www.youtube.com/watch?v=Mut_u40Sqz4`
12/9/2023 9:41 PM: create NeilBranch0
```
(base) nsambhu@CSE001022:~/github/ReinforcementLearningCourse$ git branch
* main
(base) nsambhu@CSE001022:~/github/ReinforcementLearningCourse$ git branch NeilBranch0
(base) nsambhu@CSE001022:~/github/ReinforcementLearningCourse$ git branch
  NeilBranch0
* main
(base) nsambhu@CSE001022:~/github/ReinforcementLearningCourse$ git checkout NeilBranch0 
Switched to branch 'NeilBranch0'
(base) nsambhu@CSE001022:~/github/ReinforcementLearningCourse$ git branch
* NeilBranch0
  main
```
12/9/2023 9:42 PM: config upstream remote
```
(base) nsambhu@CSE001022:~/github/ReinforcementLearningCourse$ git remote -v
origin	git@github.com:nicknochnack/ReinforcementLearningCourse.git (fetch)
origin	git@github.com:nicknochnack/ReinforcementLearningCourse.git (push)
(base) nsambhu@CSE001022:~/github/ReinforcementLearningCourse$ git remote add upstream git@github.com:nicknochnack/ReinforcementLearningCourse.git
(base) nsambhu@CSE001022:~/github/ReinforcementLearningCourse$ git remote -v
origin	git@github.com:nicknochnack/ReinforcementLearningCourse.git (fetch)
origin	git@github.com:nicknochnack/ReinforcementLearningCourse.git (push)
upstream	git@github.com:nicknochnack/ReinforcementLearningCourse.git (fetch)
upstream	git@github.com:nicknochnack/ReinforcementLearningCourse.git (push)
```
12/9/2023 9:46 PM: config origin remote
```
(base) nsambhu@CSE001022:~/github/ReinforcementLearningCourse$ git remote set-url origin git@github.com:neilsambhu/ReinforcementLearningCourse.git
(base) nsambhu@CSE001022:~/github/ReinforcementLearningCourse$ git remote -v
origin	git@github.com:neilsambhu/ReinforcementLearningCourse.git (fetch)
origin	git@github.com:neilsambhu/ReinforcementLearningCourse.git (push)
upstream	git@github.com:nicknochnack/ReinforcementLearningCourse.git (fetch)
upstream	git@github.com:nicknochnack/ReinforcementLearningCourse.git (push)
```