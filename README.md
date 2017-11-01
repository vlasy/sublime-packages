# sublime-packages

## Install Sublime on Ubuntu

According to [official instructions](https://www.sublimetext.com/docs/3/linux_repositories.html#apt)

```
wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
sudo apt-get install apt-transport-https
echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
sudo apt-get update
sudo apt-get install sublime-text
```

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
