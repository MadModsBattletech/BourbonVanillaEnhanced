# Camera Unchained

[Battletech Mod][ModTek] Suppress forced camera movements. Simple focus on relevant events without blocking players ability to control camera.

## Details
Even with all camera settings disabled the game still takes away control of camera on certain events:
- Sensor lock
- Powering up
- Standing up
- Death
- Melee

This mod prevents that and will (by default, configurable) replace these forced camera movements with a simple focus on the relevant position (without disabling control or randomly changing rotation).  
Some less intrusive camera events are whitelisted (by default, configurable), such as the initial objective focus, artillery cams and the mission ending ride.

### Full list of events that are supressed
You can play around with these and add some to the whitelist in settings if you like:
- "BattleTech.ActiveProbeSequence.FireWave"
- "BattleTech.ActorMovementSequence.OnBlipAcquired"
- "BattleTech.ActorMovementSequence.OnPlayerVisChanged"
- "BattleTech.ActorMovementSequence.ShowCamera"
- "BattleTech.ArtilleryObjectiveSequence.SetState"
- "BattleTech.ArtillerySequence.SetState"
- "BattleTech.AttackStackSequence.OnActorDestroyed"
- "BattleTech.AttackStackSequence.OnAttackBegin"
- "BattleTech.AttackStackSequence.OnChildSequenceAdded"
- "BattleTech.MechDFASequence.BuildMeleeDirectorSequence"
- "BattleTech.MechDFASequence.BuildWeaponDirectorSequence"
- "BattleTech.MechDFASequence.OnAdded"
- "BattleTech.MechDisplacementSequence.ShowCamera"
- "BattleTech.MechJumpSequence.ShowCamera"
- "BattleTech.MechMeleeSequence.BuildMeleeDirectorSequence"
- "BattleTech.MechMeleeSequence.BuildWeaponDirectorSequence"
- "BattleTech.MechMeleeSequence.FireWeaponsFinal"
- "BattleTech.MechMeleeSequence.OnAdded"
- "BattleTech.MechMortarSequence.SetState"
- "BattleTech.MechStandSequence.OnAdded"
- "BattleTech.MechStartupSequence.OnAdded"
- "BattleTech.MissionEndSequence.ShowCamera"
- "BattleTech.MultiSequence.FocusCamera"
- "BattleTech.SensorLockSequence.OnAdded"
- "BattleTech.ShowActorInfoSequence.OnChildSequenceAdded"
- "BattleTech.ShowActorInfoSequence.SetState"
- "BattleTech.StrafeSequence.SetState"

## Thanks
* pardeike
* HBS