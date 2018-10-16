# useful-commands

About GIT

Git is, first and foremost, a version control system (vcs) and it is an open source.

There are two types of VCS
1) Distributed version control system
2) Centralized version control system

There are many versions  control system out of which CVS, SVN, Mercurial, Fossil etc.

Git is also called as Source Code Management (SCM)

With Git, 3 basic issues where solved when working on projects. They are,


1) It has made easier to manage large projects.
2) It helps you to avoid overwriting the team' advances and work
3)Just push the code to the git repository. Its very simple and light weight

Files in a repository go through three stages before being under version control with git

1) Working directory (Untracked)
2) Staging (staged)
3) Committed

GIT commands

git --version

git config --global user.name "name"
git config --global user.email
email@address.com

git init

git config --list 

git clone

git --help

git add filename

git add .

git commit -m "any message"

git commit -a -m "anymessage"

git push

git pull

git log

git status

git remote add anyname url_of_empty_repository

git push origin master

git branch branchname

git checkout branchname

git merge branchname1 branchname2 (master stl)master

git rebase branchname1 branchname2

git branch -m old_branch_name new_branch_name // branch rename

git branch -d branchname1 //delete the merged branch

git branch -d -r origin/branch_name origin/branch_name origin // to delete the remote branch

git push origin --delete branchname  // delete the mranch from remote

git diff

git revert HEAD

git reset

git resetgit push origin master --force

git log --graph --oneline --decorate

git --help

git --help command

git blame filename

git clean -df

git -n clean

git -dn clean

git ls-files --stage

git ls-files --cached

git ls-files --modified

git ls-files --others

git ls-files --deleted

git ls-files --unmergerd

git ls-files --killed

git format-patch COMMIT_ID

git fetch origin




------------------------------------------------------------------------------------------------------------------------
ANT COMMANDS

ant clean

ant validate

ant test

ant deploy

ant compile
------------------------------------------------------------------------------------------------------------------------
MAVEN COMMANDS

mvn archetype:create
-DgroupId=org.yourcompany.project
--DartifactId=application


mvn archetype:create
-DgroupId=org.yourcompany.project
--DartifactId=application
-DarchetypeArtifactId=maven-archetype-webapp

mvn clean

mvn validate

mvn compile

mvn verify

mvn install

mvn clean install

mvn test

mvn deploy

mvn package

mvn deploy:deploy-file -Dfile=/path/to/jar/file -DrepositoryId=repos-server -Durl=http://repos.company.org/test -DgroupId=javax
-DartifactId=mail -Dpackaging=jar
-Dversion=1.0.1


------------------------------------------------------------------------------------------------------------------------
GRADLE COMMANDS

gradle clean
gradle assemble
gradle build

------------------------------------------------------------------------------------------------------------------------


