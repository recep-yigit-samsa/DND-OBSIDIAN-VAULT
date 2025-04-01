# Thessalhydra

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Thessalhydra | Monstrosity | 4 | 69 (6d12 + 30) | 14 | walk: 30 ft., swim: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Flurry of Bites | 1d6 + 4 + 4d4 | - | - |
| Maw | 1d10 + 4 + 1d10 | - | - |
| Tail Pincer | 1d12 + 4 | 14 | - |
| Acid Saliva {@recharge 5} | 4d8 | 15 | - |


**Multiattack.** The thessalhydra makes one maw attack and one Flurry of Bites.

**Flurry of Bites.** {@atk mw} {@hit 7} to hit, reach 10 ft., one target. {@h}7 ({@damage 1d6 + 4}) piercing damage plus 10 ({@damage 4d4}) poison damage.

**Maw.** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}9 ({@damage 1d10 + 4}) piercing damage plus 5 ({@damage 1d10}) acid damage.

**Tail Pincer.** {@atk mw} {@hit 7} to hit, reach 10 ft., one target. {@h}10 ({@damage 1d12 + 4}) slashing damage, and the target is {@condition grappled}. As an action, the target can escape the grapple by succeeding on a {@dc 14} Strength ({@skill Athletics}) or Dexterity ({@skill Acrobatics}) check (its choice). Until this grapple ends, the thessalhydra can't use its tail pincer.

**Acid Saliva {@recharge 5}.** The thessalhydra spits a glob of acid at a point it can see within 30 feet of it. Each creature within 10 feet of that point must make a {@dc 15} Dexterity saving throw, taking 18 ({@damage 4d8}) acid damage on a failed save, or half as much damage on a successful one.

^Tags: #monster #type_monstrosity