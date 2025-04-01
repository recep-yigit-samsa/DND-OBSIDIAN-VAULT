# Draconic Shard

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Draconic Shard | Undead | 17 | 168 (16d12 + 64) | 17 | walk: 0 ft., fly: {'number': 80, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Telekinetic Rend | 2d8 + 6 | - | - |
| Inhabit Object | 1d8 force | - | - |
| Psychic Crush {@recharge 5} | 10d10 | 20 | - |


**Multiattack.** The shard makes two Telekinetic Rend attacks.

**Telekinetic Rend.** {@atk ms,rs} {@hit 12} to hit, reach 10 ft. or range 120 ft., one target. {@h}15 ({@damage 2d8 + 6}) force damage.

**Inhabit Object.** The shard disappears as it pours its psychic essence into a Medium or smaller nonsentient object it can see within 30 feet of it, magically possessing it. The object uses the shard's AC, and any damage dealt to the object applies to the shard's hit points. The shard inhabits the object until it uses an action to leave; until it is turned; until it is reduced to 0 hit points; or until an effect that ends possession, such as a {@spell dispel evil and good} spell, is used on it. When it leaves the object, it reappears in the nearest unoccupied space. While inhabited, the object becomes a magic item if it wasn't already, and a Tiny cracked gemstone matching the kind of gem dragon the shard was in life appears somewhere on the object. The shard can cause the object to fly using the shard's own flying speed, use its senses, speak verbally or telepathically, cast spells, and use its legendary actions. If a creature wears or carries the inhabited object, the shard can grant the creature the following benefits: Each of the creature's attacks deals an extra {@damage 1d8} force damage on a hit. The creature gains resistance to psychic damage.

**Psychic Crush {@recharge 5}.** The shard unleashes a pulse of psychic power. Each creature of the shard's choice in a 60-foot-radius sphere centered on it must make a {@dc 20} Intelligence saving throw. On a failed save, the creature takes 55 ({@damage 10d10}) psychic damage and is {@condition stunned} until the end of its next turn. On a successful save, the creature takes half as much damage and isn't {@condition stunned}.

^Tags: #monster #type_undead