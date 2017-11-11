C++ Base Project
---
Creates a C++ base project. Handles environment variable setting, unit testing, and debugging via lldb. Additional info can be found in project/README.md

## Installation
Clone this repository to someplace safe. HOME is a good place.

```
$ git clone https://github.com/Vandise/cppnew
```

Add the following to your `~/.bashrc`

```
export PATH=$PATH:~/cppnew/
```

Reload your `~/.bashrc`

```
$ source ~/.bashrc
```

Create your C++ project

```
$ cppnew test_project
```

You're Done!

## Why?
I structure most of my projects similar to this. The Makefile generally changes, but this sets up a simple C++ project skeleton.