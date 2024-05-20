Off the West coast of the mainland lies the domain of the [[Immortal Isle]]. Ruled by a [[ Lich King]] known as [[The Fist of Order]], its people are accustomed to living with the undead on a daily basis. Few households lack at least one undead servitor, and necromancy is regarded as a noble profession. They are an indulgent, academic people, accustomed to the dead performing manual labor for them. At 1st level, you gain the Immortal Islander feat.

**Additional Feats:** **4th** [[enhanced-familiar-wizard|Enhanced Familiar]]

```statblock
layout: Pathfinder 2e Misc Layout
name: "Immortal Islander"
level: "Feat 1"
trait_01: "Archetype"
trait_02: "Cultural"
columnWidth: 700px
description: "You gain a Familiar. Your familiar is unusual, and has the following exceptions to the normal Familiar rules: \n - It is Small or Medium instead of Tiny \n - It is an undead humanoid skeleton \n - It has the following natural familiar abilities: Darkvision, Manual Dexterity \n - It has the Undead specific familiar ability and the [[undead|Undead]] type instead of animal. This does not count against your limit on the number of familiar abilities.\n\nWhen you first gain the familiar, or when you spend a week of downtime to replace it, choose any skill. The familiar's modifier for that skill is equal to your level plus your spellcasting ability modifier (Intelligence if you don't have one. If you have multiple spellcasting abilities modifiers, you may choose which one to use).\nYour familiar shares part of your mind and will, and does not count as Mindless\nThis familiar cannot become a Specific Familiar\nAdditionally, you become Trained in [[chapter-4-skills#Lore (Int)|Undead Lore]]."
```

```statblock
layout: Pathfinder 2e Misc Layout
name: "Immortal Islander Dedication"
level: "Feat 2"
trait_01: "Archetype"
trait_02: "Cultural"
trait_03: "Dedication"
prerequisites: "Immortal Islander"
columnWidth: 700px
description: "You gain the [[stitch-flesh-botd|Stitch Flesh]] feat, and may use [[chapter-4-skills#Arcana (Int)|Arcana]] instead of Medicine when treating Undead.\nYou become Trained in Arcana. If you were already Trained in Arcana, you instead become trained in a skill of your choice. If you cast a spell or use an item on your undead familiar or animal companion, you may choose to ignore that creature’s negative healing when resolving that spell."
special: "You can't select another Dedication feat until you have gained two other feats from the Immortal Islander archetype"
```

```statblock
layout: Pathfinder 2e Misc Layout
name: "Martial Necromancy"
level: "Feat 4"
trait_01: "Archetype"
trait_02: "Cultural"
prerequisites: "Immortal Islander Dedication"
columnWidth: 700px
description: "You gain a young Animal Companion. It is an [[undead-companion-loag|Undead Companion]], as described in the Book of the Dead. It must be either a Skeletal Servant, Skeletal Mount, or Zombie. Feats that would cause your animal companion to increase in size do not do so."
```

```statblock
layout: Pathfinder 2e Misc Layout
name: "Undead Soldier"
level: "Feat 6"
trait_01: "Archetype"
trait_02: "Cultural"
prerequisites: "Martial Necromancy"
columnWidth: 700px
description: "Your animal companion gained by Martial Necromancy becomes Mature. It becomes Trained in simple weapons, as well as light armor and gains the [[Pathfinder-2E-SRD-Markdown-main/rules/abilities/shield-block|Shield Block]] general feat, and they gain a reaction they can only use for Shield Block despite being a minion.\nAny effect that would increase your animal companion's proficiency in Unarmored Defense or Barding also increases its proficiency with Light armor.\nAny effect that would increase your animal companion's proficiency in Unarmed attacks also increases its proficiency in Simple weapons."
```

```statblock
layout: Pathfinder 2e Misc Layout
name: "Necromancer"
level: "Feat 6"
trait_01: "Archetype"
trait_02: "Cultural"
prerequisites: "Immortal Islander Dedication, expert in Arcana or Occult or Religion"
columnWidth: 700px
description: "You learn the [[create-undead|Create Undead]] ritual for Skeletons and Zombies, as well as one other type of undead of your choice. You may cast Create Undead without secondary casters. When you do, you must fulfill any requirements for the secondary caster and must attempt the secondary check normally performed by that secondary caster. You gain a +2 circumstance bonus to your roll when acting as the primary or secondary caster for the Create Undead ritual, and may use Arcana or Occultism when acting as the secondary caster instead of Religion if you wish. When acting as primary caster, you can perform all Create Undead rituals in 4 hours instead of 1 day."
```

```statblock
layout: Pathfinder 2e Misc Layout
name: "Undead Champion"
level: "Feat 8"
trait_01: "Archetype"
trait_02: "Cultural"
prerequisites: "Undead Soldier"
columnWidth: 700px
description: "Your animal companion gained by Martial Necromancy becomes a Nimble or Savage animal companion. Skeletons are always Nimble, Zombies are always Savage. Both types of animal companion become Trained in martial weapons and medium armor.\nAny effect that would increase your animal companion's proficiency in Unarmored Defense or Barding also increases its proficiency with Medium armor.\nAny effect that would increase your animal companion's proficiency in Unarmed attacks also increases its proficiency in Martial weapons."
```

```statblock
layout: Pathfinder 2e Misc Layout
name: "Undead Exemplar"
level: "Feat 14"
trait_01: "Archetype"
trait_02: "Cultural"
prerequisites: "Undead Champion"
columnWidth: 700px
description: "Your animal companion gained by Martial Necromancy becomes specialized. They become Expert in simple weapons and martial weapons. You may choose the following additional Specialization:\n**Warrior**\nYour companion is drilled to act as a soldier on the battlefield. Its gains Expert proficiency in light and medium armor as well as simple and martial weapons. During an encounter, even if you don’t use the Command an Animal action, your animal companion can still use 1 action on your turn to Strike or Raise a Shield. This overwrites the normal limitations on mindless undead animal companions."
special: "You can select this feat up to three times. Each time, add a different specialization to your companion."
```

```statblock
layout: Pathfinder 2e Misc Layout
name: "Lich King's Disciple"
level: "Feat 18"
trait_01: "Archetype"
trait_02: "Cultural"
prerequisites: "Necromancer, master in Arcana or Occultism or Religion"
columnWidth: 700px
description: "When casting the [[create-undead|Create Undead]] ritual, if you roll a success as either the primary or secondary caster you count it as a Critical Success. Reduce the spell level required and the cost to cast Create Undead by two steps, to a minimum of spell level 2 and 15gp. You may have two additional minions from this Ritual."
```