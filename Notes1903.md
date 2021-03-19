* ./UseCases.md  Revisar SergioM + Sergio T. Mover UC a fichero por UC
* Sergio M. Renombrar Mv -> Move
* Plantilla Nombre UC: Move from [Tableau, Foundation, Waste, Stock] to [Tableau, Foundation, Waste, Stock]
* Change terminology allow -> Request
* Simplify actions

# Analysis:
Interfaz unica con el modelo en el Game.
Avoid Controllers get too much knowledge from model.

# Use cases.plantuml (Sergio M.)
Move from stock to Waste -> include flip stock.
Remove flip deck
Rename Play Again Restart Game
Extract ShowBoard as a included UC.

# Start Game (Javi)
* Eliminar cosas internas.

# From Stock to WAste (Sergio T.)
Rename deck -> Stock

# Waste to Foundation (Javi)
Show board is a sub-UC.

# Waste To Tableau (Sergio M)
User select action before card
DisplayGame -> ShowBoard.
Remove state Destination

# Tableau to Tableau
Seleccionar carta, no una pila. Se mueven todas las que cuelguen.

# Foundation to tableau
simplify tableau selection. User always select destination. No automatic movement.

# Random Movement
Rename Hint
Remove lose detection
Rename GameClosed -> ClosedGame

# Help Summary
Move actions to arrows

# Exit Game
Request for confirmation

# Interfaz
Update Pile -> Tableau
