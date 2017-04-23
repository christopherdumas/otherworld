# Otherworld

## About the Game Itself
Welcome to Otherworld! In Otherworld, you are dropped into a detailed
(every single item has at least one special description or more), well
simulated (there is a day/night and weather system, in addition to the
best liquid system that could be reasonably implemented), and
generally fun world. Every puzzle has a logical solution that has to
do with what you would do to solve it in the game world with its
extant rules, instead of special objects or riddles. This real-world
basis has a few exciting advantages: solutions, while they won't be
obvious, always make sense before and after the fact. This means that,
in theory, a player should be able to make it from start to finish
through the game by logically puzzling things out without needing
hints or clues from outside the game and without making it
unwinnable. Why you can, and surely will, learn by death in
Otherworld, you shouldn't have to if you have a sharp eye and pay
close attention to what the game tells you.

# About the Game World
## Rooms
Otherworld is currently in development, but it is expected to have at
least 80 rooms. Lest you fear that they will all be similar (remember
Level 9's 'Snowball'?) here is the styleguide for rooms in Otherworld:

1. Each room should have at least two connections, one back to where
the player came from, and one somewhere else.
2. Each room should have a description consisting of at least two
sentences with atmospheric details as well as purely
game-pertinent information.
3. Each room should have at least on interesting or significant
feature, which may or may not be hidden at first.
4. Room descriptions should NOT referance the player in ANY WAY.
5. One exclamation point per 10 rooms.

Here are a few example room descriptions:

>**Ledge on Cylendar**
>A huge shaft, cylendarical, stabs down into what
>seems to be the heart of the earth, its bottom hidden in
>gloom. It almost fifteen feet in diameter, and you are
>standing on a small slanting ledge formed by the roots of
>the tree you just climbed through. The ground has
>collapsed above you allowing the hollow tree trunk to lead
>into this massive shaft. You can see passages leading off
>on the edges of it, but no way to get to them.

>**Meadow**
>A a simple, grassy meadow, as pure as the poets
>of old said they should be: full of simple flowers, bushes
>and small stumpy trees. It practically exudes simple
>pastoral delight! To the east and west the forest
>darkens and decends down the side of the hill that this meadow
>covers. The meadow ends to the north.

Also, using Inform's compasslook capabilities, I have made it so that
in any room outdoors you can LOOK with any compass direction to get the
description of the room in that direction, as look as no walls block
it. This increases the feel of openness.

## Objects
Every object in the game is (to some degree or another)
interactable. The goal is to never have the game respond with "You
don't see any such thing." to a reference to anything, no matter how
small, that is mentioned in the room description.  Every object has a
detailed description which can be read through examination.

## Gameplay
The game is structured around exploration: points are awarded for
every located room, and the entire map is as logical as possible, and
tries to play nice with you. Exits are always mentioned unless they
are actively hidden by a puzzle, all connections work both ways, and
the map is strictly a grid. This means that, while mapping is
necissary to complete the game, it is an easy process. While the game
is centered on exploration, there are a few side-stories and mysteries
to solve for a few extra points and interest.

## Weather, Day/Night, Player Stats
The player has stats for thirst, hunger, and fatigue, but they are
very lax and will generally warn you when you need to do something
about them. Each turn corresponds to roughly thirty minutes, and the
time is desplayed in the status bar. Weather has seasons and can be
cold, hot, sunny, rainy, or snowing. Day and night cycles are also
present.

## People, NPCs and Denizins of the Otherworld
While some puzzles may seem like combat (I can't say which ones),
there is no combat per-say in this game, since there is no combat
system. Instead the emphasis is on puzzling your way around hostiles.
In addition, while there will be a few NPCs, they are usually kept to
a minimum to avoid overwhelming the player with red-herrings.

## Magic
There is magic! It is through Latin words that you learn through
scrolls that you find. You will not receive spells, but simply Latin
nouns and verbs. While they are Latin nouns and verbs, they use
English grammar and are not conjugated to simplify the spell learning
process. Once you know a few of each, try exprementing by telling
these objects to do things. All magic spells are purely
descriptive. Pretend as if you are describing what you want the world
to look like after the spell is done. Here is an example in English:

> Rock is hot

Entered into the parser in Latin, this would make the specified rock
heat up. Repeating spells like this intesify their effects.
