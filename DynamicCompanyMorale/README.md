# DynamicCompanyMorale

[Battletech Mod][ModTek] Company morale system is made more interesting by introducing temporary morale events and meaningful financial decisions at the start of each quarter.

## Gameplay changes
* Introduce a morale reset at the end of each in game month
  * Morale resets to base value + morale bonus of the argo upgrades
* The expenditure level selection has a greater impact now
  * The morale impacts are -16, -8, +4 and +8 depending on chosen expenditures
* All morale impacts of events are made temporary (programmatically) and much more relevant
  * Morale boosts/penalties are multiplied by 4
  * The effects are temporary and expire after a while just like the MedTech/MechTech events do
  * This is reflected in the UI

## Additional notes
* A workaround for vanilla bug of randomly setting ExpenseLevel at GameLoad is included
  * Please note that this workaround needs a custom SaveState found in ModDirectory
  * Fix is applied AFTER the first NewQuarterBegin, existing saves cannot be fixed

## Thanks
* Zathoth
* donZappo
* Morphyum
* Mpstark
* janxious
* pardeike
* HBS