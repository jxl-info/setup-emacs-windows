[![Build Status](https://github.com/jcs090218/setup-emacs-windows/workflows/CI/badge.svg)](https://github.com/jcs090218/setup-emacs-windows/actions)

# Set up Emacs in Window
> A Github Action that installs a specific emacs version

## Usage:

```yaml
uses: jcs090218/setup-emacs-windows@master
with:
  version: 24.5
```

The `emacs` executable on the path will then be the requested
version. For a list of available versions, please see the
[main GNU FTP server](https://ftp.gnu.org/gnu/emacs/windows/).

#### Note about compiling binary emacs modules

[Here's an example](https://github.com/xuchunyang/strptime.el) of a project which
compiles binary modules against an Emacs installed with this method.
