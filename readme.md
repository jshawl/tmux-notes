# Tmux Notes

I’m making my way through “tmux: Productive Mouse-Free Development” and these are my notes.

## 01 - Learning the Basics

You can start tmux with just `tmux`. No need to specify the name of
the session with `tmux new -s session_name`.

If you want to preserve the tmux session you created with `tmux`, rename
the session before detaching with `<C-b>$`.

If you forget to do that and detach anyway, you can get back the last
session with `tmux attach`.

### Windows

Create a new window with `<C-b>c`. Switch between them with `<C-b>n`.

Windows feel a bit like vim’s tabs.

### Panes

Create a vertical split with `<C-b>%`.

Create a horizontal split with `<C-b>%`.