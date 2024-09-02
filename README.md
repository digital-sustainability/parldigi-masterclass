# Party Prediction

Requesting data from https://www.smartvote.ch/ and using it to train a neural network to guess which political party someone is from. Documentation is in German.

---

## 0. Einführung

In diesem Projekt geht es darum, ein neuronales Netzwerk so zu trainieren, dass es anhand der Antworten, die Kandidierende fürs Parlament auf [Smartvote](https://www.smartvote.ch) eingegeben haben, deren jeweilige Partei zu erraten. Dazu sind 4 Schritte notwendig:

### 1. Daten sammeln

Als erstes werden die Daten von Smartvote geholt und als JSON-Datei gespeichert.

### 2. Die gesammelten Daten analysieren

Im nächsten Schritt schauen wir uns die Daten etwas genauer an und erfassen einige ihrer Eigenschaften.

### 3. Die gesammelten Daten bereinigen

Zum Trainieren des neuronalen Netzwerks werden hier die Daten bereinigt. Dazu werden Erkenntnisse aus der vorhergehenden Analyse gebraucht.

### 4. Das neuronale Netzwerk trainieren und testen

Hier werden die Daten an das neuronale Netzwerk gefüttert und anschliessend wird gemessen, wie gut das Modell die Kandidierenden einteilen kann. Als Abschluss folgt dann noch eine kurze Interpretation der Fehlermatrix der Testdaten.

## Installation

Für die optimale Erfahrung empfehle ich [Visual Studio Code](https://code.visualstudio.com/) zu verwenden. Zum Lesen, Bearbeiten und Ausführen der Notebooks gibt es die Jupyter-Erweiterung, die (innerhalb von VSCode) mit `ext install ms-toolsai.jupyter` installiert werden kann.

1. [Git](https://git-scm.com/download) installieren.
2. [Python](https://www.python.org/downloads/) installieren.
3. Repository klonen mit `git clone https://github.com/lionelsemion/party-prediction.git && cd party-prediction`.
4. pipenv installieren. Auf Linux mit `sudo apt install pipenv`, auf Windoof nach [dieser Anleitung](https://www.pythontutorial.net/python-basics/install-pipenv-windows/)
5. Libraries installieren mit `pipenv install`.

## Getting Started

Die Notebooks können der Reihe nach ausgeführt werden. Das zweite (Daten Analysieren) muss zum Trainieren des NN nicht zwingend ausgeführt werden. Wenn Visual Studio Code verwendet wird, muss je nachdem zum Ausführen noch ein Kernel ausgewählt werden. Rechts oben hat es dazu einen Knopf. Dort können auch gleich einige Erweiterungen installiert werden, die hilfreich für die Arbeit mit Jupyter sind.

## Contributors

Ich (Lionel Stürmer) habe das Projekt alleine entwickelt und dokumentiert
