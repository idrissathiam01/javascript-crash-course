## SECTION 2:  How to Manipulate DOM in JavaScript
***

<em>[http://https://www.youtube.com/watch?v=Qqx_wzMmFeA&t=1100s](Part of Qazi Rafeh's, aka Clever Programmer, JavaScript Crash Course)</em>

Import external script
>	<script type = "text/javascript" {src="javascript.js"} > (Cloze deletion)


(Git Setup Step 1) Begin Git Setup and Assign Code Changes to Username
>	git config --global user.name "Idrissa Thiam"

(Git Setup Step 2) Local Git Repo, Initialize Git and Track Code Changes to Email Address
>	git config --global user.email idrissathiam01@gmail.com

(Git Setup Step 3) Track all local changes
>	git config --global push.default matching

(Git Setup Step 4) Stage all local changes
>	git config --global alias.co checkout

(Git Setup Step 5) Initialize Git (and create repo locally)
>	git init


Stage files to local Git repo
>	git add . 

Commit changes locally
>	git commit -am "Initial commit"


(Git Setup Step 6) Create Remote repo (via Github or Bitbucket, etc)

(Git Setup Step 7) Create local ssh key
>	cat ~/.ssh/id_rsa.pub

(Git Setup Step 8) Add local ssh key remote repo

(Git Setup Step 9) Authenticate to Remote repo via CLI
>	ssh -T git@github.com

(Git Setup Step 10) Add remote repo to local Git workflow (via github)
>	git remote add origin git@github.com:idrissathiam01/{repo_name}.git

(Git Setup Step 11) Push local changes to remote repo
>	git push -u origin master




