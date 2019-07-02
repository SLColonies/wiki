---
title: Version 0.2.0.0 Alpha
date: 2019-07-01
---
{% include tag.html tag="added" %}

**HUD Market/Inventory Symbol:**<br>
The HUD market symbol on the HUD has been added. When clicked, players will get the following options:
- View:
	- When clicked, players will be able to open a web browser page which will list their current inventory. From within the web based inventory, they are able to use an item which effects players stats, or drop items they no longer need.
- Give:
	- System will scan for nearby players. When a player is selected, you are given the option to simply give them items.
- Trade:
	- System will scan for nearby players. When a player is selected, you are able to select which item you would like to trade with that other player, and how many. You will be asked to confirm, then the other player will receive notification to accept or deny the trade request. The other player then see's the offer and makes a trade counter-offer. When both parties agree, trade is completed and items transfered to each players inventory.
- Use:
	- Use an item, such as food, drink, potions. 
- Rez:
	- A number of items in the game are made to be rezzable. Such as certain foods, drinks, potions, weapons, tools, furniture and more. When you select an item to rez, the server will send you the physical version and remove the database version from your inventory. **NOTE:** Once rezzed, items cannot be returned to virtual inventory and are also sent to you as no-copy & no-transfer versions. The latter feature is in place to prevent the selling of items on the SL Marketplace for L$.

Market symbol. When clicked, gives you options:
		-	List Inventory
			This will open the users webpage which will list all inventory currently held by player.
			
		-	Trade Item
			On click, scans players in range. On selection of player, type in item that is to be traded, followed by quantity. 
			Perhaps there is a way to expand on this to allow both players to make a trade request before accepting from both sides, to help stop scamming etc? Might not be worth the time $$$ investment though?
			
		-	Use Item
			Allows the use of an item directly from the database? Such as food, healing potions etc? This will enable us to develop a HUD with quickbar for a player to use potions and food from a hud on the fly straight from database. Not sure on this one yet, will decide/delay when we get to this step.
			
		-	Rez Item
			I plan on changing crafting stations so that they do not create 'phyical' objects. Instead, they only create database objects. This will prevent people from using the 'SL Marketplace' to sell goods like what has happened with DFS and G&S, greatly reducing the economy and value of goods.
			
			It will also allow greater control of trading, supply and demand in the RPG marketplaces by allowing the sale of crafted items and weapons in database form.
			
			When an item is one which can be physical, like food, tools, weapons, their name in the datase would be something ending with (*) so for example: Basic Sword (*). 
			When they click rez and type in the item they wish to rez, that is when the server will check their inventory and send them a copy of the physical object, and delete their database item. This object will be No Mod, No Copy, No Transfer.	