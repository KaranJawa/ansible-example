# ansible-example

## Prerequisites

* MacOS X
* Xcode

## Setup

```
xcodebuild -license
xcode-select --install

# install homebrew
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

# install homebrew cask
brew install caskroom/cask/brew-cask

# install ansible
brew install ansible

# create ansible inventory file
mkdir -p /usr/local/etc/ansible
echo localhost > /usr/local/etc/ansible/hosts
```

## Run

```
ansible-playbook android-developer.yml
```