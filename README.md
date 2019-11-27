# common-utility
Common utility implementation where it can use any java project. 


# Adding this as submodule:
Clone your repo. 
Ex : git clone https://github.com/chamlyidunil/test-submodule-project.git

then go to new project folder. 
Ex : test-submodule-project

Then add this repo as submodule 
Ex : git submodule add https://chamlyidunil@github.com/chamlyidunil/common-utility.git

Then common-utility folder will create and common-utility repo clone into that project. 
also .gitmodules will create in current folder. 
.gitmodules looks like 
[submodule "common-utility"]
	path = common-utility
	url = https://chamlyidunil@github.com/chamlyidunil/common-utility.git
  
# get update from submodules
git submodule foreach git pull

# Commit submodule changes. 


cd common-utility - then git commit. 

# reference URL
https://stackoverflow.com/questions/1030169/easy-way-to-pull-latest-of-all-git-submodules

https://mirrors.edge.kernel.org/pub/software/scm/git/docs/git-submodule.html
