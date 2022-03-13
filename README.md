# ViennaMC-Doc
Informations about the changes in ViennaMC

## Get Started
Server is Minecraft Java Edition `1.18.2`.
- Limited support is offered for older and newer minecraft clients (if you are on a different update, server will try to accomodate you but there might be glitches.
- Very limited support is given for Bedrock edition. Bugs WILL be present if you use bedrock.

## Lands / claims
On the server, you can claim chunks to protect your belongings and builds. Your chunk limit will grow with playtime and when you invite players into your claim.

### Commands
To create a new land: `/lands create <LandName>`
To claim a new chunk (or your currently selected area, see below): `/lands claim`
To claim multiple chunks at once: `/lands selection`
To change land settings, trust people etc.: `/lands menu`
If you have more than one land, you can choose which you are editing: `/lands edit`
  - This will change which land is affected by other lands commands.
<More commands to document>
  
## Gameplay changes
### Homes
Create a home with `/sethome <homeName>`
 - You can increase the amount of Homes you can create/own through playtime.
Teleport to your home with `/home <homeName>`
 - Teleporting to a home requires you to wait 3 seconds and to be standing still.
Manage multiple homes by using `/homes`
Delete a home with `/removehome <homeName>` or `/delhome <homeName>`

### Teleportation
Send a request to teleport to another player using `/tpa <playerName>`
 - You can accept/deny a teleport request by using `/tpaccept` or `/tpdeny`
Send a request to teleport another player to you using `/tpahere <playerName>`

Teleport to a random location by using `/rtp`
 - Cannot be used in The End or The Nether
Teleport to your previous location before your most recent teleport by using `/back`

Check and use player-made warps by using `/warps`
 - Manually warp to player-made warps by using `/warp <warpName>`

### Composters
 - [todo]
  
### AutoShulkers
 - [todo]
  
### Bigger chests
 - [todo]
  
### Marriage
Marry another player by using `/marry <playerName>`
 - Divorce your partner by using `/marry divorce <playerName>`
 - Show all married players by using `/marry list <page>`
 - Specify your gender in your marriage by using `/marry gender <female/male>`
Toggle a partner only chat mode by using `/marry chat`
Instantly teleport to your partner by using `/marry tp`
Enable/disable PVP between your partner with `/marry pvp`
Set a shared marriage home by using `/marry sethome`
 - Teleport to your marriage home by using `/marry home`
Find out how long your partner last logged in by using `/marry seen`
Give health to your partner by doing `/marry heal`
 - Trade your health to your partner until they either are on max health or you are on half a heart.
Gift your partner the current item(s) you hold by using `/marry gift`

### Elevators
 - [todo]

### Dynmap
 - [todo]
  
### Jobs - XP through gameplay
 - [todo]

### Emotes (Hugs, pats and bonks)
 - [todo]
  
### Graves
On death, place a player head of the slain player that stores their items.
 - Graves last for 20 minutes and cannot be interacted with by other players
 - Once you respawn, you are given a Compass that points to your grave, right clicking this compass shows you how far you are from your grave.
 - Right click the player head to interact with your grave and retrieve your items.
 - Shift+Right Click to instantly put your items back into your inventory.
 - After taking all of the items from your grave, a zombie with your player head is spawned.

### Hardmode and Easymode
Able to toggle between challenging, levelled mobs `/hardmode`, or fully vanilla mobs `/easymode`.
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
