Terminal commands I'm using with Windows Powershell terminal

Thought I'd list the terminal commands I've used as a way to emphasise my learning.

cd

change directory/folder - and some variants of it's usage:

cd ..

to go back up one level

cd ~

to go back to my C:\Users\Alex directory/folder on my Windows PC

cd directoryname1/directoryname2 

etc to navigate to a specific sub directory from where I am currently located

I'm slow at this navigation business.

cd <first letters of next directory> then tap the tab key

this fills in the remaining characters for me, and if there are more than one directory starting with those letters, tapping tab again selects the next one. Nice. That makes me a little faster and reduces typo errors.

ls

list out whatever is in the directory
files, folders, anything.
using this to help me see what's in the next level down I need to navigate to.


mkdir directoryname

creating a new directory/folder with the name "directoryname"
so far I am only game to first navigate with cd commands to the directory in which I'd 
like to add a new directory, then add a new folder with mkdir. 
OK so I'm a pussy, or an octocat, but baby steps right?


git branch

shows me the various branches that exist in my "repository". Not sure if I'm using the 
term "repository" correctly.
for now I'm just going to stay in master branch and add/make changes to that. I figure 
that at the moment all I'm doing is adding text files, I can't really do much harm.
I'm not sufficiently comfortable with the relationships between what's on my PC and 
what's on my github to use branches just yet. I'm liable to get lost.


git status

tells me if I have made any changes since last "commit". Suggests perhaps I need to do a...


git add -A

which as I understand it place all changes in a "staging area", ready to be committed to 
the branch I am currently in/on/at/loitering about.
The "-A" is probably a bit over the top and no doubt I'll need to learn to be more subtle 
with my use of git add commands.


git commit -m "comments go here"

so this actually records the changes from the "staging area" into the "repository", and 
adds a new unique ID to it.
the -m "comments go here" adds some commentary to explain what the change is about.


git push origin master

now this I only partially understand. The impact of this is to copy the changes in the 
"repository" on my PC up to what's stored in my github account. That's probably not quite 
the  right way of putting it but that's what seems to happen.

It does ask me for my github username and password to complete the action.
No doubt there is a way for that to be automated so it's unnecessary to type those in 
each time.

git pull origin master

today I used this for the first time. As I was offline with internet down for the past week and a half, i was confined to occasional visits to Github via occasional remote or phone connection and so updated readme.md files via the Github interface.

I had no idea if this would correctly download/merge my Github 21-day-challenge with my local PC version.

Going through my local version shows that the directories on my PC have all updated correctly, so that's a small win and no merge conflicts. That's probably because once the net went down, I decide to not do anything with my remote while I was using Github interface to create the readme files for the challenge.