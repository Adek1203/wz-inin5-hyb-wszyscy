# Zasady współpracy – Przewodnik po stolicach Europy 

Dzięki za zainteresowanie współtworzeniem projektu!  
Poniżej znajdziesz instrukcje, jak możesz się zaangażować i wprowadzać zmiany w ramach zaliczenia przedmiotu **Zarządzanie Projektem Wdrożeniowym**.

---

## Jak zgłaszać zmiany

1. Forkuj repozytorium
2. Sklonuj je na swój komputer
3. Stwórz nowy branch według wzoru: `nazwa_stolicy-twoje_imię`
   - np. `berlin-adrian`
4. Wprowadź zmiany lokalnie (HTML + zdjęcia)
5. Zrób commit i wypchnij (`push`) zmiany na GitHub
6. Utwórz Pull Request (PR) z opisem, co zostało dodane

---

##  Styl commitów

Stosuj jasne, krótkie komunikaty commitów. Przykłady:

- `feat: dodano sekcję Berlin z obrazkiem`
- `fix: poprawiono ścieżkę do obrazka`
- `docs: utworzono CONTRIBUTING.md`

---

##  Nazwy branchy

Używaj nazw zgodnych z celem i strukturą projektu:

- `berlin-adrian` – sekcja dla Berlina, autor Adrian

---

## Struktura plików

- Wszystkie zdjęcia stolic umieszczaj w folderze `img/`
- Edytuj plik `index.html` – każda stolica jako osobna sekcja:
  
```html
<section>
  <h2>Nazwa stolicy</h2>
  <img src="img/nazwa.jpg" alt="Opis stolicy">
</section>
