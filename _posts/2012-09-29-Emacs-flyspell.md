---
layout: post
title: Flyspell-mode speed on Emacs 24 for OSX 
---

Note to self: Auto =flyspell-mode= in the Emacs starter kit really slows down typing. The [EmacsWiki](http://emacswiki.org/emacs/InteractiveSpell#toc4) suggests that this can be improved when using =aspell= by invoking =(setq ispell-extra-args '("--sug-mode=ultra"))=. But this is already in place in the starter-kit and doesn't help much. Turning it off appears to be the right answer, but it disables auto-highlighting of misspelled words. This problem appears on OSX--it's not noticeable on Emacs 24 running on Ubuntu.  
