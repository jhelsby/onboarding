# Onboarding

## MacOS

### Basics

* Clean up the Dock, make the icons smaller, and autohide it.
* Disable user interface sounds.

### Software

* [iTerm2](https://iterm2.com/). If [Ghostty](https://ghostty.org/download) is allowed use that instead.

* [`oh-my-zsh`](https://ohmyz.sh/).

* [`powerlevel10k`](https://github.com/romkatv/powerlevel10k?tab=readme-ov-file#getting-started).

* [homebrew](https://brew.sh/). Then:

  * ```bash
    brew install fzf nvim tmux
    ```

* Zsh history:
    ```bash
    cat <<'EOF' >> ~/.zshrc
    HISTSIZE=1000000
    SAVEHIST=1000000
    HISTFILE=~/.zsh_history
    
    setopt APPEND_HISTORY
    setopt SHARE_HISTORY
    setopt INC_APPEND_HISTORY
    setopt HIST_IGNORE_DUPS
    setopt HIST_IGNORE_SPACE
    setopt HIST_REDUCE_BLANKS
    EOF
    ```

* [VLC](https://www.videolan.org/).

* Ensure my desktop is backed up, or has shortcuts to backed-up files. (Dropbox, Google Drive, etc.).
