## Wprowadzenie 

Jak wiadomo w serwisie filmweb.pl każdy użytkownik może wystawić danemu filmowi ocenę w skali 1-10. Na podstawie ocen wszystkich użytkowników obliczana jest ważona średnia ocena filmu, która decyduje o pozycji filmu w rankingu. Często zdarza się, że części setne oceny rozstrzygają o lokacie filmu na określonych pozycjach, a spadek oceny o części dziesiętne skutkuje spadkiem o dziesiątki lub setki pozycji w rankingu najwyżej ocenionych pozycji.
Podobnie w serwisie filmweb.pl istnieje baza danych dla osób kina zawierająca oceny wystawiane aktorom i reżyserom za całokształt ich twórczości w skali od 1-10 przez użytkowników serwisu i - jak można się domyślić – ranking najlepiej ocenianych artystów rządzi się podobnymi prawami.
Można zadać pytanie w jakim stopniu popularność, dobór obsady filmu i reżyseria, rozumiana jako osoba reżysera, oddziałują na postrzeganie filmu przez społeczność użytkowników. Niniejsze opracowanie powstało jako próba wyjaśnienia, z wykorzystaniem metod ilościowych w jaki sposób liczba otrzymanych głosów, średnia ocena aktorów grających główne role w filmie oraz ocena reżysera filmu wpływają na całościową ocenę dzieła w oczach społeczności użytkowników, analizując najwyżej oceniane filmy.

### Metodyka i wykorzystane narzędzia

Przedmiotem analizy były średnie oceny 796 filmów wystawione przez użytkowników serwisów, pobrane ze stron filmweb.pl. Baza danych osób kina pobrana została ze strony filmwebu, odfiltrowując osoby, które otrzymały poniżej 100 głosów użytkowników.

Jako średnia ocena aktorów dla danego filmu przyjęta została średnia ocen czterech aktorów grających główne role z bazy danych filmweb.pl.

Bazą wyjściową dla filmów, które zostały wybrane do analizy posłużył ranking "wszechczasów" ze strony imdb.com „Top 1000”. Obejmował on szerszy katalog dzieł niż ranking "top 500" filmwebu.
Aby porównać go z rankingiem Top filmwebu, należało odfiltrować filmy, dla których nie można było wyznaczyć średniej oceny aktorów grających w danym filmie (niektóre filmy, które bywają popularne w serwisie imdb stanowią niszę wśród polskich użytkowników, więc aktorzy z ich obsady nie są popularni w serwisie filmweb, przez co brak wystarczająco licznej próbki głosów do uwiarygodnienia ich oceny). Spośród 1000 najwyżej ocenianych filmów z „Top 1000” dla imdb.com pozostały zatem 796 tytułów do analizy, dla których udało się wyznaczyć średnią oceną aktorów i reżysera dla portalu filmweb.pl.

Bazowa tabela moviedata.csv znajduje się w repozytorium. 

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/huberttt/imdb-filmweb/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
