# Wolfwere

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Wolfwere | Humanoid | 4 | 55 (10d8 + 10) | 12, 13 | walk: {'number': 30, 'condition': '(40 ft. in dire wolf form)'} ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack (Hybrid form only) | - | - | - |
| Longsword (Humanoid form only) | 1d8 + 4 + 1d10 + 5 | - | - |
| Bite (Wolf or Hybrid form only) | 2d6 + 4 | 14 | - |
| Claws (Hybrid form only) | 2d4 + 4 | - | - |
| Lethargic Song (Humanoid form only) | - | 13 | - |
| Change Shape | - | - | - |


**Multiattack (Hybrid form only).** The wolfwere makes two attacks: one with its Bite and one with its Claws.

**Longsword (Humanoid form only).** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}9 ({@damage 1d8 + 4}) slashing damage or 10 ({@damage 1d10 + 5}) slashing damage if used with two hands.

**Bite (Wolf or Hybrid form only).** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}11 ({@damage 2d6 + 4}) piercing damage. If the target is a creature, it must succeed on a {@dc 14} Strength saving throw or be knocked {@condition prone}.

**Claws (Hybrid form only).** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}9 ({@damage 2d4 + 4}) slashing damage.

**Lethargic Song (Humanoid form only).** The wolfwere plays a magical melody on an instrument. Every Humanoid within 200 feet of the wolfwere that hears the melody must succeed on a {@dc 13} Wisdom saving throw or be slowed for 10 minutes, as if the {@spell slow} spell has been cast on them. A creature can repeat the saving throw at the end of each of its turns. If a creature's saving throw is successful, the effect ends on it. A target that successfully saves is immune to this wolfwere's melody for the next 24 hours.

**Change Shape.** The wolfwere polymorphs into a wolf-humanoid hybrid or into a Humanoid (elf or human), or back into its true form, which is a dire wolf. Its statistics, other than its AC, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies

^Tags: #monster #type_humanoid