# Empyrean

| Name | Type | CR | HP | AC | Speed |
|------|------|----|----|----|-------|
| Empyrean | Unknown | 23 | 346 (21d12 + 210) | 22 | walk: 50 ft., fly: {'number': 50, 'condition': '(hover)'} ft., swim: 50 ft., canHover: True ft. |

### Actions:

| Ability | Damage | Save DC & Type | On Successful Save |
|---------|--------|----------------|--------------------|
| Multiattack | - | - | - |
| Sacred Weapon | 6d6 + 10 | - | - |
| Divine Ray | 6d8 + 8 | - | - |


**Multiattack.** The empyrean makes two attacks, using Sacred Weapon or Divine Ray in any combination.

**Sacred Weapon.** {@atkr m} {@hit 17}, reach 10 ft. {@h}31 ({@damage 6d6 + 10}) Force damage, and the target has the {@condition Stunned|XPHB} condition until the start of the empyrean's next turn. The target can choose not to be {@condition Stunned|XPHB}, in which case it takes an extra 21 Force damage that bypasses {@variantrule Resistance|XPHB} or {@variantrule Immunity|XPHB}.

**Divine Ray.** {@atkr r} {@hit 15}, range 600 ft. {@h}35 ({@damage 6d8 + 8}) Necrotic or Radiant damage (empyrean's choice).

^Tags: #monster #type_unknown