# Tuisvn: Terminal user interface for Subversion

## What is tuisvn

Tuisvn is subversion(svn) client like tig(https://github.com/jonas/tig).

![](./docs/screenshot.png)

## System requirement

- Linux
- Installed svn command.

## Usage

~~~shell
$ tuisvn [repository path or url]
~~~
If argv is omitted, repository path is set the current directory.

## Development status

Tuisvn is under development.  
Implemented status is following...
- [x] file and directory tree. (svn ls)
- [x] revision history. (svn log)
- [ ] revision diff
- [ ] revision cat

## License

Copyright (C) 2022 [Yoshihide Shirai](mailto:yoshihide.shirai@gmail.com).

Licensed under the [MIT License](LICENSE).