# sublime-packages

## What to sync
`Packages/User` folder

## Where is it located
* Windows - `~/AppData/Roaming/Sublime\ Text\ 3/Packages/User`
* Ubuntu - `~/.config/sublime-text-3/Packages/User`

## How to init on first machine

```
$ git init
$ git remote add origin git@github.com:vlasy/sublime-packages.git
$ git fetch
$ git commit -am "added: settings and packages"
$ git push
```

## How to use on other machines

```
$ git init
$ git remote add origin git@github.com:vlasy/sublime-packages.git
$ git fetch
$ git reset --hard origin/master
```
