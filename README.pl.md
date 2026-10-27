<p align="center">
  <img src="assets/banner_minimal.png" alt="Star UI" width="100%" />
</p>

<p align="center">
  <a href="README.md">English</a> &nbsp;|&nbsp; <b>Polski</b>
</p>

<p align="center">
  <a href="https://github.com/debil38/Star-Ui/releases"><b>Pobierz APK</b></a>
  &nbsp;•&nbsp;
  <a href="https://github.com/debil38/Star-Ui/issues">Zgłoś błąd</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/wersja-v0.0.1-black" alt="wersja" />
  <img src="https://img.shields.io/badge/Android-8.0%2B-black" alt="Android" />
  <img src="https://img.shields.io/badge/Kotlin-Jetpack%20Compose-black" alt="Kotlin" />
</p>

---

> ⚠️ **Wersja testowa (pre-release).** Mogą występować błędy, a funkcje mogą się zmieniać.

## Zrzuty ekranu

<p align="center">
  <img src="assets/home_dark.png" width="240" alt="Pulpit motyw ciemny" />
  <img src="assets/drawer_dark.png" width="240" alt="Lista aplikacji motyw ciemny" />
  <img src="assets/drawer_2_dark.png" width="240" alt="Lista aplikacji motyw ciemny" />
  <img src="assets/settings_dark.png" width="240" alt="Ustawienia motyw ciemny" />
  <img src="assets/home_white.png" width="240" alt="Pulpit motyw jasny" />
  <img src="assets/drawer_white.png" width="240" alt="Lista aplikacji motyw jasny" />
  <img src="assets/drawer_2_white.png" width="240" alt="Lista aplikacji motyw jasny" />
  <img src="assets/settings_white.png" width="240" alt="Ustawienia motyw jasny" />
</p>

## Funkcje

- **Pulpit z wieloma stronami** i zapamiętywaniem ostatniej strony
- **Dock** do 5 ulubionych aplikacji
- **Lista wszystkich aplikacji** z wyszukiwarką
- **Wyszukiwarka na pulpicie**: znajdź aplikację lub szukaj w Google
- **Zegar i data** na ekranie głównym
- **Tryb jasny i ciemny** z płynną animacją
- **Jednolite ikony** popularnych aplikacji i monochromatyczny styl reszty
- **Kształt ikon**: koło, squircle lub kwadrat
- **Tapety** osobno dla pulpitu, blokady lub obu naraz
- **Menu po przytrzymaniu ikony**: dodaj na pulpit lub do docka, informacje, odinstaluj
- **Ustawienia**: rozmiar ikon, kolumny, nazwy aplikacji, tryb ciemny

## Instalacja

1. Wejdź w [Releases](https://github.com/debil38/Star-Ui/releases) i pobierz `StarUI.apk`.
2. Zezwól na instalację z nieznanych źródeł, jeśli system o to zapyta.
3. Zainstaluj aplikację i naciśnij **Home**.
4. Wybierz **Star UI** jako domyślny ekran główny.

## Gesty

| Akcja | Efekt |
|---|---|
| Przytrzymanie pustego miejsca | Tapeta, nowa strona, ustawienia |
| Podwójne stuknięcie pustego miejsca | Ustawienia launchera |
| Przytrzymanie ikony | Menu aplikacji |
| Wstecz lub Home | Powrót na pierwszą stronę |

## Wymagania

- Android 8.0 lub nowszy (zalecany Android 14+)

## Testowano na

| Urządzenie | System | Uwagi |
|---|---|---|
| Samsung Galaxy A52s | LineageOS (Android 16) | Działa dobrze, czasami są lagi na liście aplikacji |
| Samsung Galaxy A55 | Oficjalny system Samsunga (One UI) | Działa dobrze |

Testowałeś na innym urządzeniu? Daj znać w [Issue](https://github.com/debil38/Star-Ui/issues).

## Znane problemy

- Czasami lagi przy przewijaniu listy aplikacji na Galaxy A52s.

## Budowanie ze źródeł

1. Zainstaluj [Android Studio](https://developer.android.com/studio).
2. Sklonuj repozytorium:
   ```
   git clone https://github.com/debil38/Star-Ui.git
   ```
3. Otwórz projekt w Android Studio i poczekaj na synchronizację Gradle.
4. Podłącz telefon z włączonym debugowaniem USB i kliknij **Run**.

Dla płynności uruchamiaj wariant **release** (Build → Select Build Variant).

## Ograniczenia

Star UI jest launcherem, więc nie zastępuje paska powiadomień ani ekranu blokady (należą do systemu Android). Widżety systemowe i przeciąganie ikon nie są jeszcze dostępne.

## Plany

- [ ] Przeciąganie i zmiana kolejności ikon
- [ ] Foldery na pulpicie
- [ ] Panel powiadomień i szybkich ustawień
- [ ] Kropki powiadomień na ikonach
- [ ] Gesty i widżety
- [ ] Płynniejsze przewijanie listy aplikacji

## Zgłaszanie błędów

Otwórz [Issue](https://github.com/debil38/Star-Ui/issues) i podaj model telefonu, wersję Androida oraz kroki prowadzące do problemu. Przy wersji testowej każde zgłoszenie bardzo pomaga.
