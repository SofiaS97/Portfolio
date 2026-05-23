# Portfolio
Benvenuto! Al momento, lo spazio raccoglie le presentazioni executive e i report tecnici relativi ad alcuni dei miei principali progetti di ingegneria, analisi dati e automazione. 

> 📌 **Nota:** Il codice sorgente, gli script di automazione e i dataset associati verranno caricati progressivamente nei rispettivi moduli non appena completata la fase di refactoring e pulizia.

## 📂 Contenuto del Repository

Puoi trovare le presentazioni direttamente nella cartella `/presentazioni` ai seguenti link:

1. 📄 [Design and development of a sensorized anklet for restoring proprioception in lower leg [Tesi magistrale in Biomeccanica](presentazioni/Presentazione_Tesi.pdf)
2. 📄 [Estensione del Progetto di Tesi - Sviluppi Futuri](./presentazioni/Presentazione_Tesi.pdf)
3. 📄 [Export automatico di dati in temperatura (Progetto Line-of-Work)](./presentazioni/Automazione_Lavoro.pptx)
4. 📄 [Calssificazione automatica eventi (Progetto Line-of-Work)](./presentazioni/Automazione_Lavoro.pptx)

## 🔬 Dettaglio dei Progetti

### 1. Progetto di Tesi Magistrale
* **Focus:** Propriocezione, design e caratterizzazione cavigliera sensorizzata, circuito low-cost e elaborazione segnali.
* **Descrizione:** Il lavoro si concentra sullo realizzazione di un prototipo di cavigliera sensorizzata che, tramite Arduino e motori ERM, possa ripristinare la propriocezione nell'arto inferiore
* **Stato del codice:** *In arrivo.*.

### 2. Estensione Progetto di Tesi 
* **Focus:** Aggiunto di una sorta di telecomando dotato di pulsante e luce LED; aggiunta di una scheda di memoria SD
* **Descrizione:** Questa sezione raccoglie gli sviluppi lasciati fuori dalla discussione di tesi per vincoli di tempo, ma parzialmente testati in ambiente di simulazione. Tra quesi, la possibilità di aggiungere un telecomando doato di luce LED per aiutare l'utente nell'uso autonomo del dispositivo e l'aggiunta di una scheda di memoria SD per memorizzare le deformazioni dei sensori per ogni utente ed elaborarle successivamente
* **Stato del codice:** *In fase di testing.* 

### 3. Tool di Automazione e Data Extraction (Ambito Industriale)
* **Focus:** Automation, scripting.
* **Descrizione:** Sviluppo di un tool custom per ottimizzare il flusso di lavoro. Il progetto automatizza l'estrazione di dati grezzi da software di testing/acquisizione (in particolare dal Dewesoft X) e la loro successiva archiviazione in formati strutturati, in base alle necessità di testing.
* **Stato del codice:** *In sviluppo.* La struttura dello script principale di automazione verrà rilasciata omettendo i dati sensibili o proprietari.

### 4. Clustering e analisi dati (Ambito Industriale)
* **Focus:** Automation, scripting, classification.
* **Descrizione:** Il progetto automatizza l'estrazione di dati grezzi, la loro elaborazione e la classificazione delle forme d'onde, nonchè calcolo delle loro metriche.
* **Stato del codice:** *In sviluppo.* La struttura dello script principale di automazione verrà rilasciata omettendo i dati sensibili o proprietari.

---

## 🛠️ Stack Tecnologico Previsto

Le pipeline di calcolo e automazione descritte nelle slide si appoggiano principalmente su:
* **MATLAB** 
* **Python**
* **Arduino IDE**

---

## 📈 Roadmap di Rilascio

- [x] Caricamento presentazioni e overview dei progetti
- [ ] Rilascio degli script core per il progetto di automazione industriale
- [ ] Caricamento delle funzioni MATLAB di analisi del segnale (Tesi)
- [ ] Integrazione degli script di machine learning/clustering (Estensione tesi)

---
*Contatti: Se hai domande sulle metodologie o sull'architettura dei progetti, sentiti libero di aprire una Issue o scrivermi direttamente su LinkedIn.*
