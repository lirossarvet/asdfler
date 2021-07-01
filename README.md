# asdfler

Manage which `asdf` plugins you have as well as default versions!

NOTE: SUPER UNTESTED AND THROWN TOGETHER IN A COUPLE OF HOURS. **Use at your own risk**

## Installation

I only have MacOS intel so that's all I can build on without setting up CI/CD. Which I might do! Just...not now.

If that is also you, you can:

1. Go to [releases](./releases)
2. Download the `asdfler-macos-intel` binary
3. `sudo xattr -dr com.apple.quarantine ~/Downloads/asdfler-macos-intel`
4. `mv ~/Downloads/asdfler-macos-intel <somewhere in your path like ~/bin>/asdfler`

For non Intel MacOS folks (so...lots of people), unfortunately you have a little bit of a chicken-and-egg scenario. Your best bet is probably:

1. Install Crystal compiler (e.g., `brew install crystal`)
2. `git clone https://github.com/lirossarvet/asdfler.git`
3. `cd asdfler`
4. `shards build --release`
5. `mv bin/asdfler <somewhere in your path like ~/bin>/asdfler`

## Usage

TODO: Write usage instructions here

## Development

TODO: Write development instructions here

## Contributing

1. Fork it (<https://github.com/your-github-user/asdfler/fork>)
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## Contributors

- [Jon Anderson](https://github.com/your-github-user) - creator and maintainer
