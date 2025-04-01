# Nintra Siotta

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Nintra Siotta | Fey | 16 | 306 (36d10 + 108) | 17 | walk: 40 ft., fly: {'number': 40, 'condition': '(hover)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 2d4 + 7 | - | - |
| Shard of Shadow | 1d6 + 7 | 20 | - |
| Storm of Shattered Glass {@recharge} | 8d6 | 20 | No Damage ❌ |


**Multiattack.** Nintra makes two attacks.

**Claw.** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}12 ({@damage 2d4 + 7}) piercing damage.

**Shard of Shadow.** {@atk rs} {@hit 12} to hit, range 120 ft., one target. {@h}10 ({@damage 1d6 + 7}) necrotic damage, and if the target is a creature, it must succeed on a {@dc 20} Constitution saving throw or be {@condition poisoned} until the end of its next turn.

**Storm of Shattered Glass {@recharge}.** Nintra targets a point she can see within 60 feet of her and creates a 20-foot-radius sphere of swirling glass shards centered on that point. Each creature in the sphere must make a {@dc 20} Dexterity saving throw, taking 28 ({@damage 8d6}) slashing damage on a failed save, or half as much damage on a successful save. If Nintra is in the sphere, the shards deal no damage to her.

^Tags: #monster #type_fey