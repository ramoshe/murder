---
title: "Round Three: The Discovery"
date: Last Modified
permalink: /three/index.html
eleventyNavigation:
  key: Three
  order: 7
  title: Round Three
  parent: Game
---
Almost as soon as all the guests split up in search of the missing Elizabeth Killingsworth, the sound of screaming draws everyone deep into the labyrinth that makes up the Killingsworth Wine Vault – an expansive wine storage facility behind the Killingsworth Farmhouse. The lights will not turn on and only a sliver of moonlight shines through the window. As your eyes adjust to the darkness, you see a body face down in a large pool of blood. Your intuition tells you that *you have found the body of Elizabeth Killingsworth*.

The darkness of the Wine Vault makes an examination of the body impossible. The group decides to return to the main house to call the police. You suspect someone in the group is responsible for the murder of Elizabeth Killingsworth, and you have a few questions to ask.

---

<script src="//unpkg.com/alpinejs" defer></script>

<div x-data="{ open: false }">
    <button class="font-bold py-2 px-6 rounded" @click="open = true" style="border:1px solid gray;">Click to reveal Secret Clue when directed</button>
    <p x-show="open">
        <img src="/content/images/clue_three.png" />
    </p>
</div>