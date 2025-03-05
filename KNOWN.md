This is a list of known strings in the savegame file.

# Funds

Look for the line containing `"name": "m_iCash", "kind": "IntProperty",` and change the number after `"value":` to the desired amount of money.

# Scientists

Look for the line containing `"name": "m_iNumScientists", "kind": "IntProperty",` and change the number after `"value":` to the desired number of scientists.

# Engineers

Look for the line containing `"name": "m_iNumEngineers", "kind": "IntProperty",` and change the number after `"value":` to the desired number of engineers.

# Research

The research unlocks are found in the m_arrResearched array. They are represented by a binary switch (0 = not researched | 1 = researched). The following array elements have been identified within Enemy Within:

|Element Number|Description|
|----|----|
|1|Unknown|
|2|Xeno-Biology|
|3|Arc Thrower|
|4|Outsider Shard|
|5|Unknown|
|6|New Fighter Craft|
|7|Sectoid Commander Autopsy|
|8|Hyperwave Communication|
|9|Ethereal Device|
|10|Weapon Fragments|
|11|Alien Materials|
|12|Experimental Warfare|
|13|Elerium|
|14|Meld Recombination|
|15|Psi Armor|
|16|Carapace Armor|
|17|Skeleton Suit|
|18|Titan Armor|
|19|Ghost Armor|
|20|Archangel Armor|
|21|Beam Weapons|
|22|Precision Lasers|
|23|Heavy Lasers|
|24|Plasma Pistol|
|25|Light Plasma Rifle|
|26|Plasma Rifle|
|27|Heavy Plasma|
|28|Plasma Sniper|
|29|Alloy Cannon|
|30|Plasma Cannon|
|31|Fusion Lance|
|32|Guided Fusion Launcher|
|33|Alien Nav Computer|
|34|UFO Power Source|
|35|EMP Cannon|
|36|Interrogate Sectoid|
|37|Interrogate Floater|
|38|Interrogate Muton|
|39|Interrogate Sectoid Commander|
|40|Interrogate Berserker|
|41|Interrogate Thin Man|
|42|Interrogate Heavy Floater|
|43|Interrogate Muton Elite|
|44|Interrogate Ethereal|
|45|Sectoid Autopsy|
|46|Floater Autopsy|
|47|Thin Man Autopsy|
|48|Muton Autopsy|
|49|Chryssalid Autopsy|
|50|Unknown|
|51|Cyberdisk Autopsy|
|52|Berserker Autopsy|
|53|Heavy Floater Autopsy|
|54|Muton Elite Autopsy|
|55|Drone Autopsy|
|56|Sectopod Autopsy|
|57|Ethereal Autopsy|
|58|Mechtoid Autopsy|
|59|Seeker Autopsy|
|60|Unknown|
|61|Unknown|



# Items

Most of the items (Weapons, Alloys etc.) are located in an array called **m_arrItems**. To modify the quantity of a given item, change the associated array element number to the desired quantity. The following array elements have been identified within Enemy Unknown:

|Element Number|Description|
|----|----|
|1-8|UNDEFINED|
|9|Laser Pistol|
|10|Laser Rifle|
|11|Scatter Laser|
|12|Heavy Laser|
|13|Laser Sniper Rifle|
|14|Plasma Pistol|
|15|Light Plasma Rifle|
|16|Plasma Rifle|
|17|Alloy Cannon|
|19|Plasma Sniper Rifle|
|18|Heavy Plasma|
|20|Blaster Launcher|
|21-58|UNDEFINED|
|59|Carapace Armor|
|60|Skeleton Suit|
|61|Titan Armor|
|62|Archangel Armor|
|63|Ghost Armor|
|64|Psi Armor|
|65-76|UNDEFINED|
|77|Medikit|
|78|Combat Stims|
|79|Mind Shield|
|80|Chitin Plating|
|81|Arc Thrower|
|82|S.C.O.P.E.|
|83|Nano-Fiber Vest|
|84-88|UNDEFINED|
|89|Alien Grenade|
|90-99|UNDEFINED|
|100|Battle Scanner|
|101|?|
|102|?|
|103|S.H.I.V.|
|104|Alloy S.H.I.V.|
|105|Hover S.H.I.V.|
|106|UNDEFINED|
|107|Firestorm|
|108|UNDEFINED|
|109|Satellite|
|110-123|UNDEFINED|
|124|Phoenix Cannon|
|125|UNDEFINED|
|126|Laser Cannon|
|127|Plasma Cannon|
|128|EMP Cannon|
|129|Fusion Lance|
|130-133|UNDEFINED|
|134|Defense Matrix (Dodge)|
|135|UFO Tracking (Boost)|
|136|Uplink Targeting (Aim)|
|137-144|UNDEFINED|
|145|Sectoid Corpse|
|146|Sectoid Commander Corpse|
|147|Floater Corpse|
|148|Heavy Floater Corpse|
|149|Thin Man Corpse|
|150|Muton Corpse|
|151|Muton Elite Corpse|
|152|Berserker Corpse|
|153|Cyberdisc Wreck|
|154|Ethereal Corpse|
|155|Chryssalid Corpse|
|156|UNDEFINED|
|157|Sectopod Wreck|
|158|Drone Wreck|
|159-171|UNDEFINED|
|172|Elerium|
|173|Alien Alloys|
|174|Weapon Fragments|
|175|Alien Entertainment|
|176|Alien Food|
|177|Alien Stasis Tank|
|178|UFO Flight Computer|
|179|Alien Surgery|
|180|UFO Power Source|
|181|Hyperwave Beacon|
|182|Alien Entertainment (Damaged)|
|183|Alien Food (Damaged)|
|184|Alien Stasis Tank (Damaged)|
|185|UFO Flight Computer (Damaged)|
|186|Alien Surgery (Damaged)|
|187|UFO Power Source (Damaged)|
|188|Hyperwave Beacon (Damaged)|
|189|Fusion Core|
|190|Ethereal Device|
|191|UNDEFINED|
|192|Outsider Shard|
|193|Skeleton Key|
|194|UNDEFINED|

# Meld 

Meld is located in an array after `Meld "Command1.TheWorld:PersistentLevel.XGBattleDesc_0"`. 
Please note that this array stores the amount you found since the beginning of the game and not your current amount. 

# Team Members

TODO
