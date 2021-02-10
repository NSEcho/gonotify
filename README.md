# gonotify

gonotify is a small notifer run based on some criterum when running commands. For example, it there is a long `make` command running, you would not just stare at your screen all the time but you would check the progress from time to time and that's when gonotify kicks in.

Command criteriums are:
* `when finished`
* `if result [comparison operator] value` e.g. `when result > 0`
* `if contains <string>` e.g. `if contains "successfully"`

__if__ criteriums can be prefixed with `!` which negates the condition like `if !result > 0` means "if result is not greater than 0".

# Example

`$ gonotify when finished -- make`

# Installation

TODO

# Note for my fellow linux users

I know that this whole program could be substituted with some bash or zsh features but not everyone wants to chain commands.
