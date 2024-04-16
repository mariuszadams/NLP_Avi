# Instrukcja
Stosowana wersja pythona - 3.9.19

1. Stwórz folder w wybranym miejscu na dysku, który będzie zawierał wysłany kod. Na potrzeby instrukcji nazwiemy go "nlp_workshop".
2. Wklej otrzymane notatniki Jupyter bezpośrednio do folderu "nlp_workshop".
3. Wklej plik requirements.txt bezpośrednio do folderu "nlp_workshop".
4. Stwórz folder "data" w folderze "nlp_workshop"
5. Wklej do folderu "data" otrzymane dane.

Jest wiele sposobów na stworzenie środowiska python'owego. Poniżej opisujemy jeden z nich, lecz nie wymagamy skorzystania akurat z niego:
1. Zainstaluj manager paczek [Anaconda](https://www.anaconda.com/download).
2. Otwórz terminal dostarczony przez Anacondę, który nazywa się "Anaconda prompt".
3. W terminalu napisz `conda create --name nlp_workshop python=3.9.19`. Stworzy to podstawowe środowisko python'owe, o nazwie "nlp_workshop" oraz wersją pythona 3.9.19. Kliknij enter.
4. Anaconda po chwili najpewniej poprosi o potwierdzenie chęci stworzenia środowiska z paroma podstawowymi paczkami. Zgódź się wpisując "y" i klikając enter.
5. Po udanym stworzeniu środowiska, aktywuj je pisząc `conda activate nlp_workshop`.
6. Przejdź do folderu "nlp_workshop" w terminalu. Można to zrobić za pomocą komendy "cd" i wpisaniu pełnej ścieżki instalacji lub nawigowaniu krok po kroku, folder po folderze. Będzie to potrzebne do następnego kroku, w którym instalujemy wymagane paczki.
7. Wpisz `pip install -r requirements.txt`, aby zainstalować wszystkie wymagane pakiety.
8. Wpisz `python -m ipykernel install --user --name nlp_workshop --display-name 'nlp_workshop'`, aby zarejestrować środowisko jako kernel Jupyter.
9. Uruchom Anaconda Navigator i wybierz Jupyter Notebook.
10. Otwórz Jupyter Notebook przez Anaconda Navigator.
11. W otwartym oknie Jupyter Notebook przejdź do swojego folderu "nlp_workshop".
12. Uruchom notatnik Jupyter wybranej lekcji.
13. Kliknij opcję "kernel", aby wybrać kernel.
14. Wybierz kernel "nlp_workshop".

W przypadku problemów z ustawieniem środowiska, zapraszamy do kontaktu,
prosimy o wiadomość ze screenem błędu.
Postaramy się pomóc :)

piotr.zabek@aviva.com