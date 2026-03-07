---
layout: post
title: Build like Messi playing Chess
date: 2026-03-08 01:00:00 +0530
categories: engineering
---

At Donorbox, the signup flow had an EIN search. Type your number, get your nonprofit. Exact match. One result. Done.

The task: let them also search by name.

The devs wanted to build it all at once. New field, new results, new everything. One big thing.

I said wait. Let's play this out.

Add the name field. That's what was asked. But now — if someone types "Saint Mary", are we going to exact-match that? There are four hundred Saint Marys. So the name field needs fuzzy matching. That wasn't in the ticket. And if you're fuzzy matching, you're getting multiple results back. So now you need a list.

One requirement. Three changes. Each one forced by the last, like chess.

---

Have you watched Messi play? Not the goal goal goal goal trance. The foot and ball dance. It's not a trick. It's ten tiny touches. Each one shifts the ball just a little. The defender doesn't lunge because there's nothing to lunge at. It's easy to take one big touch. But it takes mastery to make ten small ones.

And then Messi's past him.

> **Big moves are just small moves that stayed in sequence.**
