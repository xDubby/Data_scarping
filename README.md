# Progetto di Web Scraping: Estrazione Dati da Books to Scrape
Descrizione del Progetto
Questo progetto Python è un esercizio pratico di web scraping mirato all'estrazione di informazioni strutturate dal sito dimostrativo Books to Scrape. L'obiettivo principale è raccogliere dati sui libri, inclusi titolo, prezzo e rating, e organizzarli per successive analisi.

Questo progetto rappresenta la mia prima esperienza nell'utilizzo delle librerie requests e BeautifulSoup per il web scraping, ed è stato un'opportunità per acquisire nuove competenze nell'estrazione e manipolazione dei dati da pagine web.

Funzionalità Principali
Estrazione di Titoli e Prezzi: Recupera i titoli e i prezzi di tutti i libri presenti nella pagina principale.

Conversione Rating: Gestisce l'estrazione dei rating dei libri (che sono rappresentati da classi CSS come "One", "Two", ecc.) e li converte in valori numerici interi (1, 2, ecc.) tramite una mappatura.

Organizzazione Dati: Raccoglie i dati estratti in un DataFrame pandas, rendendoli pronti per l'analisi e la visualizzazione.

Analisi Esplorativa di Base: Include esempi di analisi descrittiva e visualizzazione della distribuzione dei rating.

Tecnologie Utilizzate
Python 3.x

requests: Per effettuare richieste HTTP al sito web.

BeautifulSoup: Per il parsing del contenuto HTML e l'estrazione dei dati.

pandas: Per la manipolazione e l'analisi dei dati in formato DataFrame.

matplotlib.pyplot / seaborn: Per la visualizzazione dei dati (es. istogramma dei rating).