﻿# Interfejsy-WWW-Projekt
Tematem projektu jest Tablica Ogłoszeń, na której możliwe jest odczytywanie i zapisywanie ogłoszeń. Ogłoszenia zapisywane są w basie danych, i mogą składać się z tekstu oraz istnieje możliwość załączenia załącznika w postaci obrazu (który również przechowywany jest w bazie danych). Back-end projektu napisany został w Pythonie przy pomocy frameworka Django 4.0. Jako baza danych wykorzystywany jest sqllite3. Natomiast przyciągająca oko warstwa wizualna projektu została stworzona przy pomocy narzędzia Bootstrap (wersja 5) oraz dodatkowych plików CSS oraz JS. 
Za nawigację na stronie Notice Board odpowiedzialny jest pasek nawigacyjny na górze strony, gdzie może przejść do:

- strony głównej 
- strony kontaktu z właścicielem strony
- strony logowania (jeżeli nie jesteśmy zalogowani)
- strony rejestracji (jeżeli nie posiadamy jeszcze konta)
- strony z tematami 
  - strona z ogłoszeniami dotyczącymi danego tematu

Na stronie z tematami, można wybrać temat z listy tematów stworzonych przez innych użytkowników, lub dodać rozpocząć własny temat (lecz, aby dodać własny temat należy być zalogowany). Jeżeli chcemy dodać temat nie będąc zalogowani, system przekieruje nas do  strony logowania, dodanie tematu dostępnie jest jedynie po zalogowaniu. 
Na stronie z ogłoszeniami, widnieją ogłoszenia, które użytkownicy dodali do danego tematu (wraz ze zdjęciami) ogłoszenia są sortowane po dacie utworzenia (od najnowszych wpisów do najstarszych). Jeżeli chcemy dodać jakieś ogłoszenie, to podobnie jak w przypadku dodania tematu, należy być zalogowanym na stronie. Jeżeli chcemy dodać ogłoszenie na stronie nie będąc zalogowani, system przekieruje nas do  strony logowania. 
Co więcej, na stronie po zalogowaniu pojawia się możliwość edycji wpisów, których jesteśmy właścicielami, czyli takich które kiedyś dodaliśmy (oczywiście będąc zalogowanym). Edycja wpisu daje nam możliwość zmiany tytułu wpisu, głównego kontentu wpisu oraz dodanie lub usunięcie grafiki do wpisu. 
Za wyszukiwanie tematu jaki interesuje zwyczajnego użytkownika odpowiedziana jest wyszukiwarka tematów, umieszczona na środku w pasku nawigacyjnym. Jeżeli danych temat nas interesuje, po wpisaniu w wyszukiwarkę pojawi się lista tematów skojarzonych z zapytaniem.
