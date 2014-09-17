---
tags: conditionals, cli, wip
language: ruby
resources: 0
---

# Simplified Blackjack

## Background

In [Blackjack](http://en.wikipedia.org/wiki/Blackjack) the goal is to have a hand that is closer to 21 than the hand of the dealers without ever exceeding a card total of 21. 

However, in this simplified version of Blackjack, we'll cut out that "compare with the dealer's hand" part and pretend that the goal of the game is to have a card total of, or very close to, (but never exceeding) 21.

To start, a player gets dealt two cards, each of which have values between 1-11. If they happened to get unlucky and have a sum of 22 (two 11-value cards), then they lose. Otherwise, they can decide to hit or to stay.

If they hit, they get dealt another card. If the sum of their three cards exceeds 21, they've lost. If it does not, they can decide to hit or stay again FOREVER.

## Objective

Practice conditional logic including nested conditionals by making a command line game that plays blackjack. This lab is test driven so just run `rspec` to get started.

## Resources
* [Wikipedia](http://en.wikipedia.org/) - [Blackjack](http://en.wikipedia.org/wiki/Blackjack)
