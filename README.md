# REST API z regułą decyzyjną

Ten projekt to przykładowe REST API stworzone z wykorzystaniem Flask w Pythonie na potrzeby laboratorium.
Wymagania:
- Python 3.x
- Flask
- Requests (do testów)

Zainstaluj:
-pip install -r requirements.txt

Po uruchomieniu API będzie dostępne pod adresem:  
http://127.0.0.1:5000/

##Endpointy

- `/` – zwraca: `Witaj w moim API!`
- `/mojastrona` – zwraca: `To jest moja strona!`
- `/hello?name=Imię` – np. `?name=Sebastian` → `Hello Natalia!`
- `/api?x=3&y=5` – porównuje x i y i zwraca wynik reguły decyzyjnej
- `/api/v1.0/predict?num1=3&num2=4` – prosta symulacja modelu ML:
  - jeśli `num1 + num2 > 5.8` → prediction = 1
  - w przeciwnym razie → prediction = 0


