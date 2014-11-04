## Install Rails

### Setup for OS X version 10.9 or later

We will be using Homebrew as the application management tool in Mac.

1) Install Command line tools on terminal (You shall do this already in section 5.1)

```
xcode-select --install
```

2) Install [Homebrew](http://brew.sh/)

```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

3) Install [rbenv](https://github.com/sstephenson/rbenv)

```
brew update
brew install rbenv rbenv-gem-rehash ruby-build
echo 'eval "$(rbenv init -)"' >> ~/.zshrc
echo 'export PATH="$HOME/.rbenv/shims:$PATH"' >> ~/.zshrc
source ~/.zshrc
```

4) Build Ruby with rbenv

```
rbenv install 2.1.2
```

5) Set default Ruby version

```
rbenv global 2.1.2
```

6) Install Ruby on Rails

```
gem i rails --no-ri --no-rdoc
```

### Setup for Windows

1) Download [RailsInstaller](https://github.com/railsinstaller/railsinstaller-windows/releases/download/3.0.0-alpha.2/railsinstaller-3.0.0.exe) and run it. Click through the installer using the default options.

2) Open `Command Prompt with Ruby on Rails` and run the command

```
rails -v
```

If the Rails version is less than 4, update it using a following command

```
gem update rails --no-ri --no-rdoc
```

## Goals

- You should install the Rails environment into your computer
- You can check the version of Rails by `rails -v`

## References

- [Rails Girls Guides](http://guides.railsgirls.com/install/)
