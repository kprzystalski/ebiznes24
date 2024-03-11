**Zadanie 1 Docker**

Należy stworzyć obraz Dockerowy  na bazie debianowej dystrybuji (bez zainstalowanych paczek javy, kotlina, itp.) oraz zainstalować kotlina, go lub scalę. Należy również dodać narzędzia do budowania np. sbt, gradle, odpowiednio do języka. Na tym obrazie powinien być również klint do statycznej analizy kodu w Kotlinie.

3.0 obraz ubuntu z Pythonem w wersji 3.8

3.5 obraz ubuntu:22.04 z Javą w wersji 8 oraz Kotlinem

4.0 do powyższego należy dodać najnowszego Gradle’a oraz paczkę JDBC SQLite w ramach projektu na Gradle (build.gradle)

4.5 stworzyć przykład typu HelloWorld oraz uruchomienie aplikacji przez CMD oraz gradle

5.0 dodać konfigurację docker-compose


Termin gr. 1: 20.03 
Termin gr. 2: 18.03


**Zadanie 2 Scala**

Należy stworzyć aplikację na frameworku Play w Scali 2. 

3.0 Należy stworzyć kontroler do Produktów

3.5 Do kontrolera należy stworzyć endpointy zgodnie z CRUD - dane pobierane z listy

4.0 Należy stworzyć kontrolery do Kategorii oraz Koszyka + endpointy zgodnie z CRUD

4.5 Należy aplikację uruchomić na dockerze (stworzyć obraz) oraz dodać skrypt uruchamiający aplikację via ngrok

5.0 Należy dodać konfigurację CORS dla dwóch hostów dla metod CRUD

Kontrolery mogą bazować na listach zamiast baz danych. CRUD: show all, show by id (get), update (put), delete (delete), add (post).


Termin gr: 1: 25.03
Termin gr. 2: 27.03 
