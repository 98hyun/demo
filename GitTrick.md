# [GitTrick](https://learngitbranching.js.org/?locale=ko)

> branch  

make and checkout branch 'develop'

`git checkout -b develop`  

> merge   

merge develop to origin(set origin)

`git merge develop` 

> rebase  

make one line, but remain somewhere.(i don't know.)   
git rebase {you want to go.}. so set node which you want to move.  

`git rebase main`

plus rebase {thing} to {here}  

`git rebase here thing`  

> Relative reference 

you have to know where is 'HEAD' 

`git checkout HEAD~3` 

`git branch -f main HEAD~3`   

> reset, revert 

if you want to go back, use 'reset'.  
if you want to go back, but remain record. use 'revert' 

`git reset`   
`git revert pushed`  

> cherry-pick 

if you want to copy but remain original.(not rebase)   

`git cherry-pick c4 c6 c7`  

> interactive rebase  

if you want to copy but, pick and omit. 

`git rebase -i HEAD~4`

> tag 

usually, release update version. 

`git tag v1 hash`  
`git show tag`

> fakeTeamwork

i don't what for.  

`git fakeTeamwork 2`  
