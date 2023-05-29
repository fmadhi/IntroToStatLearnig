# IntroToStatLearnig
Using Python to go through exercises in the the book An intro to Sta Learning 
I am using I am using Ubuntu 22 in windows subsytem for linux and below are some setup I am using to set my env


    sudo apt-get update
    sudo apt-get install build-essential
    sudo apt update -y && sudo apt upgrade -y
    sudo apt install python3 python3-pip
    sudo apt-mark auto python3
    pip3 install jupyter
    /usr/local/bin/jupyter-notebook --allow-root

then use windows browser to access

    to setup zsh
    sudo apt-get install zsh
    sudo apt-get install git
    sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

add to ~/.bashrc
    if test -t 1; then
      exec zsh
    fi

add theme to ~/.zshrc
    # Find and change this
    ZSH_THEME="robbyrussell"

    # To this
    ZSH_THEME="agnoster"

install fonts in windows 
Clone the powerline repository on Windows

    git clone https://github.com/powerline/fonts.git

Open an admin PowerShell, navigate to the root of the repo and run this:

    .\install.ps1
    # using dircolors.ansi-dark
    curl https://raw.githubusercontent.com/seebi/dircolors-solarized/master/dircolors.ansi-dark --output ~/.dircolors
    ## set colors for LS_COLORS
    eval `dircolors ~/.dircolors`
