# Dybbuk

## Stat Block

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Dybbuk | fiend | 4 | 37 (5d8 + 15) | 14 | walk 0, canHover True |

## Abilities

- **STR** 6 | **DEX** 19 | **CON** 16 | **INT** 16 | **WIS** 15 | **CHA** 14
- **Saving Throws:** -  
- **Skills:** Deception ++6, Intimidation ++4, Perception ++4  
- **Damage Resistances:** acid, cold, fire, lightning, thunder, bludgeoning, piercing, slashing (from nonmagical attacks)  
- **Condition Immunities:** charmed, exhaustion, frightened, grappled, paralyzed, petrified, poisoned, prone, restrained  
- **Senses:** darkvision 120 ft.  
- **Languages:** Abyssal, Common, telepathy 120 ft.

## Traits

**Incorporeal Movement.** The dybbuk can move through other creatures and objects as if they were {@quickref difficult terrain||3}. It takes 5 (1d10 damage) force damage if it ends its turn inside an object.

**Magic Resistance.** The dybbuk has advantage on saving throws against spells and other magical effects.

**Violate Corpse.** The dybbuk can use a bonus action while it is possessing a corpse to make it do something unnatural, such as vomit blood, twist its head all the way around, or cause a quadruped to move as a biped. Any beast or humanoid that sees this behavior must succeed on a DC 12 Saving Throw Wisdom saving throw or become frightened condition for 1 minute. The frightened condition creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. A creature that succeeds on a saving throw against this ability is immune to Violate Corpse for 24 hours.


## Actions

| Action | Hit or Save | Damage | On Save |
|--------|--------------|--------|----------|
| Tendril | +6 to hit | 2d8 + 4 damage) necrotic | - |
| Possess Corpse {@recharge} | - | - | - |

**Tendril.** {@atk mw} +6 to hit to hit, reach 5 ft., one target. {@h}13 (2d8 + 4 damage) necrotic damage. If the target is a creature, its hit point maximum is also reduced by 3 ({@dice 1d6}). This reduction lasts until the target finishes a short or long rest. The target dies if this effect reduces its hit point maximum to 0.

**Possess Corpse {@recharge}.** The dybbuk disappears into an intact corpse it can see within 5 feet of it. The corpse must be Large or smaller and be that of a beast or a humanoid. The dybbuk is now effectively the possessed creature. Its type becomes undead, though it now looks alive, and it gains a number of temporary hit points equal to the corpse's hit point maximum in life.

While possessing the corpse, the dybbuk retains its hit points, alignment, Intelligence, Wisdom, Charisma, telepathy, and immunity to poison damage, exhaustion condition, and being charmed condition and frightened condition. It otherwise uses the possessed target's game statistics, gaining access to its knowledge and proficiencies but not its class features, if any.

The possession lasts until the temporary hit points are lost (at which point the body becomes a corpse once more) or the dybbuk ends its possession using a bonus action. When the possession ends, the dybbuk reappears in an unoccupied space within 5 feet of the corpse.


^Tags: #combat_ready #monster #type_fiend #cr_4