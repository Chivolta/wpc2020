# Zaliczenie przedmiotu Wirtualizacja i przetwarzanie w chmurze

Autor: Jacek Kurek (193613) (WZISS22412IS)

## Projekt, impplementacja oraz wdrożenie aplikacji w środowisku AWS

Applikacja generująca animację ze zdjęć, wdrożona z wykorzystaniem usług dostępnych w obrębie chmury AMAZON

### Wymagania dotyczące funkcjonalności

* Rejestracja użytkownika
* Autoryzacja dostępu do aplikacji
* Autoryzacja dostepu do zasobów
* Przechowywanie plików
* Integracja z wykorzystaniem HTTP
* Integracja z wykorzystaniem serwera kolejki
* Implementacja właściwej transformacji obrazów do video
* Notyfikacja użytkownika o zakończonym procesie

### Usługi wspomagające realizacje wymagań

* Amazon Cognito -> rejestracja oraz zarządzanie użytkownikami
* Simple Email Service -> wysyłanie maila o stworzonej animacji
* S3 -> przechowywanie plików
* CloudWatch -> logowanie i pomoc w debugowaniu
* Simple Queue Service -> kolejka do animacji i notyfikacji 
* Cloud9 -> IDE
* Lambda -> tworzenie funkcji do przyjmowania zdjęć, wysyłania do kolejki, tworzenia animacji i wysyłania notyfikacji na maila
* API Gateway -> API REST do integracji z funkcjami Lambda

### Charakterysytka modułów aplikacji
Wykorzystanie technologie, sposób integracji, opis funkcjonalności

* UI
    {opis}
* Transcoding
    {opis}
* Notyfikacje
    {opis}

## Wady i zalety wdrożenia z wykorzystaniem chmury

+
+
+
+

-
-
-
-

## Wykorzystane uslugi

* Bucket -> link i nazwa bucketu
* API Gateway -> Link i nazwa 
* Lambda (zlecenie przygotowania animacji) -> link i nazwa
* Kolejka (zlecenia do wykonania) -> link i nazwa
* Lambda (transcoding) -> link i nazwa
* Kolejka (notyfikacje do wysłania) -> link i nazwa
* Lambda (notyfikacja) -> link i nazwa

