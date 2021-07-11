# Aufgabe 1 in BdK6.5.3 (wB/öB) P3 Data Librarianship und Programmierung

## 1. Text-Editor der Wahl

Ich habe mich für vs code entschieden, editiere aber gerade noch in nano.

## 2. Eine Python-Bibliothek 

Matplotlib. Matpoltlib ist eine Python Bibliothek, die es möglich macht, verschiedenste mathematische Diagramme zu erstellen.

## 3. Eine Fehlermeldung und Ihre Lösung

### Fehler
KeyError                                  Traceback (most recent call last)
<ipython-input-12-1da2f6ed1e3e> in <module>
----> 1 pmid_data["result"]["pubdate"]

KeyError: 'pubdate'

Mit dem zweiten key ["pubdate"] ließ sich das Erscheinungsjahr nicht ansprechen, der der key unter "results" nicht zu finden war.

### Lösung
Um pubdate ansprechen zu können, muss zunächst der Teil angesprochen werden, der das Erscheinungsjahr enthält, in diesem Fall der key, der der PubMed ID entspricht

## 4. Was ist JupyterLab?

JupyterLab ist eine Arbeitsumgebung, die vor allem die Arbeit mit Jupyter Notebooks unterstützt, aber auch die Nutzung von Editoren, der Kommandozeile und anderen individualisierten Modulen möglich macht. 

## 5. Was ist der große Unterschied zwischen de Webframeworks flask und Django?

Django ist ein All-in-One Framework, das die zu nutzenden Tools zum großen Teil vorgibt. Flask hingegen ist ein Microframework, das diese Entscheidungen dem Nutzer überlässt 
