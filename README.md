# advent_of_code_2024

## what

See [last year's repo](https://github.com/benlubas/advent_of_code_2023) for some deeper commentary
and explanation. Here's a brief description of what I'm doing:

I'm solving these problems by opening the input text in a neovim buffer and then manipulating the
text in the buffer until only the answer remains. I then write these commands to a plaintext file.
And I can source the file after opening the input text buffer and it will run them automatically and
produce the result.

These exact commands might not work for you. I'm using noice.nvim which deals with the press enter
menu, which I think causes things to fail. I also don't always use `:norm!` sometimes I use `:norm`
which means that remaps can cause issues.

I'm allowing simple `eval` calls, but I'm not going to use full on vimscript or lua. Mostly I use
`:norm!`, `:let` to "record" macros to registers that I later play, and `:s` for substitutions. But
of course other `:` commands are fair game as well.

## why

It's fun, and it gets funny reactions from people.
