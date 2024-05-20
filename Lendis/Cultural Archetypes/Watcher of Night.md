You were raised in or near one of the forts that keep watch on the [[Forest of Night]], such as [[Dawn Keep]] or [[Drakhold]]. Your childhood was spent learning to hunt, and manning the watch towers that line the border of the forest. Yours has been a life under siege, a martyr to protect the peaceful lands at your back.

**Additional Feats:** **6th** [[attack-of-opportunity-champion|Attack Of Opportunity]] **8th** [[blind-fight-ranger|Blind-fight]]

```statblock
layout: Pathfinder 2e Misc Layout
name: "Watcher of Night"
level: "Feat 1"
trait_01: "Archetype"
trait_02: "Cultural"
columnWidth: 700px
description: "You gain the [[canny-acumen|Canny Acumen]] general feat."
```

```statblock
layout: Pathfinder 2e Misc Layout
name: "Watcher of Night Dedication"
level: "Feat 2"
trait_01: "Archetype"
trait_02: "Cultural"
trait_03: "Dedication"
prerequisites: "Watcher of Night"
columnWidth: 700px
description: "While keeping [[watches-and-rest|Watch]] during a rest, you gain a +2 circumstance bonus to your [[chapter-9-playing-the-game#Perception|Perception]] rolls, including initiative. You do not suffer a -4 penalty to your Perception checks while sleeping, and you always wake at the start of combat if at least one other ally is aware of the danger. You can regain fatigue while sleeping in armor.\nYou gain [[low-light-vision|Low-Light Vision]]; If you already have Low-Light vision, you gain [[Pathfinder-2E-SRD-Markdown-main/rules/abilities/darkvision|Darkvision]]. If you already have Darkvision, you gain a +1 status bonus to Perception checks in darkness."
special: "You can't select another Dedication feat until you have gained two other feats from the Watcher of Night archetype"
```

```statblock
layout: Pathfinder 2e Misc Layout
name: "Avenge the Fallen ⬲"
level: "Feat 4"
trait_01: "Archetype"
trait_02: "Cultural"
prerequisites: "Watcher of Night Dedication"
trigger: "An allied character gains the Dying condition as a result of an enemy effect"
columnWidth: 700px
description: "Immediately gain and perform a single Action."
```

```statblock
layout: Pathfinder 2e Misc Layout
name: "Still Standing ⬲"
level: "Feat 4"
trait_01: "Archetype"
trait_02: "Cultural"
prerequisites: "Watcher of Night Dedication"
frequency: "Once per day"
trigger: "You lose the Dying condition by succeeding at a Recovery check"
columnWidth: 700px
description: "You regain hit points equal to your character level. If you rolled a critical success on the recovery check, you regain hit points equal to twice your character level instead. Your Wounded value does not increase as a result of losing the Dying condition."
```

```statblock
layout: Pathfinder 2e Misc Layout
name: "Bring It Down! ⬽"
level: "Feat 8"
trait_01: "Archetype"
trait_02: "Cultural"
prerequisites: "Avenge the Fallen"
columnWidth: 700px
description: "You Strike one enemy within range. If you hit, each other allied character within 10 feet of you may use their Reaction to immediately Strike that same enemy."
```

```statblock
layout: Pathfinder 2e Misc Layout
name: "Exploit Opening ⬻"
level: "Feat 12"
trait_01: "Archetype"
trait_02: "Cultural"
prerequisites: "Avenge the Fallen"
columnWidth: 700px
description: "You may only use this action if your most recent action on this turn was an attack that scored a critical success. You Strike against the same target, but treat a result of Failure as Success."
```