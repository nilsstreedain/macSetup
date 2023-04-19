# macSetup
Repo detailing my personal macOS setup process (In progress)

## Install Homebrew
Download/run Homebrew install script:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Add Homebrew to PATH
```
echo 'eval $(/opt/homebrew/bin/brew shellenv)' >> $HOME/.zprofile
```

## Install mas
Install mas:
```
brew install mas
```

Signin to mas:
```
mas signin email@me.com
```

## Install Apps From Brewfile
Download/run brewfile:
```
brew bundle --file=<(curl -fsSL https://raw.githubusercontent.com/nilsstreedain/brewfile/main/Brewfile) 
```
