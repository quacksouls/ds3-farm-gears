# Item Discovery

To farm in-game items, you need as high Item Discovery as you can get. Your Item
Discovery can be increased by using these: Symbol of Avarice, a Crystal Sage's
Rapier in each hand, Gold Serpent Ring(+0,+1,+2,+3), Rusted (Gold) Coins, as
high Luck as you can get. Ask someone to drop farming equipment for you.

Item Discovery can also be increased by your Hollowing stat and a Hollow infused
weapon. With at least 15 Hollowing (at which you are hollowed), equipping a
Hollow infused weapon would increase your Item Discovery. The exception is the
Hollow Slayer, which has no effect on your Item Discovery. Below are some data
on how many points can be added to your Item Discovery depending on the upgrade
level of a Hollow infused weapon. The data show that with at least 15 Hollowing
points, wielding a +0 Hollow infused weapon would add 2 points to your Item
Discovery. You get the maximum of 5 points added to your Item Discovery when you
wield a +10 Hollow infused weapon.

-   +0: 2
-   +1: 3
-   +2: 3
-   +3: 3
-   +4: 3
-   +5: 4
-   +6: 4
-   +7: 4
-   +8: 4
-   +9: 4
-   +10: 5

Is there a maximum value for Item Discovery? Suppose you have 99 Luck. During
any farming session, you can equip the Gold Serpent Ring+3, Symbol of Avarice,
and Crystal Sage's Rapier for a total of 465 Item Discovery. You might be
surprised why you would get 465 Item Discovery instead of 464. Your base Item
Discovery is 100 and you have 99 Luck, so your Item Discovery is now 199. The
Gold Serpent Ring+3 and the Symbol of Avarice add 115 and 100 points,
respectively, to your Item Discovery. Finally, the Crystal Sage's Rapier adds 50
points to your Item Discovery. So in theory you should have 199 + 115 + 100 + 50
= 464 Item Discovery. Where does the extra 1 point come from? This extra point
comes from stacking the Gold Serpent Ring+3 with the Symbol of Avarice, the
stacking being multiplicative instead of additive. Equipping a second Crystal
Sage's Rapier would increase your Item Discovery to 515. If you also use a
Rusted Gold Coin, you would have 615 Item Discovery for 60 seconds. At 99 Luck,
using a +10 Hollow infused weapon and having 99 Hollowing have no effect on your
Item Discovery. The reason is that being hollowed and wielding a Hollow infused
weapon would increase your Luck, but since you already have 99 Luck you cannot
increase your Luck any further. Therefore the maximum Item Discovery you can
have is 615.

How does Item Discovery relate to your chance of receiving an item from a kill?
According this wiki

http://darksouls3.wikidot.com/game-mechanics-general#toc10

your chance of getting a drop of any item is related in the following way to
your Item Discovery and the true drop rate of the item. Let _Chance_ be your
chance of obtaining a particular item. Suppose _ItemDiscovery_ is your Item
Discovery and _TrueRate_ is the actual drop rate of the item. Then your chance
of getting the drop is

```
Chance = (ItemDiscovery / 100) * TrueRate
```

How do you know the value of _TrueRate_ for each item? The true drop rate of
each item is contained in the file

```
C:\Program Files (x86)\Steam\steamapps\common\DARK SOULS III\Game\Data0.bdt
```

which can be read by using Yapped

https://www.nexusmods.com/darksouls3/mods/306

The true drop rates have been converted to a readable spreadsheet thanks to the
following people from the ?ServerName? Discord server: Cryptid Tracker, TKPG.
You can read the true drop rates here:

https://docs.google.com/spreadsheets/d/1K4FwS61pLzfQPXAfTZxVMLmRdxohUMhaW5jbZXHG814/edit#gid=23676873
