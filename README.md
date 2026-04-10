 Asset Quality Dashboard

Interaktives Analyse-Dashboard zur automatischen Erkennung und Visualisierung von Datenqualitätsproblemen in IT-Asset-Datensätzen.

Features
- Robuster CSV-Upload (UTF-8, ISO-8859-1, CP1252, BOM etc.)
- Automatische Datenbereinigung + Normalisierung
- Heuristische Analyse-Engine:
  - Abgelaufene Garantien bei aktiven Geräten
  - Duplikate
  - Virtuelle Maschinen vs. physische Hardware
- KPI-Karten + interaktive Tabs (Expired | Duplicates | VMs)
- Export gefilterter Datensätze als CSV
- Dark-Mode UI (Bootstrap DARKLY)

 Technologie-Stack
- Python 3.8+
- Dash + dash-bootstrap-components
- pandas + plotly
- dash-iconify

 Installation & Start

```bash
 1. Repo klonen
git clone https://github.com/deinusername/asset-quality-dashboard.git
cd asset-quality-dashboard

 2. Virtuelle Umgebung
python -m venv .venv
source .venv/bin/activate    # Windows: .venv\Scripts\activate

 3. Abhängigkeiten
pip install -r requirements.txt

4. Starten
python asset_dashboard.py
