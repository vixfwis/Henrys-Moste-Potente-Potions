# Henry's Moste Potente Potions: Short Recipes

A compact version of the recipes in [README.md](README.md), one line per potion. Read each line left to right as a sequence of actions. Every step is timed exactly: do the next step as soon as the previous one ends.

## Legend

```
Base:     Water / Wine / Spirits / Oil
C         add to Cauldron
M         put into Mortar (no grinding yet)
GC        grind Mortar, add to Cauldron
GD        grind Mortar, put into Dish
DC        add Dish to Cauldron
↓ ↑       lower / raise Cauldron
1H        turn Hourglass, wait until it runs out
9H/10     turn Hourglass, wait until just before it runs out
          (~1-2 s left of 10 s; recipes pin this at 9/10, i.e. 1 s left)
H/2       turn Hourglass, wait until halfway
1B 5B     pump Bellows 1x / 5x
Dist      distil into Phial
Pour      pour into Phial
Pour G    pour into Mortar and grind (powders)
```

## Ingredients

```
Aman  Amanita Muscaria
Bell  Belladonna
Boar  Boar's Tusk
Cham  Chamomile
Char  Charcoal
Cob   Cobweb
Comf  Comfrey
Dand  Dandelion
Eld   Elderberry Leaves
Eye   Eyebright
Fev   Feverfew
Gin   Ginger
Henb  Henbane
HPar  Herb Paris
LCoal Leached Coal
Mari  Marigold
Mint  Mint
Net   Nettle
Pop   Poppy
Sage  Sage
Salt  Saltpetre
SJW   St. John's Wort
Sulf  Sulphur
This  Thistle
Val   Valerian
Worm  Wormwood
```

## Any Level

```
Aesop               Spirits: 2 Comf GC 1 Boar C ↓ 1 Bell GD ↑ DC Dist
Aqua Vitalis        Water:   2 Dand C ↓ 1 Mari GC 1H Dist
Artemisia           Spirits: 1 Sage C ↓ 2 Worm GC H/2 Dist
Bane Poison         Wine:    1 Worm C ↓ 2 Bell GC 5B ↑ 1 Aman C Dist
Bowman's Brew       Spirits: 2 Eye C ↓ 1H 1 SJW GD ↑ DC ↓ 5B ↑ Dist
Buck's Blood Potion Oil:     1 SJW GC 1 Comf C ↓ 9H/10 1 Dand C 5B ↑ Pour
Chamomile Decoction Wine:    1 Sage GD 2 Cham C ↓ 9H/10 ↑ DC Pour
Cockerel            Spirits: 2 Mint GC ↓ 9H/10 1 Val C 1H Dist
Digestive Potion    Water:   2 This C ↓ H/2 1 Net GC H/2 ↑ 1 Char GC Pour
Dollmaker Potion    Spirits: 2 HPar C ↓ 9H/10 H/2 1 Val GC H/2 Dist
Embrocation         Oil:     1 Pop 1 Val C ↓ 1 Eye GD ↑ DC 1 Boar C ↓ Pour
Fever Tonic         Wine:    3 Fev C ↓ 1 Eld GC ↑ 2 Gin C Dist
Fox                 Oil:     1 Net 1 SJW GC ↓ 1 Char GD ↑ DC 1 Bell C ↓ Pour
Hair o' the Dog     Water:   1 Sage 1 SJW C ↓ 9H/10 H/2 1 Mint GD ↑ DC Pour
Lead Shot Gunpowder Water:   1 Salt 1 Sulf GC ↓ H/2 1 Char GC H/2 Pour G
Lethean Water       Spirits: 2 Worm GC 1 Bell C ↓ 9H/10 9H/10 9H/10 ↑ 1 Henb C Dist
Lion Perfume        Spirits: 2 Sage C ↓ 2 Mint GD ↑ DC Pour
Lullaby             Oil:     1 Pop C ↓ 9H/10 1 This C 9H/10 ↑ 1 HPar GC Pour
Marigold Decoction  Water:   1 Net C ↓ 2 Mari GD ↑ DC Pour
Mintha Perfume      Wine:    3 Dand 1 Mint GC ↓ 9H/10 9H/10 1 Mari C 5B ↑ Dist
Moonshine           Spirits: 2 Worm C ↓ 2 Mint GC Dist
Nighthawk           Water:   2 Eye GC 1 Bell C ↓ 9H/10 H/2 1 Cham GD ↑ DC Pour
Painkiller Brew     Spirits: 3 Pop GC 1 Mari C ↓ 5B 1 Comf C 9H/10 Dist
Quickfinger         Water:   1 Cob 2 Eye C ↓ 1H 2 Val GC H/2 ↑ Pour
Saviour Schnapps    Wine:    1 Net C ↓ 2 Bell GC H/2 ↑ Pour
Scattershot Powder  Water:   1 Salt 1 Sulf GC ↓ 9H/10 H/2 1 LCoal GC Pour G
Soap                Oil:     2 This GC ↓ 1 Char GD 1 Dand C 9H/10 ↑ DC Pour
```

