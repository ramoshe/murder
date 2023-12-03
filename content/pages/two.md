---
title: "Round Two: The Search"
date: Last Modified
permalink: /two/index.html
eleventyNavigation:
  key: Two
  order: 5
  title: Round Two
  parent: Game
---
A quarter of an hour has passed. You hastily gulped down a glass of the Killingsworth Farm wine, but a somber mood still lingers in the air. *Where is Elizabeth Killingsworth?* You feel ill at ease with this strange group of uninvited guests. One of the other guests – you don't notice who – suggests the group split up to find Elizabeth.

You wonder about the people around you and the circumstances that brought each person to Killingsworth Farm today. As the group begins to spread in different directions in search of Elizabeth, you decide to use this opportunity to find out more about the others.

---

<script src="//unpkg.com/alpinejs" defer></script>

<div x-data="{ open: false }">
    <button class="font-bold py-2 px-6 rounded" @click="open = true" style="border:1px solid gray;">Click to reveal Secret Clue when directed</button>
    <p x-show="open">
        <img src="/content/images/clue_two.png" />
    </p>
</div>