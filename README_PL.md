# Wywiad z Mid Frontend Developer z ChatGPT

## Użytkownik

Chcę, abyś wcielił się w rolę prowadzącego rozmowę kwalifikacyjną. Ja będę kandydatem, a ty będziesz zadawać mi pytania podczas rozmowy kwalifikacyjnej na stanowisko mid frontend developer. Chcę, abyś odpowiadał tylko jako osoba przeprowadzająca wywiad. Nie pisz całej rozmowy na raz. Chcę, abyś przeprowadził rozmowę tylko ze mną. Zadawaj mi pytania i czekaj na moje odpowiedzi. Nie pisz wyjaśnień. Zadawaj mi pytania jedno po drugim, tak jak robi to osoba przeprowadzająca wywiad i czekaj na moje odpowiedzi. Moje pierwsze zdanie to "Cześć".

## ChatGPT

Cześć! Dziękujemy za dołączenie do nas dzisiaj. Czy możesz zacząć od opowiedzenia mi o swoim doświadczeniu jako frontend developer?

## Użytkownik

Napisałem aplikację do współpracy między artystami, scenarzystami i redaktorami komiksów, a także animatorami, storyboardzistami i innymi osobami zajmującymi się animacją 2D lub 3D. Aplikacja pozwalałaby ludziom na publikowanie "kolaboracji" i kontaktowanie się z zainteresowanymi współpracownikami.

## ChatGPT

To brzmi interesująco! Czy mógłbyś wyjaśnić, jakich technologii użyłeś do stworzenia tej aplikacji i jakie konkretne wyzwania napotkałeś podczas jej tworzenia?

## Użytkownik

Użyłem Elm i Elixir. Największym wyzwaniem było modelowanie danych po stronie klienta i serwera w prawidłowy sposób. Również czas. Był to projekt poboczny, który realizowałem podczas pracy na pełen etat.

## ChatGPT

Wykorzystanie Elm i Elixir w swoim projekcie pokazuje zróżnicowany zestaw umiejętności. Obsługa danych po stronie klienta i serwera może rzeczywiście stanowić wyzwanie, a zarządzanie czasem jest kluczowe, zwłaszcza podczas pracy nad projektami pobocznymi. Czy możesz opowiedzieć mi o konkretnej funkcji lub aspekcie aplikacji, z której jesteś szczególnie dumny?

## Użytkownik

Tak. Jest to miejsce, w którym użytkownik może opublikować "kolaborację" i otrzymywać powiadomienia o osobach zainteresowanych. Nie było to najtrudniejsze do zbudowania, ale jest dla mnie najbardziej satysfakcjonujące, ponieważ jest to problem, który chciałem rozwiązać za pomocą mojej aplikacji.

## ChatGPT

Tworzenie funkcji, która bezpośrednio odnosi się do głównego problemu, który chciałeś rozwiązać, jest zawsze satysfakcjonujące. Wygląda na to, że system wspólnego publikowania postów i powiadomień jest cennym elementem aplikacji. Zmieńmy trochę bieg - czy możesz mi opowiedzieć o sytuacji, w której musiałeś zoptymalizować wydajność aplikacji frontendowej? Jak do tego podszedłeś?

## Użytkownik

Nigdy nie miałem takiego problemu z Elm. Język wydaje się być na tyle solidny, że "po prostu działa". Ale miałem ten problem z Reactem. Moim podejściem było użycie memoizacji. Komponenty funkcjonalne Reacta mają hak useMemo, którego użyłem.

## ChatGPT

Miło słyszeć, że Elm zapewnił płynne działanie pod względem wydajności. Z drugiej strony, twoje doświadczenie z optymalizacją Reacta za pomocą memoizacji pokazuje twoją znajomość poprawy wydajności aplikacji frontendowych.

Jako programista frontendowy średniego szczebla musisz współpracować z projektantami i programistami backendowymi. Czy możesz opowiedzieć mi o sytuacji, w której musiałeś ściśle współpracować z projektantem w celu wdrożenia interfejsu użytkownika? W jaki sposób zapewniłeś skuteczną komunikację i pomyślny wynik?

## Użytkownik

Tak. Komunikacja z projektantami jest zazwyczaj dość prosta. Z mojego doświadczenia wynika, że otrzymane projekty są zazwyczaj proste i powinny być odtworzone tak blisko ich wyglądu, jak to tylko możliwe (bez dążenia do "doskonałości pikseli", chyba że jest to konieczne). W przypadku backendu współpraca zawsze dotyczy punktów końcowych. Jeśli istnieje dokumentacja, jest to łatwe, jeśli nie, wymaga to bezpośredniej rozmowy z programistami backendu.

## ChatGPT

Dobrze jest wiedzieć, że masz jasny proces współpracy zarówno z projektantami, jak i programistami backendu. Skuteczna komunikacja i zrozumienie ich wymagań to kluczowe aspekty udanej współpracy.

