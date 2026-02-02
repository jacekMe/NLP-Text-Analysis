# NLP Document Analysis & Ranking

## 📝 Opis projektu
Projekt realizowany w ramach studiów na kierunku Biznes Elektroniczny. Głównym celem było przygotowanie silnika wyszukiwania, który na podstawie zapytania użytkownika (Query) wskazuje najbardziej adekwatne dokumenty z zestawu danych tekstowych.

## 🛠 Wykorzystane technologie
* **Język:** Python 3.x
* **Biblioteki:** * `Pandas` & `NumPy`: Manipulacja i strukturyzacja danych.
  * `NLTK`: Preprocessing (Stopwords, PorterStemmer).
  * `Scikit-learn`: Wektoryzacja tekstu (TF-IDF, Bag of Words, Binary).
  * `WordCloud` & `Matplotlib`: Wizualizacja wyników.

## 🚀 Kluczowe etapy pracy
1. **Preprocessing:** Czyszczenie danych tekstowych, usuwanie znaków specjalnych i tokenizacja.
2. **Stemming:** Redukcja słów do ich rdzeni przy użyciu algorytmu Portera w celu poprawy trafności wyszukiwania.
3. **Wektoryzacja:** Implementacja i porównanie trzech podejść: binarnego, BoW (Bag of Words) oraz TF-IDF.
4. **Analiza trafności:** Obliczenie podobieństwa dokumentów do zapytania i wybór 5 najbardziej adekwatnych wyników.
5. **Wizualizacja:** Generowanie chmur słów dla analizowanych zbiorów.

## 💡 Czego się nauczyłem?
* Rozumienia różnic między modelami reprezentacji tekstu (TF-IDF vs BoW).
* Praktycznego zastosowania technik NLP do filtrowania i rankowania informacji.
* Pracy w środowisku Jupyter Notebook w celach analitycznych.
