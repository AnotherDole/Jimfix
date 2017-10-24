This is a small collection of fixes and tweaks aimed at an Ascension + Fixpack
v10 + SCS v30 install. It should be smart about not letting you install
components you don't need, but you should still pay attention. I do not have a
copy of BG2 EE so please tell me if any additional issues arise in that
version of the game.

		       --- Fix Sunfire Power Levels ---

The damage effects on the level 10 version of Sunfire incorrectly have a power
level of 3. The primary effect of this is that they will be blocked by a Minor
or regular Globe of Invulnerability. The level 11 version also has one of its
damage effects set to power level 6. The component fixes both errors.

Credit to Alesa_BH for noticing this.

	     --- Enable Spell Immunity in Sequencers/Triggers ---

TobEx is intended to allow you to place Spell Immunity into Contingencies and
Triggers. However, this functionality is not enabled by default. This
component enables it.

	    --- Shield of Reflection works on SCS Flame Arrows ---

In vanilla, the Reflection Shield reflects the mage spell Flame Arrow. SCS
mages are scripted to act as if this is the case. However, with the "Make
Protection from Normal Missiles affect some magical projectiles" component,
the Reflection Shield does not actually reflect Flame Arrow. This component
re-adds that ability to the Reflection Shield.

			 --- Fix Smarter Abazibal ---

In previous versions of Ascension + SCS, when Abazigal turned in to a dragon
he would also spawn a purple dragon named Tamah. In SCS v30, Tamah does not
appear if you have installed the Smarter Abazigal component. Abazigal also has
the wrong script which may make him unreasonably difficult to kill for some
parties. This component fixes both glitches.

Credit to Mad Mate on the G3 forums for help with this fix.

		  --- Fix Smarter Irenicus at the Throne ---

A scripting glitch causes Irenicus to be completely harmless during the
opening fight at the Throne of Bhaal if you have the component that adds SCS
AI to him. This component fixes this.

Credit to Alesia_BH for noticing this and to Aasim for help with this fix.

	    --- Remove Entourage from Ascension Fallen Solars ---

In the original Ascension version of the first fight at the Throne of the
Bhaal, you must fight two Fallen Solars. As of SCS v25, the Smarter Celesitals
Component causes both of these Fallen Solars to additionally spawn with two
Mariliths, a Succubus, and an Alu-fiend. While it has not been officially
confirmed, there is significant evidence to suggest that these extra demons
are unintentional. This component removes them.

		    --- Fix incorrect casting animations ---

In the vanilla game, several spells have casting animations that don't match
the actual school of the spell. The Fixpack fixes some of these but misses
others. This component takes a broad approach and checks each standard mage
and priest spell individually. If the casting animation does not match the
spell school, the casting animation is changed.

This component also fixes a vanilla bug where the spell Conjure Animals is
erroneously set as an Enchantment spell.

This component may be overkill. It provides of a listing of all the changes it
makes so if you don't like some of them, you can uninstall the component.

		       --- Prevent silent prebuffs ---

Under certain conditions, SCS smarter mages will silently gain some long
duration prebuffs. This component changes this behavior to always display
these prebuffs in the combat log.

	   --- Add spell school notifications to the combat log ---

By paying attention to the casting animation or by listening to the casting
sounds, it is possible to determine the school of the spell a mage or priest
is casting. This tweak makes this information clearer by adding a message to
the combat log as well. It should be installed after any component that
modifies spells and combines well with the component that fixes incorrect
casting animations. You can pick the minimum casting speed of spells that you
would like this tweak to affect.

There are two issues with this tweak:
1) It works by modifying the spells so it applies to your spells as well as
enemy spells. 

2) It does not take into account the fact that some enemies have innately
lower casting times for spells. The intent of this tweak is to not provide you
with any information that you didn't already have access to, but this may not
always be the case.

If there are any spells that are not affected but should be, or should be
affected but are not, please let me know.

		--- Add expiration notifications for buffs ---

This component adds periodic reminders to the combat log for when spell buffs 
are about to expire. The reminders come when there are 120, 60, 30, 12, and 6
seconds remaining in the buff. I can add other options if there is interest.

And again, please let me know if this component affects spells that it
shouldn't or if it doesn't affect a spell that it should.

		--- Add expiration notifications for item buffs ---

This is the same as the previous component except with buffs from items.
Mostly this affects potions and protection scrolls, but it also includes
the Greenstone and Shield Amulets.

			--- Reveal all hidden doors ---
			
This component sets all hidden doors to be immediately selectable so that you
don't have to wait for a character to detect them.