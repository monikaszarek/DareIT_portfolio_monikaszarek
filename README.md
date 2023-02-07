# **Task 1**
### *Subtask 1*
###### 4 punkty
### *Subtask 3*
#### Cześć, jestem Monika i wzięłam udział w projekcie, bo chcę zmienić zupelnie swoją ścieżkę zawodową, mieć ciekawe możliwości rozwoju, lepiej zarabiać i udowodnić samej sobie, że techniczny świat jest dla mnie tak samo osiągalny jak dla umysłów ścisłych. 
Liczę na to, że nauczę się testować oprogramowanie, że zostanę pokierowana w razie gdybym się pogubiła, czego nie miałabym, gdybym uczyła się na własną rękę. Mam nadzieję, że uda mi się zmienić pracę, a rodzina jeszcze bardziej nie będzie rozumieć "czym ja się właściwie zajmuję w tej pracy" :D 
###### **Monika**

### *Subtask 4*
Aplikacja [Scouts](https://scouts-test.futbolkolektyw.pl/) polega na zapisywaniu rozgrywek, graczy, ich danych i osiągnięć. 
Interfejs strony jest bardzo prosty, brakuje mu ciekawego layoutu, nie przyciąga wzroku ani nie zatrzymuje użytkownika na dłużej. Być może taki był zamysł, żeby skupić się na danych meczowych. 
# Funkcjonalności aplikacji:
* menu główne po lewej
* gracze po lewej
* zmiana języka po lewej
* funkcja wyloguj po lewej
* ilości meczów, graczy, raportów i akcji w ramkach na górze - nie są interaktywne
* krótki opis i konktakt w ramce poniżej
* dodawanie gracza
* ostatnie aktywności

#### Funkcjonalności są podstawowe i proste. Dodałabym możliwość podejrzenia ilości meczów itp. w ramkach
#### Aplikacja jest intuicyjna i jasno pokazuje gdzie należy kliknąć
# Błędy w formularzu dodawania gracza (moim zdaniem :wink:):
* akceptuje datę urodzenia z przyszłości
* akceptuje ujemną wagę i wzrost
(podobne błędy w dodawaniu meczów)
# Błąd w raporcie
* klikam dodaj raport i przenosi mnie do meczów, nie da się dodać żadnego rapotu 

### *Subtask 5*
[Jira](https://szarek.atlassian.net/jira/core/projects/CPP/board)



# **Task 2**
### *Subtask 1*
[Test casy na podstawie User Story](https://docs.google.com/spreadsheets/d/1rGu57qn0IdWP1_3YaCT3b9rxNTlUJVlFymQebloicxw/edit#gid=0)
### *Subtask 2*
[Test casy na podstawie własnych doświadczeń](https://docs.google.com/spreadsheets/d/1sfz2hqsLsrdWFUQKjtwgV5G_kOTplzmiu4QXpamDY8g/edit#gid=0)
### *Subtask 3*
Dlaczego piszemy test casy?
###### *Po to, żeby można było łatwiej przejść przez te same przypadki po wprowadzonych zmianach przy testach regresji. Ale dla mnie też dlatego, że można bardzo dokładnie "przebadać" stornę czy aplikację, którą się testuje i szybciej zlokalizować rzeczy, które nie zadziałały zgodnie z wytyczną.* 

###### PS. Macie chyba buga w formularzu do wysyłki zadania :wink:
###### Ostatni punkt Subtask 4 jest z gwiazdką, nie da się nic nie zaznaczyć ani wybrać opcji "nie wykonałam" mimo, że jest tylko dla chętnych. Pozostali muszą wybierać niezgodnie z prawdą.
![](https://imgupload.pl/images/2023/01/24/dareitbug.png)



# **Task 3**
### *Subtask 1*
Formatki to jednocześnie linki z subtaska 2
### *Subtask 2*
[Testy 1](https://docs.google.com/spreadsheets/d/1vKMLvCxi0sO3O3yxstgoZ5OXnYVuoZ29bLUyg8ofTi0/edit#gid=0)

[Testy 2](https://docs.google.com/spreadsheets/d/1eUQ28OViTIZt6eofay6IeRoSz7wi9ZEkwDnPD2JWDf8/edit#gid=0)
### *Subtask 3*
[Raport](https://docs.google.com/spreadsheets/d/1PxsP_LTxdmFd-sDnmVwOgs5O36vECdYhYoRAw5kbyeM/edit#gid=0)

# **Task 4**
### *Subtask 2*
###### Dziewczyny, dałyście do przetestowania zbyt dobrze zrobioną apkę :smile:
###### Dlatego zamiast robić formatkę, do błędów, których nie znalazłam, opiszę dwie rzeczy. 

:point_right: <i>Zacznijmy może od specyfikacji. Testowana była aplikacja OLX wersja 5.77.0, aktualizowana przez producenta 31.01.2023r. Testowana na telefonie Xiaomi Redmi Note 11 (2201117TY) 6.02.2023 koło godziny 20 oraz na przeglądarce Chrome wersja 109.0.5414.120</i>

:one: Na początek różnica między aplikacją otwieraną w przeglądarce, a natywną. W tej pierwszej w zakładce "obserwujesz" w polu "obserwowane wyszukiwania" pojawia się ile można mieć takich obserwowanych wyszukiwań (0/50), a w natywnej tego nie ma. W poniższych linkach screeny:

[przeglądarka](http://imgurl.pl/img2/3_63e272b791da9.jpg) 

[apka](http://imgurl.pl/img2/5_63e272b794b1a.jpg)

:two: Pomijając pozycjonowanie i promowanie ogłoszeń, niektóre pojawiają się po kilka razy:

[1](http://imgurl.pl/img2/1_63e272b7863b0.jpg)

[2](http://imgurl.pl/img2/4_63e272b7948a6.jpg)

[3](http://imgurl.pl/img2/7_63e272b794eb2.jpg)

![Alt Text](https://i.pinimg.com/originals/0f/d5/f6/0fd5f629cdfa85f1d99b3797941acc00.jpg)

### *Subtask 3*
<ol>
<li><i>Do czego służy aplikacja, jaki jest jej cel?</i></li>
Aplikacja służy do sprzedawania i kupowania rzeczy i nieruchomości, a także to szukania pracy. Ma na celu pozowolić na szybkie komunikowanie się osób na linii kupujący-sprzedjący / oferujący/szukający.

<li><i>Kto ma być użytkownikiem końcowym aplikacji?</i></li>
Kupujący, sprzedający, wymieniający rzeczy, szukający i oderujący pracę

<li><i>Czy według Ciebie aplikacja jest user friendly?</i></li>
Jak najbardziej. Jest prosta, najważniejsze funkcje są w zasięgu kciuka, użytkownik intiucyjnie się po niej porusza, łatwo znaleźć zakłądkie, których się potrzebuje. Nic nie jest ukryte, trudno dostępne, użytkowanie aplikacji nie irytuje. W podobnie przyjemny sposób korzysta się z webbowej wersji.

<li><i>Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność?</i></li>
Nie lubię poprawiać rzeczy dobrych - a ta taka jest - bo wychodzą z tego często potworki (taki jest mój user experience), które tylko wkurzają. Lepsze jest wrogiem dobrego :wink:

<li><i>Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?</i></li>
Są do siebie mocno podobne. Ma się wrażenie, że różnią się tylko rozdzielczością. Ale z zauważalnych prostych różnić, to w przeglądarce od razu widać wszystkie dostępne kategorie, a w apce trzeba to sobie przewinąć i rozklikać. Najważniejsze funkcje są w apce na dole, a w przeglądarce u góry strony. 
</ol> 
