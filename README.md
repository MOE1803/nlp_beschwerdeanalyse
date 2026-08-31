# NLP-Analyse von Bürgerbeschwerden - Stadt Konstanz #
Dieses Projekt wendet klassische NLP-Techniken auf reale Bürgermeldungen des Mängelmelders der Stadt Konstanz an, um die am häufigsten angesprochenen
Themen automatisch zu identifizieren. Ziel ist es, Entscheidungsträgern i der Stadtverwaltung eine datenbasierte Priorisierung
zu ermöglichen, ohne dass jede einzelne Meldung manuell gelesen werden muss.

Zur Ausführung das Repository klonen, eine virtuelle Umgebung (nlp_env) anglegen und aktivieren, die benötigten Pakete installieren (u.a. spaCy inkl. Modell de_core_news_sm, scikit-learn, gensim, pyLDAvis, wordcloud, pandas) und anschließend die Notebooks in numerischer Rehenfolge
- Vorverarbeitung
- Vektorisierung
- Themenmodellierung
- Visualisierung
  
ausführen.

Jedes Notebook lädt seine Eingabedaten aus dem jeweils vorangegangenen Checkpoint im Ordner "output" und speichert dort auch seine eigenen Ergebnisse ab, sodass der gesamte Ablauf nachvollzeihbar reporduzierbar ist.
