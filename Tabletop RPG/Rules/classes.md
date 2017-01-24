# General Abilities
_Unstoppable_  
This unit cannot be flanked.

_Omni Tool_  

_Tech Hardpoint_  

_Endurance Costs_  
* Low: 2
* Medium: 4
* High: 8
* Very High: 16

## Proficiencies

_Armor Proficiency_  

_Weapon Proficiency_  

## Specializations
_Armor Specialization_  

_Weapon Specialization_  

_Dual Wield Specialization_  


# Class Overview
* _Commando [`AGI`]_  
    Mobile ranged support & dps which controls the battlefield through tactical maneuvers and employs advanced technology and weapons to devastate his enemies.
    * _Marine [`PRES`]_  
    The epitome of the perfect super soldier. Augmented to perform superhuman feats of strength, and trained in sophisticated battle disciplines, the Marine takes ultimate control of the battlfield and makes a natural party leader.
    * _Bounty Hunter [`INT`]_  
    Able to handle almost any situation, the Bounty Hunter brings the most devastating technology to bear, including Javelin Missile Systems and Jetpacks. With his aresnal of explosives and gadgets, the Bounty Hunter is a true one man army, obliterating foes from afar.
* _Marauder [`STR`]_  
    * _Warblade_  
* _Heavy [`STR`]_  
    * _Immortal_  
    * _Juggernaut_  
* _Scoundrel [`AGI`]_  
    * _Outrider [`WILL`]_  
    * _Assassin [`INT`]_  
* _Specialist [`INT`]_  
    * _Medic_  
    * _Operator_  
* _Adept [`WILL`]_  
    * _Templar_  

# Base Classes
## Commando
| Details | |
|----|----|
| Primary Attribute | Agility |
| Weapon Proficiency | Medium |
| Armor Proficiency | Heavy |
| Base Health | 24 |

### Starting Equipment
* Carbine
* Handgun
* Silencer

### Abilities
| Level | Proficiency | Features                                                                         |
| ----- | -----       |----------------------------------                                                |
| 1     | +2          | Tactical Visor, Overwatch                                                        |
| 2     | +2          | Soldier's Endurance, Weapon Specialization (proficient), Tech Hardpoint (low)    |
| 3     | +2          | Run and Gun, Tech Hardpoint (medium)                                             |

#### Tactical Visor [grid]
// TODO

#### Overwatch
* Action: Standard
* Endurance Cost: Medium

The Commando uses a tactical maneuver to enter Overwatch until the start of his next turn. While in Overwatch, the Commando can take opportunity attacks on any target that takes a move action in his line of sight and is not in cover. These opportunity attacks do not consume his reaction.

#### Soldier's Endurance 
* Action: Bonus
* Endurance Cost: Medium
* Triggers healing surge in combat. Healing surges triggered this way do not consume charges.

// FLUFF

#### Run and Gun
* Action: Bonus
* Endurance Cost: Low
* Gain the effects of the dash, disengage, and dodge actions.
* Can move after making ranged attacks.
* Ignore cumbersome property of weapons.

// FLUFF

## Marauder
| Details | |
|----|----|
| Primary Attribute | Strength |
| Weapon Proficiency | Heavy |
| Armor Proficiency | None |
| Hit Dice | 30 |

### Starting Equipment
* Heavy Claymore

### Abilities
| Level | Proficiency | Features                           |
| ----- | -----       |----------------------------------  |
| 1     | +2          | Rage, Ignore Pain, Athletics (1)   |
| 2     | +2          | Mubarak Disciplines (Tier 1)       |
| 3     | +2          | Warrior's Fury                     |

#### Rage
Each time the Marauder deals damage with a standard attack, or takes damage from an attack he gains `1` point of rage. These rage points can be used to excecute special abilities. Rage points are depleted at the end of combat.

#### Rage Costs
* Low: 1
* Medium: 3
* High: 5
* Very High: 10

#### Ignore Pain  
* Action: Standard
* Duration: Encounter
* Endurance Cost: Low

The Marauder consumes all of his current rage, gaining temporary hp equivalent to `3x` rage consumed.

