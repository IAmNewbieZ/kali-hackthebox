# kali-hackthebox-theme

<img width="1901" height="831" alt="image" src="https://github.com/user-attachments/assets/702c1c3c-834a-4d3e-822f-d687833b9bf7" />

# Install
1. Check if there is `/usr/share/qtermwidget5/color-schemes` or `/usr/share/qtermwidget6/color-schemes` (Remember using root).If you don't have it, then my colour scheme can't support your terminal. If yes, chmod 644 `HackTheBox.colorscheme` and copy it over there. Close the terminal and reopen it. Select the new colour scheme named HackTheBox.
2. Copy `zshrc.txt` to your local `.zshrc` and enter the command `source .zshrc`
3. Copy `tmux.conf` to your local `.tmux.conf` and enter the command `tmux source .tmux.conf`, after that press Ctrl+F and I to install the plugins. Then wait for a bit and it will finish. 

# Optional
You want to list all the directories but with green colour instead of blue. Please change the value of `[Color4Intense]` to `Color=0,255,106` in `HackTheBox.colorscheme`. This will change all the blue to green colour
