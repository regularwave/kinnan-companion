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

Treasure Vault
Activate to generate "half" of "infinite" C treasures.
Is an artifact (any artifact tutor) with a mana ability (Moonsilver Key) and land (Crop Rotation).

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

C Sinks
Dimensional Infiltrator
Exile everyone else's libraries.
Dodges removal as long as one player has a land somewhere in their library.

Prophet of Distortion
Draw your deck.

Thrasios, Triton Hero
For some winning lines, it it is important to leave specific cards in the deck. Can this ever be an issue if the cards are consecutive as you'd scry one to the bottom but then be forced to put the second onto the battlefield tapped or draw it?

Winning
Notes on ways to win
Assume "infinite" U, G, and C mana available/in mana pool.

Straightforward
Blue Sun's Zenith
BSZ works great with Thrasios on the battlefield as you can force one player to lose and then use Thrasios to put the BSZ back into your hand as many times as needed to cause all other players to lose.

Drown in Dreams
Target one player with the draw mode and another with the mill mode. Use Endurance to put your graveyard on the bottom and then find DiD again with Thrasios.

Finale of Devastation
With enough creatures on the battlefield to get around blockers, make all of your creatures enormous, give them haste, then attack.

Stroke of Genius
Force one player to lose by drawing too many cards.

Thassa's Oracle
Draw until there are a number of cards left in your library ≤ your devotion to U, play TO.

Walking Ballista
Cast with a large X, ping each other player until they lose.
Note: no opportunity to add counters if you put WB onto the battlefield through Kinnan's ability.

Cephalid Coliseum
A complex line with a few different methods. Allows for an "instant-speed" win. For all cases, assume "infinite" U, G, and C, and that Thrasios is on the battlefield.

The "easy" line - Colossal Skyturtle and Invasion of Ikoria
Setup:
Cephalid Coliseum on the battlefield (tapped or untapped)
Flash enabler (untapped Emergence Zone on the battlefield, High Fae Trickster on battlefield or in hand, Valley Floodcaller on battlefield or in hand, etc)
Hullbreaker Horror on battlefield or in hand or Tidespout Tyrant on the battlefield
Threshold
Mirage Mirror on the battlefield (not copying anything) or in hand
Have access to Colossal Skyturtle and Invasion of Ikoria (can be in deck)
Have any other permanent on the battlefield (must be non-creature if Valley Floodcaller is your flash enabler; Sol Ring in this example)

Gain the ability to cast spells as though they had flash (Activate Emergence Zone's second ability or have High Fae Trickster or Valley Floodcaller on the battlefield, etc).
Activate Thrasios until you have Colossal Skyturtle and Invasion of Ikoria in your hand.
If not on the battlefield, cast Mirage Mirror.
HH trigger you can decline or target any permanent an opponent controls/TT trigger targets any permanent an opponent controls.
Activate Mirage Mirror targeting Cephalid Coliseum. (This is the beginning of the loop.)
Activate the Mirage Mirror copy of Cephalid Coliseum targeting an opponent. Mirage Mirror will end up in your graveyard. Hold priority.
Activate Colossal Skyturtle's first channel ability to return Mirage Mirror to your hand. Do not allow the Mirage Mirror copy of Cephalid Coliseum's ability to resolve.
Cast Invasion of Ikoria with X≥7.
HH/TT trigger targets Sol Ring.
Resolve HH/TT trigger, returning Sol Ring to your hand.
Resolve Invasion of Ikoria, returning Colossal Skyturtle to the battlefield from your graveyard. Do not allow the Mirage Mirror copy of Cephalid Coliseum's ability to resolve.
Cast Mirage Mirror.
HH/TT trigger targets either Colossal Skyturtle or Invasion of Ikoria.
Resolve HH/TT trigger, returning either Colossal Skyturtle or Invasion of Ikoria to your hand.
Resolve Mirage Mirror. Do not allow the Mirage Mirror copy of Cephalid Coliseum's ability to resolve.
Cast Sol Ring.
HH/TT trigger targets whichever of Colossal Skyturtle or Invasion of Ikoria is still on the battlefield.
Resolve HH/TT trigger, returning whichever of Colossal Skyturtle or Invasion of Ikoria is still on the battlefield to your hand.
Resolve Sol Ring. Do not allow the Mirage Mirror copy of Cephalid Coliseum's ability to resolve.
Loop.

Repeat the loop for one opponent until they have "infinite" Cephalid Coliseum activations targeting them. Then repeat the whole process for each other opponent, holding priority throughout. Once all opponents have "infinite" Cephalid Coliseum activations targeting them, start allowing them to resolve. If your opponents have interaction - or find it from the Cephalid Coliseum draws - you can repeat the loop in response to the interaction to eliminate that player. This is the "easy" setup mainly because it only requires you to gain threshold once at the beginning.