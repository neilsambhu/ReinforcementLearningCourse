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
12/9/2023 9:51 PM: there is a manual setting of the upstream for the push command
```
(base) nsambhu@CSE001022:~/github/ReinforcementLearningCourse$ git push origin
fatal: The current branch NeilBranch0 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin NeilBranch0

(base) nsambhu@CSE001022:~/github/ReinforcementLearningCourse$ git push --set-upstream origin NeilBranch0 
```
12/9/2023 9:53 PM: TODO: create Anaconda environment.  
12/9/2023 10:12 PM: TODO: work on coding example.  
```
pip install jupyterlab
```
```
jupyter lab
```
12/9/2023 10:20 PM: pip install of stable-baselines3 does not work. TODO: downgrade python to 3.8.  
12/9/2023 10:25 PM: python 3.8 worked.  
12/9/2023 10:46 PM: environment step function gives 5 values. TODO: try python 3.7.  
12/9/2023 10:55 PM: there are still 5 values from the step function  
12/9/2023 11:09 PM: I added the truncated value as an output from the step function.  
12/10/2023 1:36 PM: python command
```
(RLC2) nsambhu@CSE001022:~/github/ReinforcementLearningCourse$ jupyter lab
```