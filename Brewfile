# Jose Javier Gonzalez Ortiz
# Brewfile

tap 'homebrew/science'

cask_args appdir: '/Applications'

### UNIX DEFAULTS
tap 'homebrew/dupes'
brew "coreutils"
brew "binutils"
brew "diffutils"
brew "ed", args: ['with-default-names']
brew "findutils", args: ['with-default-names']
brew "gawk"
brew "gnu-indent", args: ['with-default-names']
brew "gnu-sed" , args: ['with-default-names']
brew "gnu-tar", args: ['with-default-names']
brew "gnu-which", args: ['with-default-names']
brew "gnutls"
brew "gnupg"
brew "grep", args: ['with-default-names']
brew "gzip"
brew "less", args: ['with-pcre']
brew "lsof"
brew "make", args: ['with-default-names']
brew "nano"
brew "openssh"
brew "pstree"
brew "readline"
brew "rename"
brew "rsync"
brew "screen"
brew "stow"                                 # Symlink creator, useful for dotfiles
brew "tree"                                 # Recursive display
brew "watch"                                # Execute and monitor every X seconds
brew "wdiff", args: ['with-gettext']
brew "wget"

### SHELLS, GIT, PYTHON and RUBY
brew "git"
brew "git-extras"                           # Extra commands for convenience
brew "git-crypt"                            # Enables secretfiles
brew "git-lfs"                              # Better handling of large files
brew "git-flow"                             # CLI  utils for git-flow

brew "bash"                                 # Apple's is 3.2 current is 4
brew "bash-completion"                      # Bash completion is lacking so this fixes it
brew "fish"                                 # Friendly interactive sheell. Good defaults but not POSIX
brew "zsh"                                  # Better shell, specially with zPrezto
brew "zsh-completions"                      # General ZSH completions
brew "mosh"                                 # Mobile Shell

### WINE
cask "xquartz"                              # DEP: WineHQ dependency
brew "wine"                                 # For Windows software
brew "winetricks"                           # Extra wine utils
cask "wine-stable"                          # GUI Wine interface
cask "wineskin-winery"                      # Wine wrapper
cask "playonmac"                            # Wine wrapper with nice UI

### PROGRAMMING LANGUAGES
brew "xz"
brew "pyenv"                                # Python version management
brew "pyenv-virtualenv"                     # For managing virtual envs
brew "pyenv-ccache"                         # Make Python build faster
brew "pyenv-which-ext"                      # Integrate pyenv and system commands (looks up commands in other python versions)
brew "pipenv"                               # TODO: use pipenv instead of pyenv

brew "ruby"
brew "rbenv"
brew "ruby-build"

brew "perl"

### EDITORS
# Widely used CLI editors
brew "vim", args: ['override-system-vi', 'with-python3']
brew "neovim"

# Regular emacs window does not behave properly. Use this port instead
tap "railwaycat/emacsmacport"
brew "emacs-mac"
cask "emacs-mac"

### CLI UTILITIES
brew "ack"                                  # Better grep
brew "atool"                                # A script for managing file archives (aunpack)
brew "aspell", args: ['with-lang-es']       # Spell checker
brew "autossh"                              # Persistent SSH port forwarding
brew "bat"                                  # Improved cat with highlight and paging
brew "bitwarden-cli"                        # Bitwarden CLI utility
brew "diff-so-fancy"                        # More colorful diff
brew "dockutil"                             # Manages the dock icons
brew "duti"                                 # Set default document and URL handlers
brew "elinks"                               # CLI web browser
brew "fasd"                                 # Fasd offers quick access to files and directories
brew "fd"                                   # Fast alternative to find
brew "fdupes"                               # CLI duplicate finder
brew "fping"                                # More usable ping
brew "fzf"                                  # Fuzzy finder
brew "fzy"                                  # Another Fuzzy finder
brew "graphviz"                             # Graph visualization software
brew "gocryptfs"                            # FUSE encrypted FS
brew "hardlink-osx"                         # Hard link functionality on macOS
brew "htop"                                 # Display system usage
brew "imagemagick", args: ['with-librsvg', 'with-fontconfig'] # Good image editing software
brew "lnav"                                 # Log viewer
brew "lftp"                                 # Terminal FTP client
brew "mas"                                  # Install software from app store
brew "mackup"                               # Configuration Syncer
brew "cmark"                                # Mkvtoolnix dependency
brew "ctags"                                # ctags binaries are required for vim
brew "mkvtoolnix", args: ['with-qt5']       # Mkv tools
brew "media-info"                           # Media info for videos
brew "minicom"                              # Serial port communication
brew "moreutils"                            # Some extra niceties including parallel
brew "ncdu"                                 # Storage analyzer
brew "nmap"                                 # Network management package
brew "pandoc"                               # Document conversion
brew "plowshare"                            # CLI Hoster Downloader
brew "pv"                                   # Monitor the progress of data through a pipe.
brew "qpdf"                                 # Pdf CLI utility
brew "ranger"                               # Console file manager with VI key bindings
brew "ripgrep"                              # Search similar to ag but faster
brew "rclone"                               # Rsync to cloud storage
brew "rmate"                                # Remote TextMate for SSH sublime
brew "shellcheck"                           # Test shell scripts for errors
brew "subliminal"                           # Subtitle renamer
brew "terminal-notifier"                    # Enable terminal notifications for scripts
brew "tig"                                  # text-mode interface for git
brew "thefuck"                              # To correct mistypes in commands
brew "the_silver_searcher"                  # Search similar to ack but faster
cask "osxfuse"                              # Dependency of sshfs
brew "sshfs"                                # TO mount disks over SSH
brew "doxygen"                              # tmux dependency
brew "tmux", args: ['with-utf8proc']        # Terminal multiplexer and server
brew "trash"                                # To use OS trash instead of rm forever
brew "unison"                               # Sync both ways folders
brew "write-good"                           # CLI tool for technical writing
brew "youtube-dl"                           # Download YouTube (and others) from CLI

