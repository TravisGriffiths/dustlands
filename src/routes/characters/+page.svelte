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
      <h4>Path Inclinations</h4>
      These are the "powers" or abilities of the path. This is usually a list, but sometimes is a choice in a list. 

      <h3>Warrior</h3>
      A professional fighter, soldier or man-at-arms 
      <Stat label="Health" value="3 strikes" />
      <Stat label="Armor" value="Heavy 3+ w/shield otherwise 4+" />
      <Stat label="Boon" value="Strength and Melee" />

      <div>
         <h4>Inclinations</h4>

         <div class="my-2">
            <i>Shield Sacrifice</i> - Once per scene as a free action, you may choose to deflect all attack damage from yourself or a close ally 
            for the entire round, but your shield is destroyed by this maneuver. You can activate this even after damage has been inflicted.
            You may spend 5 karma to avoid destroying your shield. If your shield is destroyed, your Armor save becomes the normal shieldless 4+. 
            A warrior must be using a shield to use this maneuver (naturally). 
         </div>

         <div class="my-2">
            <i>Brutal Strikes</i> - As a master of two handed weapons, your strikes score critical hits on a 5 or 6. You cannot use a shield to use this, and must have a two handed weapon equiped.
         </div>
      </div>
      


   </section>

   <section id="bloodlines">


   </section>
</article>