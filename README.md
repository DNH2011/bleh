# Planes & Powers

A self-contained, classic-inspired card duel playable in a modern browser. Open `index.html` directly—there is no build step, server, or external dependency.

## Play

- Play one land each turn, then click lands to tap them for mana.
- Click a card in your hand to cast it when you can pay its cost.
- Creatures have summoning sickness; select **Attack** on a later turn to send ready creatures into combat.
- The AI takes its turn automatically when you choose **Pass / end turn**.
- Search the card catalog to browse the included cards; use **How to play** for control details.

The card frame follows the requested layout: name and casting cost at the top, decorative illustration in the middle, rules text below, and power/toughness at the lower right for creatures. Illustrations are original emoji-and-gradient artwork rendered locally by the page.

The supplied list is very large and contains many legacy rules interactions. This playable prototype includes a curated selection of those cards and implements core duel effects; it displays card text for the included catalog and treats specialized effects as informational where they are not yet simulated. Mana notation distinguishes **B** (blue) from **K** (black), following the supplied list.
