# Git bash for windows powerline theme

Light & simple powerline theme for Git bash for windows

![ScreenShot](screenshot.png)


## Install:

```bash
cd $HOME
mkdir -p .bash/themes/git_bash_windows_powerline
git clone https://github.com/Enprogames/git_bash_windows_powerline.git .bash/themes/git_bash_windows_powerline
```

Create .bashrc file in $HOME:
```bash
nano ~/.bashrc
```
And add the following to it:
```bash
# Theme
THEME=$HOME/.bash/themes/git_bash_windows_powerline/theme.bash
if [ -f $THEME ]; then
   . $THEME
fi
unset THEME
```

## Prerequisites

* In order for this theme to render correctly, you will need a
[Powerline-patched font](https://github.com/powerline/fonts).

I recommend [Space Mono for Powerline](https://github.com/powerline/fonts/blob/master/SpaceMono/Space%20Mono%20for%20Powerline.ttf)

Set font for git bash: 

1. Open git bash
2. Right click > Options > Text > Font > Select
3. Enter "Space Mono for Powerline" under font
4. Click Ok
5. Click Apply, then Save

## License

MIT
