### 0, Shell Tutorials

The website is [here](https://www.shellscript.sh).

What shell is running in an OS?

```shell
linux > echo $SHELL
```

### 1, Change the prompt symbol

To follow the typographical convention used in the shell tutorial, the prompt symbol should be conform to the rule. 

```shell
PS1="$ " ; export PS1 # If you are a root the "#" will be replace by "$".
```

### 2, Philosophy

1. The most criterion must be a clear, readable layout.
2. Second is avoiding unnecessary commands.

### 3, A first script

1. `#!` indicates that whatever kind of shell, such as `ksh`, `csh` or anything else, is used, the following code will be interpreted by "Bourne Shell".