git is a way to track file changes in a repository. It's mostly used for code but you could use it for anything, like keeping group documents.

the collection of code for a project on git is called a repository
GitLab is a way to view and manage git online; GitHub etc do a similar thing. QSET uses GitLab
Git and GitLab aren't the same thing; GitLab is where you can nicely manage your git


`git clone https://code.engineering.queensu.ca/qset/rover/rover-onboarding-repo.git nameOfFolderYouWant`

# How to contribute:
pushing = pushing your changes upstream, that is the "online" version
pulling = pulling changes from upstream

# Branches
after you clone the repository, you're in the master branch by default. this is the main version, and you won't be able to push anything without a mod's permission
so you need to create your own branch so you can make changes

To switch between branches
`git checkout -b branchname`

To make a new branch
`git branch`

Files you changes (currently in staged changes)
`git branch`

Making commits (adding changes)
`git commit -m "Explain your commit`
(never add changes directly to main/master branch)




