# progremir's dotfiles

Install [Brew](https://brew.sh/)
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

To set up all my dotfiles run the following command:
```
$ sh -c "$(curl -fsLS chezmoi.io/get)" -- init --apply --verbose https://github.com/progremir/dotfiles.git
```

You might have to install developer tools before running this command. Don't worry tho, you'll see the popup if you need to.

