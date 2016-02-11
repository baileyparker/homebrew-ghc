# homebrew-ghc

GHC 7.8 Stable Release formula for [Homebrew](http://brew.sh/). Most Linux package managers haven't added GHC 7.10, but the only formula available for OSX is `homebrew/ghc`, which is the latest stable 7.10 release.

## How do I install this formula?

Run `brew tap baileyparker/ghc` and then `brew install ghc78`. This will not shadow your existing ghc installation, so you may need to symlink `ghc` (and `ghci`) to `/usr/local/bin/ghc78`. You can also `brew unlink ghc && brew link ghc78` to make this your default GHC version.

## License

This formula is licensed under the BSD 2-Clause License. See LICENSE for more.
