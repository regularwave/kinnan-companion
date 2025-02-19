# kinnan-companion
Assume Kinnan is in play.
Kinnan's first ability is a mana ability that triggers from the resolution of an activated mana ability; it does not use the stack and cannot be responded to (See CR 605, specifically 605.1b).
The source of the "extra" mana is Kinnan, not the non-land permanent tapped for mana.
Interaction with multipliers: Kinnan adds "on top" of the multiplied mana. Arcane Signet + Nyxbloom Ancient = four mana of one color.

Going "Infinite"
Basalt Monolith
Tap for 3+1 C. Pay 3 to untap. C floating. Repeat.

Hullbreaker Horror/Tidespout Tyrant
Need: HH/TT on field and 2 permanents that are collectively mana positive (one of which is in hand and the other is on the battlefield, or both on the battlefield with another spell in hand).
HH, Mox Amber + Sol Ring example with SR in play:
Tap SR for 2+1 C. (Mana pool is CCC.)
Cast MA, HH trigger targets SR. (Mana pool is CCC.)
Resolve HH trigger returning SR to hand. (Mana pool is CCC.)
Resolve MA. (Mana pool is CCC.)
Tap MA for U+U. (Mana pool is UUCCC.)
Cast SR, HH trigger targets MA. (Mana pool is UUCC.)
Resolve HH trigger returning MA to hand. (Mana pool is UUCC.)
Resolve SR. (Mana pool is UUCC.)
Loop. Tap MA for G+G every other MA cast to generate "infinite" U, G, and C.

A 0 mana value rock pairs with any other rock.
- be careful with Mox Opal's metalcraft
- Mox Diamond is good for getting the chain started if other rocks are already in play but not great as a HH/TT trigger target
- Chrome Mox: can decline the imprint trigger - it won't make mana but can bounce something else that goes positive with itself (SR, Mana Vault)
Two 2 mana value rocks don't work.
Is rock_A_mv + rock_B_mv < rock_A_mana_produced+1 + rock_B_mana_produced+1? 

HH/TT Without Kinnan
Sol Ring + 0mv
Mana Vault + 0mv
Sol Ring + Mana Vault
Mana Vault + 2mv
Is rock_A_mv + rock_B_mv < rock_A_mana_produced + rock_B_mana_produced?

Nyxbloom Ancient
"If you tap a permanent for mana, it produces three times as much of that mana instead."
This is a replacement effect and happens "before" Kinnan's mana ability triggers. Arcane Signet will produce 4 mana of one color - not 6 - with Kinnan and NA on the battlefield.
NA + Grim Monolith
NA causes Grim Monolith to go infinite with itself, similarly to Basalt Monolith.
Tap for 3x3+1 C. Pay 4 to untap. 6 C floating. Repeat.

NA+GM Without Kinnan
Tap for 3x3 C. Pay 4 to untap. 5 C floating. Repeat.

Others
Machine God's Effigy
If you or an opponent has a Devoted Druid on the battlefield and you resolve MGE and copy the DD, you should be able to generate "infinite" U or G and only split second can stop you.
MGE copying DD has these relevant characteristics:
Type: Artifact (not Creature)
T: Add U.
T: Add G.
Put a -1/-1 counter on ~this~: Untap ~this~.

Tap for U+U or G+G
Untap with -1/-1 ability.
Loop.

Because the MGEDD doesn't have toughness, it will never die from the -1/-1 counters. The mana abilities can't be responded to. Except for split second spells, responses to the -1/-1 ability can be responded to with another activation of the -1/-1 ability.

Freed From the Real/Pemmin's Aura
Put FFtR/PA on a creature that can tap for any color. It is notable that the untap abilities are on the enchantment itself and are not abilities granted to the creature (potentially allowing you to get around Harsh Mentor effects).

