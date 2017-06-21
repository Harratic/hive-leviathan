# hive-leviathan
github directory ^^^

project idea

To create an app that rolls dice and calculates the results for the game
Warhammer 40k 8th Edition.  This app will take inputs of:

        Who is attacking? and how many?
        What weapon is being used?
        Who is being attacked?
        Are there any special rules or re-rolls in effect?

The app will then return the amount of damage the defending unit receives.

The app will contain stats of units and weapons and will compare those, along
with dice rolls produced by the app to determine the outcome.


Things needed to program:

    A dice roller,
    Stats of units in an object or directory,
    a dynamic interface of pull down menus in the app that change based on the
    chosen result of the previous menu.

  App Structure:    

        4 pull down menus

            Menu 1: a list of different armies
            Menu 2: a list of unit in the chosen army
            Menu 3: a list of weapons available to that unit
            Menu 4: a list of possible special rules or re-rolls

        1 input boxes for number of attacks

        1 button to start the "battle simulation"


Foreseen complications:

    weapons that auto-hit (such as flamers)
    weapons that do multiple points of damage to a single model, but not the unit as a whole
    weapons that do variable amounts of damage (1d6 or 1d3)
    melta weapons roll 2d6 and choose the higher one, discard the lower for damage.
    invulnerable saves instead of armor saves and which to choose if both available.
    terrain bonus to armor save if applicable
