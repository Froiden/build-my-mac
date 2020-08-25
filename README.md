# build-my-mac
How to build the PC in just 30 minutes


## Install Apps
```
curl -L https://raw.githubusercontent.com/Froiden/build-my-mac/master/scripts/brew_apps.sh | sh
```
## Copy Sensitive Creds
- aws
```
cp ~/.aws/config
cp ~/.aws/credentials
```

## Configure Git Profile 
- Configure local Git profile

```
git config --global user.name “Ajay Kumar choudhary”
git config --global user.email “email@email.com”
```
