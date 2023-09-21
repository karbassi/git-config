# .gitconfig file

Git looks in the `~/.config/git/config` file, which is specific to each user.

## Quick Install

```sh
(mv ~/.config/git{,-bak} || mkdir -p ~/.config/git) && git clone --recurse-submodules https://github.com/karbassi/git-config.git ~/.config/git
```

## Installation

```sh
# Backup git config folder or Make sure you have a ~/.config/git folder
mv ~/.config/git{,-bak} || mkdir -p ~/.config/git

# Clone current repo
git clone --recursive https://github.com/karbassi/git-config.git ~/.config/git

# Duplicate example file: local.example -> local
cp ~/.config/git/local{.example,}
```

## Additional

I would highly suggest installing and using [git extras](https://github.com/tj/git-extras) as well.

## Contributing

The [contributing guide](CODE_OF_CONDUCT.md) is a good place to start. If you have questions, feel free to ask.

## License

MIT © [Ali Karbassi](https://karbassi.com)
