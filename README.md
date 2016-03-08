#Set It Up

1) Install bash-completion

Mac OS X:

```shell
brew install bash-completion git
```

Ubuntu/Debian:

```shell
sudo apt-get install git bash-completion
```

*Install instructions for other systems may be found here: https://github.com/bobthecow/git-flow-completion/wiki/Install-Bash-git-completion#ubuntudebian*

2) Modify your `.bash_profile` (replace subl with your text editor or nano)

```shell
subl ~/.bash_profile
```

3) Paste the contents of [`.bash_profile`](.bash_profile) the previous shell script into your `.bash_profile`

4) Source your bash profile

```shell
source ~/.bash_profile
```

5) Profit $.

###In Case of error

If you receive the error: `-bash: __git_ps1: command not found`

Place this line at the top of your `.bash_profile`
```
source '/usr/local/etc/bash_completion.d/git-prompt.sh'
```

Save it and run `source ~/.bash_profile` again.
