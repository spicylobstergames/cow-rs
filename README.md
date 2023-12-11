# Rewriting Curse of War

Spicy Lobster wants to port https://github.com/a-nikolaev/curseofwar to Rust-lang.

There are many things to like about this project:

- Small, fully specced out design. There aren’t really any unknown unknowns for the shape of the game.
- The game is 10 years old and dormant for a long time, plus it was never cross-platform, so there’s genuine value in porting it, aside from ‘just because’.
- Written in ~3000 lines of C code and composed of ~15 files in total (not counting the .h header files). It should be very easy to map out the complete porting roadmap in GitHub issues to open up for additional potential contributors.
- It's a terminal-friendly game, which means we can make a lo-fi version of it with ratatui.
- There is a very high quality art asset that already has everything we need.

## Roadmap

More details to come, but the initial plan is very simple: Do a pretty loose translation to Rust. Not trying too hard to copy the original architecture, but copying the game logic.

Milestone 1: terminal graphics.

Milestone 2: 2D graphics.

## Art 
https://stevencolling.itch.io/isle-of-lore-hex-tiles

![image](https://github.com/spicylobstergames/cow-rs/assets/583842/cd12125a-969b-45c9-8998-d86008c0f2ba)

## Ambition

We'll put this game out on Steam for free. Perhaps at a later point in time we will create some paid DLC for it if we can think of a novel enough value-add.
