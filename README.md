# .gitconfig file

Git looks in the `~/.config/git/config` file, which is specific to each user.

## Installation
```
# Backup git config folder
mv ~/.config/git{,-bak}

# Clone current repo
git clone --recursive https://github.com/karbassi/gitconfig.git ~/.config/git

# Create local file
cp ~/.config/git/local.template ~/.config/git/local
```

## Contributing

The [contributing guide](CODE_OF_CONDUCT.md) is a good place to start. If you have questions, feel free to ask.

## License

MIT © [Ali Karbassi](https://karbassi.com)
