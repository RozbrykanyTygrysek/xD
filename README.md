Komendy Linuxa
Każdą komenda posiada własny opis dostępny poprzez podanie parametru --help, np.
ls --help

lista plików w katalogu
ls

lista plików z właściwościami
ls -l

jeżeli lista katalogów  jest większa niż ekran
ls -l | more

Wyświetlenie bieżącego katalogu (Print Working Directory)
pwd

zmienienie katalogu na domowy użytkownika
cd

przejście do katalogu /var/www/flaga
cd /var/www/flaga

przejście do katalogu wyższego
cd ..

przeście do katalgu głównego
cd /

wyświetlenie pliku xd.py.można używać strzałek góra/dół pageup/pagedown
more xd.py

tworzenie katalogu w bieżącym katalogu testowy_katalog (Make Directory)
mkdir testowy_katalog

tworzenie katalogu w zadanym katalogu
mkdir /var/www/flaga/testowy_katalog

usunięcie pliku
rm test.txt

kopiowanie pliku xd.py xd_kopia.py
cp xd.py xd_kopia.py

zmiana właścieiela/grupy na root dla pliku/katalogu test.txt
chown root test.txt

zmiana uprawnień do pliku, np. nadanie pełnych uprawnień do pliku test.txt dla wszsytkich
chmod 777 test.txtx
0 (---) Brak uprawnień
1 (--x) Wykonywanie (uruchamianie) pliku, dostęp do katalogu
2 (-w-) Zapis
3 (-wx) Zapis i wykonywanie
4 (r--) Odczyt
5 (r-x) Odczyt i wykonywanie
6 (wr-) Odczyt i zapis
7 (rwx) Odczyt, zapis i wykonywanie
w zapisie 777:
Pierwsa cyfra - uprawnienia dla właściciela pliku
Druga cyfra - uprawnienia dla grupy
Trzecia cyfra - uprawnienia dla wszystkich

