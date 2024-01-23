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

# FEEL IT
https://huggingface.co/MilaNLProc/feel-it-italian-sentiment (non serve)
https://huggingface.co/MilaNLProc/feel-it-italian-emotion (è piu interessante)

Vantaggi: sembra piu preciso di VADER. forse è dovuto al fatto che non usa google translate API. bisogna approfondire pattern.it
# Quale usare per il nostro scopo
Dato che Vader è particolarmente adatto per l'analisi dei Social Media ed è progettato specificatamente per l'inglese,
mentre Spacy è una libreria più generica per il Natural Language Processing e supporta molte lingue diverse. Per ciascuna lingua supportata, Spacy offre modelli specifici che possono essere caricati.
Date queste considerazioni risulta opportuno utilizzare Spacy per il nostro scopo (informazioni su Vader:https://stackoverflow.com/questions/45275166/is-vader-sentimentintensityanalyzer-multilingual, informazioni su Spacy:https://spacy.io). 
