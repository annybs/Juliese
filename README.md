# Anny: Juliese

[anny.audio](https://www.anny.audio)

First performed live @ ODI Leeds, 29th April 2016.

[Listen to Juliese on Bandcamp](https://annyfm.bandcamp.com/track/juliese) (though IMO [this live version](https://annyfm.bandcamp.com/track/juliese-live-3) is better)

## Files

`juliese.scd` is a simple SuperCollider startup file to configure audio routing and load project samples.

`juliese.tidal` is the full Juliese composition for Tidal Cycles.

`samples.csv` contains sample attributions. All samples are available in `samples/` directory.

## Snippets

The main `juliese.tidal` reflects the original composition, and includes 'initial states' of the various patterns used with notes on what should be changed and when. New patterns are prefaced with a comment like `-- @something` declaring its 'key' for reference.

In the `snippets/` directory are [yasnippet](http://joaotavora.github.io/yasnippet/)-compatible snippet files reflecting these references, and additionally a `julsetup` snippet (which contains the project setup) and a `juliese` snippet that provides a convenient list of all project snippets.

For easy loading and use in emacs Tidal, copy or symlink the snippets into a `haskell-mode` major group in one of your snippet folders.

## License

- Source code: [CC-BY-SA](https://creativecommons.org/licenses/by-sa/4.0/)
- Samples: see origins of sample attributions for individual licenses
