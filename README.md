# RetiGeografiche

Testing di VADER e SPICY per l'analisi del sentiment di frasi italiane.
# iniziamo da VADER
Svantaggi: 1. Funziona solo in inglese
soluzione: questo progetto su github: https://github.com/brunneis/vader-multi utilizza l'API di google translate. Nota bene: capisce automaticamente il linguaggio da tradurre
Vantaggi: 1. è preciso. capisce con efficienza frasi positive, negative e neutre. 
Nota bene: se analizza una frase in ita e la stessa frase in eng, da risultati leggermente diversi (punteggi 'neg' 'neu' 'pos' leggermente diversi). Io suppongo che sia perché 2 lingue diverse non possono mai essere tradotte ugualmente reciprocamente -> l'API di google non è perfetta.
