# Parldigi Masterclass

Diese Parldigi Masterclass dient der Einführung in das Thema von Algorithmen, Daten, und Software in der Politik.
Zu Beispielszwecken werden wir mithilfe von Daten Arbeiten die von [Smartvote](https://www.smartvote.ch) bezogen werden können.


# Vorbereitung
Alle Codes sind in der Programmiersprache [Python](https://www.python.org/) geschrieben.
Um die Codes auszführen verwenden wir eine webbrowserbasierte Umgebung welche Python Codes ausführen kann.
Diese Umgebung nennt sich [JupyterLite](https://jupyter.org/try-jupyter/lab/).

## JupyterLite aufsetzen
Schritt für Schritt Anleitung

---

## 0. Einführung

In diesem Projekt geht es darum, Daten von Smartvote einzusammeln und basierend darauf spannende Erkentnisse zu sammeln. Dazu sind vier Schritte notwendig


### 1. Daten sammeln

Als erstes werden die Daten von Smartvote geholt und als JSON-Datei gespeichert.

### 2. Die gesammelten Daten analysieren

Im nächsten Schritt schauen wir uns die Daten etwas genauer an und erfassen einige ihrer Eigenschaften.

### 3. Die gesammelten Daten bereinigen

Zum Trainieren des neuronalen Netzwerks werden hier die Daten bereinigt. Dazu werden Erkenntnisse aus der vorhergehenden Analyse gebraucht.


## Vorbereitung

Für die optimale Erfahrung empfehle ich [Visual Studio Code](https://code.visualstudio.com/) zu verwenden. Unter "Terminal" am oberen Bildschirmrand kann auch gleich ein neues Terminal geöffnet werden.

1. [Git](https://git-scm.com/download) installieren.
2. Repository klonen mit `git clone https://github.com/lionelsemion/party-prediction.git && cd party-prediction`.
3. [Python](https://www.python.org/downloads/) installieren.
4. pipenv installieren. Auf Linux mit `sudo apt install pipenv`, auf Windoof nach [dieser Anleitung](https://www.pythontutorial.net/python-basics/install-pipenv-windows/)
5. Libraries installieren mit `pipenv install`.


## Contributors
Die Codes wurde von folgenden Personen entwickelt und konzipiert:

- [Lionel Stürmer](https://github.com/lionelsemion/) Initiale Erstellung der Codes
- [Prof. Dr. Marcel Gygli](https://www.bfh.ch/de/ueber-die-bfh/personen/ywvhtmvrnkn3/) Adaption der Codes und simplifizierung für den Use Case
