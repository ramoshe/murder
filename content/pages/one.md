---
title: "Round One: Introductions"
date: Last Modified
permalink: /one/index.html
eleventyNavigation:
  key: One
  order: 5
  title: Round One
  parent: Game
---
The sun is setting beyond the rolling hills of California's lush wine country, and you find yourself standing in the hall of the main house on Killingsworth Farms.

You arrived earlier today to see Elizabeth Killingsworth, a recent widow who, due to hard times, is looking to sell the farm that she and her husband purchased just over a year ago.

Five others have joined you in the hall. Elizabeth, however, is not present. The strangers around you are looking at you with interest. You help yourself to a glass of wine from the hall table and introduce yourself.

---

<script src="//unpkg.com/alpinejs" defer></script>

<div x-data="{ open: false }">
    <button class="font-bold py-2 px-6 rounded" @click="open = true" style="border:1px solid gray;">Click to reveal Secret Clue when directed</button>
    <p x-show="open">
        <img src="/content/images/clue_one.png" />
    </p>
</div>