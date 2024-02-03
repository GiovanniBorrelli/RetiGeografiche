# RetiGeografiche

Testing di VADER e SPICY per l'analisi del sentiment di frasi italiane.
# iniziamo da VADER

Svantaggi: 1. Funziona solo in inglese.
soluzione: questo progetto su github: https://github.com/brunneis/vader-multi utilizza l'API di google translate. Nota bene: capisce automaticamente il linguaggio da tradurre

Vantaggi: 1. è preciso. capisce con efficienza frasi positive, negative e neutre. 
Nota bene: se analizza una frase in ita e la stessa frase in eng, da risultati leggermente diversi (punteggi 'neg' 'neu' 'pos' leggermente diversi). Io suppongo che sia perché 2 lingue diverse non possono mai essere tradotte ugualmente reciprocamente -> l'API di google non è perfetta.

# finiamo con SPACY
Svantaggi: 1. allora, spacy ce l'ha un modello in italiano:  it_core_news_sm. tuttavia, non è compatibile con il sentiment analysis!!! ho dovuto cercare e scaricarmi una libreria a parte (pattern) e usare pattern.it. 
2. rispetto a vader, funziona con solo una lingua alla volta
Vantaggi: sembra piu preciso di VADER. forse è dovuto al fatto che non usa google translate API. bisogna approfondire pattern.it

### FEEL IT
Vantaggi: Lingua italiana, informazioni sulle emozioni.
Svantaggi: Addestrato tramite social media, questo potrebbe causare un leggero calo di accuratezza per altri campi di studio.
https://huggingface.co/MilaNLProc/feel-it-italian-sentiment (non serve)
https://huggingface.co/MilaNLProc/feel-it-italian-emotion (è piu interessante)

# Quale usare per il nostro scopo
Dato che Feel-It è in italiano e oltre a indicare se il sentimento è positivo o negativo fornisce anche informazioni sull'emozione che l'interlocutore prova risulta essere il più adatto per progetto.


# DATASET di parole preso da: https://github.com/sigmasaur/AnagramSolver