Tap for U+U. (Mana pool is UU.)
Pay U to untap. (Mana pool is U.)
Loop to generate "infinite" U.
Tap for G+G. (Mana pool is "infinite" U and GG.)
Pay U to untap. (Mana pool is "infinite" U and GG.)
Loop to generate "infinite" G. (Mana pool is "infinite" UG.)

FFtR/PA Without Kinnan
Nyxbloom Ancient
Tap for UUU. (Mana pool is UUU.)
Pay U to untap. (Mana pool is UU.)
Loop to generate "infinite" U.
Tap for GGG. (Mana pool is "infinite" U and GGG.)
Pay U to untap. (Mana pool is "infinite" U and GGG.)
Loop to generate "infinite" G. (Mana pool is "infinite" UG.)

Creatures that produce more than one mana on their own
Bloom Tender (FFtR/PA is your blue permanent)
Tap for UG. (Mana pool is UG.)
Pay U to untap. (Mana pool is G.)
Loop to generate "infinite" G. (Mana pool is "infinite" G.)
Tap for UG. (Mana pool is "infinite" G and one U).
Unfortunately, you can't "get ahead" and also generate "infinite" U with this setup. It does allow you to recast Kinnan from the CZ any number of times, though, if the the issue is that Kinnan isn't on the battlefield.

Sanctum Weaver
Because SW is an Enchantment Creature you now control (at least) two enchantments.
Tap for UU. (Mana pool is UU.)
Pay U to untap. (Mana pool is U.)
Loop to generate "infinite" U.
Tap for GG. (Mana pool is "infinite" U and GG.)
Pay U to untap. (Mana pool is "infinite" U and GG.)
Loop to generate "infinite" G. (Mana pool is "infinite" UG.)

Incubation Druid
Agatha's Soul Cauldron makes it easier to put a +1/+1 counter on this (a single counter will do - you don't have to Adapt 3).
Tap for UUU. (Mana pool is UUU.)
Pay U to untap. (Mana pool is UU.)
Loop to generate "infinite" U.
Tap for GGG. (Mana pool is "infinite" U and GGG.)
Pay U to untap. (Mana pool is "infinite" U and GGG.)
Loop to generate "infinite" G. (Mana pool is "infinite" UG.)

"Infinite" C - Things To Do
Unlimited Filters
Creature
Crossroads Candleguide
Scarecrow, EtB exile card in a graveyard

Prismite
Golem

Signpost Scarecrow
Scarecrow, Vigilance

Stonework Packbeast
Beast, Cleric, Rogue, Warrior, and Wizard

Non-creature
Energy Refractor
EtB draw

Gemstone Array
Save up counters for a future turn if you can't utilize the mana now.

Urn of Godfire
Sacrifice to destroy creature or enchantment

Special
Agatha's Soul Cauldron
Doesn't filter mana but allows Kinnan (or other creature) activations using only C.

Mirage Mirror
On battlefield: Basalt Monolith/Grim Monolith, a permanent that can generate both U and G, and Mirage Mirror. If the U/G-generating permanent is a creature, Mirage Mirror will need to have been on the battlefield since the beginning of the turn.
Priority is relevant; see RC117.3c.
Have "infinite" C.
Activate Mirage Mirror targeting Basalt Monolith/Grim Monolith. Hold priority.
Activate Mirage Mirror targeting the U/G-generating permanent. Hold priority.
Repeat the previous two steps an "infinite" number of times.
Then you start resolving the stack of Mirage Mirror activations - the "top" one will be one targeting the U/G-generating permanent.
Mirage Mirror is now a copy of the U/G-generating permanent. Tap for U or G.
Resolve the next Mirage Mirror activation.
Mirage Mirror is now a copy of Basalt Monolith/Grim Monolith. Pay CCC or CCCC to untap.
Repeat the previous four steps until the stack is cleared.
The result is that you have "infinite" U, G, and C.
Important to note that once one activation of Mirage Mirror has resolved it no longer has the copy ability. Mirage Mirror's "end state" might be relevant - adjust what the first activation targets if it is.

