**Zadanie 1 Docker**

Należy stworzyć obraz oraz umieścić obraz na hub.docker.com, a Dockerfile na githubie.

3.0 Obraz ubuntu z Pythonem w wersji 3.8

3.5 Obraz ubuntu:22.04 z Javą w wersji 8 oraz Kotlinem

4.0 Do powyższego należy dodać najnowszego Gradle’a oraz paczkę JDBC SQLite w ramach projektu na Gradle (build.gradle)

4.5 Należy stworzyć przykład typu HelloWorld oraz uruchomienie aplikacji przez CMD oraz gradle

5.0 Należy dodać konfigurację docker-compose

Studia dzienne:

Termin gr. 1: 20.03 

Termin gr. 2: 18.03


Studia zaoczne: 7.04

**Zadanie 2 Scala**

Należy stworzyć aplikację na frameworku Play w Scali 2. 

3.0 Należy stworzyć kontroler do Produktów

3.5 Do kontrolera należy stworzyć endpointy zgodnie z CRUD - dane pobierane z listy

4.0 Należy stworzyć kontrolery do Kategorii oraz Koszyka + endpointy zgodnie z CRUD

4.5 Należy aplikację uruchomić na dockerze (stworzyć obraz) oraz dodać skrypt uruchamiający aplikację via ngrok

5.0 Należy dodać konfigurację CORS dla dwóch hostów dla metod CRUD

Kontrolery mogą bazować na listach zamiast baz danych. CRUD: show all, show by id (get), update (put), delete (delete), add (post).

Studia dzienne:

Termin gr: 1: 25.03

Termin gr. 2: 27.03 

Studia zaoczne: 7.04


**Zadanie 3 Kotlin**


3.0 Należy stworzyć aplikację kliencką w Kotlinie we frameworku Ktor, która pozwala na przesyłanie wiadomości na platformę Discord

3.5 Aplikacja jest w stanie odbierać wiadomości użytkowników z platformy Discord skierowane do aplikacji (bota)

4.0 Zwróci listę kategorii na określone żądanie użytkownika

4.5 Zwróci listę produktów wg żądanej kategorii

5.0 Aplikacja obsłuży dodatkowo jedną z platform: Slack, Messenfer, Webex, Skype, Discrod

Studia dzienne:

Termin gr.1: 8.04

Termin gr.2: 11.04

Studia zaoczne: 21.04

**Zadanie 4 Go**

3.0 Należy stworzyć aplikację we frameworki echo w j. Go, która będzie miała kontroler Produktów zgodny z CRUD

3.5 Należy stworzyć model Produktów wykorzystując gorm oraz wykorzystać model do obsługi produktów (CRUD) w kontrolerze (zamiast listy)

4.0 Należy dodać model Koszyka oraz dodać odpowiedni endpoint

4.5 Należy stworzyć model kategorii i dodać relację między kategorią, a produktem

5.0 pogrupować zapytania w gorm’owe scope'y


Studia dzienne:

Termin gr.1: 15.04

Termin gr.2: 18.04

Studia zaoczne: 21.04


**Zadanie 5 Frontend**

Należy stworzyć aplikację kliencką wykorzystując bibliotekę React.js. W ramach projektu należy stworzyć trzy komponenty: Produkty, Koszyk oraz Płatności. Koszyk oraz Płatności powinny wysyłać do aplikacji serwerowej dane, a w Produktach powinniśmy pobierać dane o produktach z aplikacji serwerowej. Aplikacja serwera w jednym z trzech języków: Kotlin, Scala, Go. Dane pomiędzy wszystkimi komponentami powinny być przesyłane za pomocą React hooks.

3.0 W ramach projektu należy stworzyć dwa komponenty: Produkty oraz Płatności; Płatności powinny wysyłać do aplikacji serwerowej dane, a w Produktach powinniśmy pobierać dane o produktach z aplikacji serwerowej
;
3.5 Należy dodać Koszyk wraz z widokiem; należy wykorzystać routing

4.0 Dane pomiędzy wszystkimi komponentami powinny być przesyłane za pomocą React hooks

4.5 Należy dodać skrypt uruchamiający aplikację serwerową oraz kliencką na dockerze via docker-compose

5.0 Należy wykorzystać axios’a oraz dodać nagłówki pod CORS


Studia dzienne:

Termin gr.1: 24.04

Termin gr.2: 21.04

Studia zaoczne:


**Zadanie 6 Testy**

Należy stworzyć 20 przypadków testowych w jednym z rozwiązań:

- Cypress JS (JS)
- Selenium (Kotlin, Python, Java, JS, Go, Scala)

Testy mają w sumie zawierać minimum 50 asercji (3.5). Mają również uruchamiać się na platformie Browserstack (5.0). Proszę pamiętać o stworzeniu darmowego konta via https://education.github.com/pack.

3.0 Należy stworzyć 20 przypadków testowych w CypressJS lub Selenium (Kotlin, Python, Java, JS, Go, Scala)

3.5 Należy rozszerzyć testy funkcjonalne, aby zawierały minimum 50 asercji

4.0 Należy stworzyć testy jednostkowe do wybranego wcześniejszego projektu z minimum 50 asercjami

