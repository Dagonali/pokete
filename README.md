# Pokete

## What is it?
Pokete is a small terminal based game in the style of a very popular and old game from gamefreak.

## Installation
For linux just do this:
```Shell
$ git clone https://github.com/lxgr-linux/scrap_engine.git
$ git clone https://github.com/lxgr-linux/pokete.git
$ cp ./scrap_engine/scrap_engine.py ./pokete
$ ./pokete/pokete.py
```
For windows first install pynput and then do a windows equivalent to the above.

## How to play?
Imagine your a Pokete-Trainer and your goal is it to run aroud in the world and catch/train as many Poketes as possible and to get the best trainer.

First of all you get a starter Pokete (Steini), that you can use to fight battles with other Poketes. (The player name and the starter Pokete will be choosen using a wizard later)
The controls are w a s d to walk around. When entering the high grass (;), you may be attacked by a wild Pokete. You can choose betwen the attacks (as long their ap is over 0) your Pokete got, by pressing the acording number. The wild Pokete will fight back, you can kill it and gain XP to level up your Pokete or you can catch it to let it fight for you. To catch a Pokete you have to first weaken the enemy and then throw a Poketeball. And with a bit luck you can catch it.
Pressing the "1" key you can take a look at your curend deck, see the detailed information of your pokete and your attacks or rearange them.
Changes will only be saved by quiting the game using the exit function.
Since your a Pokete-Trainer, you can also fight against other trainers, the one other "a", that's stayng in the middle of the landscape will start a fight with you, when you go into his way. You can not escape from such a trainer fight, you either have to win, or lose. Those trainer fights give double the XP.
In case one of your Poketes dies, or is too weak, you can heal it by going into the house, aka, Pokete-Center, talk the the person there and choose the healing option.
There you can also take a look at all your poketes, and not just the first six. The ones marked with an "o" are the ones in your deck.

The red balls all over the map, are Poketeballs, you need to catch poketes. Stepping on such a ball adds it to your inventory. A store to buy them will be added later.

## Game depth
Not only are there Poketes that are stronger than others, but also Poketes with different types, wich are effective against some types and ineffective gainst others.

type|effective against|ineffective against
---|---|---
normal| |
stone|flying, fire|plant
plant|stone, ground|fire
water|stone, flying, fire|plant
fire|flying, plant|stone, water
ground|normal|flying
electro|stone, flying|ground
flying|plant|stone

## Tips
- In conversations you can very easiely skip the text printing by pressing any key
- When you want to see the next text in a conversation, also just press any key
- Don't play on fullscreen, the game then starts to be overseeable
- Do't be offended by the other trainers, they may swear at you

## TODO
- Add a wizard to set name and choose starter pokete at the start
- Add More maps
- Add types for attacks and poketes --- Done
- Add evolving
- Add more than one Pokete for trainers
- Colored Poketes
- A store to buy Poketeballs

## Dependencies
Pokete depends on python3 and the python-scrap_engine module.
On windows pynput has to be installed too.

## Contributing
Feel free to contribute what ever you want to this game.
New Pokete contributions are especially welcome, those are located in /pokete_data/poketes.py
