# ML-homework


Analiza danych sprzedaży mieszkań

Projekt ten ma na celu przeprowadzenie analizy danych sprzedaży mieszkań oraz predykcję cen mieszkań na podstawie dostarczonego pliku z danymi. Wykorzystane zostaną 2 różne modele machine learning, a także zostaną przeprowadzone optymalizacje hiperparametrów w celu znalezienia najlepszego modelu.



 projekcie przyjęto następujące założenia:

Plik z danymi wejściowymi nazywa się "Sacramento_real_estate_transactions.csv" i znajduje się w tym samym katalogu co skrypt główny.
Dane wejściowe zawierają informacje dotyczące powierzchni mieszkań, liczby pokoi, lokalizacji, itp.
Ceny mieszkań są wartościami numerycznymi i stanowią wartość docelową do przewidzenia.
Wszystkie modele machine learning wykorzystują ten samy zbiorów danych treningowych i testowych.


Aby uruchomić ten projekt, wymagane są następujące zależności:

Python (w wersji 3.7 lub nowszej)
Biblioteki Python zdefiniowane w pliku requirements.txt
Opis funkcji

Projekt składa się z następujących funkcji i etapów:

Wczytanie danych: Dane sprzedażowe zostaną wczytane z pliku "dane_sprzedazowe.csv".
Eksploracja danych: Wykonana zostanie eksploracyjna analiza danych, korelacji między zmiennymi itp.
Przygotowanie danych: Dane wejściowe zostaną poddane obróbce, takiej jak usuwanie wartości odstających, normalizacja itp.
Podział danych: Dane zostaną podzielone na zbiór treningowy i testowy.
Utworzenie modeli: Stworzone są dwa różne modele machine learning.
Optymalizacja hiperparametrów: Dla każdego modelu zostanie przeprowadzona optymalizacja hiperparametrów w celu znalezienia najlepszych wartości.
Wybór najlepszego modelu: Na podstawie wyników optymalizacji, zostanie wybrany najlepszy model do dalszej analizy.
Zwizualizowanie wyników: Wyniki analizy i predykcji zostaną zwizualizowane w formie wykresów i raportów.


