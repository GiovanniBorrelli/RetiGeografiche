# Analisi del Sentimento in Italiano

Questo repository contiene un progetto per l'analisi del sentiment di frasi in lingua italiana utilizzando diverse librerie e modelli, tra cui VADER, Spacy e Feel-It. L'obiettivo principale è valutare le prestazioni di queste risorse nell'identificare e classificare il sentiment delle frasi italiane.

## Librerie e Modelli Utilizzati

### VADER

VADER è una libreria ampiamente utilizzata per l'analisi del sentiment in inglese. Tuttavia, per estendere la sua applicazione all'italiano, è stato utilizzato un progetto di traduzione automatica basato sull'API di Google Translate. Si è notato che i punteggi di sentiment possono variare leggermente tra le frasi originali in italiano e le loro traduzioni in inglese, presumibilmente a causa delle differenze linguistiche e delle limitazioni dell'API.

### Spacy

Spacy offre un modello in italiano (it_core_news_sm), ma non include funzionalità di sentiment analysis. Pertanto, per effettuare l'analisi del sentiment in italiano, è stata necessaria l'implementazione di una libreria aggiuntiva (pattern.it). Anche se Spacy lavora solo con una lingua alla volta, sembra offrire una precisione superiore rispetto a VADER, forse grazie all'assenza dell'uso dell'API di traduzione di Google.

### Feel-It

Feel-It è un modello specifico per l'italiano che fornisce non solo informazioni sul sentiment (positivo o negativo) ma anche sulle emozioni associate a una determinata frase. Tuttavia, va notato che questo modello è stato addestrato principalmente su dati provenienti dai social media, il che potrebbe influire leggermente sulla sua accuratezza in altri contesti.

## Dataset

Il dataset utilizzato per valutare le prestazioni di queste librerie e modelli è stato ottenuto da [AnagramSolver](https://github.com/sigmasaur/AnagramSolver). Questo dataset comprende una vasta gamma di parole italiane e sarà utilizzato per testare l'efficacia dei vari approcci di analisi del sentiment.

## Scopo del Progetto

L'obiettivo principale di questo progetto è determinare quale tra le librerie e i modelli considerati sia il più adatto per l'analisi del sentiment in italiano. In particolare, si cerca di valutare la precisione e l'affidabilità di ciascun approccio in diverse situazioni linguistiche e contesti di utilizzo.

## Contributi e Feedback

Siamo aperti a contributi e feedback da parte della comunità. Se hai suggerimenti per migliorare questo progetto o desideri condividere le tue esperienze con l'analisi del sentiment in italiano, ti invitiamo a partecipare alla discussione e a proporre eventuali modifiche.

Grazie per il tuo interesse nel nostro progetto!
