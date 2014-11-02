spider_solitaire
================

A Python implementation of Spider Solitaire.

I wrote this because the games I find online have various deficiencies.
Most annoyingly, they dn't leave enough vertical space between the cards so that you
can see the suits.  In most cases, all you can tell is the rank and color.
Also, they use the protocol that when the player completes a suits from King to Ace, it is
automatically taken out of play immediately. The rule is that it remains in play until
the player takes it out.  Often, this can be used to great advantage in organizing other piles.

I've added a couple of variants that make the game easier, different from the simple-minded
two-suit or one-suit version one usually sees.  One is circular spider, where a King can be placed
on an Ace, and the other is open spider where all cards are initially dealt face up.  I've also added
open circular, combining both variants, but this is hardly necessary; so far as I can recall, I've
never lost the circular game.