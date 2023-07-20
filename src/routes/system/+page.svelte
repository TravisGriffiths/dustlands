<script>
   import T from "$lib/components/T.svelte";
</script>

<article>

   <h1>The EZd6 System</h1>

   <hr>

   The <a href="https://www.ezd6.com/">EZd6 system</a> is played with 1 to 6 six sided dice, written by the amazing DM Scotty
   available from <a href="https://www.drivethrurpg.com/browse.php?keywords=ezd6&x=0&y=0&author=&artist=&pfrom=&pto=">DriveThru RPG</a> 
   is a minimalist system that has won endless awards and praise from both game reviewers and GMs alike. The system tries to 
   keep all of the fun and stories of common RPGs while cutting the rules to the smallest set possible. The focus is to drive 
   ineresting stories quickly, while making player choices central. 

   <p></p>

   <h2>Core Mechanic</h2>

   Every task has a difficulty, and a target number for that task ranging from Easy (2) to Super Hard (6)
   <ul>
      <li>Easy (2)</li>
      <li>Normal (3)</li>
      <li>Hard (4)</li>
      <li>Very Hard (5)</li>
      <li>Super Hard (6)</li>
   </ul>

   Roll a six sided dice. If you roll the task target number, or higher, your character succeeds. 

   <h2>Core Combat</h2>
   Every opponent has a difficulty to hit just like tasks. For the average enemy, the target number is 3. Characters are normally
   simply a 3 for any opponent to hit. Succeeding on an attack roll will always do a single <a href="#strikes">strike</a> of 
   damage on an opponent no matter what the weapon. <a href="#crital-hits">Critical Hits</a> can do more damage, see below. 

   <h2>Boons</h2>
   When a character is particularly good at doing something, they get a "boon". A boon means you may roll 
   <span class="font-bold">two</span> dice and take the <span class="font-bold">highest</span>. The target number to beat for 
   the task is the same. 

   <h2>Banes</h2>
   When a character is attempting something unusually difficult, for example fighting in total darkness, they will have 
   a "bane". A character with a bane rolls two dice and take the <span class="font-bold">lowest</span>. Banes cancel 
   out boons, resulting in a normal one die roll. 

   <h2>Failure</h2>
   Failure is not all bad. While the character will not succeed at the task, any character failures earns a 
   <a href="#karma">Karma</a> point. Lots of failure, leads to lots of karma which can save a character when 
   they really need it. Karma is explained below. 

   <h2>Critical Failures</h2>
   Rolling a one is a critical failure. It means that not only did a character fail the task, but the GM may apply more secondary 
   difficuties to the situation. Droping a weapon, running out of ammunition, alerting the guards are all examples. 
   <span class="font-bold">Note:</span> the <span class="underline">KEPT</span> die must roll a one. Since a boon is rolling two and keeping the highest, to 
   roll a critical failure while having a boon, means the player has to roll double ones. A skilled character might fail, but 
   is unlikely to really screw up. Likewise a character working under difficult conditions, with a bane, has two chances to roll 
   a critical failure, as either die can be a one, and will be kept.  

   <h2 id="critial-success">Critical Success</h2>
   Similar to critical failures, a 6 is always a success. In combat, hitting an opponent with a critical success does the normal 
   strike of damage, and the player may roll to hit again. On the "confirming" roll, rolling a further six will do another strike, 
   and allow a player to roll again to see if the critical hit continues. There is NO limit on how much damage this can cause. It is 
   also totally possible to use <a href="karma">Karma</a> to "bump" these rolls, allowing massive critical strikes when a players really needs them, if 
   they are willing to spend the resources on them. It is also important to know, that if a critical streak continues to do damage 
   after the first target is defeated, it can continue to strike reachable nearby opponents. 

   <h2 id="karma">Karma</h2>
   Karma is a meta currency that all characters have. A character normally gets 3 karma points at the start of any session. As 
   metioned, any failure earns a character an additional karma point. A karma point can be spent to move a roll by 1 for each 
   karma point spent. If the karma spent turns the roll into a <span class="font-bold">success</span> the karma is spent and 
   the character succeeds in a task. Note that karma cannot mitigate a critical failure unless a player decides to spend enough
   karma to turn the critical failure into a success. The other major use of karma is to keep a critical success roll going in 
   order to create massive damage in a single attack. All karma resets back to 3 each session, and so it a "use or lose" pool.
   Im addition, spending 5 karma can buy a hero die if a player desires. Finally, karma may <span class="font-bold">not</span> 
   be used for Magic, Miracles or any Magic Resistance rolls, these are the manifestation of Chaos, and are immune to mortal karma. 

   <h2>Hero Dice</h2>
   Every character get a single hero die at the start of each session. This can be used to reroll <span class="font-bold">ANY</span>
   roll made by a player, to include those rolls usually excluded from karma manipulation. This is usually kept to reroll critical 
   rolls like final death saves, but a player may use them at any time they wish. The reroll must be kept, unless a second hero die 
   is used for a further reroll. 

   <h2>Time</h2>
   Time is measured in 3 units. Narrative time, Action time and Scenes. Narrative time is the flow of time when time is not flowing 
   form moment to moment. It is the normal flow of time during a game session. This may be a few minutes at an Inn or could suddenly
   leap ahead weeks or months. The flow is organic an set by the story, but each player should get input into what is going on. 
   Action time is usually the time used when a party engages in combat, but could also be any time where seconds matter and things 
   are happening very fast. In these cases, player actions go in strict order with each player having an action going around all 
   players. Scenes are called "encounters" in other systems and is just a natural segment of the story. Most effects with a duration
   will map to a scene. Action time usually all falls into a single scene each time it starts and stops. 

   <h2>Actions</h2>
   In Action time, each character gets a <span class="font-bold">move, action</span> and a <span class="font-bold">free action</span>. 
   A move is the ability for a character to move or reposition. Actions are things like an attack, pick up an item, cast a spell or arm a shield. Most things that require a roll are actions. A player may also choose to use actions to do additional 
   movement instead of a normal action if desired. A player may also choose to <span class="font-bold">delay</span> which allows a 
   player to jump in at any point in the round before all players and opponents have acted. This allows players to intterupt opponets 
   so is sometimes desirable. Free actions are quick and simple actions, like speaking (short phrases), taking potions, drawing weapons 
   (as opposed to shields) etc. 

   <h2>Move</h2>
   A move action can move a character about 30 feet (10 meters). Everything within 30 feet is considered <span class="font-bold">near</span> and 
   everything farther than that is condiered <span class="font-bold">far</span> difficult terrain can cause the distance covered in 
   a single move action to be less. 

   <h2>Initiative</h2>
   Normally, all players go in order around the table, in whatever direction the players wish. Then all the opponents act. The only
   exception is when the characters are surprised, in which the turn will instead start with all the opponents, then the players as 
   normal. 

   <h2>Contests</h2>
   Opposed actions, like grappling are contests. The character and opponent both roll, using any boons and karma spent, and the 
   highest roll wins. Ties mean there is no winner for this round and the contest continues to the next one. 

   <h2>Saves</h2>
   There are rolls to resist negative effects or damage. There are several different types and they all work a bit differently. 

   <h4>Armor</h4>
   By far the most common type of save. Whenever a character is hit, they can make an armor save. In general, this is a 4 or better for 
   heavy armor, 5 or better for medium and a 6 for light. If the player succeeds on the save, the strike does not penetrate. If a character
   is hit with a critical, the save is rolled for each strike of the critical, potentially mitiating each. For very large weapons or 
   massive spells that do more than a single strike in an attack, only the first strike may be deflected. 

   <h4>Miraculous</h4>
   When a charcter faces a certain death *save or die* situation the player rolls a miraculous save. Each character path has a target 
   for what this roll is, but most have to roll a hard 6. As this is essentially divine intervention, karma may 
   <span class="font-bold">not</span> be used for this roll, but hero dice may. For most other "save" type of events, being on fire 
   being poisoned, or falling, this is also a miraculous save. However, because these are more "mundane" rather than divine checks, 
   a player <span class="font-bold">can</span> use karma on these rolls. For most of these, as the damage potential is open ended, the 
   player will roll taking strikes for every failed save until they succeed...or die <a href="strikes">(see: strikes)</a>. For effects 
   like poison or burning that take place over time, this will be one save per turn. For instant effects, like a fall, all saves and damage 
   is rolled, and applied in one turn. This makes these effects considerably more deadly than in many other games, and makes resistance or 
   boons with these rolls more valuable than many players expect. 

   <h4>Magic</h4>
   Many spells require a target to resist. The roll is usually determined by the spell and caster. For example, a spell cast against 
   many targets is much easier to resist than one cast against only one. As this is the stuff of raw chaos however karma can not be used 
   either to boost these rolls.  

   <h2 id="strikes">Strikes</h2>
   Most characters have 3 strikes. That is they can be hit 3 times before dying. All normal weapon hits do a single strike of damage unless
   a critical strike is rolled. Giant weapons like ballista and similar can do two or more strikes per hit. Note that an armor save is for 
   mitigating a single strike, so that in these rare cases, involving massive weapons or spells, a character can succeed an armor 
   save and still take "overflow" damage. This does not apply to simple crits. Each strike in a crit series has an armor roll as normal 
   Opponents may be able to take less or more strikes. Healing strikes can happen naturally at a rate of one strike 
   per day, if the character spends it fully at rest. Healing in this manner requires a proper place to really rest. Hard living 
   out in the wilderness is not going to allow this to happen. A character must be in a <a href="#sanctuaries">Sanctuary</a> to rest. This does not need to be anything complex. Just a "home base", or a comfortable area free of stress and challenges. See details below. Magic and some inclinations can speed this up considerably. 
   
   <h4>Uncouncious and Dying</h4>
   When a character takes the last strike, they get a miraculous save to avoid it in <T c="b">addition</T> to the normal armor save. 
   Succeeding on this roll prevents the strike. This roll may not use karma. Failing this, a character falls unconcious. They lose all 
   spell anchors, fall prone, and may suffer other effects depending on the situation. Absent any intervention, the character must 
   succeed on a miraculous save every turn without help from karma or will <T c="b">die</T>. For characters having inclinations making 
   them resistant to death, the bonus or reroll only applies to the very first roll to fall unconcious, not to any following saves. The 
   chances of any character surviving more than a round or two in this state are remote. Resurection, is occasionally possible, but rarely 
   succeeds. To have any chance of succeeding, it must be attempted within 3 days of death. The body must be in excellent condition. The 
   miracle roll is made against maximum resistance, being a full six resistance dice. Failure often causes the body to raise as a 
   zombie or other undead, although cases of divine fire consuming the body or worse effects are known. The failure effect is always bad, and up to 
   the player of the dead character, but no retries are going to be possible.  Resurection is theoretically possible, but the Gods 
   do not often give up souls. 

   <h2 id="spells">Magic & Miracles</h2>
   Full magic casters will have a "circle" of magic in which they have been inducted or otherwise trained. This sets the flavor and tone of all the spell effects they can use. These effects are <T c="b">not</T> enumerated. Magic is chaos and doesn't sit in a dictionary to be memorized or cataloged. Each caster has to navigate the path the mastering chaos personally, and even casters the same circle who studied the same effect under the same teacher will have significant, even huge differences in all the details of magical effects they create. For players this means they make up spells as desired, in accordance with the flavor of the character's chosen circle. The resistance roll against the effect taking place is decided by the GM depending on how expansive, powerful and closely the spell adhears to the casters circle. For simple effects happening in narrative time that hold to the flavor of a magic circle is unlikely to require a roll at all. E.g. an elemental pyromancer can light fires in narrative time without having to roll. For other effects, with some exceptions, a caster can only cause a single strike of damage, which will be resisted with a single die. 
   Adding targets, adds dice at 1:1, up to the maximum of 6. A few circles bend these guidelines a bit. 
   Lesser effects are easier, while effects that instantly remove threats (e.g. turn an opponent to stone) will be harder. 
   Any spell that takes place over multiple rounds must be anchored, that is, concentrated on. 
   Only one effect can be anchored at a time. Taking any strikes, or falling unconcious will break the anchored spell.

   <h4>Spell Power</h4>
   Every caster can use from one to three dice to power thier spells and overcome the resistance roll. The trade off is that any one rolled 
   on any of these dice cause the spell to fail, no matter what the highest roll was, unless the caster decides to "push through" and take 
   <T c="b">Spell Burn</T>. That is, they can choose to willingly take a strike of damage to have the spell succeed IF the roll would have otherwise been 
   a success. This is totally up to the player. Using more dice on a spell has no other effect on things like the damage done. Spells 
   <T c="b">CANNOT</T> be critical successes. 

   <h4>Spell Cost</h4>
   Powerful spells may require the character spend karma to cast or maintain, at the option of the GM. 

   <h4>Order of Casting</h4>
   When casting a spell, the order of events is
   <ol>
      <li>Player describes the spell to be cast</li>
      <li>GM announces difficulty and rolls resistance</li>
      <li>The player decides what spell power to use (1-3 dice) and rolls</li>
      <li>Player decides on spell burn if applicable.</li>
      <li>Spell takes effect or fails</li>
   </ol>

   <h4>Effects</h4>
   An incomplete list of possible effects, use your imagination and do not be afraid to experiment.  
   <ul>
      <li>Dulled Senses</li>
      <li>Fear</li>
      <li>Fatigue</li>
      <li>Pushing/Pulling</li>
      <li>Immobile</li>
      <li>Knocked Down</li>
      <li>Cursed</li>
      <li>Polymorphed</li>
      <li>Silenced</li>
      <li>Stunned</li>
      <li>Slowed</li>
   </ul>

   Beneficial Effects
   <ul>
      <li>Armored</li>
      <li>Enhanced Senses</li>
      <li>Boosted</li>
      <li>Concealed</li>
      <li>Enhanced Movement</li>
   </ul>
   

   <h2 id="sanctuaries">Sanctuaries</h2>
   These are simply locations where a character can rest and heal effectively. Most paid lodging, Inns and the like would be considered a sanctuary, while camping and living hard would not. Healing can still take place out in the wild, but takes much longer. A character can only heal a single strick per <T c="b">week</T> outside of a sanctuary. Most parties will develop one, or even multiple "bases" that count as sanctuaries for this purpose. Wardens have the ability to make semi-permanent "camps"
   that are able to serve as sanctuaries. 


   <h2 id="scrolls">Scrolls, Potions and Magic Items</h2>
   Scrolls are consumable magic items that allow characters with the proper training to cast the magic contained in them. 
   They are destroyed on use. Scrolls are most commonly written on sheets of paper, but can be any encoding of a spell ritual allowing the trained to make use a consumable spell effect. Clay tablets, carved bones, even tatoos are possible. These are created by Sorcerers, and require time and karma to complete. Most magic circles require acolytes to produce quite a few of these before they can graduate. These are most often sold or distributed and are a key source of the circles financial and political power. To cast from a scroll, a player rolls 2 six sided dice and reroll any ones (scrolls cannot critical fail by nature) for the casting check. 
   
   <p></p> 
   
   <b>Potions</b> are a different beast, being a consumable magic item usable by anyone. These are possible as magic is woven into the nature of the entire world, and those who have studied these natures can distill these effects and inclinations into useful effects. While circle mages often do study Alchemy, the full time creation of potions is usually done by trained Alchemists, who produce these as a primary job. Most settlements will have at least a single individual trained in creating potions. They may be willing to sell (or buy) both potions and ingredients from characters. In larger settlements, Alchemists often have an entire separate crafts guild just like any other mage circle. 

   <p></p>

   Magic Items are created by Sorcerers much like Scrolls. The art of doing this well, and safely, is considerably more involved and thus tends to be a specialty within the schools. Artificers require significantly long times and karma to produce these items, and so are not typically done by characters. These items are often commisioned by the wealthy and powerful from skilled artificers. Once created, these items resist the passage of time and are hard to destroy, and so are prized treasures to be found in ruins and ancient sites, giving one of the primary motivations to explore the Wastes.

</article>