[![Shipping files](https://github.com/neuefische/ds-pandas-numpy/actions/workflows/workflow-02.yml/badge.svg?branch=main&event=workflow_dispatch)](https://github.com/neuefische/ds-pandas-numpy/actions/workflows/workflow-02.yml)
# Einführung in Pandas und Numpy

![Pandas](./images/pandas_photo.jpg)
<span>Foto von <a href="https://unsplash.com/@pbernardon?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Pascal Bernardon</a> auf <a href="https://unsplash.com/s/photos/panda?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

In diesem Repository findest du **Jupyter Notebooks**, an denen ihr als **Pair-Programmer** gemeinsam arbeiten sollt.

Bitte stelle sicher, dass du das Repository **geforkt** hast, es auf deinem Rechner **geclont** hast und anschließend eine **neue virtuelle Umgebung** eingerichtet hast.

---

## Umgebung einrichten

Die hinzugefügte [requirements-Datei](requirements.txt) enthält alle Bibliotheken und Abhängigkeiten, die wir benötigen, um Pandas und Numpy auszuführen.

### **`macOS`** – folgende Befehle ausführen:

- Installiere die virtuelle Umgebung und die benötigten Pakete mit den folgenden Befehlen:

```bash
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

### **`WindowsOS`** – folgende Befehle ausführen:

- Installiere die virtuelle Umgebung und die benötigten Pakete mit den folgenden Befehlen.

Für die `PowerShell` CLI:

```powershell
pyenv local 3.11.3
python -m venv .venv
.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
```

Oder…

Für die `Git-Bash` CLI:

```bash
pyenv local 3.11.3
python -m venv .venv
source .venv/Scripts/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```

**Hinweis:**  
Wenn beim Ausführen von `pip install --upgrade pip` ein Fehler auftritt, versuche stattdessen:

```bash
python.exe -m pip install --upgrade pip
```

---

Am Ende dieses Repositories solltest du:  

- verstehen, warum Pandas und Numpy wertvolle Werkzeuge für Data Scientists sind  
- sicher im Umgang mit Pandas DataFrames und Numpy-Arrays sein  
- wissen, wie man Datensätze kombiniert  
- einfache EDA auf einem neuen Datensatz durchführen können  
- grundlegende Plots erstellen können, um Daten besser zu verstehen  