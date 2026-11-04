# Zasady Współpracy
Dziękuję za zainteresowanie moim projektem. Aby ułatwić współpracę, proszę o przestrzeganie poniższych zasad.

## 1. Przygotowanie projektu
1. Sklonuj repozytorium na swój komupter
```bash
git clone https://github.com/USER/REPO.git
```

2. Przejdź do katalogu projektu
```bash
cd REPO
```

3. Utwórz wirtualne środowisko
```bash
python -m venv .venv
```

4. Aktywuj środowisko i zainstaluj zależności, jeżeli projekt zawiera plik requirements.txt
```bash
.venv\Scripts\Acivate.ps1
```
```bash
pip install -r requirements.txt
```

## 2. Praca z gałęziami
- **NIE WPROWADZAJ** zmian bezpośrednio na gałęzi *main*
- do każdego zadania utwórz osobną gałąź
- stosuj czytelne nazwy gałęzi:
  - feature/add-task - nowa funkcjonalność
  - docs/update-readme - zmiany w dokumentacji

## 3. Zasady pisania kodu
- stosuj czytelne nazwy zmiennych i funkcji
- przestrzegaj podstawowych zasad **PEP 8**
- dodawaj komentarze tam, gdzie wymagane są wyjaśnienia
- nie powielaj kodu (zasada DRY)
- nie pisz kodu na zapas (zasada YAGNI)
- **przed wysłaniem zmian sprawdź, czy program działa poprawnie**

## 4. Commity
Każdy commit powinien zawierać krótki i zrozumiały opis zmian w trybie rozkazującym. Przykłady:
```bash
git commit -m"feat: dodaj zadanie..."
git commit -m"fix: popraw element input"
git commit -m"docs: zaktualizuj readme.md"
```

## 5. Zgłoszenia (Issues)
...

## 6. Pull Requests
...

## 7. Komunikacja w zespole
- szanuj pozostałych uczestników projektu
- informuj zespół o problemach i opóźnieniach
- omawiaj istotne zmiany przed ich wprowadzeniem
- korzystaj z Issue i Pull Request do dyskusji dotyczących projektu

**Dziękujemy za współpracę i wkład w rozwój projektu!**
