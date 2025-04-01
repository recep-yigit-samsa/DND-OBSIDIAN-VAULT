# Tosculi Hive Queen

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Tosculi Hive Queen | Monstrosity | 12 | 189 (18d10 + 90) | 17 | walk: 40 ft., fly: 60 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Scimitar | 2d6 + 7 | - | - |
| Stinger | 6d4 + 7 | 17 | - |
| Implant Egg | - | 20 | - |


**Multiattack.** The tosculi hive queen makes four Scimitar attacks.

**Scimitar.** {@atk mw} {@hit 11} to hit, reach 5 ft., one target. {@h}14 ({@damage 2d6 + 7}) slashing damage.

**Stinger.** {@atk mw} {@hit 11} to hit, reach 5 ft., one creature. {@h}22 ({@damage 6d4 + 7}) piercing damage, and the target must succeed on a {@dc 17} Constitution saving throw or be {@condition poisoned} for 1 minute. While {@condition poisoned} in this way, the target is also {@condition paralyzed}. A {@condition poisoned} target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. The hive queen's potent poison can be removed only by the {@spell greater restoration} spell or similar magic.

**Implant Egg.** The hive queen implants an egg into an {@condition incapacitated} creature within 5 feet of her that isn't a Construct or Undead. Until the egg hatches or is removed, the creature is {@condition poisoned}, {@condition paralyzed}, and doesn't need to eat or drink. The egg hatches after 30 days, and the larval tosculi bursts out of the host, killing the host in the process. A creature can take its action to remove the egg by succeeding on a {@dc 20} Wisdom ({@skill Medicine}) check. Alternatively, a spell or effect that cures disease disintegrates the unhatched tosculi.

^Tags: #monster #type_monstrosity