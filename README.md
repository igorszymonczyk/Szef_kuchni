# Szef Kuchni

## Opis projektu
Szef Kuchni to aplikacja, która umożliwia wyszukiwanie przepisów dla zapytań postaci: zestaw produktów, okazja, czas przygotowania, trudność. Aplikacja umożliwia sterowanie gestami w celu przesówania stron przepisu.
Projekt składa się z dwóch głównych części:
- **Frontend** (React / JavaScript)
- **Backend** (Python / Flask)

## Wymagania
Przed uruchomieniem aplikacji upewnij się, że masz zainstalowane:
- **Node.js** (dla frontendu)
- **Python 3.8+** oraz `pip` (dla backendu)

## Instalacja i uruchomienie

### 1. Backend (Flask + Python)

Przejdź do katalogu `backend/` i zainstaluj wymagane zależności:
```sh
cd backend
pip install -r requirements.txt
```
Uruchom serwer backendu
```sh
python app.py
```

### Frontend (React + JavaScript)
Przejdź do katalogu głównego projektu i zainstaluj zależności:
```sh
npm install
```
Uruchom aplikację frontendową:
```sh
npm start
```

### Struktura projektu
```sh
Szef-kuchni-Frontend/
├── backend/            # Kod backendu (Python, Flask)
│   ├── app.py         # Główny plik aplikacji backendowej
│   ├── models.py      # Modele bazy danych
│   ├── config.py      # Konfiguracja aplikacji
│   └── ...
├── src/               # Kod frontendu (React)
│   ├── components/    # Komponenty UI
│   ├── App.js         # Główny komponent aplikacji
│   └── ...
├── package.json       # Konfiguracja frontendu
├── requirements.txt   # Wymagania dla backendu
└── README.md          # Ten plik
```
