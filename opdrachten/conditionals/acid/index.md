# Acid test

Gegeven is het volgende Python-programma:

    ph = float(input("Geef een pH-waarde: "))
    if ph < 7.0:
        print("Het is een zuur")
    else:
        print("Het is een base")

Maak een Python-bestand aan genaamd `acid.py`. Splits bovenstaande programma op zodat het voldoet aan onze standaard-manier van programma's schrijven. Hierin is er een **functie die een berekening doet** en een **hoofdprogramma dat de input en output afhandelt**. Het moet er ongeveer zo uitzien:

    def is_acidic(...) -> bool:
        <functie met docstring, voorbeelden en implementatie>
    
    if __name__ == '__main__':
        <hoofdprogramma doet alleen input en print, en roept is_acidic aan>

## Hint

- De logica is al gegeven. Het enige dat je moet doen is het in de template passen. Maar dat is niet helemaal triviaal, zie de volgende hint.

- Het is noodzakelijk om zowel in `is_acidic` als in de `__main__` een `if`-`else` toe te voegen.
