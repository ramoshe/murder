---
title: "Round Five: The Final Clues"
date: Last Modified
permalink: /five/index.html
eleventyNavigation:
  key: Five
  order: 9
  title: Round Five
  parent: Game
---
You can hear the wail of the distant police sirens. Soon investigators will be swarming Killingsworth Farms and asking questions you may not want to answer. You still have a few minutes, though, and there are a few issues with your fellow guests you want to clear up...

---

<script src="//unpkg.com/alpinejs" defer></script>

<div x-data="{ open: false }">
    <button class="font-bold py-2 px-6 rounded" @click="open = true" style="border:1px solid gray;">Click to reveal Secret Clue when directed</button>
    <p x-show="open">
        <img src="/content/images/hello.jpg" />
    </p>
</div>