# Stat-Mech-Mini-Project
This is the repository for Advanced Statistical Mechanics Mini Project as part of coursework. Collaborators can upload/edit codes regularly here.

##Message to collaborators

#If you are using GitHub to do edits.
If you want to edit the code by copying to your pc and pasting it totally in github again, I wouldn't recommend it because when you do that GitHub will lose the edit history and show that the whole code is changed instead of whatever line you have edited. So it would be easier and organised if you can edit the specific line instead in GitHub.

#Another way in editing the code, in a easier way(Starting would be difficulty a little) using Git in PC (works in all OS)

First install Git in your system (You can install in Visual Studio directly if windows).

Second, you can connect your git in pc to your GitHub profile by email address.

Now you can clone this repository using SSH (would recommend this because, if you have your SSH public-key given in your GitHub you dont need to type your GitHub password to push (I think the other way is stopped but anyway use SSH). If you don't know how to create public and private key for your PC, refer internet sources on how to create those. And to add public-key to GitHub, refer to your settings --> Advanced.

Once all this done, now you can clone this repo using the following command "git clone SSH-of-repository" (SSH of repository can be found from GitHub --> repository --> code button --> SSH

once you clone it, you have the GitHub repository in your local system.

you can edit now. 

once your edit is done and ready to send the edit from local system to repository, you need to add the edited files using the command "git add ." ( ' . ' is to take all the files which you have edited, if you want to push just one file instead of other edited files, instead of ' . ' use the file name.

Now, add commit (which is basically a comment in git) for the edit using the command "git commit -m "whatever the comment is" " (write the comment inbetween " ", don't leave the "")

Now everything is done, you just need to send them to repository using the command " git push "

you are done, but wait what if someone else edited it in repository and you need to be up to date with that repository? use the command " git pull " to get the updated version of repository.

That's all
