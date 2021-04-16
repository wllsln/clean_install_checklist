# Clean Install Checklist

## Priority Backup

* Backup Data
  * Browser Profiles
    * [ ] Chrome
    * [ ] Chrome Extensions
    * [ ] Firefox
  * Desktop
  * Documents
  * Downloads
  * Fonts
    * [ ] [Backup Fonts](https://discussions.apple.com/thread/737547)
  * Music
  * Photos
  * Recycle Bin
* Software Cleanup
  * Default Applications
    * [ ] iCloud
    * [ ] iTunes - [Deauthorize Apple ID](https://support.apple.com/en-us/HT201251)
    * [ ] Keychains - turn on sync to iCloud
  * Installed Applications
    * [ ] Avira
    * [ ] Covenant Eyes - log out
    * [ ] Dashlane
    * [ ] DaVinci Resolve - export library
    * [ ] Day One - document storage location, export to archival format, store in OneDrive
    * [ ] iDrive
    * [ ] Symantec VIP Access - call in to disable
* Homebrew Configuration
  * Identify configuration and copy over

## Clean Setup

* Homebrew
  * Configuration
    * [ ] Homebrew `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
    * [ ] MacStore CLI  `brew install mas-cli/tap/mas`
    * [ ] Update brewfile with software to install
    * [ ] Update wllsln/my_setup script
  * Software (should be in brewfile)
    * [ ] Avira `brew install --cask avira-antivirus`
    * [ ] Dropbox `brew install --cask dropbox`
    * [ ] iDrive `brew install --cask idrive`
    * [ ] Chrome `brew install --cask google-chrome`
    * [ ] Firefox `brew install --cask firefox`
    * [ ] Rectangle `brew install --cask rectangle`
    * [ ] Zoom `brew install --cask zoom`
  * For Development (should be in brewfile)
    * [ ] Postman `brew install --cask postman`
* Software Manual Installation
  * Development
    * [ ] Sublime Text 3
    * [ ] Package Control for Sublime Text 3 `https://packagecontrol.io`
  * Security
    * [ ] Dashlane
  * Utilities
    * [ ] Covenant Eyes
    * [ ] DaVinci Resolve
* Software Manual Configuration
  * iTunes
* Restore backup
  * Browser Profiles
    * [ ] Chrome
    * [ ] Chrome Extensions
    * [ ] Firefox
  * Desktop
  * Documents
  * Downloads
  * Fonts
  * Music
  * Photos
* Other configuration
  * [ ] Add Chinese language support
  * [ ] Turn on FireVault
  * [ ] Disable Siri

## Future Investigation

* For Development
  * Dash
  * Screen Multiplexing (e.g. tmux)
  * iTerm2
  * Install `oh-my-zsh`  https://github.com/robbyrussell/oh-my-zsh
  * Shell
    * maximum-awesome: `https://github.com/square/maximum-awesome`
    * `https://www.cyberciti.biz/faq/howto-fix-macos-keeps-asking-my-ssh-passphrase-since-i-updated-to-sierra/`
    * zsh-syntax-highlighting: `https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md`
