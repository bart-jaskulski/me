# devdocs tui

I want to create a devdocs TUI, which will be able to interactively query devdocs.io for
documentation, without the need for browser, JS, etc. Just download the docs and show them with
markdown.

Currently I have a simple bash script `dd`, which glues together fzf, lynx etc, but I wanted to
improve the experience with shorter commands (like `dd init` to search all phrases for init).

It would be great to support both lynx and plain markdown, with lynx being able to provide dynamic
linking (requires running server).

There are tools which already exists, but either suck or are invalid for me:

- https://github.com/toiletbril/dedoc
- https://github.com/girishji/devdocs.vim (great, but I have troubles with making it work)

Impact: 4
Confidence: 2
Ease: 5
Category: Personal Tooling
