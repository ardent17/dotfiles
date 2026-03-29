# dotfiles

Jess's cursed macOS terminal setup.

What you get:
- Dracula Terminal theme (purple void, neon text)
- Dracula zsh theme + Powerlevel10k prompt (MesloLGS Nerd Font)
- Linus Torvalds rants on shell startup
- zsh-syntax-highlighting so your commands glow
- Optional: fortune | cowsay | lolcat for rainbow screaming cows

## Install (rough sketch)

1. Clone these dotfiles:

   git clone https://github.com/ardent17/dotfiles.git ~/.dotfiles

2. Symlink configs:

   ln -s ~/.dotfiles/.zshrc ~/.zshrc
   ln -s ~/.dotfiles/.p10k.zsh ~/.p10k.zsh

3. Install Oh My Zsh and Powerlevel10k the usual way.

4. Fonts: install MesloLGS NF (the Nerd Font Powerlevel10k recommends) and set it as the font in Terminal.

5. Dracula Terminal theme:
   - Download Dracula.terminal from the Dracula Terminal page.
   - In Terminal → Settings → Profiles, import Dracula.terminal.
   - Set the Dracula profile as Default.

6. Restart Terminal. If you don’t feel immediately ready to hack a mainframe from your now-cursed cyberpunk command altar, something is deeply wrong.

This setup exists purely for my pleasure: maximum glow, maximum chaos, zero apologies.
