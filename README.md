# GitConfig
Learning to configure git

## Git file configuration paths
- /etc/gitconfig *all user in the machine*
    - git config **-system** to write on this file.
- ~/.gitconf *current user*
    - git config **--global** to write on this file.
- ./.config/git *working directory*
- **configuration order overwrites others configurations made, from local to etc**  

## Indentity config

`git config --global user.name "Alison"`  
`git config --global user.email "a@mail.com"`  

## Editor config
`$ git config --global core.editor [vim],[nano],[vscode]`  

## Viwe global config
`git config --global --list`  
`git config list`  
`git config user.name`  

## Get help whit git
`git help <verb>`  
`git <verb> --help`  
`man git-<verb>`  
**egx:** `git help config`
