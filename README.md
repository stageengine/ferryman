# Ferryman

For the purposes of showing off the mechanics of the Stage engine (https://engine.sgail.com), Ferryman is a short-story about a lost soul, finding his way.

## Getting started

Firstly, make sure you have the Stage engine installed on your machine: https://engine.sgail.com/learn/installation.

All you need to compile and play the game is as follows:

```sh
# Compile the Ferryman game files.
stage build [documents]/ferryman/

# Play the compiled game.
stage play ferryman.stg
```

## The pictures

`assets/` holds the two pictures the game shows for itself, named in `config.yaml`:

- `icon.png`, 800x800, the mark shown where Ferryman sits on a shelf beside other games.
- `cover.png`, 2400x1000, the banner shown above the game on its own.

Both are PNGs, and Stage asks for an icon of at least 800x800 and a cover of at least 1200x600.
The cover is drawn wider than the least it may be because whatever shows it crops to the shape it
has room for, and a picture with something to spare either side of the subject survives that.
They are built into `ferryman.stg` rather than carried beside it, so the game is still one file
to hand to somebody.

## More information

For more information and to learn how to make your own games, see https://engine.sgail.com/learn.
