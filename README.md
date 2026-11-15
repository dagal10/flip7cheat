# Flip 7 Odds

A one-page helper for the card game Flip 7. Tap the cards as they come out (other players' cards and your own) and it tells you whether to **HIT** or **STAND**, with your bust chance and expected score.

Open `index.html` in a browser, or host it with GitHub Pages (Settings → Pages → Deploy from a branch → `main` / root).

- Tracks the full 94-card deck (numbers 0–12, +2/+4/+6/+8/+10, ×2, Freeze, Flip Three, Second Chance).
- Cards stay out of the deck across rounds until you hit **Reshuffle deck**, as in the real game.
- The recommendation comes from an optimal look-ahead over the remaining deck (×2, modifiers, Second Chance and the +15 Flip 7 bonus included).
- Progress is saved in your browser, so a page reload doesn't lose it.
