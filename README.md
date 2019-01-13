# TravellerCompanion
The public page for the TC discord bot.


Current commands:
```
Homebrew:
  	re-entry/orbit !entry / !orbit A B C D :: inspired by T5
```
######!entry
Inspired by the SAFE/SLOW/FAST re-entry mechanic from Traveller 5, I have tweaked it for my own games. I uses the Speed Rating of the ship and the Planet UWP number to calculate ascent/descent time, then uses Atmosphere UWP and Armour Rating to determine how much damage will be inflicted by friction and air resistance.
```
MGT2e:
	UWP Translator !uwp - Translates UWP
  	Selling goods  !sell - Selling price of goods
  	Buying goods   !buy - What trade goods are available
```
######!uwp
Takes the 8 characters of a UWP code and outputs their meaning.
######!sell / !buy
Using MGT2e trade rules, this takes Trade Codes and Broker Skill to calculate the quantity of goods, variety of goods and random extras.
Selling uses the same system.


```
Universal:
  	wallet         !wallet - keep track of your finances
  	dice roller    !r XdY - rolls dice
  	system map     !map - create or call a map
  	Travel time    !t - Journey time in space
  	Random NPC     !npc - generate a random NPC for inspiration
```

######!wallet
Designed for Travellers to keep their accounts to hand, this stores a Credit quantity and account log history unique to you.
######!r - roll dice
Dice roller
######!map
Creates a system map as per your specifications, or pulls one from memory. It also plots planet positions as per their orbit depending on how many days have passed since you last pulled the map. This can also be used to calculate the distance between two points in the solar system.
######!t - Travel time
Enter your ship Speed Rating and the distance to be travelled and outputs how long it will take.
It also calculates how long to travel from a planet's orbit to/from it's 100D jump point.
######!npc
Generates a random npc.
