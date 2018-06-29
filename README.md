# system-setup
### *General information*
---
This repository will be housing certain shell scripts and accompanying programs which will be used for setting up a newly installed system.
The repository will house the respective shell scripts per branch. Since I am starting off with Ubuntu only, I will be creating the branch names as per names of the OS.
For example, the first branch to house the shell script will be for `Ubuntu 18.04` and hence the name of the branch would be `bionic_beaver`.
###### *Note: As of now the only support will be for Ubuntu OS which can be most probably extended to Debian based distributions. Please refer to the branches for more information.*
---
### *Setting up the system - basically the usage of this script*
---
In order to run the script and set up the system, just clone the repository. Once cloned, just navigate to the respective directory location where the repository is copied and then execute the `setup.sh` script. That's about it.
I am a novice shell script writer. Please give it a look before executing the script.

---
### *Programs, libraries and packages which will be installed upon running the `setup script`*
---
##### Libraries:
+ libncurses5-dev (`aptitude`)
+ libbgnome2-dev (`aptitude`)
+ libgnomeui-dev (`aptitude`)
+ libgtk2.0-dev (`aptitude`)
+ libatk1.0-dev (`aptitude`)
+ libbonoboui2-dev (`aptitude`)
+ libcairo2-dev (`aptitude`)
+ libx11-dev (`aptitude`)
+ libxpm-dev  (`aptitude`)
+ libxt-dev  (`aptitude`)
+ python-dev  (`aptitude`)
+ python3-dev (`aptitude`)
+ ruby-dev  (`aptitude`)
+ lua5.1  (`aptitude`)
+ liblua5.1-0-dev  (`aptitude`)
+ libperl-dev (`aptitude`)
+ automake (`aptitude`)
+ pkg-config (`aptitude`)
+ libpcre3-dev (`aptitude`)
+ zlib1g-dev (`aptitude`)
+ liblzma-dev (`aptitude`)

##### Programs:
- Vim (`source build`)
- Ranger (`aptitude`)
- Tmux (`aptitude`)
- Irssi (`aptitude`)
- GCC C++ compiler (`aptitude`)
- Clang compiler (`aptitude`)
- Neovim (`aptitude`)
- Axel (`aptitude`)
- Synaptic Package Manager (`aptitude`)
- VLC Media Player (`aptitude`)
- Alpine (`aptitude`)
- Silversearcher-ag (`source build`)
- Rainbowstream (`aptitude`)

##### Packages:
* texlive-full (`aptitude`)

### *Directory structure to be set by `setup script`*
---
```
$HOME/data/
├── _code
│   ├── _blender
│   │   └── _animation_files
│   ├── _commit
│   │   ├── bitbucket
│   │   │   ├── git
│   │   │   └── hg
│   │   └── github
│   └── _test_bed
│       ├── _skunkworks
│       │   ├── _android
│       │   ├── _eclipse
│       │   ├── _intelli_j
│       │   ├── _kern
│       │   ├── _psp
│       │   ├── _pycharm
│       │   └── _venv
│       │       ├── python2
│       │       └── python3
│       └── _standalone
│           ├── asm
│           ├── c
│           ├── cpp
│           ├── flex_bison
│           ├── ipython_notebooks
│           ├── java
│           ├── javascript
│           │   ├── angular
│           │   ├── jquery
│           │   └── node
│           ├── misc
│           ├── python2
│           ├── python3
│           ├── shell
│           └── TeX
├── _programs
│   ├── _code_ref
│   ├── _nix_execs
│   └── _repo_clone
│       ├── cvs
│       ├── git
│       ├── hg
│       ├── svn
│       └── wgetf
└── _storage
    ├── games
    │   ├── AAA
    │   └── indie
    ├── misc
    ├── mvc
    ├── OS
    ├── transmission
    │   ├── games
    │   ├── misc
    │   ├── mvc
    │   └── OS
    └── youtube
        ├── misc
        ├── music_videos
        └── tut_videos
```
