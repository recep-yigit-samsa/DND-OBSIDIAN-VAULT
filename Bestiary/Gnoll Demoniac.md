# Gnoll Demoniac

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Gnoll Demoniac | Fiend | 8 | 135 (18d8 + 54) | 16 | walk: 30 ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Abyssal Strike | 5d6 + 3 | - | - |
| Hunger of Yeenoghu {@recharge 5} | 8d6 | 14 | Half Damage ✅ |


**Multiattack.** The gnoll makes two Abyssal Strike attacks.

**Abyssal Strike.** {@atkr m,r} {@hit 6}, reach 5 ft. or range 60 ft. {@h}20 ({@damage 5d6 + 3}) Poison damage.

**Hunger of Yeenoghu {@recharge 5}.** The gnoll conjures a 30-foot {@variantrule Cube [Area of Effect]|XPHB|Cube} of magical {@variantrule Darkness|XPHB} originating from a point it can see within 60 feet, which lasts for 1 minute or until the gnoll's {@status Concentration|XPHB} ends on it. This area is {@variantrule Difficult Terrain|XPHB}. {@actSave dex} {@dc 14}, any creature that starts its turn in this area or enters it for the first time on a turn. {@actSaveFail} 28 ({@damage 8d6}) Necrotic damage, and the gnoll or a creature of its choice it can see gains 10 {@variantrule Temporary Hit Points|XPHB}. {@actSaveSuccess} Half damage only.

^Tags: #monster #type_fiend