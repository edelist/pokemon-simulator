To run the game, execute the makefile in terminal.

Game Commands:

m ID x y
  "move": command Trainer ID to move to location (x, y).
  
c ID1 ID2
  "move towards a PokemonCenter”: command Trainer ID1 to start heading to PokemonCenter ID2.
  
g ID1 ID2
  “move towards a PokemonGym”: command Trainer ID1 to start heading towards PokemonGym ID2.
  
s ID
  "stop": command Trainer ID to stop doing whatever it is doing.
  
p ID potion_amount
  “buy potions”: command Trainer ID to buy potion_amount of potion at a PokemonCenter.
  
b ID battle_amount
  “complete battle_amount battles at a PokemonGym”: command Trainer ID to complete battle_amount of battles at a PokemonGym.
  
a
  "advance": advance one-time step by updating each object once.
  
r
  "run": advance one-time step and update each object, and repeat until either the update function returns true for at least one of the objects, or 5 time steps have been done.
  
q
  "quit": terminate the program
  
n TYPE ID X Y
  create a new object with the specified TYPE, ID number, (X, Y) location.
  TYPE is a one letter abbreviation for the type of object:
    ● c – PokemonCenter
    ● g – PokemonGYM
    ● t – Trainer
    ● w – WildPokemon
    

Enjoy the game!!

...if there are any bugs, feel free to let me know!
