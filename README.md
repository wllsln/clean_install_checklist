# Clean Install Checklist

## Priority Backup

* Backup Data
  * Browser Profiles
    * Chrome
      * [ ] Save open sessions to Toby
      * [ ] Export bookmarks
      * [ ] Log out of accounts
    * Firefox
      * [ ] Export bookmarks
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
    * [ ] ProPresenter 6 - verify how to sync library
    * [ ] Symantec VIP Access - call in to disable
* Homebrew Configuration
  * Identify configuration and copy over

## Clean Setup

* Homebrew
  * Configuration
    * [ ] Homebrew `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
    * [ ] MacStore CLI  `brew install mas-cli/tap/mas`
    * [ ] Update brewfile with software to install (e.g. tmux)
    * [ ] Update wllsln/my_setup script
  * Software (should be in brewfile)
    * [ ] Adobe Creative Cloud `brew install --cask adobe-creative-cloud`
    * [ ] Avira `brew install --cask avira-antivirus`
    * [ ] Dropbox `brew install --cask dropbox`
    * [ ] iDrive `brew install --cask idrive`
    * [ ] Chrome `brew install --cask google-chrome`
    * [ ] Discord `brew install --cask discord`
    * [ ] Firefox `brew install --cask firefox`
    * [ ] Microsoft Office `brew install --cask microsoft-office`
    * [ ] OBS `brew install --cask obs`
    * [ ] OneDrive `brew install --cask onedrive`
    * [ ] Rectangle `brew install --cask rectangle`
    * [ ] Slack `brew install --cask slack`
    * [ ] Spotify `brew install --cask spotify`
    * [ ] Sublime Text `brew install --cask sublime-text`
    * [ ] VLC `brew install --cask vlc`
    * [ ] Zoom `brew install --cask zoom`
  * For Development (should be in brewfile)
    * [ ] iTerm2 `brew install --cask iterm2`
    * [ ] Postman `brew install --cask postman`
* Software Manual Installation
  * Development
    * [ ] Package Control for Sublime Text 3 `https://packagecontrol.io`
  * Productivity
    * [ ] Adobe Lightroom Classic
    * [ ] Adobe Photoshop
    * [ ] Microsoft Excel
    * [ ] Microsoft OneNote
    * [ ] Microsoft PowerPoint
    * [ ] Microsoft Word
  * Security
    * [ ] Dashlane
  * Utilities
    * [ ] Amphetamine
    * [ ] Blackmagic ATEM Switchers
    * [ ] Blackmagic Desktop Video
    * [ ] Covenant Eyes
    * [ ] DaVinci Resolve
    * [ ] Display Menu
    * [ ] ProPresenter 6
* Software Manual Configuration
  * iTunes
* Restore backup
  * Browser Profiles
    * Chrome
      * [ ] Log into Personal and Prophet accounts
      * [ ] Install Chrome extensions: Toby, SmileAlways, Adblock, AODocs
      * [ ] Load bookmarks (if necessary)
      * [ ] Restart Toby sessions
    * Firefox
      * [ ] Load bookmarks
  * Desktop
  * Documents
  * Downloads
  * Fonts
  * Music
  * Photos
* Other configuration
  * [ ] Sync iDrive
  * [ ] Add Chinese language support
  * [ ] Turn on FireVault
  * [ ] Disable Siri
  * ProPresenter 6
    * [ ] Create new ProPre user
    * [ ] Sync Propresenter Library
    * [ ] Turn off screensaver
    * [ ] Enable Amphetamine on Startup

## Future Investigation

* For Development
  * Dash
  * maximum-awesome: `https://github.com/square/maximum-awesome`
  * `https://www.cyberciti.biz/faq/howto-fix-macos-keeps-asking-my-ssh-passphrase-since-i-updated-to-sierra/`
  * zsh-syntax-highlighting: `https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md`
  * `https://github.com/hunttom/bodega/blob/master/developer_setup/dev_env.sh`
