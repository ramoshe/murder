---
title: "Round Six: The Revelation"
date: Last Modified
permalink: /six/index.html
eleventyNavigation:
  key: Six
  order: 10
  title: Round Six
  parent: Game
---
The police have arrived. You know that your secrets will soon be exposed so you decide to make a confession.

---

<script src="//unpkg.com/alpinejs" defer></script>

<div x-data="{ open: false }">
    <button class="font-bold py-2 px-6 rounded" @click="open = true" style="border:1px solid gray;">Click to reveal Secret Clue when directed</button>
    <p x-show="open">
        <img src="/content/images/hello.jpg" />
    </p>
</div>