# Metaklasy - tworzenie interfejsów deklaratywnych

Ten katalog zawiera prezentację o podstawach metaklas w Pythonie i chyba
jedynym ich zastosowaniu które ma sens - implementacji "deklaratywnych" API
podobnych do modeli Django czy SQLAlchemy, albo serializerów Django Rest
Framework.

## Oglądanie prezentacji

Otwórz plik `Prezentacja.slides.html` w dowolnej współczesnej przeglądarce.

## Edycja lub testowanie

Prezentacja została stworzona jako notatnik Jupyter Notebook. Aby działał
wymagane jest środowisko które możesz sobie utworzyć za pomocą
[pipenv](https://pipenv.readthedocs.io/en/latest/install/#installing-pipenv).

Po zainstalowaniu tego narzędzia wykonaj w niniejszym katalogu
`pipenv install`. Następnie możesz korzystać z poniższych komend:

* `pipenv run notebook` - uruchamia notatnik w twojej domyślnej
przeglądarce.
* `pipenv run slides` - generuje nowy plik ze slajdami (uwaga, to nadpisze
istniejący plik `Prezentacja.slides.html`!)
* `pipenv run serve` - generuje nowy plik ze slajdami, uruchamia proces który
serwuje go po HTTP i otwiera stronę serwera w twojej domyślnej przeglądarce.

