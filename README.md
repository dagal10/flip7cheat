# Flip 7: With a Vengeance Odds

A one-page helper for **Flip 7: With a Vengeance**. Tap the cards as they come out (other players' cards and your own) and it tells you whether to **HIT** or **STAND**, with your bust chance and expected score.

Live page (once GitHub Pages is on): https://dagal10.github.io/flip7cheat/

- Set up the players in turn order and pick your seat; each card you tap goes to whoever's turn it is, and the turn moves on automatically.
- Action cards (Flip Four, Just One More, Swap, Steal, Discard) walk you through picking targets and cards. Any card on the table can be moved, swapped, discarded or removed.
- **Live camera:** point your phone at the table and it recognises the face-up cards right on the phone (no AI service, no account, nothing uploaded). It reads each number card's name banner (FOUR, ELEVEN, LUCKY, THE ZERO…) with Tesseract OCR, so tilted and upside-down cards work; red modifier cards are read by their number and action cards by their colour. Cards in the zone at the bottom of the picture go to you; other new cards follow turn order. It doesn't catch every card, so tap in any it misses.
- Keeps round scores and running totals to 200.
- Tracks the full 108-card deck: numbers 0–13 (with the Unlucky 7 and Lucky 13), −2/−4/−6/−8/−10, ÷2 and 10 action cards.
- Applies the special cards: the Unlucky 7 discards your other number and modifier cards; the Lucky 13 lets you hold a second 13; holding the 0 means you score 0 unless you Flip 7, so you must keep hitting.
- Cards stay out of the deck across rounds until you hit **Reshuffle deck**, as in the real game.
- The recommendation comes from an optimal look-ahead over the remaining deck (up to 6 cards ahead).
- Progress is saved in your browser, so a page reload doesn't lose it.

## Third-party code

`vendor/tesseract/` contains [Tesseract.js](https://github.com/naptha/tesseract.js) 5.1.1 and tesseract.js-core (Apache-2.0, licences included) and the English `best_int` language data from `@tesseract.js-data/eng` (MIT), bundled so the page works without any outside service.
