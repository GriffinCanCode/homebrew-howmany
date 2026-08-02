# Homebrew Tap for HowMany

This is a Homebrew tap for the [HowMany](https://github.com/GriffinCanCode/howmany) code analysis tool.

## Installation

```bash
brew install GriffinCanCode/howmany/howmany
```

Homebrew taps this repository as part of that command. `howmany` is not in
homebrew-core, so a bare `brew install howmany` will not find it.

## About HowMany

HowMany is a fast, intelligent code analysis tool with parallel processing, caching, and beautiful visualizations. It provides comprehensive statistics about files, lines of code, complexity, and development time estimates.

## Formula

`Formula/howmany.rb` builds from the official GitHub release tarballs. It is
generated, not hand-maintained: the `update-homebrew-formula` job in the main
repository's release workflow copies `packaging/howmany.rb` here on every `v*`
tag with that release's url and checksum stamped in. Edit it there, not here.
