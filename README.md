# adjacent_pairs
Calculate how often a shuffled deck of paired cards will have at least one adjacent pair.

The card game Memory, also known as Concentration, Matching, or Pairs, requires a deck of cards, each with exactly one match. On each turn, a player turns over two cards, one after the other. If they match, the player keeps the match, and takes another turn. If they don't, the next player has a turn.

Suppose you shuffle and deal the cards. One of the players turns over a card, then the card immediately next to it. They match! But rather than celebrating, she accuses you of not shuffling. Is that fair? How often will a deck of n pairs of cards (2n cards) have at least one match of adjacent cards?

This calculation does not consider the layout of the cards on the floor/table, only their order in the deck immediately after shuffling.

With 2 pairs, there are 3 possible arrangements: 2 pairs side by side, 1 pair in the middle, and alternating cards. Each of these has the same number of variants. So in 2 of 3 possible deck orders, there will be at least one adjacent pair. But with a larger deck, is it still 2 times out of 3? Is it larger, smaller?
