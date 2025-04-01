# Intellect Devourer

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Intellect Devourer | Aberration | 2 | 28 (8d4 + 8) | 12 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Claw | 2d4 + 2 | - | - |
| Devour Intellect | 2d10 | 12 | - |
| Steal Body | - | 12 | - |


**Multiattack.** The intellect devourer makes one Claw attack and uses Devour Intellect.

**Claw.** {@atkr m} {@hit 4}, reach 5 ft. {@h}7 ({@damage 2d4 + 2}) Slashing damage.

**Devour Intellect.** {@actSave int} {@dc 12}, one creature the intellect devourer can see within 5 feet. {@actSaveFail} 11 ({@damage 2d10}) Psychic damage, and the target has the {@condition Stunned|XPHB} condition until the end of the intellect devourer's next turn.

**Steal Body.** {@actSave int} {@dc 12}, one Small or Medium creature within 5 feet that has the {@condition Incapacitated|XPHB} condition, is a Humanoid or Beast, and has 10 {@variantrule Hit Points|XPHB} or fewer. {@actSaveFail} The intellect devourer possesses the target, consumes its brain, and teleports inside its skull. While there, the intellect devourer has {@variantrule Cover|XPHB|Total Cover} against attacks and other effects originating outside its host. The intellect devourer retains its Intelligence, Wisdom, and Charisma scores; its understanding of Deep Speech; its telepathy; and its Detect Intelligence trait. It otherwise adopts the target's game statistics. It knows everything the target knew, including spells and languages. If the host body dies, the intellect devourer must leave it. The intellect devourer is also forced out if the target regains its devoured brain by means of a {@spell Wish|XPHB} spell. By spending 5 feet of its movement, the intellect devourer can voluntarily leave the body, teleporting to the nearest unoccupied space within 5 feet of it. The body then dies unless its brain is restored before the end of the intellect devourer's next turn.

^Tags: #monster #type_aberration