#### Mubarak Disciplines 
The Marauder chooses to specialize in one of three ancient battle disciplines, gaining new abilities as he gains levels.

* Tal'dari Zealot
    * Tier 1
        * Gain: Dual Wield Specialization
        * Gain: Zephyr Strike
* Arbiter of Zala'nosh
    * Tier 1
        * Gain: Armor Specialization (Heavy Shield)
        * Gain: Titan's Grip
        * Gain: Unstoppable
    * Tier 2
        * Gain: Hand of Zala'nosh
* Harbinger of Chaos
    * Tier 1
        * Gain: Weapon Specialization (Heavy)
        * Gain: Inferno Strike

#### Zephyr Strike
_"Soft o'er the shrouds aerial whispers breathe, that seemed but zephyrs to the train beneath."_  
* Action: Bonus
* Duration: Turn
* Rage Cost: High
* Range: Long

The Marauder's body becomes one with the wind, and he materializes at a location within range. For the duration of the turn, the Marauder has advantage on attacks and spells.

#### Titan's Grip 
The Marauder may simultaneously wield both a two handed melee weapon in his main hand and a shield in his off hand, however while equipped in this manner his speed is reduced by `one` square.

#### Hand of Zala'nosh 
* Action: Full
* Endurance Cost: High
* Requires Equipped: Shield
* Duration: Channeled

The Marauder interposes his shield in between his allies and his foes, granting full cover to both himself and all allies in a short cone behind him. Additionally, if the Marauder has any temporary hit points from Ignore Pain, they will also shield allies who take damage while under the protective barrier. 

While channeling, the Marauder cannot move, change direction, or take any action. Moving the shield requires recasting the ability.

#### Inferno Strike  
_"He makes the winds his messengers, flaming fire his ministers."_

* Action: Full
* Rage Cost: High
* Details
    * Area of Effect: Line (3), Medium
    * Range: Melee
    * Damage: Weapon
    * Damage Type: Fire
    * Targets: Agility
    * Affected targets are stunned for `1d4` rounds

Primal fire surrounds the Marauder's weapon, surging ahead in a line as the warrior hefts it forward, striking all enemies in the area of effect. Enemies are engulfed in a roiling torrent of supernatural flame, a testament to the Mubarak faith and power.

#### Warrior's Fury 
_"Ideals are peaceful. History is violent."_

* Action: Bonus
* Endurance Cost: Very High
* Details
    * Gain `5` rage instantly
    * Double move speed for `1d4` rounds

The Marauder channels deep seeded rage, becoming an unstoppable juggernaut of fury.

## Heavy
| Details | |
|----|----|
| Primary Attribute | Constitution |
| Weapon Proficiency | Heavy |
| Armor Proficiency | Heavy |
| Hit Dice | 30 |

### Starting Equipment
// TODO

### Abilities
| Level | Proficiency | Features                            |
| ----- | -----       |----------------------------------   |
| 1     | +2          | Mechanized Chassis, Basic Power Armor, Overshield, Tech Hardpoint (low) |
| 2     | +2          | Mechanized Protocols, Immortality Protocol     |
| 3     | +2          | Oppression Protocol, Tech Hardpoint (medium)   |

#### Mechanized Chassis
While there are many variants of Power Armor, they are all based on a similar mechansized chassis and share many similar attributes. Those common attributes are listed below.

* Entering and exiting the mechanized chassis is a full round action.
* Advantage on all `STR` ability checks.
* Double carrying capacity.
* Cannot be flanked.
* Unable to benefit from cover.
* Treated as a mechanical unit.
* No penalty for using ranged weapons while engaged in melee.

Entering and exiting the mechanized chassis is a full round action.

#### Basic Power Armor
Basic Power Armor provides the following benefits.
* One equipped item can be mounted to the armor itself, reducing its encumbrance to 0 and ignoring the cumbersome property. However, this item cannot be removed from the chassis.
* Increases AC by `2`.
* `1` Protocol hardpoint.

#### Overshield 
* Action: Full
* Endurance Cost: Medium
* Duration: Until Cancelled

