# Enemy

## State machine
Questi sono gli stati:
### Idle (roaming)
Il nemico ancora non ha avvistato il giocatore quindi o sta fermo o segue un percorso di pattuglia
### Following
Il nemico ha individuato il giocatore e inizia a seguirlo. Se il nemico esce dall campo visivo del nemico per più di un tot secondi torna allo stato di roaming.
### Attacking
Il nemico è abbastanza vicino al giocatore per attaccarlo. Esegue l'attacco e torna in following.


## Triggers
Il nemico utilizza 3 aree per vedere intorno a se. Se il giocatore in queste areee soddisfa le loro condizioni il nemico passa allo stato di **following**:
- l'area grande (Rossa): se il giocatore entra in quest'area emettendo suoni rumorosi come saltare o correre 
- l'area piccola (Grigia): se il giocatore entra in quest'area emettendo suoni silenziosi
- cono visivo (Verde): se il giocatore entra nell'area




![image](/DevGuide/images/EnemyTriggerZone.drawio.svg)
