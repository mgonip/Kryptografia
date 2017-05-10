# Kryptografia
Autorzy: Niesuch, Zecior, Mgonip

Jezyk programowania: Java

Cel: Projekty na zaliczenie przedmiotu "Zaawansowane metody ochrony informacji" 

## Spis treści:
1. Branch master
2. Branch projekt2
3. Wymagane oprogramowanie
4. Instalacja programu
5. Prawa autorskie i licencja

## Branch master:
### Opis:
Realizacja szyfru podstawieniowego przy pseudolosowo generowanym kluczu. Aplikacja szyfruje i deszyfruje wybrany przez użytkownika tekst. Na podstawie szyfrogramów program tworzy jego charakterystykę, a dodatkowo przy wczytaniu odpowiednio długiego tekstu jest w stanie wygenerować statystykę wzorcową w celu wykonania kryptoanalizy. Aplikacja przechowuje wszystkie (bez powtórzeń) użyte klucze w archiwum kluczy.

### Linki:
* [Dokumentacja](https://github.com/mgonip/Kryptografia/tree/master/docs/Dokumentacje)
* [Aplikacja](https://github.com/mgonip/Kryptografia/tree/master/docs/Aplikacja)

## Branch projekt2:
###Opis:
Realizacja szyfrów DES, AES i RC4. Aplikacja szyfruje i deszyfruje tekst użytkownika wybranym przez niego algorytmem. Wersja pozbawiona funkcji generowania statystyki wzorcowej, tworzenia charakterystyki szyfrogramu oraz kryptoanalizy.

### Linki:
* [Aplikacja](https://github.com/mgonip/Kryptografia/tree/master/docs/Projekt2/Aplikacja)

## Wymagane oprogramowanie:
Poza małymi wymaganiami sprzętowymi, niezbędne do działania programu jest oprogramowanie wymienione poniżej: 
* Dowolny system operacyjny 
* Zainstalowana maszyna wirtualną Javy w wersji JRE 7+

## Instalacja programu:
Aby zacząć używać programu wystarczy uruchomić plik o nazwie "kryptografia.jar" / "kryptografia2.jar", 
które dostępne są w sekcji Linki. W celu korzystania z archiwum kluczy należy dodatkowo stworzyć plik tekstowy (jeżeli nie 
istnieje w folderze programu) o nazwie „klucze” z rozszerzeniem *.txt.

## Prawa autorskie i licencja:
Copyright 2015 Niesuch, Zecior, Mgonip, Inc. Kod wydany na licencji [MIT](https://github.com/mgonip/Kryptografia/blob/master/LICENSE.md).