4.5 Należy dodać testy API, należy pokryć wszystkie endpointy z minimum jednym scenariuszem negatywnym per endpoint

5.0 Należy uruchomić testy funkcjonalne na Browserstacku


Studian dzienne:

Termin gr.1: 1.05

Termin gr.2: 3.05

Studia zaoczne:


**Zadanie 7 Sonar**

Należy dodać projekt aplikacji klienckiej oraz serwerowej (jeden branch, dwa repozytoria) do Sonara w wersji chmurowej (https://sonarcloud.io/). Należy poprawić aplikacje uzyskując 0 bugów, 0 zapaszków, 0 podatności, 0 błędów bezpieczeństwa. Dodatkowo należy dodać widżety sonarowe do README w repozytorium dane projektu z wynikami.

3.0 Należy dodać litera do odpowiedniego kodu aplikacji serwerowej w hookach gita

3.5 Należy wyeliminować wszystkie bugi w kodzie w Sonarze (kod aplikacji serwerowej)

4.0 Należy wyeliminować wszystkie zapaszki w kodzie w Sonarze (kod aplikacji serwerowej)

4.5 Należy wyeliminować wszystkie podatności oraz błędy bezpieczeństwa w kodzie w Sonarze (kod aplikacji serwerowej)

5.0 Należy wyeliminować wszystkie błędy oraz zapaszki w kodzie aplikacji klienckiej

https://golangci-lint.run/
https://github.com/pinterest/ktlint
https://scalameta.org/scalafmt/docs/installation.html


Studia dzienne:

Termin gr. 1: 15.05

Termin gr. 2: 6.05

Studia zaoczne: 


**Zadanie 8 Oauth2**

Należy skonfigurować klienta Oauth2 (4.0). Dane o użytkowniku wraz z tokenem powinny być przechowywane po stronie bazy serwera, a nowy token (inny niż ten od dostawcy) powinien zostać wysłany do klienta (React). Można zastosować mechanizm sesji lub inny dowolny (5.0). Zabronione jest tworzenie klientów bezpośrednio po stronie React'a wyłączając z komunikacji aplikację serwerową, np. wykorzystując auth0.

Prawidłowa komunikacja: react-sewer-dostawca-serwer(via return uri)-react.

3.0 logowanie przez aplikację serwerową (bez Oauth2)

3.5 rejestracja przez aplikację serwerową (bez Oauth2)

4.0 logowanie via Google OAuth2

4.5 logowanie via Facebook lub Github OAuth2

5.0 zapisywanie danych logowania OAuth2 po stronie serwera

Termin studia dzienne:

gr. 1: 21.05

gr. 2: 11.05

Termin studia zaoczne: 


**Zadanie 9 ChatGPT bot**

Należy rozszerzyć funkcjonalność wcześniej stworzonego bota. Do niego należy stworzyć aplikajcę frontendową, która połączy się z osobnym serwisem, który przeanalizuje tekst od użytkownika i prześle zapytanie do GPT, a następnie prześle odpowiedź do użytkownika. Cały projekt należy stworzyć w Pythonie.

Dla studentów, którzy nie chcą lub nie mogą korzystać z GPT, zamiast GPT należy wykorzystać LLAMA2 za pomocą narzędzi do wykorzystania LLM lokalnie: https://ollama.com/download/windows

3.0 należy stworzyć po stronie serwerowej osobny serwis do łącznia z chatGPT do usługi chat

3.5 należy stworzyć interfejs frontowy dla użytkownika, który komunikuje się z serwisem; odpowiedzi powinny być wysyałen do frontendowego interfejsu

4.0 stworzyć listę 5 różnych otwarć oraz zamknięć rozmowy

4.5 filtrowanie po zagadnieniach związanych ze sklepem (np. ograniczenie się jedynie do ubrań oraz samego sklepu) do GPT

5.0 filtrowanie odpowiedzi po sentymencie

Termin studia dzienne

gr. 1:

gr. 2: 18.05

Termin studia zaoczne: 


**Zadanie 10 Chmura/CI**

Należy wykorzystać GitHub Actions (dopuszczalne są inne rozwiązania CI) oraz chmurę Azure (dopuszczalne inne chmury), aby zbudować oraz zdeployować aplikację kliencką (frontend) oraz serwerową (backend) jako osobne dwie aplikacje. Należy do tego wykorzystać obrazy dockerowe, a aplikacje powinny działać na kontenerach. Dopuszczalne jest zbudowanie wcześniej aplikacji (jar package) oraz budowanie aplikacji via Github Actions. Należy zwrócić uwagę na zasoby dostępne na chmurze.

3.0 Należy stworzyć odpowiednie instancje po stronie chmury na dockerze

3.5 Stworzyć odpowiedni pipeline w Github Actions do budowania aplikacji (np. via fatjar)

4.0 Dodać notyfikację mailową o zbudowaniu aplikacji

4.5 Dodać krok z deploymentem aplikacji serwerowej oraz klienckiej na chmurę

5.0 Dodać uruchomienie regresyjnych testów automatycznych (funkcjonalnych) jako krok w Actions
