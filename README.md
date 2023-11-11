# demo-mac-intro

## Git

Make github pretty

```bash
git config --global format.pretty '%Cred%H%Creset -%C(yellow)%d%Creset %s %Cgreen(%ad) %C(bold blue)<%an>%Creset'
```

## Show all files on Mac

```bash
# Show all hiddenfiles
defaults write com.apple.finder AppleShowAllFiles YES;
Killall Finder

# Change back
defaults write com.apple.finder AppleShowAllFiles NO;
Killall Finder
```
