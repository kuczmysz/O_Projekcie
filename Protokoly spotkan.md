# Protokoły spotkań

## Agenda na najblższe spotkanie 
Zbieramy tematy na najbliższą telekonferencje dla zespołu OpenPKW Mobile tj: **20.04.2015 godz. 19:00** Będę wdzięczny za akceptację schematu data, [autor],[status],[treść]* 


* 20.04.2015. Czy na pewno usuwamy przycisk Zamknij ? Bo gdy go usuniemy to zapewne musimy dodać jeszcze jeden "Sheet" do aplikacji  "Czy na pewno chcesz wyjść ?  z buttonami TAK/NIE - pomijam kwestie, że i tak musimy zapewne taki Sheet dodać
* 16.04.2015. Zastanowić się kiedy przeprowadzić szkolenie z draw.io, dillinger i github 
* 16.04.2015. Zastanowić się gdzie umieścić "Credits" z naszymi nazwiskami w aplikacji i w jakiej formie ( link do www czy w samej App)
* 14.04.2015. Zaprezentowanie dodatkowych wymyślonych przez czlonków zespołu features`ów i usprawnień dla budowanej przez nas App oraz przedstawienie uwag do wysłanego PaperBrowser



## Aktualna lista ToDo: 
Aktuala lista ToDo zawiera wszystkie aktualnie otwarte pozycje. Nazewnictwo: **data-nr: [odpowiedzialny] [status ], [opis]**. 


* 14.04.2015-2 [All] [Pending] Przemysleć koncepcje Paper Browser - Zaproponować nowe kolejne zmiany i innowacje
* 14.04.2015-3 [Rafał] [Pending] Napisac User Stories, które przekształcą sie w taski developerskie

* 14.04.2015-4 [Rafał] [Pending] załozyć liste dyskusyjną mobilki@openpkw.pl
* 14.04.2015-5 [Rafał] [Pending] Wysłać Oficialne Pismo z prośbą do Panstwowej Komisji Wyborczej o udostepnienie ok 27500 namiarów na Obwodowe Komisje Wyborcze na najbliższe wybory Prezydenckie 2015 w trybie informacji jawno-publicznej - Plik CSV ( gmina, teryt, lokal, adres, Nr komisji w gminie, ilośc uprawnionych do głosowania )
* 16.04.2015-6 [Michal] [Pending] Ile można zawrzeć danych ( ilość ) w kodzie QR i czy jeden kod QR trzeba by zastosować na pojedynczą i kolejną strone protokołu wyborczego 



##16.04.2015 20:00
Format: Telekonferencja / Skype  
Czas: 120 min.  
Obecni: Michal Urbaniak, Wojciech Radzioch ,Przemek Kislo, Rafal Regula, Marcin Nowowiejski, Radek Majkowski

**Dyskusja**
* Przywitanie  dwóch nowych osób w projekcie i przedstawienie ich backgroud i skillsów 

  *  Marcin -   Android Tester, Kraków
  *  Radek  - WindowsPhone Developer, .Net, C++,  Warszawa

* W wyniku dyskusji udalo sie ustlić i podjac nastepujace decyzje:

 *  Zdecydowalismy się na zrezygnowanie z użycia Codu Captcha w aplikacji 
 *  Usuniemy przycisk Zamknij z ostatniego Paper Browser Sheet  
 *  Dodamy Polityke Prywatnosci i zasady korzystania z aplikacji - na pierwszej stronie aplikacji pod samym Logo
 *  Zrezygnujemy z wprowadzenia przez użytkownika wpisywania powtórnie drugiego maila w celu założenia konta, jednoczesnie dodajac pole komisji wyborczej do,  której sie zgłasza jako wolentariusz w swojej gminie
 *  Dla II Tury wyborów - zmienimy automatycznie Interface Aplikacji przy pomocy API
 *  W przypadku uruchiomienia wewnętrznej aplikacji aparatu fotograficznego uruchomimy go w max dostepnej rozdzielczośći i wielkości ekranu dla danego modelu  telefonu i aparatu fotograficznegio z nim związanego
 
Ustalilismy także, iż aplikacja docelowo w przyszlosci powinna:
 *  W sposob automatyczny rozpoznawać dane z protokołu wyborczego za pomoca OCR bądź tez Kodu QR 
 *  Powinna zostać wyposażona w protokól SSL do enkrycpji i przesylania danych
 

**ToDo zrobione:** 
* 14.04.2015-1 [All] [Done] Proszę o założenie swoich kont na (http:// www.github.com) i podanie mi założonych loginów np na Skype w naszej konferencji skajpowej o nazwie "OpenPKW Mobile"
*  14.04.2015-4 [Rafał] [Done] Załozyć główne repo projektu w Organizacji OpenPKW i ustawić członków zespołu mobile jako contributors ( po otrzymaniu loginów github )

 ##Risk & Issue Log

**Risk & Issue closed:** 

* Ustalilismy, iż po zapisaniu zdjęc w pamieci telefonu bądź na karcie SD - aplikacja w chwili pojawienia się łącza i-net samoczynnie wyśle dane w postaci zdjęc i danych z protokołu  wyborczego z informacją dla użytkownika o przeprowadzonej wysyłce w postaci automatycznej

* Czy wprowadzenie captcha nie wpłynie negatywnie na ilość dodatkowych użytkowników ? i czy jest to istotne z naszego pkt widzenia. Jak to jest w innych tego typu aplikacjach ? - Issue Closed Patrz ----> Rezygnacja z Captcha


##13.04.2015 20:00
Format: Telekonferencja / Skype  
Czas: 120 min.  
Obecni: Kamil Szymczuk, Michal Urbaniak, Wojciech Radzioch ,Przemek Kislo, Rafal Regula 

**Dyskusja**
* Przywitanie nowych osób i przedstawienie backgroud i skillsów poszczególnych członków projektu
  *  Kamil -  Developer Android, Gdansk
  *  Michal -  Developer Android, BackEnd, Java, Bash, Json, Poznan
  *  Przemek -  Developer Android, Json, Bielsko Biała  
  *  Wojtek - Developer Android, Łódż
  *  Rafal - Organizacja, Architektura, PMO, Warszawa
  
* Opis i charakterystyka wyborów w naszym kraju a także prac w obwodowych/lokalnych komisjach wyborczych

* Opis jak skontruowany jest projekt OpenPKW a takze jak ma wyglądać praca i koncepcja działań w OpenPKW Mobile
 *  Wspólne ustalenie nazwy projektu na: OpenPKW_Mobile 
 *  Dyskusja na temat PaperBrowser i opis koncepcji aplikacji 
 * Pomysł dodania Klienta Webowego do zapisu zdjęc Offline bądz dodania feature zapisywania zdjęc w samej aplikacji w przypadku braku dostępu do internetu w danej chwili i w przyszłosci mozliwość wysłania tychże zdjęc gdy połączenie i-net będzie dostępne
 * Do rozważenia pomysł dodania w Apce kodu capcha przy rejestrowaniu nowego użytkownika 
 * Koncepcja zamiany wprowadzenia numerów komisji "z palca" na listę rozwijaną połączoną z geolokalizacją GPS --- > Patrz ToDo nr
14.04.2015-5 [Rafał]
 * Zmiana środowiska developerskiego i obnizenie wymagań DEV do wersji 4.0 Android ( ok 93 % rynku)
 
##Risk & Issue Log

* Czy jak damy mozliwość zapisania zdjęc np na karcie SD bądz w pamięci telefonu użytkownikom, to czy nie spowoduje to ze użytkownicy zapomną nam wysłac te zdjecia ? Przez co mozemy ich nigdy nie otrzymać bądz otrzymamy je w mało racjonalnym czasie ?
* Czy wprowadzenie captcha nie wpłynie negatywnie na ilość dodatkowych użytkowników ? i czy jest to istotne z naszego pkt widzenia. Jak to jest w innych tego typu aplikacjach ?



 

















  


 




 













