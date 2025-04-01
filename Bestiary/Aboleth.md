# Aboleth

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Aboleth | Aberration | {'cr': '10', 'xpLair': 7200} | 150 (20d10 + 40) | 17 | walk: 10 ft., swim: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Tentacle | 2d6 + 5 | 14 | - |
| Consume Memories | 3d6 | 16 | Half Damage ✅ |
| Dominate Mind (2/Day) | - | 16 | - |


**Multiattack.** The aboleth makes two Tentacle attacks and uses either Consume Memories or Dominate Mind if available.

**Tentacle.** {@atkr m} {@hit 9}, reach 15 ft. {@h}12 ({@damage 2d6 + 5}) Bludgeoning damage. If the target is a Large or smaller creature, it has the {@condition Grappled|XPHB} condition (escape {@dc 14}) from one of four tentacles.

**Consume Memories.** {@actSave int} {@dc 16}, one creature within 30 feet that is {@condition Charmed|XPHB} or {@condition Grappled|XPHB} by the aboleth. {@actSaveFail} 10 ({@damage 3d6}) Psychic damage. {@actSaveSuccess} Half damage. {@actSaveSuccessOrFail} The aboleth gains the target's memories if the target is a Humanoid and is reduced to 0 {@variantrule Hit Points|XPHB} by this action.

**Dominate Mind (2/Day).** {@actSave wis} {@dc 16}, one creature the aboleth can see within 30 feet. {@actSaveFail} The target has the {@condition Charmed|XPHB} condition until the aboleth dies or is on a different plane of existence from the target. While {@condition Charmed|XPHB}, the target acts as an ally to the aboleth and is under its control while within 60 feet of it. In addition, the aboleth and the target can communicate telepathically with each other over any distance. The target repeats the save whenever it takes damage as well as after every 24 hours it spends at least 1 mile away from the aboleth, ending the effect on itself on a success.

^Tags: #monster #type_aberration