## High Level

The level column is the minimum alchemy level. `any` marks potions that have only one recipe.

```
Aesop               18+ Spirits: 2 Comf GC 1 Boar C ↓ 1 Bell GC ↑ Dist
Aqua Vitalis        12+ Water:   2 Dand C ↓ 1 Mari GC Dist
Artemisia           12+ Spirits: 1 Sage C ↓ 2 Worm GC Dist
Bane Poison         14+ Wine:    1 Worm C ↓ 2 Bell GC 1B 1 Aman C ↑ Dist
Bowman's Brew       28+ Spirits: 2 Eye C ↓ 1 SJW GC 1B ↑ Dist
Buck's Blood Potion 28+ Oil:     1 SJW GC 1 Comf C ↓ 1 Dand C 1B ↑ Pour
Chamomile Decoction 18+ Wine:    1 Sage M 2 Cham C ↓ GC ↑ Pour
Cockerel            28+ Spirits: 2 Mint GC ↓ 1 Val C Dist
Digestive Potion    16+ Water:   2 This C ↓ 1 Char GD 1 Net GC DC ↑ Pour
Dollmaker Potion    18+ Spirits: 2 HPar C ↓ 1 Val GC Dist
Embrocation         18+ Oil:     1 Pop 1 Val C ↓ 1 Eye GC ↑ 1 Boar C ↓ Pour
Fever Tonic         any Wine:    3 Fev C ↓ 1 Eld GC ↑ 2 Gin C Dist
Fox                 14+ Oil:     1 Net 1 SJW GC ↓ 1 Char GC ↑ 1 Bell C ↓ Pour
Hair o' the Dog     18? Water:   1 Sage 1 SJW C ↓ 1 Mint GC ↑ Pour
Lead Shot Gunpowder 22+ Water:   1 Salt 1 Sulf GC ↓ 1 Char GC Pour G
Lethean Water       16+ Spirits: 2 Worm GC 1 Bell C ↓ 1 Henb C Dist
Lion Perfume        16+ Spirits: 2 Sage C ↓ 2 Mint GC ↑ Pour
Lullaby             16+ Oil:     1 Pop C ↓ 1 HPar GD 1 This C DC ↑ Pour
Marigold Decoction  18+ Water:   1 Net C ↓ 2 Mari GC ↑ Pour
Mintha Perfume      18+ Wine:    3 Dand 1 Mint GC ↓ 1 Mari C 1B Dist
Moonshine           any Spirits: 2 Worm C ↓ 2 Mint GC Dist
Nighthawk           18+ Water:   2 Eye GC 1 Bell C ↓ 1 Cham GC ↑ Pour
Painkiller Brew     20+ Spirits: 3 Pop GC 1 Mari C ↓ 1B 1 Comf C Dist
Quickfinger         24+ Water:   1 Cob 2 Eye C ↓ 2 Val GC Pour
Saviour Schnapps    22+ Wine:    1 Net C ↓ 2 Bell GC Pour
Scattershot Powder  14+ Water:   1 Salt 1 Sulf GC ↓ 1 LCoal GC Pour G
Soap                16+ Oil:     2 This GC ↓ 1 Char GD 1 Dand C DC ↑ Pour
```
