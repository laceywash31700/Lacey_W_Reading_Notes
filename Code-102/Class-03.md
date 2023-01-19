# Class-03 Reading Notes

## What is Git?

To understand git you may want to understand the history of git. 
 
 ### History of Git
> 1. **VCS (Version Control System)** 
> - A system that allows you to revist various versions of a file. you can track modification and compare changes so, mistake can easily be remedied 
> 
> 2. **Local Version Control**
> - A local VCS on one database on your harddrive 
>
> 3. **CVCS (Centrralized Version Control)**
> - The need for collaboration lead to CVCS's becoming the next big thing in tech. This system has a single server storing all changes and file versions,
> which can be accessed by various parties. Allowing programmers to streamline the collab process by taking out the need for local drives and giving them more knowledge 
> of team members changes and giving admins more control.
>
> 4. **DVCS (Distributed Version Control)**
> - There was a problem with CVCS's. if the CVCS goes kaput you can't work on work with your team on files or save changes and if the the files on the harddrive become
> corrupted, without a backup, you are fucked and all the work you and your team did would be lost except on local hardrives. To prevent this DVCS's were invinted. 
> DVCS allowed you to mirror repos: that can be used to replace lost data. they can also make multiple mirrored repos allowing programmers to work in teams in various  > ways to complete joint projects. Which made work flow much easier, which leads us back to git.

## So, what what does that have to do with git?
 git is a version control system that allows developers to work on a code from diffrent enviorments like local and remote drives. Git is a DVCS that stores data in a 
 file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to 
 it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.
    -It relies on local operations to because most information is already avalible on local disk. this makes collaboration much faster taking out the need to fetch 
    information from a server allowing programmers to work even when offline or on a VPN.
 
 Git changed two major things in programming.
 1. It allowed you to **keep track of changes** acting as a gatekeeper and detecting file corruption or loss of information in transit.
 
 2. Git is set up to greatly minimize the possibility of **lost data** to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of 
    your file that is committed to be lost.
 
