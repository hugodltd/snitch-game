# ⚡ Catch the Golden Snitch

My first game! Made by Hugo.

You fly a broom, catch the Golden Snitches 🟡 for points,
and dodge the Bludgers ⚫. You get 3 lives.

## How to play

- Move with the **←** and **→** arrow keys
- Or move your mouse / drag your finger

## Play it here

https://hugodltd.github.io/snitch-game/

## How it's made

The whole game is in one file, `index.html`. It uses HTML, CSS and JavaScript.

Want to change it? Near the top of the `<script>` part there are three
settings you can play with:

```js
const FALL_SPEED = 2.5;      // how fast things fall
const SPAWN_EVERY = 55;      // frames between new things (smaller = harder)
const BLUDGER_CHANCE = 0.3;  // 0.3 means 30% of things are Bludgers
```
