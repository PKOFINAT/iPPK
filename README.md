![](https://www.finat.pl/static/front/infosite/img/logo/pko-finat.svg)
# PPK w PKO Finat
PKO Finat oferuje Instytucjom Finansowym narzędzia do obsługi programu PPK w tym między innymi internetową aplikację dedykowaną dla pracodawców. Istnieje kilka możliwości przekazywania danych do Instytucji Finansowych przez pracodawcę:

•	uzupełnienie formularza za pośrednictwem aplikacji dostępnej przez przeglądarki internetowe (iPPK),

•	przesłanie plików "płaskich", również za pośrednictwem aplikacji iPPK,

•	wymiana danych poprzez API Rest.

Możliwość korzystania z API jest konfigurowana na poziomie Instytucji Finansowej, która zarządza PPK w Podmiocie Zatrudniającym.
Założyliśmy profil PKO Finat API na GitHubie po to, aby mogli Państwo łatwiej zgłaszać problemy, zadawać pytania i szukać odpowiedzi w już rozwiązanych wątkach.

# iPPK REST API w PKO Finat
API to usługa sieciowa, która umożliwia wymianę informacji między aplikacją iPPK a oprogramowaniem zewnętrznym. Dzięki niej programiści mogą zintegrować własne rozwiązania z mechanizmami serwisu. W ramach API REST udostępnimy szereg metod, które odpowiadają poszczególnym funkcjom serwisu. Opisaliśmy je w dokumentacji, którą można znaleźć pod [tym adresem](https://www.finat.pl/media_files/2fe2de66-590b-4570-8ed4-889496cde789.pdf). Prosimy o zapoznanie się z nią przed rozpoczęciem integracji z API.
Metody udostępniane przez API:
1.	Kartoteki:

a)	Utwórz uczestnika

b)	Edytuj dane uczestnika

c)	Znajdź uczestnika

d)	Zarejestruj początek zatrudnienia

e)	Zarejestruj koniec zatrudnienia

2.	Dyspozycje:

a)	Zarejestruj dyspozycje

b)	Pobierz listę dyspozycji

c)	Pobierz PDF dyspozycji

d)	Zmień status dyspozycji

3.	Składki:

a)	Załaduj paczkę składek

b)	Pobierz status paczki składek oraz listę błędów

c)	Pobierz listę i szczegóły paczek składek

d)	Pobierz listę składek uczestnika

# Jak zadawać pytania i zgłaszać problemy w GitHubie?

Prosimy o wejście w zakładkę [Issues](https://github.com/PKOFINAT/iPPK/issues) i założenie nowego zgłoszenia. Prosimy Państwa o padanie w zgłoszeniu jak najdokładniejszych informacji, zachowując przy tym bezpieczeństwo danych (**Prosimy o niepublikowanie w zgłoszeniach Kluczy API Pracodawcy i Pracownika oraz Danych Osobowych**)