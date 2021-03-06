# Stat system scaling:
Minimum stat: 0 (should only happen due to penalties, instant failure in most scenarios)

Nominal stat: 8 ("average" person)

Very high stat: 14 (realistic world class human, maximum cost-effective in chargen)

Maximal stat: 20 (higher may be achievable, but we're not worried about balancing at that point.)


# Skill system scaling:
Minimum skill: 0 (no training)

Maximum skill: 10 (requires regular training to maintain, "professional" level)


# Monster melee skill scaling:
Minimum skill: 0 (no melee potential; turret, fungal wall)

Nominal skill: 4 (average critter; most zeds & giant insects)

Notable skill: 6 (competent/carnivore; bear, wolf, police/survivor zeds)

Very high skill: 8 (dangerous opponent; dark wyrm, vinebeast)

Maximal skill: 10 (highest for balance purposes; jabberwock, tribot, shoggoth, gracken)


# Speeds:
Zombies are a bit faster than "shambling". Zombified versions of fast critters will remain fast, but in general the process slows the undead version. Further, under no circumstances should a zed be more than 50% faster than base character speed. Currently, this means "capped at 150".


# Dodge System assumptions:
Dodge chance is based on attacker's melee skill and target's dex stat and dodge skill.

Successful dodges negate the attack and impose a cumulative penalty on dodges within the same turn.

## Dodge Use Cases:
An individual with no skill and nominal stats in ideal circumstances against a basic opponent should occasionally be able to dodge.

An individual with no skill and nominal stats in ideal circumstances against a skilled opponent should rarely if ever be able to dodge.

An individual with world-class dodging ability, in ideal circumstances against a basic opponent should have a negligible chance of failure.

An individual with world-class dodging ability, in ideal circumstances against a skilled opponent should have a moderate chance of failure.

The effect of increasing dodge skill has a growth rate with diminishing returns that accelerates sharply at the point where you move beyond the dodge a "regular" character is likely to achieve (7  and above)

The balance of melee versus dodge should favour dodge which, after all, isn't effective against a wide variety of other types of attacks.

Even a world class dodger should not be able to dodge continuously when attacked many times a turn.


# MELEE WEAPONS:
## To-Hit Bonuses
To-hit bonuses start at '-2' and are modified as follows for weapons that have the following properties:

### Grip
Grip is a measure of how well you can control the weapon to quickly respond to situational changes.

-1 - Particularly hard to grip items, (especially those that are innately slipper or very rounded with no obvious gripping edge) such as basketballs and barrels, or which are dangerous to hold because of very sharp edges, like scrap metal and broken glass.

+0 - Any object that doesn't fall into one of the categories below. Examples include 2x4s, computer monitors, wires, stingers and clothing. Basically, anything that has a grippable component, but which is too thick, too thin, or too flimsy to grab comfortably in a way that can reliably control the object.

+1 - A weapon with a fairly solid grip, like a pipe, a rock, guitar neck, pool cue or a heavy stick.

+2 - A weapon with a dedicated grip shaped to the hand, like a sword, axe, knife, or police baton, or that is strapped to the body (or is a piece of the body). Fists would get a +2 bonus here, bringing them to "0" total, since none of the others would apply.

### Length
Length allows more surface area for potential contact, and reduces the need to control the positioning of the body to guarantee a hit. It also allows the player to strike from a safer distance, allowing them to worry more about trying to hit without being hit in return, and allows for swings with larger arcs, making dodging such a strike more difficult.

+0 - Any object without a length bonus.

+1 - Objects that, when held, extend over a foot (1/3 of a meter) in length from the hand. A normal american 12inch ruler is the handy boundary guide for when an item should switch over to a +1 bonus (the ruler, losing several inches when held, does not get one - unless you added a handle to it!).

+2 - An object that is over 3 feet in length from the point where it is held. Includes swords, spears, quarterstaffs, poles, and a lot of other stuff.

### Striking Surface
Some weapons need to strike in a certain way to be effective. Others are more difficult to use "incorrectly".

-2 - Single-Point weapons - Picks, spears, syringes. Any weapon that has a single point that must contact the enemy in a specific way in order to deal a decent amount of damage. Also, weapons with difficult attack angles, like scythes, where the damaging part of the weapon is faced away from the enemy.

-1 - Line of damage weapons - Swords, knives, and other weapons that require a solid strike along a particular piece of the weapon, where the weapon can be said to have an attack angle, fall here. Weapons that have point attacks but are still effective without any solid hit, such as a nailboard, would also fall here.

+0 - attack-anywhere weapons - Clubs, pipes, maces, etc, where the weapon will be dealing full damage with a solid blow no matter how it is angled, because every surface is a striking surface.

+1 - Weapons that can still do significant damage even with glancing blows would fall here. Jagged tearing weapons and electric weapons like a stun baton would fall here.

### Balance
A measure of how well-suited the item is for being swung/thrust/etc. This factors in overall balance of the weapon, weight is accounted for separately.

-2 - Very clumsy or lopsided items ill-suited for swinging or thrusting.  Characterized by requiring effort just to hold steady.  frying pan or pot, chainsaw, chair, vacuum cleaner.

-1 - Balance of the object is uneven, but in a way that at least doesn't interfere with swinging. axes, sledgehammer, rifle, scythe, most polearms.

+0 - Neutral balance, neither well nor poorly weighted for the typical use. Heavy stick, rock, pool stick, kitchen knives, claw hammer, metal pipe, crowbar, handguns.

+1 - Well-balanced for swinging or stabbing.  Baseball bat, golf club, swords, quarterstaff, knives.

##Damage
Weapon's relative strength is based on an approximate formula involving its damage, to-hit, techniques and few other factors.
This strength will be expressed in "points" or dpt (damage per turn) as damage per turn is the most significant balancing factor.

### Damage per turn
Melee weapon's relative strength is measured by damage per turn (more precisely: damage per 100 moves). The damage is sum of all damage types (average of min/max where random) from the weapon alone, without including strength in the calculation.
For bashing weapons, it is assumed the character can achieve the maximum damage, but this strength isn't added to damage (or critical damage).

### To-hit
While not a direct measure of damage, to-hit bonus has to be included in the calculations, as it has a significant effect on actual damage output (through hit and crit rate).

Each point of to-hit is "worth" roughly a 10% increase/decrease in damage per turn or 2.5 points of damage per turn (whichever is higher).

### Techniques
Rapid strike technique increases damage per turn by 0.66 / 0.5 = 132%
Other techniques are generally too situational to be worth any points here.

### Weapon tiers
Damage per turn should put the weapon into one of those categories:

<10 - Not weapons. Those items may be pressed into service, but are unlikely to be better than fists. Plastic bottles, rocks, boots.

11-15 - Tools not meant to strike and improvised weapons. Two-by-fours, pointy sticks, pipes, hammers.

16-25 - Dangerous tools or crude dedicated weapons. Golf clubs, two-by-swords, wooden spears, knife spears, hatchets, switchblades, tonfas, quarterstaves.

26-35 - Good dedicated weapons or the most dangerous of tools. Wood and fire axes, steel spears, electric carvers, kukris, bokken, machetes, barbed wire bats.

36-45 - Weapons of war, well designed to kill humans. Wakizashis, katanas, broadswords, zweihanders, combat knifes, battle axes, war hammers, maces, morningstars.

46+ - Sci-fi stuff. Diamond katanas, monomolecular blades, lightsabers and chainswords.

## Other melee balancing factors
### Attack speed
Out of two weapons with same dpt, the faster one is generally better.
Faster weapons allow more damage granularity (less overkill), make it less likely to miss a turn (and thus dodge/block recharges) and make positioning easier.
Slower weapons will pierce armor better, but currently most enemies are very lightly armored.

### Damage type
At low skill, piercing damage suffers from scaling and bashing damage from damage limit due to low strength and skill. Cutting damage is not affected.
At high skill, bashing damage is generally the strongest, but still suffers from the damage limit.
Exotic damage types (currently only fire) do not scale with skills or crits.

# LIQUIDS:
Multi-charge items are weighed by the charge/use.  If you have an item that contains 40 uses, it'll weigh 40x as much (when found in-game) as you entered in the JSON. Liquids are priced by the 250mL unit, but handled in containers.  This can cause problems if you create something that comes in (say) a gallon jug (15 charges) and price it at the cost of a jug's worth: it'll be 15x as expensive as intended.

To that end, here's a list of containers with non-one volume.  If you have something spawn in 'em, divide the "shelf" price by this value to arrive at the correct price to list in the JSON.

- plastic bottle: 2

- glass jar: 2

- glass bottle: 3

- plastic canteen: 6

- 3L glass jar: 12, as expected

- gallon jug: 15