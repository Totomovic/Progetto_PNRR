# Analisi del PNRR in Italia – Progetto Jupyter

## Descrizione del progetto
Questo progetto esplora e analizza i dati del **Piano Nazionale di Ripresa e Resilienza (PNRR)** in Italia, utilizzando dataset ufficiali open data del portale ([https://pnrr.datibenecomune.it/).](https://pnrr.datibenecomune.it/fonti/regis/)  
L’obiettivo è comprendere la distribuzione territoriale dei progetti, l’allocazione dei finanziamenti, lo stato di avanzamento e l’attività dei soggetti coinvolti, gare e subappalti.

Il progetto è sviluppato in **Python** tramite **Jupyter Notebook** e utilizza librerie di data analysis come `pandas`, `matplotlib` e `seaborn` per la visualizzazione dei dati.

---
## 🗂 Dataset utilizzati

I dataset provengono dal **portale open data ufficiale ItaliaDomani**, aggiornati regolarmente:

1. **PNRR_soggetti.csv** – Elenco dei soggetti (enti pubblici e privati) coinvolti nei progetti.
2. **PNRR_progetti.csv** – Tutti i progetti PNRR con finanziamenti, missione, componente e misure.
3. **localizzacioneammTitolari_interoperabilità.csv** – Informazioni geografiche dei progetti e amministrazioni titolari.
4. **aggiudicatari_gare.csv** – Imprese aggiudicatarie delle gare collegate ai progetti.
5. **subappaltatori_gare.csv** – Subappaltatori coinvolti nelle gare.
6. **gare.csv** – Dati sulle gare pubbliche (CIG, importi, tipologia procedura).

> Fonte ufficiale: https://pnrr.datibenecomune.it/fonti/regis/

---

## 🔍 Obiettivi dell’analisi

- Analizzare la distribuzione dei **progetti PNRR per regione, provincia e comune**.
- Studiare l’**allocazione dei finanziamenti** per missione, componente e misura.
- Identificare i **principali soggetti attuatori** e le **amministrazioni titolari**.
- Analizzare le **gare e gli aggiudicatari**, comprese le informazioni sui subappaltatori.
- Creare **visualizzazioni interattive e grafici statistici** per rappresentare i dati in modo chiaro.
- Esplorare l’**avanzamento dei progetti** e le correlazioni tra stanziamenti e localizzazione territoriale.

---

## 🧪 Analisi incluse nel notebook

1. **Importazione e pulizia dati**  
   - Conversione dei tipi numerici e date  
   - Rimozione di duplicati e valori mancanti  

2. **Analisi esplorativa dei dati**  
   - Totale finanziamenti per missione e componente  
   - Numero di progetti per regione e comune  
   - Top 10 soggetti attuatori e aggiudicatari  

3. **Visualizzazioni**  
   - Bar chart e pie chart di stanziamenti e progetti  
   - Heatmap Missione x Regione  
   - Analisi gare e subappalti  

4. **Esportazione dei risultati**  
   - CSV aggregati per missione, regione e soggetti  
   - Grafici in formato PNG/HTML nella cartella `output/`

---

## ⚙️ Librerie e strumenti

- Python 3.10+
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Jupyter Notebook
