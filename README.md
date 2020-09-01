# cc_week02day02

# cc_week02day02

Code used 

## created a new repo in github named 'cc_week02_day02'

In gitbash,

$ git clone URL of repo
$ cd cc_week02_day02
$ touch colour.txt

## write contents in file 'colour.txt'

$ git add .
$ git commit -m "changed to blue1"
$ git log

## contents in file 'colour.txt' updated

$ git add .
$ git commit -m "changed to blue2"
$ git log

## create a new branch named 'purple' :

$ git branch purple
$ git checkout purple
 
## contents in file 'color.txt' updted

$ git status
$ git add .
$ git commit -m "changed to purple1"
$ git log

## contents in file 'colour.txt' updated

$ git add .
$ git commit -m "changed to purple2"
$ git log

## Switching to master branch 'CVRaman' :

$ git checkout CVRaman

## contents in file 'colour.txt' updated

$ git add .
$ git commit -m "changed to blue3"
$ git log

## contents in file 'colour.txt' updated

$ git add .
$ git commit -m "changed to blue4"
$ git log

## create a new branch named 'green':

$ git branch green
$ git checkout green
 
## contents in file 'colour.txt' updted

$ git status
$ git add .
$ git commit -m "changed to green1"
$ git log

## contents in file 'colour.txt' updated

$ git add .
$ git commit -m "changed to green2"
$ git log

## Switching to master branch 'CVRaman' :

$ git checkout CVRaman

## contents in file 'colour.txt' updated

$ git add .
$ git commit -m "changed to blue5"
$ git log

## merging the master & green :

$ git merge green
$ git add .
$ git commit -m "master-green merged"
$ git log

## merging the master & purple :

$ git merge purple
$ git add .
$ git commit -m "Master-green-Purple merged"
$ git log