# Utilities

Bash Scripts that I have found useful over time and would like to preserve and/or share.
Some of these will be more useful to people than others. "getignore" could feasibly be a valuable utility to anybody who frequently creates software projects. "obsdaily", on the other hand, is hard coded to my file system and would need to be refactored to be useful to anybody but me.
These are free to do with as you like, they are not licensed.
They are also not maintained in any structured way. They get updates/fixes if and when I choose.

## getignore
Get gitignore
'getignore' is a utility written to fetch .gitignore template files from the gitignore template repository on GitHub. It can list all available files, download any one, and append to existing .gitignore files. Searching the list can be done with 'getignore --list | grep -i [searchterm]'

## steen
STart Ec2 ENvironment
'steen' is a CLI utility for managing running AWS EC2 instances. It can start, stop or check the status of any running EC2 instance by name or ID.

## progstat
Program Status
'progstat' is a small bash script I wrote for checking a list of git repos.
This one has limited value to anyone other than me. All of the values are hard coded. You can probably skip this one unless you really want to modify it to your uses.

## obsdaily
Obsidian Daily GitHub Push
'obsdaily' is the script called by Windows Task Scheduler to automatically commit and push my Obsidian notes once per day.
