<script>
   import Stat from "$lib/components/Stat.svelte";
</script>

<article>

   <section>

      <h1>Making a character</h1>

      Character creation is simple and quick. First, get an idea of what kind of character you would like to play. This 
      concept is important in the choices you will make next. Unlike other systems it is impossible to make a "ineffective"
      character. While some concepts will be superior in different situations, as they should be. There are no right and 
      wrong choices to be made. Also, unless two players make totally identical choices for the entire process, characters 
      will have significant differences. It is entirely possible and playable for every player to decide to be a spellcaster
      or warrior. There are no "gaps". Keep your concept in mind and choose what seems fun. 

      <h3>Character Creation Steps</h3>
      <ul>
         <li>
            <a href="#paths">
               Choose a Hero Path
            </a>
         </li>
         <li>
            <a href="#bloodlines">
               Choose a Bloodline
            </a>
         </li>
         <li>
            <a href="#inclinations">
               Choose Inclinations
            </a>
         </li>
         <li>
            <a href="#aspects">
               Create Aspects
            </a>
         </li>
         <li>
            <a href="#circles">
               (Casters Only) Choose a Circle of Sorcery
            </a>
         </li>
      </ul>

   </section>

   <section id="paths">
      <h2>Hero Paths</h2>
      
      A hero path is what would be called a "class" in most other systems. The choice will set the framework and the 
      most important strengths and weaknesses your character will have. Each path has the following:
      <h4>Health</h4>
      This is the number of Strikes this path gets. It is usually 3. Rather than heroes and monsters having mountains
      of "hit points". This tends to create long slogs, and slows play. All weapons do 1 strike of damage on a hit. 
      critical hits and a few other things can cause more. 
      <h4>Armor & Miraculous Saves</h4> 
      This is the target number on the path's armor save. An armor save is made whenever you are hit. Rolling the number
      or higher means the attack does not penetrate the characters armor. This is set by path, not by an equipment purchase.
      Miraculous save is the target number for what would usually be a "saving throw" in other systems. To catch yourself from 
      falling off a cliff, survive a bad poisoning or other dangers use this target number.  
      <h4>Boon</h4>
      These are the types of things a character is especially good at. Rather than a specific description of a set list of 
      "skills", this is a general category or categories that a path is good at. When making checks for this type of check 
      this role will have a boon, being able to roll another die, usually making the check for these tasks 2 dice rather than 
      the normal one. When either "Melee" or "Ranged" is listed, it is that weapon type, meaning that role is able to use an 
      extra die when rolling attacks with that type. 
      <h4>Path Abilities</h4>
      These are the "powers" or abilities of the path.

      <h3>Beastmaster</h3>
      Animal friend
      <Stat label="Health" value="3 strikes" />
      <Stat label="Armor" value="Medium, save 5+,  miraculous save 6" />
      <Stat label="Boon" value="Melee OR Ranged and Animal tasks" />
 
      <div>
 
       <div class="my-2">
          <i>Beastspeech</i> - You can speak to any animal. 
       </div>
 
       <div class="my-2">
          <i>Beast Aid</i> - You can convince beasts to aid you for a limited time under the right circumstances. 
       </div>
 
       <div class="my-2">
          <i>Beast Friend</i> - You start with a beast companion. It is your friend, not a slave. It will stay with you as long as it is well treated, protected and looked after. 
          It may be any animal up to medium size, having 1 or 2 strikes. 
       </div>
 
      </div>

      <hr>

      <h3>Brute</h3>
      A tower of muscle and primal rage
      <Stat label="Health" value="5 strikes" />
      <Stat label="Armor" value="Light (5+), Miraculous Save 6" />
      <Stat label="Boon" value="Melee and Strength tasks" />

      <div>

            <div class="my-2">
               <i>Enrage</i> - You can sacrifice one of your strikes to inflict an extra strike on a hit. 
            </div>

            <div class="my-2">
               <i>Superstitious</i> - You have a boon to resist magic you do not wish to affect you. 
            </div>

      </div>

      <hr>

      <h3>Conjurer</h3>
      A mage, sorcerer and master of the arcane 
      <Stat label="Health" value="3 strikes" />
      <Stat label="Armor" value="Light, saves on 6 for both Armor and miraculous checks" />
      <Stat label="Boon" value="Arcane tasks" />
 
      <div>
 
       <div class="my-2">
          <i>Barrier</i> - As an action, you can shield yourself with magic util it absorbs a hit or your fall unconcious.
       </div>
 
       <div class="my-2">
          <i>Master of Magic</i> - Gain mastery in one <a href="#circles">circle of Sorcery</a>. 
          This allows you to cast <a href="/system#spells">spells</a> themed to this circle. 
       </div>
 
       <div class="my-2">
          <i>Seeker of Sorcery</i> - Can use <a href="/system#scrolls">scrolls</a>. Start with two random scrolls. 
       </div>
 
       <div class="my-2">
          <i>Focus</i> - You have a magic focus, (wand, staff etc.) which can make magic attacks doing a single strike of damage. 
          These attacks are unable to crit. You must choose the nature of these attacks at creation (bolts of fire, necrotic rot etc.). 
          No matter the nature of the attack, these simple focus strikes will not have secondary effects, e.g. fire bolts will not start fires, but outright magic spells <i>can</i>.
       </div>
 
      </div>
 
      <hr>

      <h3>Delver</h3>
      A master of the deep and dark, a tomb raider
      <Stat label="Health" value="3 strikes" />
      <Stat label="Armor" value="Medium (5+), Miraculous Save 6" />
      <Stat label="Boon" value="Melee OR Ranged Weapons and spelunking/subterrainean exploration tasks" />

      <div>

         <div class="my-2">
            <i>Gear</i> - Always ready to explore, you have a climbing kit, with pitons, 50' rope, torches, a small hammer and some chalk. 
         </div>

         <div class="my-2">
            <i>Jack</i> - Pick a bonus inclination in addition to the normal selections and any bonus for your bloodline. 
         </div>

      </div>

      <hr>

     <h3>Friar</h3>
     A shaman, holy man, priest or charlatan
     <Stat label="Health" value="3 strikes" />
     <Stat label="Armor" value="Medium and Blessed, Save on both Armor and Miraculous checks on a 5+" />
     <Stat label="Boon" value="Resisting heretical Magic and Religious knowledge checks" />

     <div>

      <div class="my-2">
         <i>Empathic Healing</i> - As a free action. Heal anyone in near range of a single strike by absorbing one strike. They gain a strike you lose one. 
      </div>

      <div class="my-2">
         <i>Holy Light</i> - As an action, once per day, call down holy light within near range. The light can either heal allies or damage enemies. 
         For healing, roll number of dice equal to number of allies. For each 4+ in this pool, you can heal a single strike on an ally of your choice.
         No ally may be affected by more than a single strike of healing. 
         For damaging enemies, roll the same pool equal to the number of enemies, each 4+ allows you to inflict a single strike. Undead and deamons take 2 strikes for each of these. 
         You can regain this abilty by spending 5 karma. In addition, unlike other miraculous or magical effects, you may spend karma on these rolls. 
      </div>

     </div>

     <hr>

     <h3>Rascal</h3>
     A criminal, scoundral, thief or acrobat. 
     <Stat label="Health" value="3 strikes" />
     <Stat label="Armor" value="Light and quick on your feet - Roll 2d6, keep highest aginst 6 for both Armor and Miraculous saves" />
     <Stat label="Boon" value="Acrobatic tasks" />

     <div>
      
      <div class="my-2">
         <i>Tricks</i> - Once per turn as a free action, you may avoid a singe <i>melee</i> strike, provided that attack did not roll a 6.
      </div>

      <div class="my-2">
         <i>Gank</i> - If you surpise an opponent or they are engaged with another combatant, roll 2d6 to attack, each die can independently do a strike of damage.
         If you normally would have a boon on the attack the dice are just the 2d6 independent attacks (you do not gain an additional die unless your attack would normally be a singe die)
         Both of these dice can crit independently.
      </div>

     </div>

     <hr>

     <h3>Skald</h3>
     A lore master, historian, academic or entertainer
     <Stat label="Health" value="3 strikes" />
     <Stat label="Armor" value="Medium, save 5+, Prognostication, miraculous save 5+" />
     <Stat label="Boon" value="Lore and Performance tasks" />

     <div>

      <div class="my-2">
         <i>Scroll Master</i> - You are able to cast magic from <a href="/system#scrolls">scrolls</a>. Start with 2 random scrolls. 
      </div>

      <div class="my-2">
         <i>Traveler</i> - On your travels and studies you have managed to hone a skill, like Melee, Acrobatics, Diplomacy, Observation. 
         Select a skill to gain a boon in. 
      </div>

      <div class="my-2">
         <i>Strands of Fate</i> - As a student of the Weave of Fate, you are able to manipulate Fortune.
         Allies, within near range, may spend karma against the GM, subtracting a pip per karma point on thier rolls as desired. 

      </div>

     </div>

     <hr>

     <div class=" grid grid-cols-3 gap-2">

    
         <div class="col-span-2">
            <h3>Warden</h3>
            A master of the wilderness, hunter, a survivor
            <Stat label="Health" value="3 strikes" />
            <Stat label="Armor" value="Medium (5+), Miraculous Save 6" />
            <Stat label="Boon" value="Ranged Weapons and Wilderness Tasks" />

            <div>
               <div class="my-2">
                  <i>Trailfinder</i> - You can track and find traces of passing creatures or individuals. 
               </div>

               <div class="my-2">
                  <i>Forager</i> - You can sustain yourself and others in the outdoors. Under most circumstanses, this is automatic, but in challenging conditions this might require rolls. 
               </div>

               <div class="my-2">
                  <i>Make Camp</i> - Given at least 3 hours in normal conditions, you can create a camp comfortable enough to count as a <a href="/system#sanctuaries">sanctuary</a>, allowing party members to recover hits while resting there. 
               </div>

               <div class="my-2">
                  <i>Survivalist</i> - Given nothing but sticks and stones, bones and leather, and some time, can create simple tools, weapons and light armor. 
               </div>
            </div>
         </div>

         <div class="p-2">
            <img src="/imgs/warden.jpg" alt="Warden" class="object-cover">
         </div>

      </div>
     <hr>

     <div class=" grid grid-cols-3 gap-2">

     
      <div class="p-2">
         <img src="/imgs/warrior.png" alt="warrior" class="object-cover" >
      </div>
    

     <div class="col-span-2">
         <h3>Warrior</h3>
         A professional fighter, soldier or man-at-arms 
         <Stat label="Health" value="3 strikes" />
         <Stat label="Armor" value="Heavy 3+ w/shield otherwise 4+" />
         <Stat label="Boon" value="Strength and Melee" />

         <div>

            <div class="my-2">
               <i>Martial Instruction</i> - Somewhere, somehow, you gained access to, and mastery to the martial skills of a full blown <a href="#/styles">Martial Style</a> decide on the style, source and details. 
            </div>

            <div class="my-2">
               <i>Enemies</i> - No one gets as good as you are without fighting somehone. This causes enemies. Choose yours and record who they are. 
            </div>

            <div class="my-2">
               <i>Shield Sacrifice</i> - Once per scene as a free action, you may choose to deflect all attack damage from yourself or a close ally 
               for the entire round, but your shield is destroyed by this maneuver. You can activate this even after damage has been inflicted.
               You may spend 5 karma to avoid destroying your shield. If your shield is destroyed, your Armor save becomes the normal shieldless 4+. 
               A warrior must be using a shield to use this maneuver (naturally). 
            </div>

            <div class="my-2">
               <i>Brutal Strikes</i> - As a master of two handed weapons, your strikes score critical hits on a 5 or 6. You cannot use a shield to use this, and must have a two handed weapon equiped.
            </div>

            <div class="my-2">
               <i>Dual Weapons</i> - You are deadly when dual wielding weapons. Attack with an extra boon when using two weapons in this way, for a 3d6 on attacks.
               To do this, you must have multiple one-handed weapons equipped. This means not using a shield or a larger weapon. 
            </div>
         </div>
      </div>
      </div>
     <hr>
     

   </section>

   <section id="bloodlines">

      <h2>Bloodlines</h2>
      For thousands of years, all of the old races, elves, dwarves, goblins, orc, even ogres and trolls lived in proximity. Crossbreeding was inevitable. 
      The cataclysm made this even more pronounced, as pure survival overtook petty concerns of racial purity. 
      As a result, everyone has mixed parantage, usually in a complex and unfathomable complexity going back over unrecorded centuries. 
      Heights and sizes range from nearly 3 feet to over 7 feet tall, with variations of pointed ears, facial hair and a vast range of skin tones. 
      Different individuals retain differnt advantages from this genetic diversity. These are divided into major and minor traits. 
      A character may have a single major bloodline trait or 2 minor traits selected from those below. These reflect the major traits showing through from your heritage.
      Selections must all come from a single choice of bloodline group, and the mixed bloodline, since many phenotypes are opposites (large and small size for example)

      <h4>Robust Bloodline</h4>
      <ul>
         <li><b class="mr-2">Vigorous Metabolism</b><i>Minor</i> Boon to resist poison</li>
         <li><b class="mr-2">Ogre Blood</b><i>Minor</i> Boon to Strength tasks</li>
         <li><b class="mr-2">Pureblood Ogre</b><i>Major</i> Succeed on save to loose your last strike on a 4+</li>
         <li><b class="mr-2">Troll Blood</b><i>Minor</i> Regain one strike per day outside a sanctuary</li>
         <li><b class="mr-2">Pureblood Troll</b><i>Major</i> Regain one strike per at the start of each scene</li>
         <li><b class="mr-2">Orcish Tradition</b><i>Minor</i> Boon to Melee (cannot stack with any other source)</li>
      </ul>

      <h4>Diminuative Bloodline</h4> 
      <ul>
         <li><b class="mr-2">Ground Level</b><i>Minor</i> Boon to notice threats below eye level.</li>
         <li><b class="mr-2">Scamper</b><i>Minor</i> Foes larger than you have difficulty hitting you (+1 to target number)</li>
         <li><b class="mr-2">Scurry</b><i>Minor</i> As a move can hide in cover or broken ground. Avoids all attacks, but may not attck to remain hidden.</li>
         <li><b class="mr-2">A Little Luck</b><i>Major</i> Start with 3 extra karma</li>
         <li><b class="mr-2">Beneath Notice</b><i>Minor</i> Boon on checks to hide and sneak</li>
         <li><b class="mr-2">Duck</b><i>Minor</i> Automatically succed on an armor save, once per session</li>
      </ul>

      <h4>Arcane Bloodline</h4>
      <ul>
         <li><b class="mr-2">Stalwart Will</b><i>Minor</i> Boon to resist mind altering magic</li>
         <li><b class="mr-2">Shadow Sight</b><i>Minor</i> Double vision range in dim light</li>
         <li><b class="mr-2">Arcane Link</b><i>Minor</i> Can summon a small ball of light in your hand at will</li>
         <li><b class="mr-2">Fireblooded</b><i>Minor</i> Boon to resist fire. (may only select a single Elemental resistance)</li>
         <li><b class="mr-2">Iceblooded</b><i>Minor</i> Boon to resist cold.  (may only select a single Elemental resistance)</li>
         <li><b class="mr-2">Shockblooded</b><i>Minor</i> Boon to resist lighting.  (may only select a single Elemental resistance)</li>
         <li><b class="mr-2">Acidblooded</b><i>Minor</i> Boon to resist acid.  (may only select a single Elemental resistance)</li>
         <li><b class="mr-2">Wareblooded</b><i>Minor</i> Can grow teeth and claws at will, Boon to climb, can use as Melee Weapons</li>
         <li><b class="mr-2">Blindsight</b><i>Major</i> Able to ecolocate and see in full darkness</li>
      </ul>

      <h4>Mixed Bloodline</h4>
      <ul>
         <li><b class="mr-2">Erudite</b> <i>Major</i> Pick an additional inclination</li>
         <li><b class="mr-2">Affluent</b><i>Minor</i> Start with 2 healing potions or an extra random scroll</li>
         <li><b class="mr-2">Aquatic Bloodline</b><i>Minor</i> Boon to swimming and similar checks in water</li>
         <li><b class="mr-2">Martial Training</b><i>Minor</i> Take a bonus action on your turn once per session</li>
         <li><b class="mr-2">Family Connections</b><i>Minor</i> Once per session can arrange an introduction or assistance from family connections while in town.</li>
         <li><b class="mr-2">Decendant of the Fittest</b><i>Minor</i> Boon on checks against survival in outdoor conditions.</li>
         
      </ul>
      
   </section>

   <section id="inclinations" class="flex gap-2 flex-col">
      <h2>Inclinations</h2>
      These are the specific training and talents that differentiate characters from on another. 

      <div>
         <b>Alchemist</b> - You have trained under a master, or in the Guild of Alchemists and learned the art fo making potions. You have a boon to identifing substances. Start with two free healing potions or one random potion. 
      </div>

      <div>
         <b>Arcane Scholar</b> - You have no sorcery yourself, but have been trained in or otherwise learned to cast spells from scrolls. Start with 2 random scrolls.
      </div>

      <div>
         <b>Attuned</b> - You can blind fight and escape areas of obscured vision that can befuddle the direction of others.
      </div>

      <div>
         <b>Born Blessed</b> - You start each session with 6 karma instead of the usual 3.
      </div>

      <div>
         <b>Cantrips</b> - Not fully trained in Sorcery, but either from natural talent, or an abbriviated education, you are able to manifest basic spell effects. This is usually things like moving small near objects slowly, creating light in your hand, or producing minor illusions. These must be anchored to continue.
      </div>

      <div>
         <b>Catlike</b> - Can only ever be knoocked prone if hit by a critical and have a 4+ miraculous save against falls.
      </div>

      <div>
         <b>Checkmate</b> - You can intercept foes bore they reach targets near you. If an enemy attempts to retreat or move away from you, you can take a free attack (free action). A successful attack prevents the move. 
      </div>

      <div>
         <b>Crafter</b> - Choose a craft. Given sufficient time, you may create products of this craft. Identifing, and evaluating examples of this craft, as well as the ingredients and imputs to this craft have a boon. You will also be able to make contacts and negotiate with craftspeople of this craft with a boon. 
      </div>

      <div>
         <b>Danger Sense</b> - You cannot be surprised and have a boon to avoid traps.
      </div>
      
      <div>
         <b>Diplomat</b> - You are a master of the negotiated solution, and brimming with raw charisma. Boon to all social checks. In addition, choose 2 extra languages. 
      </div>

      <div>
         <b>Divine Spark</b> - You are touched by the divine, and are able to inflict greater damage on both Demons and the Undead when making melee attacks. Rolling a 6 on attacks against these creatures, you automatically inflict a second strike and continue to roll the critical.
      </div>

      <div>
         <b>Devout</b> - You are a pious follower of a <a href="/world#dieties">diety</a>. As one of True Faith, you may call on your dietiy for <a href="/system#spells">Miracles</a>. While you may call for miracles, the gods are fickle.
      </div>

      <div>
         <b>Doctor</b> - You can heal allies 1 Strike between scenes in narative time. Start with a healing kit with 6 uses. 
      </div>
 
     <div>
         <b>Faithful</b> - Deamons and Undead can only hit you on a 5+
     </div>

     <div>
         <b>Familiar</b> - You have a small flying demonic servant that will obey simple commands. You grow a teat somewhere on your body
         that the creature suckles a small quantity of blood every night.
         Those of holy disposition will never bond one of these creatures, and there will be social consequences to being known to have a Familar. That being said, they are very useful, and fairly common.
     </div>

     <div>
         <b>Fate Touched</b> - You start with 2 hero dice. 
     </div>

      <div>
         <b>Fighter</b> - You have a boon in Melee weapons. You cannot "double" train, so characters already having a boon in Melee cannot benefit from this inclination.
      </div>

      <div>
         <b>Insipiring</b> - You can share your karma points with anyone you can see. 
      </div>

      <div>
         <b>Iron Will</b> - You have a boon under mental attack or aginst fear. 
      </div>

      <div>
         <b>Linguist</b> - You have a natural capacity for language or have by experience or study learned a great number of them. Pick five extra languages. 
      </div>

      <div>
         <b>Lockpicking</b> -  
      </div>

      <div>
         <b>Marksman</b> - You have a boon in ranged weapons. You cannot be double trained, so characters already having a boon in Ranged cannot benefit from this boon. 
      </div>

      <div>
         <b>Slippery</b> - You can roll to escape any "bad situation" on a 4+ (grabbed, falls etc.) Although you cannot escape a combat hit, you can roll to escape a grapple. This roll takes no actions, it just happens. 
      </div>


      <div>
         <b>Sneaky</b> - You have a boon to hiding and moving around unseen.
      </div>

      <div>
         <b>Sticky Fingers</b> - You can steal small objects with a boon from targets and remain unnoticed givent the opportunity, unless you roll a 1 (double ones with the boon). A challenging environment or target might inflict a bane on the attempt putting the filcher back to rolling a flat one die. 
      </div>

      <div>
         <b>Sweek or Swift Attack</b> - You can melee attack all enemies next to you as your action. (roll for each target)
      </div>

      <div>
         <b>Tough Bastard</b> 0- When you would take you lst strike, roll a check on a single die. On a 4+ you do not take that strike. This does not stack with any other similar inclination.
      </div>

      <div>
         <b>Thief</b> - You have a boon to both find, and disable traps, and will always be able to pick a locks given time and tools. For locks, roll 1d6 to see how long it takes (lower takes longer, 1 breaks your tools). Start with a set of 3 lockpicks.
      </div>

      <div>
         <b>Treasure Sense</b> - You have a nose for finding hidden treasure and will always sense if it is nearby.
      </div>

      <div>
         <b>Victory in Failure</b> - Once per scene, when rolling a failure, you earn 2 karma rather than the normal one. 
      </div>

   </section>

   <section>
      <h2>Aspects</h2>

      Choose one to three Aspects. Aspects are minor details about a characters personality or past. An Aspect should not repeat anything about your Path or Inclination, but should be characterizations to contrast with those. These build characterization, and both allow a player to roleplay into their aspects, earning them karma. The other reason for Aspects, if a situation that allows a player to play into a character's Aspects, they can earn a boon on those checks.
      Aspects can be things like: 
      <h4>Where You are From?</h4>
      <ul>
         <li>Grew up in a region, or environment.</li>
         <li>Educated at or in an organization.</li>
         <li>Had a formative experience.</li>
      </ul>

      <h4>What Are You Like?</h4>
      <ul>
         <li>What are you known/infamous for?</li>
         <li>Do you have a particular fear?</li>
         <li>Do you have a certain belief</li>
         <li>Any unusual habits?</li>
         <li>Any unusual traits?</li>
      </ul>

      <h4>What do you want?</h4>
      <ul>
         <li>Do you have a partiular goal?</li>
         <li>Do you have a specific weakness or vice?</li>
         <li>Do you have an enemy or a hated ideal?</li>
      </ul>
   </section>

   <section>
      <h2>Circles of Sorcery</h2>


      <h3>Binding</h3>
      Binding is the Circle of capture and linking. They are not a large or rich school. They are very useful when dealing with Demons, or very large monsters. 
      As such, they are one of the most marial of all the circles of magic, comprising what amounts to a guild of monster hunters. This is usually in the form of an independent arcane martial order. 
      All members of the Circle of Binding have the power to use arcane bands, usually in the form of chains, but tenticles and other forms are known. These bands can move objects and grapple opponents. 
      Anything in near range is reachable. The bands must be maintained with an anchor. Breaking free requires an action and a roll of 6. 
   
      <h3>Warmages</h3>
      The order of warmages is a popular and powerful circle of magic, which focuses on pure damage dealing. The social integration of this group is usually some kind of well compensated service to the dominant local power. Losing support of the warmages is a good way to lose controls of power, and this has happened more than a few times in known history.  
      These mages are not subtle. Unlike other Sorcerers, they are able to do so much damage in a single attack so as to do 2 strikes of damage per attack if desired. Striking a warmage with a melee weapon will sometimes cause the attacker to suffer burns of raw chaos themselves. Any attacker rolling 1 on a melee attack against a war mage takes a strike of damage from these burns. 
      These mages are more attuned to magic than others and can feel magic in the environment around them. Being a warmage has a significant downside, in that the risk and consequenses of spellburn is greatly increased. Most older war mages sport great scars of this. Mechanically, when taking spellburn, the GM will roll random effects that will strike yourself and those around you. 
   
      <h3>Druids</h3>
      A popular, and socially very well supported circle of magic. Druids are central and crucial for securing food supplies in most communities. In many smaller communities and tribes they are actively in charge. Druids control the power of plants, modifying existing plants or bringing forth new plant life from raw magical power. 
      Plant magic requires anchoring to maintain. Losing the anchor cause the plants to rapidly die and wither away, unless the magic is executed in a very slow and deliberate way (narative time). In this way Druids are able to fertilize crops and orchards, and maximize the agricultural output from them. This is the work of days and more often weeks of slow and deliberate magical cultivation.
      Druids can create walls, ropes and snares of plants in seconds, but these last only as long as the druid concentrates on them. Breaking free of Druidic snares requires a roll of 6 and a ful action to make the attempt. 

   </section>

   <section>
      <h2 id="styles">Martial Styles</h2>
      Warriors do not learn to fight at the level that they do simply by making friends. They must be trained by a experienced fighters. This is one of the main seperators between most roles that can use weapons and the specific abilities of a Warrior. For this reason, warriors need to choose a source of this training, and also to choose at least one group they have been fighting to this point. 

      <h4>Martial Organizations</h4>
      These are common groups with enough resources and experience to train full warriors. When, and how your character was recruited, trained and relates to the martial group they learned from should be recorded.
      <ul>
         <li><b>Noble or Wealthy Trade Houses</b> - Any group of sufficient wealth and power will gain sufficient enemies to require that retinues of men at arms must be hired, trained and recruited </li>
         <li><b>Religious Martial Order</b> - Religions, Gods and Temples have goals, agendas and enemies, and so also have martial organizations. The most common are the Templars that are literally the devout guards of the physical temples.</li>
         <li><b>Tribes</b> - The world is a dangrous place. Any group of any size will have a small, dedicated cadre of individuals dedicated to protecting and defending the group. Many also take part in the persecution of conflicts against competing groups. The nature of these conflicts will depend on the group.</li>
         <li><b>Magic Circles</b> - The schools of magic are a special type of wealthy/powerful group that is able to use magic to help with its defense. It is often more efficient and desirable to be able to defend, or advance the goals of, the Circle without using magic directly. For this reason, almost all magic circles maintain martial orders of some size.</li>
         <li><b>Great Cities</b> - The few large cities have significant numbers of men at arms that defend them against threats. These are a bit different than serving a House directly in that these are political organizations large enough to allow the idea of serving the City, Kingdom or Society at large as opposed to the House leader directly to be possible.</li>
         <li><b>Raiders</b> - Bandits, criminals, and other criminal elements of all kinds maintain groups of truly skilled fighters to both protect themselves, and opress others.</li>
         <li><b>Mercenaries</b> - Many groups only require defense part time, giving rise to the market for mercenaries. This takes many forms. Some entire tribes take the form of a unitied mercenary company with all tribal members working for what is effectively a company. Others are explicit mercenary companies for hire in wars or even just as simple caravan guards. </li>
      </ul>

   </section>
</article>