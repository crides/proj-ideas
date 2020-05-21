# Project Ideas

This is just a place for all the project ideas I have, but I have no chance/time to do. These may serve as inspirations for other people.

## Terminal interface for docs.rs

Pretty much just what the name sounds like, a terminal interface for docs.rs. This should include be basically a mirror of the site, but on the terminal. This means that the functionality should include navigating the `struct`s, functions, macros, types, and other items under the current module, or the methods and trait implementations for the current `struct`, `enum` etc.

## Binary format viewer

Uses some kind of specification language, prints out the content of a binary stream/file, in the original format.

## Rio

A Rust-like scripting language. Uses some kind of GC, but Dyon-like can also be great for experiment. Features Rust-like semantics, with algebaric types and traits (would need research to see how that would work in a dynamic typed context). Heavily uses postfix syntax. Uses simple OO (`struct` like). The aim should be small and fast (like Lua for C).

## Keyboard Optimizer

There have been a lot of effort going into optimizing keyboard layouts, but they mostly go into analyzing n-grams and how they can be laid out on a keyboard. My approach would be to design an optimizer based on the flow of finger presses. It would take into account costs between key presses on a 30 alpha layout and will shuffle and pick the best layout based on a large stream of text.

## Music Visualizer

This is supposed to be a 3 dimensional visualizer. The visualization is obtained by chain the single frames in a traditional visualizer and merge them into a plane, with the horizontal axis being time and the vertical being the frequencies, and each dot will have a gray scale representing the strength. This could allow people to see the shape of a piece of audio.
