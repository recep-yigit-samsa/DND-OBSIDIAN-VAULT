# Tarrasque

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Tarrasque | Unknown | 30 | 697 (34d20 + 340) | 25 | walk: 60 ft., burrow: 40 ft., climb: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 4d12 + 10 | 20 | - |
| Claw | 4d8 + 10 | - | - |
| Tail | 3d8 + 10 | - | - |
| Thunderous Bellow {@recharge 5} | 12d12 | 27 | Half Damage ✅ |


**Multiattack.** The tarrasque makes one Bite attack and three other attacks, using Claw or Tail in any combination.

**Bite.** {@atkr m} {@hit 19}, reach 15 ft. {@h}36 ({@damage 4d12 + 10}) Piercing damage, and the target has the {@condition Grappled|XPHB} condition (escape {@dc 20}). Until the grapple ends, the target has the {@condition Restrained|XPHB} condition and can't teleport.

**Claw.** {@atkr m} {@hit 19}, reach 15 ft. {@h}28 ({@damage 4d8 + 10}) Slashing damage.

**Tail.** {@atkr m} {@hit 19}, reach 30 ft. {@h}23 ({@damage 3d8 + 10}) Bludgeoning damage. If the target is a Huge or smaller creature, it has the {@condition Prone|XPHB} condition.

**Thunderous Bellow {@recharge 5}.** {@actSave con} {@dc 27}, each creature and each object that isn't being worn or carried in a 150-foot {@variantrule Cone [Area of Effect]|XPHB|Cone}. {@actSaveFail} 78 ({@damage 12d12}) Thunder damage, and the target has the {@condition Deafened|XPHB} and {@condition Frightened|XPHB} conditions until the end of its next turn. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_unknown