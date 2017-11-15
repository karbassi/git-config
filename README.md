# .gitconfig file

Git looks in the `~/.config/git/config` file, which is specific to each user.

## Quick Install
```sh
mkdir -p ~/.config/git && mv ~/.config/git{,-bak} && git clone --recursive https://github.com/karbassi/gitconfig.git ~/.config/git
```

## Installation
```sh
# Make sure you have a ~/.config/git folder
mkdir -p ~/.config/git

# Backup git config folder
mv ~/.config/git{,-bak}

# Clone current repo
git clone --recursive https://github.com/karbassi/gitconfig.git ~/.config/git

# Create local file
cp ~/.config/git/local.template ~/.config/git/local
```

## Additional

I would highly suggest installing and using [git extras](https://github.com/tj/git-extras) as well.

## Contributing

The [contributing guide](CODE_OF_CONDUCT.md) is a good place to start. If you have questions, feel free to ask.

## License

MIT © [Ali Karbassi](https://karbassi.com)