The Heavy creates an Overshield with a `3` square diameter, which protects all allies inside. The Overshield's hit points are equivalent to `50%` of the Heavy's max `health` and the barrier has no AC. While active, the barrier intercepts all ranged attacks on characters inside the barrier, while allowing them to attack from inside. It does not restrict movement in any way. The Heavy can only maintain one Overshield at a time.

#### Mechanized Protocols 
//TODO

#### Oppression Protocol
* Successful basic attacks disorient the target.
* Increase movement speed by `2`.

#### Immortality Protocol
* Add `CON` modifier to soak value in addition to other attributes.
* Reduce movement speed by `2`.

## Scoundrel
| Details | |
|----|----|
| Primary Attribute | Agility |
| Weapon Proficiency | Medium |
| Armor Proficiency | Light |
| Base Health | 20 |

### Starting Equipment
* Sniper Rifle
* Handgun
* Silencer
* Omni Tool

### Abilities
| Level | Proficiency | Features                                       |
| ----- | -----       |----------------------------------              |
| 1     | +2          | Opportunist, Omni Tool, Tech Hardpoint (`Low`) |
| 2     | +2          | Sneak Attack (`2d6`), Peerless Skill (`2`)     |
| 3     | +2          | Killzone, Tech Hardpoint (`Medium`)            |

#### Opportunist
On the first round of any combat, the Scoundrel may take an additional turn at the beginning of the round.

#### Sneak Attack
* Action: Bonus
* Duration: Turn
* Endurance Cost: Low

The Scoundrel takes advantage of an opponent's weakness at every opportunity. As a bonus action, the Scoundrel targets an opponent for a sneak attack. When the Scoundrel attacks and hits that target this turn and has advantage on the attack, or if the opponent is adjacent to an ally of the Scoundrel, the Soundrel deals additional sneak attack damage.

#### Peerless Skill
The Scoundrel gains a bonus rank in the given number of skills.

#### Killzone
* Action: Full
* Duration: Round
* Endurance Cost: High
* Concentration
* Area of Effect: Cone
* Range: Weapon

The Scoundrel marks a cone in front of him as a Killzone with a range equivalent to the range of his equipped weapon and concentrates on the shot. At the beginnig of his next turn, he unleashed a devastating volley of shots, firing once at every target in the area. These shots deal weapon damage and also apply sneak attack damage to targets struck in this manner.

## Specialist
| Details | |
|----|----|
| Primary Attribute | Intelligence |
| Weapon Proficiency | Light |
| Armor Proficiency | None |
| Base Health | 16 |

### Starting Equipment
* Submachine Gun
* Omni Tool
* Duster
* Ocular Enhancement

### Abilities
| Level | Proficiency | Features                                                 | TC1 | TC2 |
| ----- | -----       |----------------------------------                        |:---:|----:|
| 1     | +2          | Specialist Droid, Omni Tool, Tech Hardpoint (`Low`)      |0    |0    |
| 2     | +2          | Tech Casting, Neural Link                                |2    |0    |
| 3     | +2          | Energy Transferrence                                     |3    |1    |

#### Specialist Droid 
The Specialist begins with a standard Specialist Droid. The droid gains in power along with the specialist and moves seperately, but on the same turn, and at the direction of the specialist.

| Features | |
|----|----|
| Base Health | 12 (INT) |
| AC | 12 + INT |
| Type | Mechanical |
| Statistics | STR: `-1` AGI: `+2` CON: `+2` WILL: `+0` INT: `+0` PRES: `+0` |
| Skills | Stealth (Proficient), Perception (Proficient) |
| Cadeucius Blaster | Basic Attack: `1d6 + INT (INT)`, Energy, Medium |
| Cauterize | While under the effect of `Neural Link`, consecutive hits on the same target deal double damage. For example, three consecutive strikes would deal `1x`, `2x`, and `4x` damage respectively. |