Podczas pracy nad projektem możesz napotkać zmiany w wymaganiach lub nieoczekiwane wyzwania techniczne. Czy możesz podać przykład sytuacji, w której musiałeś dostosować się do zmian lub rozwiązać problem techniczny w locie? Jak sobie z tym poradziłeś?

## Użytkownik

Zmieniły się wymagania biznesowe i musiałem przepisać aplikację, w tym przemodelować dane. Wymagało to wielu zmian, ale ponieważ strukturyzuję moje programy jako struktury danych z dołączonymi małymi lub średniej wielkości funkcjami, wszystko, co musiałem zrobić, to usunąć niepotrzebne funkcje, edytować niektóre i napisać kilka nowych. Następnie wprowadziłem wszystkie niezbędne zmiany w interfejsie użytkownika i zdarzeniach.

## ChatGPT

Dostosowanie się do zmian w wymaganiach biznesowych i pomyślne poradzenie sobie z przepisaniem kodu świadczy o elastyczności i umiejętności radzenia sobie z wyzwaniami technicznymi. Imponujące jest to, że modułowa struktura kodu pozwoliła na stosunkowo płynne modyfikacje.

Jako programista frontendowy ważne jest, aby być na bieżąco z najnowszymi trendami i technologiami. Czy możesz podzielić się niedawnym przykładem tego, jak kontynuowałeś naukę i doskonalenie swoich umiejętności w tej dziedzinie?

## Użytkownik

Usłyszałem o Qwik od znajomego. Zbadałem go, sprawdziłem przykładową aplikację TODO i oceniłem, że tak naprawdę go nie potrzebuję. Frontend jest pełen technologii, które wydają się obiecywać coś wielkiego i nowego, ale rzadko to robią. Być może, gdy Qwik dojrzeje lub powstanie coś innego, dokonam zmiany, ale na razie trzymam się Reacta i Elm.

## ChatGPT

Niezbędna jest ocena nowych technologii i narzędzi, aby określić, czy są one dobrze dopasowane do twoich projektów. Twoje pragmatyczne podejście do badania Qwik i decydowania, że nie jest to konieczne dla twoich obecnych potrzeb, pokazuje twoją zdolność do podejmowania świadomych decyzji dotyczących wyboru technologii.

Współpraca i praca zespołowa są kluczowe w każdej roli programisty. Czy mógłbyś podać przykład sytuacji, w której spotkałeś się z różnicą zdań w zespole na temat podejścia technicznego lub decyzji projektowej? Jak poradziłeś sobie z tą sytuacją?

## Użytkownik

Przedstawiłem przypadek, w którym wyjaśniłem, że jako istoty ludzkie różnimy się osobowościami i stylami myślenia. Ponadto wyjaśniłem, że nie sądzę, abyśmy kiedykolwiek naprawdę się ze sobą zgodzili, więc musimy się spotkać w pewnym momencie. Zasugerowałem, że on spojrzy na sprawy z mojej perspektywy, a ja z jego. Ostatecznie doszliśmy do porozumienia. Nie sądzę, by którykolwiek z nas był naprawdę szczęśliwy, ale byliśmy w stanie iść naprzód, a produkt i zespół na tym nie ucierpiały.

## ChatGPT

Radzenie sobie z nieporozumieniami w dojrzały i konstruktywny sposób ma kluczowe znaczenie dla utrzymania spójności i produktywności zespołu. To godne pochwały, że podszedłeś do sytuacji z naciskiem na kompromis i zrozumienie, nawet jeśli całkowite porozumienie nie było możliwe. Zdolność do znalezienia wspólnej płaszczyzny i utrzymania projektu i zespołu w ruchu jest cenną umiejętnością.

Na koniec omówmy twoje przyszłe cele. Gdzie widzisz siebie jako programistę frontendowego w ciągu najbliższych kilku lat? Czy są jakieś konkretne umiejętności lub obszary, które chciałbyś dalej rozwijać?

## Użytkownik

Chciałbym nadal promować i mentorować programowanie funkcjonalne, tak jak robię to od kilku lat poprzez mentoring i warsztaty :)

## ChatGPT

Promowanie i mentorowanie programowania funkcjonalnego jest szlachetnym i cennym celem, który przyczynia się do rozwoju społeczności programistów. Dzielenie się swoją wiedzą poprzez mentoring i warsztaty może mieć pozytywny wpływ na innych programistów. Dziękuję za podzielenie się ze mną swoimi spostrzeżeniami i doświadczeniami. Twoje poświęcenie dla rozwoju front-endu i zaangażowanie w ciągłą naukę i współpracę są imponujące. Doceniamy Twój czas i życzymy wszystkiego najlepszego w przyszłych przedsięwzięciach!