### yabai
tap 'koekeishiya/formulae'
brew 'koekeishiya/formulae/yabai'
brew 'koekeishiya/formulae/skhd'

### MISC
brew "archey"
brew "cowsay"
brew "fortune"
brew "figlet"
brew "neofetch"
brew "sl"
brew "gti"
brew "cmatrix"
brew "pipes-sh"

##### CASKS #####

tap "caskroom/cask"
tap "caskroom/versions"
tap "caskroom/drivers"

# cask "amethyst"                             # Tiling window manager
cask "alfred"                               # Improved Spotlight
cask "appcleaner"                           # Removes plist along with the app
cask "authy"								# 2FA App
cask "bettertouchtool"                      # Macros and gestures (PAID -license)
cask "bitwarden"                            # Password manager of choice
cask "bitbar"                               # Menu custom script display
cask "borgbackup"                           # Incremental and Deduplication backup tool
cask "caffeine"                             # Prevents the computer from sleeping
cask "dropbox"                              # Cloud storage with syncing
cask "etcher"                               # Tool for flashing USB/SD/&c from .img/.iso
cask "etrecheckpro"                         # System maintenance
cask "firefox"                              # Alternative web browser
cask "flux"                                 # Changes temperature color based on time of day
cask "gmvault"                              # To backup gmail accounts
cask "google-chrome"                        # Google's web browser
cask "google-chrome-canary"                 # Google's beta web browser
cask "hammerspoon"                          # Desktop automation on macOS
cask "chrome-remote-desktop-host"           # Remote control using Google credentials
cask "iterm2"                               # Better than Terminal.app
cask "jupyter-notebook-viewer"              # Simple app to view Jupyter notebooks
cask "karabiner-elements"                   # Tool to remap keys like caps-lock
cask "keybase"                              # Keybase macOS client
cask "kitty"                                # Terminal emulator with GPU acceleration
cask "logitech-control-center"              # Drivers for keyboard and mouse
cask "logitech-options"                     # Drivers for keyboard and mouse
cask "logitech-unifying"                    # Drivers for keyboard and mouse
cask "mactex"                               # LateX and TeX
cask "malwarebytes"                         # Remove antimalware
cask "mkvtoolnix"                           # GUI for mkvtoolnix
cask "onyx"                                 # Tweak tool for OS
cask "paintbrush"                           # MS paint equivalent
cask "plex"                                 # Plex Media Player
cask "scroll-reverser"                      # Tool to invert mousewheel scroll
cask "selfcontrol"                          # Blacklisting websites
cask "slack"                                # Slack client
cask "skim"                                 # Better PDF tool with Sublime Text integration
cask "spotify"                              # Music streaming
cask "steam"                                # Gaming collection hub
cask "sublime-text"                         # Multipurpose text editor
cask "telegram"                             # Instant messaging with sync across devices
cask "the-unarchiver"                       # To deflate and decompress files
cask "transmission"                         # Torrent client
cask "tunnelblick"                          # OpenVPN client
cask "veracrypt"                            # Disk and disk image encryption
cask "visual-studio-code"                   # Visual Studio Code editor
cask "vlc"                                  # Video Player
cask "xbox360-controller-driver-unofficial" # Drivers for XBOX 360 controller
cask "yubico-yubikey-manager"               # Manager for yubikeys
cask "yubico-authenticator"                 # TOTP authenticator based on yubikeys
# PAID Casks
cask "bartender"                            # Groups menu bar items (PAID)
cask "daisydisk"                            # Handy disk space analyzer (PAID)
cask "vmware-fusion"                        # Full fledged user friendly VM (PAID)

# Quick Look plugins
cask "qlcolorcode"
cask "qlstephen"
cask "qlmarkdown"
cask "quicklook-json"
cask "qlprettypatch"
cask "quicklook-csv"
cask "hetimazipql"
cask "qlimagesize"
cask "webpquicklook"
cask "suspicious-package"
cask "qlvideo"
cask "jupyter-notebook-ql"
cask "quicknfo"
cask "qlmobi"
cask "qladdict"

# Fonts
brew "font-fontawesome"
tap 'caskroom/fonts'
cask "font-anonymous-pro"
cask "font-charter"
cask "font-cooper-hewitt"
cask "font-dejavu-sans"
cask "font-comic-neue"
cask "font-computer-modern"
cask "font-ibm-plex"
cask "font-fira-code"
cask "font-fira-mono"
cask "font-fira-sans"
cask "font-hack"
cask "font-hasklig"
cask "font-inconsolata"
cask "font-iosevka"
cask "font-menlo-for-powerline"
cask "font-monoid"
cask "font-source-code-pro"
cask "font-source-sans-pro"
cask "font-source-serif-pro"
cask "font-terminus"
cask "font-times-new-roman"
cask "font-fantasque-sans-mono"
cask "font-victor-mono"
cask "font-cascadia"
  ## Nerd fonts
cask "font-meslo-nerd-font-mono"


tap 'colindean/fonts-nonfree'
cask "font-microsoft-office"

### Mac App Store Installs
mas "Xcode", id: 497799835                          # Apple's developper tools

mas "WireGuard", id: 1451685025                     # Wireguard macOS client
