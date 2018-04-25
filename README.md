# My *.profile* config

![](https://media.giphy.com/media/33F1LSEfTJZvTTaSr0/giphy.gif)

## Top features:

- Git branch name at input line

- Useful shortuts, like:

  - `ll` for `ls -laF`

  - `la` for `ls -A`

  - `l` for `ls -CF`

  - `..` for `cd ..`

  - `port ${portNumber}` which shows you apps that use specific port (alias for `sudo lsof -i :$1`)

- Custom colors for files and directories

## Installation

Simple as that. Just place `.profile` file inside yor home (`~`) directory. 

Or you can even just use this command:

```
cd ~ && curl -O https://raw.githubusercontent.com/vd3v/.profile/master/.profile
```

After saving the `.profile` file you need to reload terminal (or open a new window)
