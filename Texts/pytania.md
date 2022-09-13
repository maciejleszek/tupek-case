# FAQ do praktyk w Łukasiewicz-PIAP

## Pytania natury ogólnej:

* Q: Co robić z materiałami? Czy dobrze robię że wysyłam załączniki mailem?
  * A: Wysyłanie materiałów mailem to zły pomysł. Wselka dokumentacja, ale i pliki robocze w tej czy w innej formie powinny trafiać do repozytorium. Mogą to być dokumenty np. *.docx, ale warto korzystać też z plików *.md (łatwiejszy podgląd), a pliki źródłowe jak wizualizcje i modele 3d zapisywać w repozytorium tak żeby łatwo było do nich sięgnąć i je obejrzeć.
* Q: Ale jak i gdzie mam zadawać pytania?
  * A: Pytania mogą iść mailem :)
* Q: Z kim, w razie problemów, mogę się kontaktować?
  * A: Wysyłac maile z pytaniami/kwestiami na __dwa__ adresy mailowe: jakub.glowka@piap.lukasiewicz.gov.pl, mateusz.macias@piap.lukasiewicz.gov.pl

## Tupek case project:

* Q: dlaczego "Tupek case project"
  * A: "Tupek" to nasza nazwa tego robocika, a "case project" bo to projekt obudowy
* Q: 1.	Znalazłem w internecie parametry podwozia robota https://botland.com.pl/podwozia-robotow/2016-dagu-wild-thumper-6wd-chassis-black-podwozie-6-kolowe-z-napedem-sparkfun-rob-11056-6952581600176.html Czy pokrywają się one z Państwa modelem i oczekiwaniami?
  * A: Wygląda bardzo podobnie. Do sprawdzenia podczas wizyty.
* Q: Czy obudowa ma być jednym elementem?
  * A: Odpowiedź m.in. na to pytanie i uzasadnienie dokonanego wyboru to część pracy, a nie założenie wstępne.
* Q: Czy obudowa ma zakrywać koła robota?
  * A: patrz punkt wyżej.
* Q: Czy coś ma być rozwiązane w ten lub inny sposób i czy to co proponuję jest dobre?
  * Przydzielone zadanie obejmuje zanalizowanie problemu, poszukiwanie rozwiązań i wybór najlepszego z nich i dopiero na końcu jego wykonanie. Do potwierdzenia czy coś jest dobre, potrzebne jest przedstawienie koncepcji rozwiązania oraz argumentów czemu to rozwiązanie jest dobre oraz jaki proces myślowy/projektowy doprowadził do danego rozwiązania.
* Q: Jakie właściwości ma spełniać obudowa? tj. otwory (czujniki, anteny, kamery, oświetlenie, wentylacja podzespołów), opływowość i wzmocnienia konstrukcji (przetłoczenia, grubsze części w pewnych miejscach)
  * A: Obudowa ma:
    * umożliwiać zamontowanie i dostęp do elementów posadowionych na robocie (patrz opis na stronie: https://micro.ros.org/docs/tutorials/demos/thumper_demo/)
    * nie pogarszać znaczaco właściwości jezdnych robota
    * zabezpieczać wrażliwe elementy (elektronikę) przed przypadkowym narażeniem mechanicznym
    * być w miarę trwała - robot służy do testów więc nie chcemy żeby użytkownik musiał się z nim obchodzić "jak z jajkiem"
    * być stosunkowo łatwa w montażu i demontażu
