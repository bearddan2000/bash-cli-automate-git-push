# bash-cli-automate-git-push

## Description
Automates github push; adds
`topics` and `description`.

Checks to see if repo exists prior to
creating one.

## Step 1
Create a ssh key for github id on host computer.

## Step 2
Create SSH Token on github.co
Paste ssh key from host in SSH TOKEN
on github.

## Step 3
Create OAuth token (this is the 32 character TOKEN
  used in the bash script)

## Tech stack
- bash
- github
- curl
- ruby

## BUG Notes
Sometimes `topics` aren't created.

## To run
`./git.sh`