#### Tech Casting [grid]
Specialists are equipped with an advanced Omni Tool which allows the usage of special Tech Abilities. These abilities are slotted into tech slots, and consume a new resource, energy, whenever they are used. The standard Omni Tool starts with a maximum of `6` tech slots, and can only hold a limited number in each tier which is defined in the abilities table above. Tech Abilities are physical items which can be bought or found, however upon reaching level 2, the Specialist may pick `4` of these items from the Tier 1 listing - a results of his intensive technology training.

The Specialist begins with `20 + (4 x INT)` energy, and gains `5 + INT` additional energy every `5` levels. These energy points are reset after a long rest.

#### Neural Link [grid]
The specialist is able to observe through the senses of his droid as an action. During this time, the Specialist is incapacitated but has complete remote control of his droid. Cancelling the neural link is a free action, but cannot be done on the same turn as activation. 

Additionally, the Specialist Droid gains the `WILL`, `INT`, and `PRES` stats and proficiencies of the Specialist while the link is active, and the droid is able to perform Omni Tool actions.

Finally, Specialist Droids will often have special abilities that are only activated while under the direct control of the Specialist through Neural Link. These abilities will be documented accoringly in the Specialist Droid stat block.

#### Energy Transferrence [grid]
The specialist is able to use tech abilities through either his Omni Tool, or the Specialist Droid. If an ability is used through the Specialist Droid, it uses both the droid and the specialist's action. Additionally, positive effects which effect the Specialist are duplicated and also effect the Specialist Droid.

## Adept
_"The secrets of Khydrian Artifacts are a pathway to many abilities some consider to be unnatural."_

| Details | |
|----|----|
| Primary Attribute | Willpower |
| Weapon Proficiency | Light |
| Armor Proficiency | None |
| Hit Dice | 16 |

### Abilities
| Level | Proficiency | Features                         | C   | KC1 |
| ----- | -----       |----------------------------------|:---:|:---:|
| 1     | +2          | Prescience, Metastasis, Impulse  |0    |0    |
| 2     | +2          | Cantrips, Presence of Mind       |2    |0    |
| 3     | +2          | Khydrian Casting                 |2    |2    |

#### Prescience 
At the beginning of each day, the Adept rolls `2d20` and records the results. At any time, the Adept can replace the result of any attack roll, ability check, or saving throw with the result of one of the stored rolls, even after the roll has already occured. Using the result this way consumes it.

#### Metastasis
At the beginning of each day, the Adept gains a pool of temporary hit points equal to `5 + WILL [scaling]`. If the Adept gains additional Metastasis points through other means, it cannot go above this cap. Unlike most temporary hit points, whenever the Adept takes damage, he can choose to take damage from this pool or from his normal health pool.

#### Impulse
* Action: Standard, Instant
* Damage: `1d4 + INT (INT)`, Force, Medium, Constitution
* On a sucessful hit the target takes damage and is marked with void fluctuations. On the target's next turn, if it deals damage, the Adept gains `Metastasis` points equal to the damage dealt. If the target has multiple attacks this effect only applies to the first.

#### Cantrips
_Light_
* Light effect.

_Telekenesis_  
* Spell Type: Force
* Target: Object
* Mage Hand effect.

_Shield_  
* Action: Standard
* Spell Type: Force
* Target: Creature
* Target gains `1d6 + INT` temporary shield points which last until the start of your next turn.

_Burden_  
* Action: Standard
* Spell Type: Force
* Target: Creature
* Attack: `(INT)`, Long, Constitution
* Half the target's movement speed for `1d4` rounds.

_Haste_  
* Action: Standard
* Spell Type: Force
* Target: Creature
* Range: Short
* Double the target's movement speed for `1d4` rounds.

_Bound_  
* Action: Standard
* Spell Type: Force
* Target: Creature
* Range: Short
* Double the target's jump distance for `1d4` rounds.

#### Presence of Mind
When the Adept's Metastasis shield is at it's maximum, he can consume it to various effect as a bonus action.
* Gain an additional `Prescience` charge. Immediately roll and record the value.
* Heal any target equal to the amount of shield points consumed.
* Add the shield points consumed as damage to the next damaging spell cast.
* Gain `1d4 + INT` endurance.