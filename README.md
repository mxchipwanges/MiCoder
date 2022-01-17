# MXOS toolchains

## Updates

#### 2021.01.17
* Only keep macOS version.

#### 2020.10.26
* First add all files.  

## Platform:  
* macOS  
* windows10  
* Linux *[NOT SUPPORTED]*  

## Configurations  

1. Install git(v1.9.5 or later):  
`https://git-scm.com/download`
 
1. Install python(v2.7.13 or v2.7.x, but v3.x.x not supported):  
`https://www.python.org`  
  
2. Install `mxos-cube` cmd tool by using `pip`:  
>`pip install mxos-cube`  
  
3. Set `MICODER` path:  
>`mxos config -G MICODER "<path to MiCoder>"`    
  
## Test
test cmd `mxos`
```
➜  EMW3080_FW git:(master_230) mxos
usage: mxos [-h] [--version]             ...

Code management tool for MXCHIP MXOS - https://github.com/MXCHIP/mxos
version 1.0.17

Use 'mxos <command> -h|--help' for detailed help.
Online manual and guide available at https://github.com/MXCHIP/mxos-cube

optional arguments:
  -h, --help   show this help message and exit
  --version    print version number and exit

Commands:

    new        Create new mxos program or component
    import     Import program from URL
    add        Add component from URL
    remove     Remove component
    deploy     Find and add missing components and source codes
    codes      Import the optional component from the remote repository
    publish    Publish program or component
    update     Update to branch, tag, revision or latest
    sync       Synchronize mxos component references
    ls         View dependency tree
    status     Show version control status

    make       Make mxos program/component
    makelib    Compile static library

    config     Tool configuration

    help       This help screen
➜  EMW3080_FW git:(master_230)
```
