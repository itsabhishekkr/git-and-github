# Version control
## Change Git Username and Email Globally
`git config --global user.name "Your New Name"`
<br>
`git config --global user.email "your.email@example.com"`
## set the local username and email
`git config user.name "Your New Name"`
<br>
`git config user.email "your.email@example.com"`
## Verify the Change
`git config --global --list`

`git config --list`

`git config user.name`

`git config user.email`

## for push all code 
`git init`<br>
`git add README.md`<br>
`git commit -m "first commit"`<br>
`git branch -M main`<br>
`git remote add origin https://github.com/itsabhishekkr/soft-engg`<br>
`git remote -v` check the remote path <br>
`git push -u origin main`<br>
## for clone from other repo
`git clone https://github.com/itsabhishekkr/soft-engg.git`<br>
`git remote add origin https://github.com/itsabhishekkr/soft-engg`<br>
`git branch -M main`<br>
`git push -u origin main`<br>

## Fetch changes from remote
`git fetch origin`<br>
## Pull (fetch + merge)
`git pull origin main`<br>
`git pull --rebase`<br>

## force push
`git push origin main --force`<br>
