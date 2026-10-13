Day 1 (12-10-2026)

Tasks
Install Git, Python, Docker. Create the Devos-bootcamp GitHub repo with README and .gitignore. i connected the remote repo with the local. 

challenges
i had probelems pushing to the remote repo because both repos were created seperately with commits in both. i had to use "git pull origin main allow-unrelated-histories" with the unrelated histories flag to pull remote state before pushing with 'git push -u origin main'. the -u flag , flags the main branch as the upstream tracker.

Day 2 (13-10-2026)

Tasks
Created a virtual environment for python 

commands
python3 -m venv devops-bootcamp
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
.\devops-bootcamp\Scripts\Activate.ps1

challenges
the first time you ran .\devops-bootcamp\Scripts\Activate.ps1 to activate the devops-bootcamp virtual environment on powershell, i got a bright  bright red "Execution Policy" error. so i set the execution policy with Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process and ran the activation command again. this time it worked.