#### Installing (Arch Linux)

##### Add repository

```
[randomsupplies]
SigLevel = PackageOptional
Server = http://r.arch.random.supplies/$arch
```

##### Install

```
pacman -Sy randomsupplies/epub2txt
```

#### Installing (OS X)

```
brew install excitoon/user/epub2txt
```

#### Installing (Windows)

##### Add repository

```
scoop bucket add user https://github.com/excitoon/scoop-user.git
```

##### Install

```
scoop install user/epub2txt
```

#### Build

##### Windows

```
cmake . -G "Unix Makefiles"
make
```

#### More information

For more information about epub2txt see

http://kevinboone.net/README_epub2txt.html
