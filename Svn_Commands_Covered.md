# Introduction #
This page lists the various commands that are covered in this svnjc app. including the possible input and output parameters


# API Guidelines #
## Add ##
**purpose** : to simulate "svn add" command using SVNKit Java Library    <br />
**External parameters**  :  (**)WC\_Dir (Current Working Directory)**<br />
**Outputs**<br />
**as retrun value** : ---<br />

## Checkout ##
**purpose** : to simulate "svn co" command using SVNKit Java Library <br />
**External parameters**  :  (**)WC\_Dir and (**) SVN\_URL  <br />
**Outputs**<br />
**as retrun value** : revision no. br/>
**returned files** :  the files are checked out into the WC\_Dir<br />

## Cleanup ##
**purpose** : to simulate "svn cleanup" command using SVNKit Java Library <br />
**External parameters**  :  (**)WC\_Dir**<br />
**Outputs**<br />
**as retrun value** : none <br />

## Commit ##
**purpose** : to simulate "svn ci" command using SVNKit Java Library <br />
**External parameters**  :  (**)WC\_Dir**<br />
**Outputs**<br />
**as retrun value** : SVNCommitInfo<br />
**message** :  Same message that we see while checking in using svn client<br />

## Copy ##
**purpose** : to simulate "svn copy" command using SVNKit Java Library <br />
**External parameters**  :  (**)URL1 (**)Branch\_URL and (**)Message to commit**<br />
**Outputs**<br />
**as retrun value** : SVNCommitInfo<br />
**message** :  Same message that we see while checking in using svn client<br />

## Delete ##
**purpose** : to simulate "svn del" command using SVNKit Java Library<br />
**External parameters**  :  (**)WC\_Dir**<br />
**Outputs**<br />
**as retrun value** : ---<br />

## Diff ##
**purpose** : to simulate "svn diff" command using SVNKit Java Library<br />
**External parameters**  :  (**)WC\_Dir**<br />
**Outputs**<br />
**as retrun value** : ---<br />
**message** :  Same message that we see while finding diff using svn client<br />

## Info ##
**purpose** : to simulate "svn info" command using SVNKit Java Library<br />
**External parameters**  :  (**)WC\_Dir**<br />
[**Outputs**: <br />  **as retrun value** : ---<br />  **message** :  Same message that we see while finding info using svn client<br />

### Log ###
**purpose** : to simulate "svn log" command using SVNKit Java Library<br />
**External parameters**  :  (**)WC\_Dir**<br />
**Outputs** : **as retrun value** : SVNLogClient<br /> **message** :  Same message that we see while finding log using svn client<br />

### Merge ###
**purpose** : to simulate "svn merge" command using SVNKit Java Library<br />
**External parameters**  :  (**)url1 (**)url2 and (**)target\_path**<br />
**Outputs**<br />
**as retrun value** : none<br />

### Resolved ###
**purpose** : to simulate "svn resolved" command using SVNKit Java Library<br />
**External parameters**  :  (**)WC\_Dir**<br />
**Outputs**<br />
**as retrun value** : ---<br />

### Revert ###
**purpose** : to simulate "svn revert" command using SVNKit Java Library<br />
**External parameters**  :  (**)WC\_Dir**<br />
**Outputs**<br />**as retrun value** : ---<br />

### Status ###
**purpose** :   to simulate "svn status" command using SVNKit Java Library <br />
**External parameters**  :  (**)WC\_Dir**<br />
**Outputs**<br /> **as retrun value** : ---<br /> **message** :  Same message that we see while finding status using svn client<br />

### Update ###
**purpose** : to simulate "svn update" command using SVNKit Java Library<br />
**External parameters**  :  (**)WC\_Dir**<br />
**Outputs**<br /> **as retrun value** : updated revision info<br /> **returned files** : list of fies updated & the old and latest revision no. <br />