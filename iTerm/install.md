# Setting up iTerm IDE

I have experienced the iTerm IDE to be very versatile and efficient in development. I've put together some instructions on installing the same environment I have set up.

A prerequisite is that you need homebrew installed! Check out installation at [Homebrew's website](https://brew.sh/).

## install zsh

Check to see if zsh is already installed:
```
zsh --version
```
<br>

Make sure you have homebrew installed:
```
brew update
brew install zsh
```
<br>

Change the standard shell with zsh:
```
chsh -s $(which zsh)
```
<br>

Check to see if zsh is correctly installed by restarting terminal
> zsh is great for `tab-completion` when browsing through folders

> try this out in your new shell
<br>
<br>

## install oh-my-zsh
`git` is a prerequisite for this

Type the following into your command line:
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
<br>
