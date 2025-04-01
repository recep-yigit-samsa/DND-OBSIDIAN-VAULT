# Cobalt Golem

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Cobalt Golem | Construct | 18 | 300 (24d12 + 144) | 21 | walk: 40 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Slam | 3d10 + 9 | - | - |
| Sword | 3d12 + 9 | - | - |
| Spinning Cleave | - | - | - |
| Magnetic Pulse {@recharge} | - | 20 | - |


**Multiattack.** The golem makes two attacks: one with its slam and one with its sword, or it uses its Magnetic Pulse and then its Spinning Cleave.

**Slam.** {@atk mw} {@hit 15} to hit, reach 5 ft., one target. {@h}25 ({@damage 3d10 + 9}) bludgeoning damage.

**Sword.** {@atk mw} {@hit 15} to hit, reach 10 ft., one target. {@h}28 ({@damage 3d12 + 9}) slashing damage.

**Spinning Cleave.** The golem makes a sword attack against each creature within 10 feet of it.

**Magnetic Pulse {@recharge}.** The golem raises its arms and unleashes a magnetic pulse. All unattended metal objects within 30 feet of it are pulled to an unoccupied space within 5 feet of the golem. Each creature wearing metal armor or made of metal within 30 feet of the golem must succeed on a {@dc 20} Strength {@quickref saving throws|PHB|2|1|saving throw} or be pulled to an unoccupied space within 5 feet of the golem, then fall {@condition prone}.

^Tags: #monster #type_construct