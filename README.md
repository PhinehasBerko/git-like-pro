# git-like-pro
learn everything about git and github

## What is “version control”
Version control is a system that records
changes to a file or set of files over time so that you can recall specific versions later

### why should you care? 
A Version Control System (VCS) is a very wise thing to use. It
 allows you to revert selected files back to a previous state, revert the entire project back to a
 previous state, compare changes over time, see who last modified something that might be causing
 a problem, who introduced an issue and when, and more. Using a VCS also generally means that if
 you screw things up or lose files, you can easily recover. 

### Different VSC available

*  Local Version Control Systems => are the simplest form of version control, and they are used primarily by solo developers rather than teams. With local version control, all project data is stored on a single computer, and changes made to project files are stored as patches.

This LVCS lacks robust features for collaboration, data security and error prone.

* Centralized Version Control Systems => there’s a central repo shared with all the developers, and everyone gets their own working copy. Whenever you commit, the changes get reflected directly in the repo. Unlike distributed systems, developers directly commit to the remote. Which means they may affect files knowingly or unknowingly.
Moreover, If that server goes down for an hour, then during that hour nobody can collaborate at all or save versioned changes to anything they’re working on. If the hard
 disk the central database is on becomes corrupted, and proper backups haven’t been kept, you lose
 absolutely everything.

*  Distributed Version Control Systems =>  In a DVCS (such as Git, Mercurial or Darcs), clients don’t just check out the latest snapshot of the files; rather, they fully mirror the
repository, including its full history.
There is a local copy of the repo for every developer on their computers. They can make whatever changes they want and commit without affecting the remote repo. They first commit in their local repo and then push the changes to the remote repo.
Furthermore, many of these systems deal pretty well with having several remote repositories they can work with, so you can collaborate with different groups of people in different ways
simultaneously within the same project. This allows you to set up several types of workflows that aren’t possible in centralized systems, such as hierarchical models.