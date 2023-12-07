# Git lab 2
## Create a new project on your local machine,then push it your remote repo.
done
## Create two branches (dev & test) then create one file on each branch, and push this changes to the remote repo.
done
## Merge this changes on Master branch and then push it to your remote master branch.
done
## Tell me how to remove them locally and remotely.
locally: git branch -d dev\
remotely: git push origin :dev
## Create an annotated tag with tagname (v1.7).
git tag -a v1.7 -m "version 1.7"
## Push it to the remote repository.
git push origin v1.7
## Tell me how to list tags.
git tag
## Tell me how to delete tag locally and remotely.
locally: git tag -d v1.7\
remotely: git push origin --delete v1.7
