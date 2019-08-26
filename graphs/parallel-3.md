	```mermaid
	graph TD
	   Attacker[Attacker<br/>type: parallel<br/>policy: sequence]-->IndividualActions[Individual Actions<br/>type: selector]
	   Attacker-->TeamActions[Team Actions<br/>type: selector]
	   IndividualActions-->Walk
	   IndividualActions-->Run
	   IndividualActions-->Kick
	   IndividualActions-->Tackle
	   TeamActions-->MoveForwardWithBallCarrier[Move Forward<br/>With Ball Carrier]
	   TeamActions-->InterposeBetweenDefenderAndBallCarrier[Interpose Between<br/>Defender and<br/>Ball Carrier]
	   TeamActions-->OccupyFreeZoneInPenaltyArea[Occupy Free<br/>Zone In<br/>Penalty Area]
	   TeamActions-->AimAtAPlaymate[Aim At A<br/>Playmate]
	   TeamActions-->AimAtTheGoal[Aim At<br/>The Goal]
	```
