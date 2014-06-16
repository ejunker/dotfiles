# dotfiles

dotfiles based on https://github.com/holman/dotfiles

## install

Install Xcode from the App Store. Launch Xcode and accept the license.

Open Terminal and run this:

```sh
git clone https://github.com/ejunker/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
script/bootstrap
```

When you see "installing dependencies" you may need to press Enter to see the password prompt.

## Applications Installed

Git will be configured with your name and email address.

It will install [Homebrew](http://brew.sh) and [Homebrew Cask](http://caskroom.io). See [Brewfile](https://raw.githubusercontent.com/ejunker/dotfiles/master/homebrew/Brewfile) and [Caskfile](https://raw.githubusercontent.com/ejunker/dotfiles/master/homebrew/Caskfile) to see the applications that are installed. You can comment out any applications that you do not want installed. You can use `brew uninstall <application>` or `brew cask uninstall <application>` to uninstall apps.

