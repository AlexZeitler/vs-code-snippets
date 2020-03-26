# vs-code-snippets

My VS Code snippets - mostly TypeScript, JavaScript, HTML and CSS.

## Location for your VS Code User settings / snippets

Depending on your platform, the user snippets file is located here:

- Windows `%APPDATA%\Code\User\Snippets\`
- macOS `$HOME/Library/Application Support/Code/User/snippets/`
- Linux `$HOME/.config/Code/User/snippets/`

More details can be found [here](https://code.visualstudio.com/docs/getstarted/settings#_settings-file-locations).

## Installation

The easiest way is to create a symbolic link using `ln` (for Linux) - **this will replace all your existing snippets** :bomb:

```bash
rm -rf $HOME/.config/Code/User/snippets # be careful, backup first!
git clone git@github.com:AlexZeitler/vs-code-snippets.git
cd vs-code-snippets
ln -s $(pwd) $HOME/.config/Code/User/snippets/
```
