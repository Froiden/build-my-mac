##  🗣   How to setup new Macbook in just 30 minutes

### 💪   Follow Below steps
1. Install Xcode and Homebrew
```
xcode-select --install
```
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
```
brew update
```

## ⚡ Node Install install nvm/node
```bash
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash
nvm install stable
```

## ⚡ Install Apps
```
curl -L https://raw.githubusercontent.com/Froiden/build-my-mac/master/scripts/brew_apps.sh | sh
```

## ⚡ Install Apps Store Apps
```
curl -L https://raw.githubusercontent.com/Froiden/build-my-mac/master/scripts/mas_apps.sh | sh
```
## ⚡ Copy Sensitive Creds
- aws
```
cp ~/.aws/config
cp ~/.aws/credentials
```

##  ⚡ Configure Git Profile 
- Configure local Git profile

```
git config --global user.name “Ajay Kumar choudhary”
git config --global user.email “email@email.com”
```
