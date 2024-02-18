# ENGLISH

### Feel-It

Feel-It is a language model specifically designed for Italian, providing information not only on sentiment (positive or negative) but also on the emotions associated with a given sentence. It's worth noting that this model was primarily trained on data from social media, which might slightly impact its accuracy in other contexts.

## Dataset

The dataset used to evaluate the performance of these libraries and models was obtained from [AnagramSolver](https://github.com/sigmasaur/AnagramSolver). This dataset includes a wide range of Italian words and will be used to test the effectiveness of various sentiment analysis approaches.

## Project Scope

Natural Language Processing (NLP) plays a crucial role in understanding the complex dynamics of criminal interceptions. However, the effectiveness of such analysis can be compromised by various challenges, including the presence of Neapolitan dialect within conversations and the limited amount of available data. Among VADER, Spacy, and Feel-It, Feel-It was chosen due to its additional capability to analyze the emotion of a sentence (joy, anger, sadness, fear). Therefore, in this context, the present study aims to use the sentiment analysis model - Feel-It - trained on Italian sentences to extract useful information from criminal interceptions. Through a careful analysis of the text in conversations, the goal is to understand the emotional state of the individuals involved, their motivations, and the relationships between them. However, limitations related to linguistic variety and data quality require a careful and multidisciplinary approach to maximize the utility of the obtained information. In conclusion, this study aims to contribute to the understanding of criminal dynamics through advanced natural language analysis, providing valuable insights for investigative and legal work.

## Tutorial

(Last tested - February 18, 2024)

| Colab | Info |
| --- | --- |
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GiovanniBorrelli/RetiGeografiche/blob/main/2%29%20Model%20(Feel-It)%20Training/UseFeel-It.ipynb) | Feel-It for criminal interceptions

You need to use the `input.xlsx` file containing all the phrases to be analyzed. The code will generate the `output_with_emotions_and_sentiments.xlsx` file.

## Contributions and Feedback

We welcome contributions and feedback from the community. If you have suggestions to improve this project or want to share your experiences with sentiment analysis in Italian, please join the discussion and propose any necessary changes.

Thank you for your interest in our project!

----------------------
# ITALIANO
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
