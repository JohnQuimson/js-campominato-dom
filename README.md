# Campo minato

## A ogni difficoltà saranno presenti 16 bombe, posizionate in modo casuale, se si clicca su una di esse il gioco termina, altrimenti la casella buona, si colorerà si blu e si potrà continuare a giocare. Il gioco termina con una vittoria: quando l'utente cliccherà su tutte le caselle buone oppure con una sconfitta: se l'utente clicca su una bomba

- Per ogni difficoltà vado a inserire in un array, i 16 numeri che saranno le bombe
- in ogni eventListener, se l'elemento cliccato appartiene all'array, la casella diventa rossa e il gioco si ferma, altrimenti si va avanti
- aggiungo in un altro array tutte le caselle valide e quando array.lenght sarà uguale a N caselle - 16, il gioco si fermerà perchè avrò vinto

### Per fare le prove, creero una quarta modalità che sarà la mod. prova in modo da verificare che tutto funzioni
