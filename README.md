# Tautininks_unciv
Best party in Europe. Making an unciv mod

-------------------------------------------

Links for useful information:
Unciv mod wiki - https://yairm210.github.io/Unciv/Modders/Mods/

Unciv github - https://github.com/yairm210/Unciv

-------------------------------------------

Templates:

UNITS
"name": "name",
"unitType": "type",
"uniqueTo": "civ",
"replaces": "unit"
"movement": number,
"strength": number,
"rangedStrength": number,
"range": number,
"cost": number,
"requiredTech": "Tech",
"requieredResourse": "Resource",
"obsoleteTech": "Tech",
"upgradesTo": "unit",
"promotions": ["promotion"],
"hurryCostModifier": number,
"uniques": ["uniques"],


NATIONS

"name": "Civ",
"leaderName": "Leader Name",
 "adjective": ["Civilian"],	"cityStateType": "Type",
"startBias": ["terrains"],
"preferredVictoryType": "Victory type",
	 
"declaringWar": "Frase",
"attacked": "Frase",
"defeated": "Speech",
"introduction": "Speech?",
"neutralHello": "Greetings",
"hateHello": "frase",
 "tradeRequest": "Asking for trade",
   			 
"outerColor": [3,2,1],
"innerColor": [1,2,3],
"uniqueName": "Unique Name",
"uniques": ["Nation Unique"],
"cities": ["Capital","city","cities"]



BUILDINGS


"name": "Name",
"replaces": "Building",
"uniqueTo": "civ",
"isNationalWonder": true,
"isWonder": if false, do not place,
"greatPersonPoints": {"production": 1},
"providesFreeBuilding":  "building",
"xpForNewUnits": 15,
"happiness": 1, "food": 2,      "production": 3, 
"science": 3,     "gold": 3,   "culture": 1,
"cost": 1,
"specialistSlots": {"Artist": 1},
"cityStrength": 5,
"cityHealth": 50,
"requiredNearbyImprovedResources": ["Resource"],
"requiredBuilding": "Building",
"resourceBonusStats": {"food": 1},
"hurryCostModifier": 40,
"maintenance": 1
"percentStatBonus": {"food": 15},
"requiredTech": "Tech"
"quote”: “A quote that will be displayed when built”,





