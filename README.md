Prezto Configs for ZSH
=======================

**NOTE**: The original author and inspiration for the powerline theme came from @davidjrice and his repository [here](https://github.com/davidjrice/prezto_powerline)
---

Included are my Prezto Configurations for my ZSH Shell. 

Some added features that are not in standard Prezto:
* Custom 1-Line Agnoster-esque prompt. With Git status, and Ruby Version. (Works with chruby + rvm!!!)
* Preconfigured Alias for opening Sublime Text 3 with the command ```subl```
* Preconfigured for Chruby (Installed via Homebrew) [Line 17-19]:```zshrc```
* Whole slew of modules already configured and ready to go

## Why Prezto over Oh-My-ZSH
Prezto gives me everything that oh-my-zsh gave me; yet it is insanely faster, and tab-completion is a dream. 
Also, there are a lot of subtle hints around prezto that oh-my-zsh doesn't have. For example: The font color of the commands I am typing, changes based on whether or not the command exists, making completion even easier. 

## Installation
Follow Linh M. Tran's Guide to install Prezto [here](http://linhmtran168.github.io/blog/2013/12/15/ditching-oh-my-zsh-for-prezto/)
Then, clone this repo and use these config files as guides when you are configuring your own prezto config. 
If you want to use my custom powerline theme, simply:
```
cp prompt_powerline_setup ~/.zprezto/modules/prompt/functions/
```
Then edit ```~/.zpretzorc``` for this line change:
```
zstyle ':prezto:module:prompt' theme 'powerline'
```

Open a new shell, and voila! You are now running Prezto, and have a very kickass theme at that. 
========================

I use this theme with iTerm2 and the solarized light theme from [here](https://github.com/altercation/solarized/tree/master/iterm2-colors-solarized)