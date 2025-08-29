# ⚽ Fantacalcio 2025-2026 – Analisi Serie A

## 📌 Descrizione
Questo progetto analizza le statistiche dei giocatori di Serie A (stagione 2024-2025) per supportare le scelte nell’asta del Fantacalcio 2025-2026.  
L’obiettivo è identificare giocatori **affidabili** e con **alto potenziale**, combinando metriche di base e avanzate, normalizzate su 90 minuti.

---

## 🎯 Obiettivi
- Pulire e normalizzare i dati provenienti da [FBref](https://fbref.com/) (scraping HTML).
- Calcolare **metriche per 90 minuti** e indicatori derivati (xG, xA, ecc.).
- Creare un **indice sintetico** con tier qualitativi (A, B, C, D).
- Visualizzare le prestazioni **per ruolo** (ATT, CEN, DIF, POR).
- Evidenziare i **Top 10 giocatori** e i profili “undervalued”.

---

## 📂 Struttura del progetto
Fantacalcio2526/
│── data/                  # Dati grezzi scaricati da FBref
│── Fantacalcio2526.ipynb  # Jupyter Notebook principale
│── OutputCSV.py           # Dati esportati in CSV
│── README.md              # Questo file
---

## 🛠️ Tecnologie usate
- **Python 3.x**
- **pandas, numpy** → pulizia e analisi dati
- **BeautifulSoup4, lxml** → scraping HTML
- **matplotlib** → visualizzazioni
- **Jupyter Notebook** → analisi interattiva

---

📊 Risultati principali
	•	Creazione di un Indice Sintetico per valutare i giocatori in modo comparabile.
	•	Classifica Top 10 attaccanti, centrocampisti, difensori e portieri.
	•	Identificazione di giocatori con differenza positiva tra gol fatti e attesi → potenziali sorprese.
	•	Visualizzazioni che mostrano il rapporto tra metriche avanzate (xG, xA, passaggi progressivi) e rendimento effettivo.

✅ Conclusioni

Il progetto mostra come sia possibile applicare tecniche di data analysis e feature engineering per supportare decisioni pratiche nel contesto sportivo.
Il workflow va dal data scraping fino alla visualizzazione dei risultati, dimostrando competenze di:
	•	Data wrangling
	•	Analisi statistica applicata
	•	Creazione di metriche sintetiche
	•	Storytelling con dati

⸻

🔮 Possibili sviluppi futuri
	•	Integrazione con altre fonti (es. Transfermarkt per i valori di mercato).
	•	Dashboard interattiva (Streamlit) per consultare ranking e filtri personalizzati.
	•	Analisi predittiva con modelli ML (regressioni su xG/xA).

⸻

👤 Autore

[Il tuo nome]
	•	LinkedIn: https://www.linkedin.com/in/giacomo-lanzoni-766a3821/
	•	GitHub: https://github.com/JackLanzoni/Fantacalcio2526
