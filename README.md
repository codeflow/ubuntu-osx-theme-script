# ubuntu-osx-theme-script

Use this repository's setup script to transform Ubuntu Linux using this OSX based theme.

## Getting Started

First clone this repository inside your $HOME directory

```sh
$ cd $HOME
$ git clone https://github.com/codeflow/ubuntu-osx-theme-script.git
```

Set permissions to setup script

```sh
$ cd $HOME/ubuntu-osx-theme-script
$ chmod +x setup
```

Set permissions to setup script

```sh
$ cd $HOME/ubuntu-osx-theme-script
$ chmod +x setup
```

Install the theme using the setup script

```sh
$ ./setup
```

### Using theme backup

This script uses as its base theme the repository: [github.com/vinceliuice/WhiteSur-gtk-theme](https://github.com/vinceliuice/WhiteSur-gtk-theme.git). If there is a problem when downloading the theme on [vinceliuice/WhiteSur-gtk-theme](https://github.com/vinceliuice/WhiteSur-gtk-theme.git) , it is possible to use the backup theme contained in this repository. To install using backup theme, just run the command below:

```sh
$ ./setup --use-backup
```
