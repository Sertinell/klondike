# Use Cases

## Actors (Sergio T.)

Player: is the only user of the application (game) 

## Domain Model (Sergio M.)

1. Baraja(deck)
2. 1 Jugador
3. Juego: Multiples partidas sin estadistica, ni guardar, ni cargar ni nada.
4. Se reparte nada más iniciar la aplicación
5. 1 Tableau
6. 7 Piles
7. 4 Foundation
8. Sacamos cartas de 3 en 3
9. Baraja Poker: 4 Palos, hearts, diamonds, clubs, spades AS-2..10-J-Q-K (https://en.wikipedia.org/wiki/Standard_52-card_deck)

## List of Use Cases

1. Player start game (Javi)

2. Player move card
2.1 From Waste to Tableau (Sergio M.)
2.2 From Waste to Foundation (Javi) 
2.3 From Tableau to Foundation (Sergio T.)
2.4 From Foundation to Tableau (Javi)
2.5 From Tableau to Tableau (Javi)

3. Player flip 3 cards from deck (Sergio T.)

4. Player exits game (Sergio M.)
5. Player restart game (Javi)
6. Player request helps (?) (Sergio T)
7. Player request a "random" movement (Sergio M)

# State Diagram (Sergio T.)
            -------|        
Start --> Play - Move -> WIN/LOST 
  ^------------------------|
