
## About

[git-conf] is collection of my git configuration files.


## Installaion

1. Clone [git-conf] repository

   ```
   mkdir ~/.git-conf
   cd ~/.git-conf
   git clone git://github.com/KhurtinDN/git-conf.git
   ln -s ~/.git-conf/.gitconfig ~/.gitconfig
   mkdir ~/bin
   cp ~/.git-conf/git-diff-wrapper.sh
   chmod +x ~/.git-conf/git-diff-wrapper.sh
   ```

2. Check system requirements


## Updating

1. Update from repository

    ```
    cd ~/.git-conf
    git pull --repbase
    ```

2. Check system requrirements


## System requirements

1. Diff and merge tool

    ```
    sudo yum install meld
    ```

[git-conf]:http://github.com/KhurtinDN/git-conf
