To the Northeast of the mainland is an [[Degand|island]] overrun by [[The Nightmare|Nightmares]], a mountainous and untamed land of great potential and danger. Over time, many settlements have been established only to be overrun before long. The latest is [[Rathenschloss]], a fortified town inhabited by daring settlers from a wide range of origins. To outsiders, Rathenschloss is doomed to be just one more ruin on that forsaken island, but the settlers refuse to give up. At 1st level you gain the Settler feat.

**Additional Feats:** **10th** [[terrain-master|Terrain Master]], **12th** [[wardens-step|Warden's Step]]

```statblock
layout: Pathfinder 2e Misc Layout
name: "Settler"
level: "Feat 1"
trait_01: "Archetype"
trait_02: "Cultural"
columnWidth: 700px
description: "You become trained in [[chapter-4-skills#Survival (Wis)|Survival]]; if you were already trained in Survival, you become trained in another skill of your choice. You gain the [[favored-terrain|Favored Terrain]] feat. When in your favored terrain, you gain a +10-foot circumstance bonus to your travel Speed. When other creatures [[follow-the-expert|Follow the Expert]] with you as a guide in your favored terrain, they gain the bonus to travel Speed. If you have access to Ranger feats, you may select the Favored Terrain feat as normal to gain a second Favored Terrain."
```

```statblock
layout: Pathfinder 2e Misc Layout
name: "Settler Dedication"
level: "Feat 2"
trait_01: "Archetype"
trait_02: "Cultural"
trait_03: "Dedication"
prerequisites: "Settler"
columnWidth: 700px
description: "You become trained in [[chapter-4-skills#Crafting (Int)|Crafting]]; if you were already trained in Crafting, you become trained in another skill of your choice. You can perform Crafting checks without the appropriate tools. If you do so, you suffer a -2 penalty to the roll and the action takes 50% longer than normal. When you are camping, you can spend 1 hour establishing a defensive position. If you do, you and your allies gain a +2 circumstance bonus to [[chapter-9-playing-the-game#Perception|Perception]] while on watch or during surprise attacks."
special: "You can't select another Dedication feat until you have gained two other feats from the Settler archetype"
```

```statblock
layout: Pathfinder 2e Misc Layout
name: "Pull Your Weight"
level: "Feat 4"
trait_01: "Archetype"
trait_02: "Cultural"
prerequisites: "Settler Dedication"
columnWidth: 700px
description: "When you perform an [[chapter-9-playing-the-game#Exploration Activities|Exploration Activity]] that would halve your speed, you may travel at full speed instead. This does not allow you to perform another Exploration Activity."
```

```statblock
layout: Pathfinder 2e Misc Layout
name: "Homestead Defender"
level: "Feat 4"
trait_01: "Archetype"
trait_02: "Cultural"
prerequisites: "Settler Dedication"
columnWidth: 700px
description: "When benefitting from Standard or Greater [[chapter-9-playing-the-game#Cover|Cover]], you increase the bonus to AC by +1, increase the bonus to Reflex and Stealth by +1, and gain an additional +2 circumstance bonus to resist any effect that would push you or knock you prone.\nAdditionally, if attacked while camping after you have established a defensive position, you may place two Barricades on the tactical map.\nBarricades are 10 foot long and 4 foot high objects that are difficult terrain and provide standard cover. They have Hardness 10, and 40(20) HP(BT)."
```

```statblock
layout: Pathfinder 2e Misc Layout
name: "In This Together ⬲"
level: "Feat 6"
trait_01: "Archetype"
trait_02: "Cultural"
prerequisites: "Settler Dedication"
trigger: "An allied character suffers damage from a trap or exploration hazard"
columnWidth: 700px
description: "Make a Survival skill check against the same DC as the trap or hazard (DC 20 if there is no DC for the trap or hazard).\n**Critical Success** You may redirect any number of damage from the trap or hazard to yourself, reducing the amount suffered by your ally by an equal amount. If this reduces the damage suffered by your ally to 0, they don’t suffer any negative effects or conditions associated with the trap or hazard. You suffer any negative effects or conditions associated with the trap or hazard.\n**Success** As a Critical Success, but you cannot reduce the damage by more than half.\n**Failure** You cannot reduce the damage taken by your ally"
```

```statblock
layout: Pathfinder 2e Misc Layout
name: "Stake a Claim"
level: "Feat 8"
trait_01: "Archetype"
trait_02: "Cultural"
prerequisites: "Homestead Defender"
columnWidth: 700px
description: "The AC bonus from Homestead Defender applies to Lesser Cover as well. When attacked while camping after you have established a defensive position, you may place two additional Barricades and always count as being in your favored terrain."
```

```statblock
layout: Pathfinder 2e Misc Layout
name: "Wild Strider"
level: "Feat 8"
trait_01: "Archetype"
trait_02: "Cultural"
prerequisites: "Settler Dedication"
columnWidth: 700px
description: "You gain the ranger’s Wild Stride class feature. This allows you to ignore the effects of all non-magical difficult terrain, treat greater difficult terrain as merely difficult terrain, and gives you an additional benefit from Favored Terrain based on the terrain."
```