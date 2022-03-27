#Stwórz katalog
mkdir python-zadanie
cd python-zadanie

#Stwórz wirtualne środowisko i zainstaluj
py -3 -m venv venv venv\Scripts\activate
pip install Flask
set FLASK_APP=hello.py
flask run

#Stwórz plik requrements.txt
pip install pipreqs
pipreqs, wklej adres przeglądaki 127.0.0.1:5000