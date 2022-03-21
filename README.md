# ViennaMC-Doc
Informations about the changes and features in ViennaMC

## Get Started
Server is Minecraft Java Edition `1.18.2`.
 - Limited support is offered for older and newer minecraft clients (if you are on a different update, server will try to accomodate you but there might be glitches.
 - Very limited support is given for Bedrock edition. Bugs WILL be present if you use bedrock.
 - We have an official Dynmap webmap at https://viennac9.apexmc.co:8234/
   - You can use `/dynmap register` in game to link your browser with your Minecraft account, this allows you to talk in chat while using your browser.
 - We have an official server resource pack that allows you to post and see emojis in the chat. By default, the server will prompt you to load the resource pack to be able to see them. Without the resource packs, they will be random chinese characters.
<details><summary>Option 1</summary>
<p>
Using the default resource pack loading option, you will see a resourcepack loading everytime you leave/join. The upside is that the resourcepack will always be kept up to date automatically.
</p>
</details>

<details><summary>Option 2</summary>
<p>
If you prefer, you can disable the server resource pack loading (click on the server, in the server list, click edit and then resource packs: Disable) and instead download the resource pack zip i will keep available in this channel (pins) and add it to your minecraft. the resource pack will not cause any issue in other minecraft servers or single player worlds.
</p>
</details>

<details><summary>Option 3</summary>
<p>
Do as in option 2, disabling the resource pack option but do not install the resource pack. You will see this kind of stuff instead of emojis: 漢
</p>
</details>
Resource pack: http://viennac9.apexmc.co:8234/resource_pack_emojis.zip 
  
## Gameplay changes
These are changes to the server through plugins or other methods that make the gameplay on ViennaMC different from others.

### Lands / Claims
Create a new land with `/lands create <LandName>`

Claim a new chunk or claim a selected area with `/lands claim` or `/claim`
 - If you have more than one land, you can choose which one you are editing with `/lands edit`
   - This will change which land is affected by other lands' commands.

To select and claim multiple chunks at once, use `/lands selection`

To change lands settings, trust people, and more, use `/lands menu`

[More to document, add images as well]

**Land permissions and settings:** You have a large amount of control over the permissions of other players inside your claims. Those can be accessed using the following steps.
 
1. Run the command [/lands menu] and then select the desired land to alter (if you have multiple lands)

2. Click "Natural flags" to change game mechanics inside your land. Includes TNT and creeper breaking blocks or not and other things.

3. Click "Roles" to change what trusted people can do inside your land (members) and what untrusted people can do inside your land. (Visitors).

4. You will find here 2 important sections. "Action flags" and "Management flags", which contain detailed instructions for you to read and chose.

[More to document]

### Homes
Create a home with `/sethome <homeName>`

![SetHome](https://i.imgur.com/bNQkMYB.png)
 - You can increase the amount of Homes you can create/own through playtime.
Teleport to your home with `/home <homeName>`

![HomeTP](https://i.imgur.com/peTX16Y.png)

 - Teleporting to a home requires you to wait 3 seconds and to be standing still.
 - Manage multiple homes by using `/homes`

  ![Homes](https://i.imgur.com/nLes7i2.png)

 - Delete a home with `/removehome <homeName>` or `/delhome <homeName>`
 ![DelHome](https://i.imgur.com/LONwDPC.png)

### Teleportation
Send a request to teleport to another player using `/tpa <playerName>`
(add image later)
 - You can accept/deny a teleport request by using `/tpaccept` or `/tpdeny`
 (add image later)

Send a request to teleport another player to you using `/tpahere <playerName>`
(add image later)

Teleport to a random location by using `/rtp`
(add image later)
 - Cannot be used in The End or The Nether

Teleport to your previous location before your most recent teleport by using `/back`
(add image later)

Check and use player-made warps by using `/warps`
(add menu image later)
 - Manually warp to player-made warps by using `/warp <warpName>`
 (add image later)

### Ranks
 - [todo]

### Composters
You can craft auto-composters. Those will boost the growth speed of crops nearby. The auto-composters have a horizontal radius of 6 and a vertical radius of 3. They can also automatically plant crops by crouch + rightclicking while holding seeds.

**AutoComposters:**

![AutoComposters](https://cdn.discordapp.com/attachments/846654800224845855/930644474483318804/unknown.png)
  
### SuperShulkers
You can craft special shulker boxes. One version will automatically destroy items of your choice when picked up and another will automatically store items store them inside the shulker box when you pick them up. Think of it this way: You're on a trip to the nether mining for ancient debris, gold and nether quartz. You have a Shulker Trashcan that destroys all the netherrack you pick up, an Auto Shulker that stores all the gold, an Auto Shulker that stores all the nether quartz and an Auto Shulker that stores all the debris.

**GarbageBox Shulkers:**

![GarbageBox Shulkers](https://cdn.discordapp.com/attachments/846654800224845855/930644474818887770/unknown.png)

**AutoShulkers:**

![AutoShulkers](https://cdn.discordapp.com/attachments/846654800224845855/930644475120848976/unknown.png)

### Bigger chests
Larger chests available to craft:
 - Cannot be made into double chests, even though i would like to
 - They provide the same space a normal doublechest would, but they have 3 pages!
 - You can change pages using left/rightclick in the empty portion outside the chests
 (maybe add gif?)
 - Cost is 1 diamond + 1 chest in a furnace. Use a normal chest as fuel and a diamond as the ingredient
 (add image)

### Better Tridents:
 - Tridents have Bedrock droprates (which are significantly higher)
 - Tridents with the Impaling enchant will also do more damage to mobs touching water, like in bedrock.
 - Tridents should more reliably come back when enchanted with Loyalty

### Enchantment Cap
 - Enchants now wont say "too expansive" anymore!
 - They also wont increase in price forever and will cap at some point if you keep repairing them.

### Proximity Chat (Optional)
 - [todo]
  
### Marriage
Marry another player by using `/marry <playerName>`
 - Divorce your partner by using `/marry divorce`
 - Show all married players by using `/marry list <page>`
 - Specify your gender in your marriage by using `/marry gender <female/male>`

Toggle a partner only chat mode by using `/marry chat`

Instantly teleport to your partner by using `/marry tp`

Enable/disable PVP between your partner with `/marry pvp`

Set a shared marriage home by using `/marry sethome`
 - Teleport to your marriage home by using `/marry home`

Find out last time your partner logged in by using `/marry seen`

Give health to your partner by doing `/marry heal`
 - Trade your health to your partner until they either are on max health or you are on half a heart.

Gift your partner the current item(s) you hold by using `/marry gift`

(add images to all of these)

### Elevators
Elevators are a system that allows you to move up and down floors simply with the crafting recipe seen below. By placing an elevator down and placing another one above or below it, you can jump to go up and shift to go down. Keep in mind that the elevators HAVE to be on the same coordinates, except for the Y level.

![Elevators](https://cdn.discordapp.com/attachments/846654800224845855/930644473849991178/unknown.png)
  
### Jobs - XP through gameplay
You can join Jobs to gain XP while playing instead of using farms. Command is `/jobs browse` and everything will be shown in a nice GUI. You can get XP by mining blocks (miner and digger), breeding animals, farming crops and more! More jobs might come when i'm happy with the current lineup. Jobs are still in the process of being tweaked/balanced and might be buffed/nerfed later.


### Emotes (Hugs, pats and bonks)
 - [todo]
  
### Graves
On death, place a player head on the location of the death (if inaccessible, pick the safest location possible) which stores the slain players' items.
 
![graveHead](https://i.imgur.com/M2Kvi5i.png)
 - Graves last for 20 minutes and cannot be interacted with by other players
 - Once you respawn, you are given a Compass that points to your grave, right clicking this compass shows you how far you are from your grave.
 
 ![GraveCompass](https://i.imgur.com/gHkiaoG.png)
 - Right click the player head to interact with your grave and retrieve your items.
 - Shift+Right Click to instantly put your items back into your inventory.
 - After taking all of the items from your grave, a zombie with your player head is spawned.

### Hardmode and Easymode
Able to toggle between challenging, levelled mobs `/hardmode`, or fully vanilla mobs `/easymode`.<br>
![Hardmode](https://i.imgur.com/Nf6RkqW.png)

![Easymode](https://i.imgur.com/tcAhmm7.png)
 - Hardmode mobs give better loot and EXP on the expense of tougher and harder mobs.
 - Completely a per player basis, mobs spawned around a player on Easymode will be vanilla, and vice-versa for Hardmode.
 - When two players on Hardmode and Easymode are next to eachother, mobs spawned around them will be on Easymode.

### Misc
 - Loot regeneration (to do)
 - Leashes are unbreakable
 - You can toggle PVP using `/togglepvp`. Both players need PVP enabled to fight. By default, PVP is disabled.
 - Enchant cap removal
 - Tree Chopping (toggle)
 - Quick inventory dumping (to do)
 - Sit
 - Mail System (to do)
 - Interactive Chat (to do)
 - [more]
