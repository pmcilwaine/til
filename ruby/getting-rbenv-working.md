# Getting rbenv working

First we need to install rbenv we can do this from homebrew

`brew install rbenv`

Once this is installed we need to update our .zshrc or other shell rc file.

`eval "$(rbenv init -)"`

We then need to reload the rc file

`source ~/.zshrc`'

We can now use rbenv properly assuming we have a valid .ruby-version file in the directory

