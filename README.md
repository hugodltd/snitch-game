# ⚡ Catch the Golden Snitch

My first game! Made by Hugo.

You fly a broom, catch the Golden Snitches 🟡 for points,
and dodge the Bludgers ⚫. You get 3 lives.

## How to play

- Move with the **←** and **→** arrow keys
- Or move your mouse / drag your finger

## Levels ⚡

Every **8 Snitches** you catch takes you up a level. Each level:

- makes things fall faster
- sends things down more often
- adds a few more Bludgers

You also get **5 bonus coins** every time you level up. The game
remembers the best level you have ever reached.

The speed stops climbing at level 13, so it stays hard but always
possible — nothing can ever fall so fast it skips straight past you.

## The Broom Shop 🧹

Every Snitch you catch is a coin you keep. Spend them in the shop on
faster brooms — from the slow old **Shooting Star** all the way up to the
**Firebolt Supreme**, which moves three times faster.

Your coins and brooms are saved in your browser, so they're still there
when you come back.

## The Legendary Pack ⭐

Save up **200 coins** and you can open the Legendary Pack. Inside are three
brooms that don't exist in any book, and every one of them is faster than
the Firebolt Supreme:

| Broom | Speed |
|---|---|
| 🌩️ Thunderstreak 9 | 52 |
| 🪶 Phoenix Feather | 62 |
| 🚀 The Hugo 3000 | 72 |

You can only buy the pack once, and it unlocks all three at the same time.

## High score to beat 🏆

**Level 20**, by Hugo.

## Play it here

https://hugodltd.github.io/snitch-game/

## How it's made

The whole game is in one file, `index.html`. It uses HTML, CSS and JavaScript.

Want to change it? Near the top of the `<script>` part there are three
settings you can play with:

```js
const FALL_SPEED = 2.5;         // how fast things fall on level 1
const SPAWN_EVERY = 55;         // frames between new things (smaller = harder)
const BLUDGER_CHANCE = 0.3;     // 0.3 means 30% of things are Bludgers
const SNITCHES_PER_LEVEL = 8;   // catch this many Snitches to level up
const SPEED_PER_LEVEL = 0.55;   // how much faster each level gets
```

Right underneath is the `BROOMS` list. Add a line to it to invent your
own broom — give it a name, an emoji, a price and a speed.
