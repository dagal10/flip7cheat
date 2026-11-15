# Flip 7: With a Vengeance Odds

A one-page helper for **Flip 7: With a Vengeance**. Tap the cards as they come out (other players' cards and your own) and it tells you whether to **HIT** or **STAND**, with your bust chance and expected score.

Live page (once GitHub Pages is on): https://dagal10.github.io/flip7cheat/

- Tracks the full 108-card deck: numbers 0–13 (with the Unlucky 7 and Lucky 13), −2/−4/−6/−8/−10, ÷2 and 10 action cards.
- Applies the special cards: the Unlucky 7 discards your other number and modifier cards; the Lucky 13 lets you hold a second 13; holding the 0 means you score 0 unless you Flip 7, so you must keep hitting.
- Cards stay out of the deck across rounds until you hit **Reshuffle deck**, as in the real game.
- The recommendation comes from an optimal look-ahead over the remaining deck (up to 6 cards ahead).
- Progress is saved in your browser, so a page reload doesn't lose it.
