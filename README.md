# PHP Data

Questo programma PHP genera un saluto in base all'orario corrente ("Buongiorno" o "Buonasera") e visualizza la data e l'ora attuali nel formato `YYYY-MM-DD HH:MM:SS`. La pagina HTML utilizza uno script in  PHP per determinare l'orario corrente e fornire il saluto appropriato.

## Contenuto

- `index.php`: Il file principale che contiene l'HTML e lo script PHP per mostrare il saluto e la data/ora.

  
## Come usare

1. Scarica il file `index.php`.
2. Carica il file sul tuo server web.
3. Accedi alla pagina tramite il browser.
4. Il saluto verrà visualizzato automaticamente, cambiando tra "Buongiorno" e "Buonasera" a seconda dell'orario corrente.
5. L'orario corrente viene visualizzato con il formato `YYYY-MM-DD HH:MM:SS`.

## Funzionamento

Lo script PHP all'interno del file `index.php` controlla l'orario corrente usando la funzione `date()`. Se l'ora è minore o uguale a 18 (6:00 PM), viene visualizzato "Buongiorno", altrimenti "Buonasera". Il tutto viene integrato nell'HTML per essere visualizzato al centro della pagina.
