# bide

Binary hiding device for testing purposes.

``` sh
# Hide curl from $PATH
bide curl

# Add curl back to $PATH
bide restore curl
```

## Installing

Until I add a quick install method do this:

``` sh
git clone https://github.com/DrPheltRight/bide.git
cd bide
sudo cp -f bide /usr/local/bin/bide
sudo chmod +x /usr/local/bin/bide
```

Or something similar :)

Make sure `/usr/local/bin` is in your `$PATH`.

## Author

Luke Morton

## License

MIT