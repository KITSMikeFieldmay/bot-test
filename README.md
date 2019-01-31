# bot-test
Re change add

https://github.com/bobvanderlinden/probot-auto-merge

### instructions 
 - add .github/auto-merge.yml to master
 - add label 'readyForAutoMerge'

check if after rebase it runs the checks and is it necessary


Repository is configured so that out of date branches can be merged (by rebase).
Can the above cause an issue ?
 
It should be safe as merge method is set to rebase so history should be fine,
possible conflicts should still prevent from merging.

There is an option to automatically update the branches but the ony available method is merge changes (same functionality as 'Update branch' button). 

Repo is configured so that branches can be merged only by rebase (in case of and auto-bot manual merges)