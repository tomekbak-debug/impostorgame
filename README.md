# Impostor — gra słowna (1–10 osób)

Prosta gra przeglądarkowa: jedna losowa osoba jest **IMPOSTOREM**, pozostali mają to samo hasło.
Hasło losuje się **dopiero po starcie rundy**, więc nikt nie zobaczy go wcześniej.
Gra działa na telefonie i komputerze (czysty HTML/JS/CSS, bez serwera).

## Jak uruchomić przez GitHub Pages (darmowe)

1. Zaloguj się na [github.com](https://github.com) i utwórz nowe repozytorium, np. **impostor**.
2. Wgraj plik `index.html` (ten z tej paczki) i opcjonalnie `README.md`.
3. Wejdź w **Settings → Pages**. W sekcji **Build and deployment** ustaw:
   - **Source:** *Deploy from a branch*
   - **Branch:** *main* (lub *master*) i folder **/root**
4. Kliknij **Save**. Po chwili dostaniesz adres strony, np.  
   `https://twojanazwa.github.io/impostor/`
5. Ten link możesz wysłać znajomym. Działa w przeglądarce telefonu i komputera.

> Jeśli na Twoim koncie GitHub Pages pokazuje się folder **/docs** zamiast **/root**, wrzuć plik do folderu `docs/` i ustaw ten folder w Pages.

## Alternatywy hostingu
- **Netlify**: przeciągnij `index.html` do dashboardu → dostaniesz link typu `https://impostor.netlify.app`
- **Vercel**: podobnie jak Netlify, świetne do statycznych stron
- **Dowolny hosting statyczny**: wystarczy jeden plik `index.html`

## Jak grać
1. Wybierz liczbę graczy (1–10). Zostaw zaznaczone „Losuj po starcie” (nikt nie zobaczy hasła wcześniej).
2. Kliknij **Rozpocznij rundę** — gracz 1 od razu widzi swoje hasło (albo „IMPOSTOR”).
3. Po przeczytaniu każdy klika **„Przeczytałem – przekażę”**. Ekran chowa się, pojawia się **odliczanie** (domyślnie 5 s), potem słowo widzi kolejny gracz.
4. Po ujawnieniu ról — runda skojarzeń i głosowanie na **IMPOSTORA**.

## Personalizacja
- **Liczba graczy**: 1–10
- **Opóźnienie przekazania**: 3/5/7/10 s
- **Hasła**: wbudowane ~300 propozycji; możesz wpisać własne (odznacz „Losuj po starcie”)
- **Kolejność**: losowa / 1→N / N→1
- **Motyw**: jasny (łatwy do czytania na telefonie)

---

© 2025 — Stworzone na prośbę użytkownika. Miłej zabawy!
