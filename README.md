### Feel-It

Feel-It è un modello specifico per l'italiano che fornisce non solo informazioni sul sentiment (positivo o negativo) ma anche sulle emozioni associate a una determinata frase. Tuttavia, va notato che questo modello è stato addestrato principalmente su dati provenienti dai social media, il che potrebbe influire leggermente sulla sua accuratezza in altri contesti.

## Dataset

Il dataset utilizzato per valutare le prestazioni di queste librerie e modelli è stato ottenuto da [AnagramSolver](https://github.com/sigmasaur/AnagramSolver). Questo dataset comprende una vasta gamma di parole italiane e sarà utilizzato per testare l'efficacia dei vari approcci di analisi del sentiment.

## Scopo del Progetto

L'analisi del linguaggio naturale (NLP) rappresenta una risorsa cruciale per comprendere le complesse dinamiche delle intercettazioni criminali. Tuttavia, l'efficacia di tale analisi può essere compromessa da diverse sfide, tra cui la presenza del dialetto napoletano all'interno delle conversazioni e la limitata quantità di dati disponibili. Tra VADER, Spacy e Feel-It, alla fine si è optato per l'utilizzo di Feel-it poiché consente in aggiunta di analizzare anche l'emozione di una frase (joy, anger, sadness, fear). Quindi, in questo contesto, il presente studio si propone di utilizzare il modello di analisi del sentiment - Feel-It - addestrato su frasi in lingua italiana, per estrarre informazioni utili dalle intercettazioni criminali. Attraverso un'analisi accurata del testo delle conversazioni, si mira a comprendere lo stato emotivo dei soggetti coinvolti, le loro motivazioni e le relazioni intercorrenti. Tuttavia, le limitazioni legate alla varietà linguistica e alla qualità dei dati richiedono un approccio attento e multidisciplinare per massimizzare l'utilità delle informazioni ottenute. In conclusione, questo studio si propone di contribuire alla comprensione delle dinamiche criminali attraverso un'analisi avanzata del linguaggio naturale, offrendo insight preziosi per il lavoro investigativo e giuridico. 

## Tutorial

(Last tested - 2024 Feb 18)

| Colab | Info
| --- | --- |
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GiovanniBorrelli/RetiGeografiche/blob/main/2%29%20Model%20(Feel-It)%20Training/UseFeel-It.ipynb) | Feel-It per le intercettazioni criminali

Bisogna utilizzare il file `input.xlsx` che contiene tutte le frasi da analizzare. Il codice restituirà il file `output_con_emozioni_e_sentimenti.xlsx`.

## Contributi e Feedback

Siamo aperti a contributi e feedback da parte della comunità. Se hai suggerimenti per migliorare questo progetto o desideri condividere le tue esperienze con l'analisi del sentiment in italiano, ti invitiamo a partecipare alla discussione e a proporre eventuali modifiche.

Grazie per il tuo interesse nel nostro progetto!
