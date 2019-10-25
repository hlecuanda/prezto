Prezto — Instantly Awesome Zsh
==============================

Prezto is the configuration framework for [Zsh][1]; it enriches the command
line interface environment with sane defaults, aliases, functions, auto
completion, and prompt themes.
***

This is a development fork, where I triage PRs, bugfixes and contributions or
work on my own new stuff for Prezto, if you want to install prezto, or if you
are looking for the [official repo](https://github.com/sorin-ionescu/prezto),
you may find it [here](https://github.com/sorin-ionescu/prezto)

## The code in this repo is mostly the work of the Prezto Team

However, branches local to this repository, **specially code *authored by me*,**
should be considered a work in (perpetual) progress, experimental, incomplete,
insecure, embarrasing, not representative of my work,  inelegant, containing
spelling errors. Most of the code may be slow, unoptimized, or poorly designed; lacks tests,
and if it doesen't lack tests, it probably fails most of them misserably; may
contain rude remarks and expletives, insults the user and its ancestry explicitly
on prominent parts of the UI, may not even compile, All of it should be
considered toxic, a terrible example of best practices, mediocre example of
worst practices and will surely cause data loss, corruption, dismotivation and incontrollable
urges to swear inappropriately. May cause kittens to die in horrible pain and agony if
executed. 

**Really, get the [official version](https://github.com/sorin-ionescu/prezto), it rocks!** 

***
Stuff you may find interesting 
--------
and probably safe to look at (unlike my code above)
- This repo's [wiki](https://github.com/hlecuanda/prezto/wiki) with some articles about _prezto_
 



Stuff I've submitted to _prezto_
----------------------------------------

- **Runcoms documentation** I wrote an explanation about [how _prezto_ ties in
  to zsh’s startup](https://github.com/hlecuanda/prezto/blob/5d2b2a776e3ae1145c25d147869371c3ddf1b274/runcoms/README.md) it turned out to be too long because i got carried away so
  I came up with a [shorter version](https://github.com/hlecuanda/prezto/blob/5ec8ce51751673bbb4e3f1c1d84858ea48fd21e5/runcoms/README.md)
- Triage of  https://github.com/sorin-ionescu/prezto/pull/1502, recommended
  against inclusion, as it actually takes away from the default
  `*-line-or-history` behavior, could be considered a regression

Stuff I’m working on
-----------------------
- Personal overrides as a module in `${ZDOTDIR:-$HOME}/contrib`
- `dialog` based install/config
- `very-vim` configuration bundle
- `tprezmux` `prezto` and `tmux` alone in a house to themselves for a weekend
  wthout adult supervision, 9 months later, this came up.

-------------------------------------------------------------
License
-------

This project is licensed under the MIT License.

[1]: http://www.zsh.org
<!-- vim: set ft=markdown sw=4 tw=78 fdm=manual  et :-->