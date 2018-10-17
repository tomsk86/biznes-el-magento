# biznes-el-magento
Projekt z biznesu elektronicznego.

Moja konfiguracja:
- używam MAMP na macu, na windows możecie użyć jakiegoś WAMP albo sami skonfigurować localhosta
- MySQL v.5.7.23
- PHP v. 7.1.20

Login do admina w magento: magentoAdmin
Hasło: Biznesprojekt123

Link do panelu admina: adres_domowy/admin


1. Pobieramy repo git clonem.
2. Wchodzimy w terminalu do folderu magento2.
3. Wpisujemy "composer install --ignore-platform-reqs". Jak nie mamy composera to możemy go zainstalować np w ten sposób
https://www.abeautifulsite.net/installing-composer-on-os-x
4. Ustawiamy nasz folder w localhost na nasze magento2 albo żeby ścieżka wskazywała na ten folder (najlepiej domyślnie żeby
wskazywała na ten folder np localhost:8080).
5. Tworzymy w np PHPMyAdmin nazwę bazy "magento2" i importujemy plik database.sql
6. Kopiujemy plik env.php do folderu magento2/app/etc.
7. Wchodzimy na naszego localhosta i powinno działać.
