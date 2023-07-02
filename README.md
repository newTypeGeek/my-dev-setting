# my-dev-setting

My setting as a developer. The steps below are focusing on **Mac OS** and **Python**

## Steo 0: The `git` command

If memory serves, simply type `git` on the terminal. Mac will handle the rest of it

## Step 1: Basic Setup

1. Install **iTerm2**
   - To replace the built in Mac Terminal with more features
   - Ref: <https://iterm2.com/>
   - 
2. Install **Homebrew**
   - Package manager for Mac
   - Ref: <https://brew.sh/>

3. Install **Oh My Zsh**
   - To enable more features for `zsh` shell
   - The `zsh` configuration will be located at `~/.zshrc`
   - Recommend to install `zsh-syntax-highlighting` and `zsh-autosuggestions`
   - Refs
     - <https://github.com/ohmyzsh/ohmyzsh>
     - <https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md>
     - <https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md>

4. Configure `vim` editor features
   - Refer to `.vimrc` in this repository. Your `vi` file will be located at `~/.vimrc`

## Step 2: Developer Setup

1. Configure `git`
   - Refer to `.gitconfig` in this reposutory. Your `.gitconfig` file will be located at `~/.gitconfig`
  
2. Install `pyenv` and `pyenv-virtualenv` plugin
   - `pyenv`: To manage multiple Python versions
   - `pyenv-virtualenv`: To create virtual environment using `virtualenv`
   - Ref: <https://realpython.com/intro-to-pyenv>
   - **Remark**: Personally, I prefer to install `poetry` (a python package manager) inside virtual environment

3. Install **Docker**
   - To containarised your application for deployment
   - Ref: https://www.docker.com/

## Step 3: Interactive Development Environment (IDE)

1. VS Code: <https://code.visualstudio.com/>
2. PyCharm: <https://www.jetbrains.com/pycharm/>
