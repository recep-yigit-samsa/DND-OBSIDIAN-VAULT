# Mage Hunter

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Mage Hunter | Monstrosity | 5 | 85 (10d10 + 30) | 15 | walk: 40 ft., climb: {'number': 40, 'condition': '(hunter form only)'} ft., fly: {'number': 10, 'condition': '(hover sentry form only)'} ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack (Hunter Form Only) | - | - | - |
| Claw (Hunter Form Only) | 2d10 + 4 | - | - |
| Tail | 4d8 + 4 | 15 | - |
| Mage Tracker (Sentry Form Only) | - | 14 | - |


**Multiattack (Hunter Form Only).** The hunter makes two Claw attacks.

**Claw (Hunter Form Only).** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}15 ({@damage 2d10 + 4}) slashing damage.

**Tail.** {@atk mw} {@hit 7} to hit, reach 10 ft., one target. {@h}22 ({@damage 4d8 + 4}) piercing damage, and the target is {@condition grappled} (escape {@dc 15}). Until this grapple ends, the target is {@condition restrained}, and the hunter can't make a Tail attack against another target.

**Mage Tracker (Sentry Form Only).** The hunter emits a pulse of energy that helps it better locate its magical quarry. Each creature within 120 feet of the hunter that has the ability to cast spells must succeed on a {@dc 14} Wisdom saving throw or be mystically marked by the hunter for 1 hour. While marked, a creature can't become hidden from the hunter and gains no benefit from the {@condition invisible} condition against the hunter. Additionally, while a marked creature is on the same plane of existence as the hunter, the hunter always knows the distance and direction to the creature.

^Tags: #monster #type_monstrosity