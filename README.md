# qdx dist

Currently qdx only includes "package" command. More will be added soon. Run "qdx package --help" to see options.

- Download latest release by using one the following links
  - [Linux](https://github.com/qislam/qdx-dist/releases/latest/download/qdx-linux) 
  - [Windows](https://github.com/qislam/qdx-dist/releases/latest/download/qdx-win.exe) 
  - [Mac](https://github.com/qislam/qdx-dist/releases/latest/download/qdx-macos) 
- Once downloaded, you can start using it on the command line without need for installing/configuring anything else.

```bash
path/to/qdx_distribution package --help
```

- For convenience you can setup an alias to the qdx executable file. This will make using the cli easier.

```bash
# For setting up alias on mac
code ~/.bash_profile

# add following to the bash profile. Assuming you are using the default download folder
alias qdx='~/Downloads/qdx-macos'
```

- You can also save the file in your repository. Remember to add it to .gitignore. It is ok to rename the file as needed.

Browse for all previous releases [here](https://github.com/qislam/qdx-dist/releases).

