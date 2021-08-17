# misodata.io

Codebase wor the misodata.io website.

- Ruby
- Jekyll


## Install locally

```zsh
brew install ruby
brew install rbenv 
brew install ruby-build
```

Add to `~/.zshrc`:
```bash
# Ruby
export SDKROOT=$(xcrun --show-sdk-path)
export PATH="/usr/local/opt/ruby/bin:$PATH"
export PATH="/usr/local/lib/ruby/gems/3.0.0/bin:$PATH"
export LDFLAGS="-L/usr/local/opt/ruby/lib"
export CPPFLAGS="-I/usr/local/opt/ruby/include"
export PKG_CONFIG_PATH="/usr/local/opt/ruby/lib/pkgconfig"
```

Setup this page

```zsh
bundle install
```

Test

```zsh
bundle exec jekyll serve
```


