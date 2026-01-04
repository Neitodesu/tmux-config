# TMUX Config

✨ Shoutout to [Dreams of Code](https://www.youtube.com/@dreamsofcode) for the config! <br>
<br>
Only thing I added was keeping the CWD when creating new window <br>

```sh
bind 'c' new-window -c "#{pane_current_path}"
```

🎨 Styled with gruvbox dark <br>

<span style="font-size: 1.2em;">Install [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm)</span>

<span style="font-size: 1.2em;">_You will need [vim-tmux-navigator](https://github.com/christoomey/vim-tmux-navigator) for neovim and tmux to integrate smoothly_</span> <br>

After installing [vim-tmux-navigator](https://github.com/christoomey/vim-tmux-navigator), create a tmux config file in

```sh
~/.config/tmux/tmux.conf
```

- Inside Tmux, navigate to conf file <br>
- Paste config inside tmux.conf <br>

Press:

```text
prefix + I
```

Then run:

```sh
tmux source ~/.config/tmux/tmux.conf
```

<em>Enjoy!</em>
