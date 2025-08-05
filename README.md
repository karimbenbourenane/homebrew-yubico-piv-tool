# karimbenbourenane yubico-piv-tool

## How do I install these formulae?

`brew install karimbenbourenane/yubico-piv-tool/yubico-piv-tool@2.7.1`

Or `brew tap karimbenbourenane/yubico-piv-tool` and then `brew install yubico-piv-tool@2.7.1`.

Or, in a `brew bundle` `Brewfile`:

```ruby
tap "karimbenbourenane/yubico-piv-tool"
brew "yubico-piv-tool@2.7.1"
```

## How do I use libykcs11 with ssh-add?

```sh
sudo mkdir -p /usr/local/lib
sudo install -m 755 "$(brew --prefix)"/lib/libykcs11.dylib /usr/local/lib
```

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
