---
layout: default
title: Agile Techniques
---

##### Table of Contents  
[Agile Learning](#agilelearning)  
[Retrospectives](#retrospectives)
[Estimation](#estimation)

<a name="agilelearning"/>
## Agile Learning

### The Brick Building Game

This is a way to teach people the basics of working as an agile team, in a short time frame.

#### What you will need

* Several large tubs of building bricks (e.g. http://brickset.com/sets/10663-1/Creative-Chest)
 * One of these per team
* A basic idea of what you're going to build
 * Examples - brewery, city, airport, house
 * Think of all the things needed to build your end-goal
 * These become your stories

#### Setting up the game

* Split the room into smaller teams
* Each team should get one tub of bricks
* Give each team the first set of stories, and 15 minutes or so to build those stories
 * The teams can act as a whole, or in smaller groups etc.
* After the first "iteration", a representative of each team will come up and "show" what they have done to everybody
* The next iteration, they should have a better idea of how many "stories" they can provide, etc.
* To mix things up
 * Change requirements after the first iteration
 * Swap team members in and out

<a name="retrospectives"/>
## Retrospectives 

### Data Gathering

The following are some common techniques we use for initial data gathering.

#### Start / Stop / Keep

Everybody writes one item per post-it, with something they'd like to Start doing, something they'd like to Stop doing and something they'd like to Keep doing.

e.g. Start monitoring servers, Stop turning up late, Keep writing tests first

Everybody sticks their post-its under the relevant section.

#### What Went Well / What Didn't Go Well / Lessons Learned

Similar to Start / Stop / Keep, but with slightly different headings forcing you to think in different way.

#### The Good Ship WDS

A picture of an old style sail boat is drawn, with wind in the sails, rocks behind, an anchor below and a tropical island ahead.  People write post-its for "Wind in the sails" (i.e. what propels us along), "Anchors" (i.e. what holds us back), "Rocks" (i.e. where we want to get away from) and the "Tropical Island" (i.e. where we are sailing toward).

An alternative is the Indiana Jones retro - a mine cart, hurtling down the tracks, with a big boulder following, and the bi-plane waiting to make your escape (mash up of multiple movies).

#### Art Attack!

Instead of writing, attendees draw their experiences.  Optionally the room can be split into smaller teams, rather than individuals, and other rules such as when the pen lifts from the page, hand over to the next person.

<a name="estimation"/>
## Estimation

Each team estimates stories in their own, internal currency.  These currencies are not related to each other, and neither are they related to "real time".

### Estimation techniques

Stories (or chunks of work) can be estimated using any of these techniques stand alone, but we prefer the "Play Your Cards Right" style.  

#### Play Your Cards Right

This technique is better for lots of stories.

* We take a pile of stories, and shuffle them as a deck of cards
* Each team member in the room takes it in turn to play
 * They can choose to play the top card from the deck, or
 * They can choose to play an existing card on the table
* For each card they play, they may place it on the table in order, with "more complex" cards at one end, and "less complex" cards at the other
 * The location of the card is up to the player only - no one else in the room gets a say at this point
* Once all cards have been played, a final round the table is done to ensure everyone is happy with the positions, again one at a time
* Natural gaps are decided, where "all these stories 'feel' the same size"
* Each section is given a score, based on the currency in use

#### Comaparative Estimation

This technique is better for a few stories.

* Each story in turn is compared to a previously played story, and the question is asked "Does this feel about the same as that?"
 * If yes, the same currency amount is used
 * If no, we choose a comparison story the next size up or down until we have found the right size.

#### Team voting (aka Planning Poker)

This technique works best for one or two stories, and a relatively small team

* Each story is discussed in turn, and every member of the team says what they think the size is
 * This is done preferably at the same time, so that undue influences can be removed
* The value assigned to the story is reached by a consensus in the room

### Estimation Currencies

We use the Fibonacci sequence to estimate stories (i.e. 1, 2, 3, 5, 8, 13, 21 etc.)
Other techniques we have used is T-shirt sizes (Small, Medium, Large, Extra-Large etc.), or doubling up (1, 2, 4, 8, 16 etc.)

### Estimation Game - Origami Estimation

* The room is split into small teams of four or five people in each
* Each team is given several pieces of origami paper (square paper with a colour on one side) and a list of origami animals to make
 * Crucial to this stage is they are not gien instructions
* The team have to estimate which animals they can build in a given period (synonymous to an agile sprint or iteration), based on the animal names alone, using one of the above techniques
* They are then given the instructions, and given the length of time, see how their estimates panned out
* Optionally they are given a second set of animals, to estimate again