# IT-ISSUES
IT issues

**Technical Debt** - Dług technologiczny - "prowizorka", "pozyczka", która kiedyś trzeba bedzie spłacić. Pierwsze funkcjonalności w projekcie są wprowadzane szybko, realizacja nastepnych trwa dłużej.

**Feature Creep** - Produkt "tonie", ma zbyt wiele funkconalności, ponieważ każdy kilent oczekuje/chce czegoś innego. 

**Death March** - Marsz śmierci - Praca nad projektem, którego nie mozna doprowadzic do końca. W trakcie projektu deadline jest przesuwany, ponieważ nie można zrealizowac załozonych planów. Demotywacja, zwolnienia, wypalenie zawodowe. W Scrumie ważna jest iteracja, po kazdym sprincie mamy działający produkt.

**Software Craftsmanship** - profesjonalizm, techniczna perfekcja i zadowolenie klienta.

**Conway's Law** - Prawo Conwaya - organizacje które projektują systemy, budują rozwiązania, które są kopiami struktur komunikacyjnych tych organizacji. Albo inaczej – architektura budowanego rozwiązania będzie izomorficzna do struktury zespołu projektowego. Prawo to jest oparte na obserwacji, że – aby dwa moduły mogły się ze sobą komunikować to – ich **projektanci i programiści muszą się ze sobą skomunikować. Dlatego struktura interfejsów systemu będzie odpowiadała strukturze komunikacji pomiędzy ludźmi, którzy te interfejsy projektują i implementują**.

**DevOps**

**Andon cord** (przycisk) - (fabryka Toyoty) - kazda osoba pracująca nad oprogramowaniem, jest w stanie wstrzymać release. Wszyscy szukają rozwiązania, produkcja jest zatrzymana.

Rollouts
Dark launch

**Product Backlog** - jest listą pracy pozostającej do zrobienia, niezbędnej do wytworzenia produktu. Zawiera on idee, wymagania, błędy oraz dług techniczny w postaci zadań związanych np z refactoringiem kodu. Najwyżej na liście zamieszczone są "itemy" o najwyższym prio. Kryteria priorytezacji: 
1. Wartośc biznesowa, 
2. Zależności - Czasami jest tak, że funkcjonalności zależą od siebie i muszą mieć odpowiednią kolejność z uwagi na wymagania biznesowe, a czasami nie da się ich zrealizować bez zachowania kolejności dyktowanej przez zależności techniczne,
3. Możliwośc wdrożenia.

**Sprint Backlog** - obejmuje on listę zagadnień, którymi w czasie Sprintu zajmował się będzie Zespół aby osiągnąć Cel Sprintu uzgodniony z Właścicielem Produktu. W backlogu tym znajdować się mogą zarówno wymagania, nad którymi Zespół pracuje, błędy do rozwiązania, usprawnienia z ostatniej Retrospekcji czy zadania techniczne związane z narzędziami i praktykami wykorzystywanymi przez Zespół. Ponieważ to Zespół Developerski jest właścicielem Backlogu Sprintu, sam decyduje o jego zawartości i formie. 

**Rebase vs Merge** - jeżeli używamy funkcji merge (jest to opcja domyślna) git stara się rozwiązać wszystkie konflikty i umieszcza nasze zmiany między zmianami innych członków zespołu, porządkując je względem linii czasu. Natomiast gdy używamy opcji rebase git przenosi nasze lokalne zmiany do takiego tymczasowego miejsca i dociąga to co się zmieniło z zdalnego repozytoriom. Po czym każdą naszą lokalną zmianę umieszcza z powrotem na branch na samej górze wszystkich dociągniętych zmian. Mówimy wtedy, że jesteśmy na samej górze HEAD. Można powiedzieć, że HEAD jest czymś w rodzaju takiego znacznika, która wersja jest aktualna. Kiedy na zdalnym repozytorium są zmiany, których jeszcze nie mamy u siebie na komputerze, mówimy że jesteśmy za HEAD (czyli za tym głównym znacznikiem), jak tylko dociągniemy zmiany to będziemy na bieżącym HEAD.
Jeśli chcemy przenieść zmiany z feature branch do master, która jest publiczną gałęzią należy używać komendy MERGE.



