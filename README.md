# Kalendarz Arkadiowy

Plugin do [Arkadia skryptów](https://github.com/tjurczyk/arkadia)
Autor: Monolith

# Instalacja

Wymagane skrypty >= 4.31 aby poprawnie zainstalowac plug-in.

```/zainstaluj_plugin https://codeload.github.com/Monolith18/arkadia-calendar/zip/master```

## Użytkowanie

Skrypt wyswietli predykcje pelni/nowiu/swiat etc.

W Imperium:
* ```/kal``` - wyswietlenie obliczen najblizszej pelni, swiat etc.

W Ishtar:
* ```/kal``` - jesli nie byl zdefiniowany wariant lub byl wyzerowany wyswietli warianty aktualnego miesiaca
* ```/kal 0``` - wyswietli warianty aktualnego miesiaca (zeruje wariant)
* ```/kal xx``` - xx to wariant , ktory ma byc uzyty do obliczen (1 do 5)
* ```lua wyswietl_warianty_ishtar(xx)``` - xx to numer miesiaca, wyswietla zadany miesiac i jego warianty niezaleznie od domeny/aktualnego miesiaca
