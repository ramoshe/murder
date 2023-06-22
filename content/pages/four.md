---
title: "Round Four: The Examination"
date: Last Modified
permalink: /four/index.html
eleventyNavigation:
  key: Four
  order: 8
  title: Round Four
  parent: Game
---
You have returned to the Wine Vaults with a flashlight in hand. In the light, you can see the many meandering paths formed by the stacked oak barrels of wine and almost get lost. Coming upon the body, you confirm that it is, in fact, Elizabeth Killingsworth, and you immediately see the cause of her death. A golden corkscrew juts out from the right side of her neck. There appears to be something inscribed on the corkscrew, but the pool of blood prevents you from getting close enough for closer inspection.

The sight of Elizabeth's body is too gruesome for some of the guests and you decide to return, once again, to the main house to ponder these new clues.

---

<script src="//unpkg.com/alpinejs" defer></script>

<div x-data="{ open: false }">
    <button class="font-bold py-2 px-6 rounded" @click="open = true" style="border:1px solid gray;">Click to reveal Secret Clue when directed</button>
    <p x-show="open">
        <img src="/content/images/clue_four.png" />
    </p>
</div>