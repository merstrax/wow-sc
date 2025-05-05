# Combat

### Weapon Type WoW to SC
- Guns &rarr; Rifles : Infantry and Ghost
- Wands &rarr; Healing Focus : Medics and Oracles
- Crossbow &rarr; Unique Ranged : Firebat Flamethrow, Marauder / Immortal Impact Cannons
- Throwing Weapon &rarr; Glaives : Adept

__Weapons that stay the same__
- Polearm &rarr; Zealot / Adept
- Dagger &rarr; Dark Templar / Specter
- Staves &rarr; High Templar

## Ranged Combat Mechanics
The ranged combat will be dealt with by making all the shots a directional cone instant cast. (Think cone of cold or multi-shot)<br>
Energy will be used as your clip value, when you have run out of energy you have to use the reload ability.<br>
Your weapon determines the amount of "energy" you receive (passive on equip: +10-50 energy)<br>
Talents and such can also increase this value to simulate extended magazines.<br>

### Ranged hit-rate mechanic:
Your abilities have 4 states - Standing, Crouching, Moving, Crouch Moving - Each one of these states changes your chance to hit.

| Miss %      |  Standing   |   Moving    |   Crouch    | Crouch Move |
| ----------- | ----------- | ----------- | ----------- | ----------- |
| Single Shot | 25% | 42% | 12.5% | 21% |
| Burst Shot  | 33% | 42% | 16.5% | 27.5% |
| Full Auto   | 50% | 83% | 25% | 41.5% |

For other none burst weapons they would follow this pattern:
Single Shot
Short Channel
Long Channel

Some classes might not have crouch but something similar to it. Ex: Heavy Terran might have slow march, reducing speed by 75%, damage received by 25% and miss chance by 66% (This is aimed to fit the theme of a line of fire-bats purging an area slowly)<br>
You can further reduce this chance with armor modifiers (Stabilizer) and scopes. Each of these would probably reduce the miss chance by 5% each in their best form.

## Elemental Combat and Damage Type Mechanics
Most enemies will have an elemental weakness and resistance. Every melee weapon and ammunition will be associated with an elemental type.<br>
Additionally elemental damage done through weapon damage and not a specified damage type through an ability, applies a debuff.

### Damage Types
- Physical : Chance to apply a sunder armor stack.
- Psionic (Arcane) : Chance to apply a sunder resist stack.
- Fire : Chance to apply a stacking burn dot, at 5 stacks increase critical hit chance by 5%.
- Poison (Nature) : Chance to apply a stacking poison dot, also reduces move speed.
- Light (Holy) : Chance to apply a debuff that reduces damage, at 5 stacks every additional proc does bonus damage.
- Dark (Shadow) : Chance to apply a debuff that reduces chance to hit, at 5 stacks every additional proc does bonus damage.

### Combined Damage Types
- Creep [Nature + Dark] : Zerg are immune to this damage type, stacks up to 20 times, at 20 stacks lose control of your character, after 30 seconds your character dies and explodes dealing massive damage.
- Radiation [Psionic + Light] : Stacking debuff that increases damage received, reduces max health and healing recieved, at 20 stacks your character dies. Zerg are weak to this damage type and receive 2 stacks at a time.
- Concussive [Physical + Psionic] : This damage type ignores shields and 50% of your armor. Chance to stun for a short period.