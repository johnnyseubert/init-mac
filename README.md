### Configuração mac

1. Instalar o [Homebrew](https://brew.sh/index_pt-br)

### Lista de pacotes bases

```text
brew install zsh
```

```text
brew install --cask raycast
```

-  Dentro do raycast instalar via o site `https://www.raycast.com/store` o plugin do brew

---

<br>

```text
brew install git

brew install --cask firefox

brew install --cask fig

brew install --cask unnaturalscrollwheels

brew install xcodes

brew install --cask visual-studio-code

brew install --cask android-studio

brew tap leoafarias/fvm
brew install fvm
```

### Configurar zsh

```zsh

SPACESHIP_PROMPT_ORDER=(
  user          # Username section
  dir           # Current directory section
  host          # Hostname section
  git           # Git section (git_branch + git_status)
  hg            # Mercurial section (hg_branch  + hg_status)
  exec_time     # Execution time
  line_sep      # Line break
  jobs          # Background jobs indicator
  exit_code     # Exit code section
  char          # Prompt character
)
SPACESHIP_USER_SHOW=always
SPACESHIP_PROMPT_ADD_NEWLINE=false
SPACESHIP_CHAR_SYMBOL="❯"
SPACESHIP_CHAR_SUFFIX=" "

ZSH_THEME="spaceship"

plugins=(git zsh-syntax-highlighting zsh-autosuggestions)

source $ZSH/oh-my-zsh.sh

alias lsort="du -sh * | sort -h"

# Update the PATH to prioritize Java 11 over Java 17
# export PATH="/Library/Java/JavaVirtualMachines/jdk-11.jdk/Contents/Home/bin:$PATH"

# FLUTTER
export PATH="$HOME/www/utils/flutter/bin:$PATH"

#NVM
export NVM_DIR="$HOME/.nvm"
. $(brew --prefix nvm)/nvm.sh
```

### Configurar flutter

-  No caminho `~/www/utils/` colocar a pasta do flutter e apontar no .zshrc

### Configurar nvm

-  `brew install nvm` colocar no .zshrc a parte que fala do NVM
