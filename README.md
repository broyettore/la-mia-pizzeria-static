# la-mia-pizzeria-static

Dobbiamo realizzare un’applicazione web che ci aiuti a gestire la nostra pizzeria.
Abbiamo bisogno di creare la nostra prima pagina (index) per l'amministratore dove mostriamo tutte le pizze che il nostro locale gestisce.
Una pizza avrà le seguenti informazioni :
* un nome
* una descrizione
* una foto (url)
* un prezzo
  
Modifichiamo quindi la view Index.cshtml generata in automatico da .Net Core scrivendo l’html che serve a noi per mostrare l’elenco delle pizze (possiamo creare una tabella con bootstrap o una qualche grafica a nostro piacimento che mostri l’elenco delle pizze... che sia funzionale e veloce per un amministratore!)

### BONUS:
Se vi avanza tempo, create anche una landing page per un cliente della vostra pizzeria che vuole vedere le vostre pizze. Chiamiamo questa pagina UserIndex.cshtml e creiamola nella cartella Home delle Views. A questo punto dovete creare all'interno di Controllers > HomeController.cs un metodo
