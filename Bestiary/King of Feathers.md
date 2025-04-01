# King of Feathers

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| King of Feathers | Monstrosity | 8 | 200 (19d12 + 52) | 13 | walk: 50 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Bite | 4d12 + 7 | 17 | - |
| Tail | 3d8 + 7 | - | - |
| Summon Swarm {@recharge 5} | - | - | - |


**Multiattack.** The King of Feathers makes two attacks: one with its bite and one with its tail. It can't make both attacks against the same target.

**Bite.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}33 ({@damage 4d12 + 7}) piercing damage. If the target is a Medium or smaller creature, it is {@condition grappled} (escape {@dc 17}). Until this grapple ends, the target is {@condition restrained}, and the tyrannosaurus can't bite another target.

**Tail.** {@atk mw} {@hit 10} to hit, reach 10 ft., one target. {@h}20 ({@damage 3d8 + 7}) bludgeoning damage.

**Summon Swarm {@recharge 5}.** The King of Feathers exhales a {@creature swarm of wasps||swarm of insects (wasps)} that forms in a space within 20 feet of it. The swarm acts as an ally of the King of Feathers and takes its turn immediately after it. The swarm disperses after 1 minute. It can't use the Summon Swarm action while it is grappling a creature with its jaws.

^Tags: #monster #type_monstrosity