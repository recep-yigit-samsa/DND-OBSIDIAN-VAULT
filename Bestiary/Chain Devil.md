# Chain Devil

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Chain Devil | Unknown | 8 | 85 (10d8 + 40) | 15 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Chain | 2d6 + 4 | 14 | - |
| Conjure Infernal Chain | 2d4 + 4 | 15 | - |


**Multiattack.** The devil makes two Chain attacks and uses Conjure Infernal Chain.

**Chain.** {@atkr m} {@hit 7}, reach 10 ft. {@h}11 ({@damage 2d6 + 4}) Slashing damage. If the target is a Large or smaller creature, it has the {@condition Grappled|XPHB} condition (escape {@dc 14}) from one of two chains, and it has the {@condition Restrained|XPHB} condition until the grapple ends.

**Conjure Infernal Chain.** The devil conjures a fiery chain to bind a creature. {@actSave dex} {@dc 15}, one creature the devil can see within 60 feet. {@actSaveFail} 9 ({@damage 2d4 + 4}) Fire damage, and the target has the {@condition Restrained|XPHB} condition until the end of the devil's next turn, at which point the chain disappears. If the target is Large or smaller, the devil moves the target up to 30 feet straight toward itself. {@actSaveSuccess} The chain disappears.

^Tags: #monster #type_unknown