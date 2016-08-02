# Tiny-Adventures
Card Game

Tiny Adventures:

	Board Layout
		3 Home zones on each side, with 3 "advantage" zones in the center
		Start the game by shuffling your deck, then drawing 3 cards
	Deck
		Deck size can be no more or less than 10 cards
		Pick atleast 3 creatures for your deck
		Pick spells to add to deck
	Creatures
		Types:
			aether, plains, graveyard, bakery, hell, jungle, time, ocean, space, business
			When creatures with the same type are stacked add 1 to each creatures power
		Power:
			Each creature has a number in the bottom right called Power
			To move a creature onto an "advantage" zone that is occupied by an enemy creature,
			your creature must have a higher power number than the enemy creature
	Turn
		Start your turn by drawing a card
		Take one of the below actions:
		You can "summon" a creature by placing it in any unoccupied home zone
		You can play a spell from your hand
		You can move any one of your creatures
		Movement:
			A creature can move from a home zone to an "advantage" zone
			A creature can move from a home zone laterally to another home zone
			A creature cannot move laterally between "advantage" zones
			Stacking:
				If a creature moves onto a home zone, or from a home zone to an "advantage" zone, that is already occupied by a friendly creature
				the moving creature stacks on top of the occupying creature
				The creatures' power combines
			If an enemy creature moves into an advantage space that your creature is controlling
			Your creature goes to the "dead zone"
	Spells
		When you play a spell that targets a creature, "attach" the card to that creature by placing it under the creature card.
		Beef: +{1} to target friendly creature's power(Jungle)
		Swing: Play and move a creature from your hand(Jungle)
		Tangle: Creatures cannot move from target zone for {3} turns(Jungle)
		Peace: -{1} to target enemy creature's power(aether)
		Bless: +{1} "point" to target friendly creature in "advantage" zone(aether)
		Cleanse: Remove any spells attached to a zone(aether)
		Drown: Remove {1} spell from an enemy creature(ocean)
		Surface: Remove {1} spell from a friendly creature(ocean)
		Sunk: Enemy discards {1} card at random(ocean)	
		Bully: Push an enemy creature back to their home zone(plains)
		Reserve: Target unoccupied enemy home zone or unoccupied "advantage" zone cannot have creatures moved onto it for the next {3} turns(plains)
		Heatwave: Any creatures on target zone take -{3} penalty to power for {3} turns(plains)
		Anti-grav: Return an enemy creature from a home zone to your opponent's hand(space)
		Abduct: Take {1} creature from enemy home zone and place in one of your home zones(space)
		Suffocate: Enemy cannot place creatures on target home zone for {3} turns(space)
		
		Pride: Return {1} friendly creature from your "dead zone" to your hand(graveyard)
		Wrath : Send {1} enemy creature to it's owner's "dead zone"(graveyard)
		Greed: -{1} "point" to target enemy creature in "advantage" zone, +{1} "point" to an adjacent friendly creature(hell)
		Sloth : Remove {1} from the number of the next spell played(hell)
		Lust: Stack a friendly creature on an enemy creature, the enemy creature subtracts the friendly creatures power from its own(hell)
		Envy: Take random card from enemy's hand(business)
		Gluttony: Put a friendly creature from any zone back in your hand, and replace with a friendly creature with higher power(bakery)
		
		Think: Draw {1} card(business)
		Profit: Add {1} to the number of the next spell you play(business)
		Rewind: Reverse your opponent's last turn(time)
		Bomb: In {3} turns any creatures on target zone are sent to their owner's "dead zone"(time)
		Flashback: Return a spell from your "dead zone" to your hand(time)
		Frosted: Target enemy creature can't move for {1} turn(bakery)
		Burnt: De-evolve, flip over, an enemy creature(bakery)	
		Gravedig: Return {1} enemy creature from enemy "dead zone" to your hand(graveyard)
	Evolving
		Each turn you have a creature on an advantage zone, you gain a "point"
		Evolve the creature, or flip the card over, once it has reached (enough points)
	Winning
		Control all 3 home zones
