🚀 Stigrock v1.2
🔥 Descrizione

Stigrock v1.2 è un progetto avanzato e professionale sviluppato per [inserisci qui la descrizione dettagliata del progetto]. È progettato seguendo le migliori pratiche di sviluppo e distribuzione per garantire qualità, affidabilità e manutenibilità.
🛠️ Installazione e Setup

    Clona il repository:

git clone https://github.com/dnfhacktm/stigrock-v1.2.git
cd stigrock-v1.2

    Crea e attiva un ambiente virtuale:

    Su Linux/macOS:

python3 -m venv venv
source venv/bin/activate

    Su Windows PowerShell:

python -m venv venv
.\venv\Scripts\Activate.ps1

    Aggiorna pip:

pip install --upgrade pip

    Installa le dipendenze:

pip install -r requirements.txt

▶️ Avvio del progetto

Con l’ambiente virtuale attivato, esegui:

python main.py

(Sostituisci main.py con il nome del file principale se differente.)
📁 Aggiunta di nuovi file o moduli

    Per creare un nuovo modulo Python in una sottocartella, ad esempio modules/:

touch modules/nuovo_modulo.py

    Mantieni una struttura ordinata come la seguente:

stigrock-v1.2/
├── main.py
├── modules/
│   └── nuovo_modulo.py
├── data/
│   └── input.txt
├── tests/
│   └── test_modulo.py
└── requirements.txt

    Per aggiungere file al repository Git:

git add nomefile.py
git commit -m "Aggiunto nuovo modulo nomefile.py"
git push origin main
