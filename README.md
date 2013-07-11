# YouCompleteMe: a code-completion engine for Vim
This is an unofficial **RELEASE** repository of [YouCompleteMe][].  You don't
need to build it anymore. Just bundle this, and it's done!

# Installation
As for a **release** repository, you may clone it like this: (no submodules)

`git clone --depth 1 git://github.com/bohrshaw/YouCompleteMe.git`

I will rebase to the upstream every time I rebuilding it. So you may update
like this:

`git fetch; git reset --hard origin/HEAD`

## Notes
* Only 32-bit Linux and Windows are supported.
* The Clang-based completion engine is not built.
* This repository may sometimes be outdated.

[YouCompleteMe]: https://github.com/Valloric/YouCompleteMe
