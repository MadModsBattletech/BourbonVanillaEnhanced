# MightyChargingJuggernaut

[Battletech Mod][ModTek] Coolant Vent is replaced by beloved Juggernaut. Juggernauts can CHARGE into other mechs at sprint range and gain GUARDED state after making regular melee attacks.

## Gameplay changes
- Coolant Vent is replaced by beloved Juggernaut.
	- Why? Because Coolant Vent is Kindergarten
- Juggernauts can CHARGE into other mechs (and ONLY mechs) at sprint range.
	- This will be handled like a sprint regarding instability reduction (none)
	- It will cause additional stability damage to the target
    - It will cause slight stability damage for the attacker on a successful hit
    - Cannot charge prone targets
	- Movement to target will not decelerate at the end
	- It will ALWAYS use the "Charge" melee animation
- Juggernauts gain GUARDED state after making regular melee attacks.
	- Instability reduction from standing/walking is applied
	- Instability reduction from bracing is supressed
- AI Juggernauts will make use of it too...
	- Beware of "Brawler Banshees"!

## Notes
- EffectData in AbilityDefGu8.json is NOT responsible for the -1 Initiative of Juggernaut Melee Attacks, this is rebuild in code.
	- "MeleeHitPushBackPhases" is still checked in AbstractActor::ResolveAttackSequence but does not work anymore
	- EffectData staying in for reference

## Thanks
* Morphyum
* RealityMachina
* donZappo
* Mpstark
* janxious
* pardeike
* HBS