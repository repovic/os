**Ukratko napiši šta znaš o registrima?**

Registri su memorijske celije ugradjene u procesor i u njima se nalaze podaci koje procesor trenutno obradjuje. To je najbrza memorija, i obicno je ima jako malo, vreme pristupa je jako kratko.

**Ukratko napiši šta znaš o keš memoriji?** 

Kes memorija sluzi da nadomesti veliku razliku u brzinama izmedju registarske memorije i primarne memorije. Sadrzi delove podataka za koje se pretpostavlja da ce ih procesor cesto koristiti. Sporija je od kes memorije, ali je zbog toga ima vise.

**Ukratko napiši šta znaš o fiksnom particionisanju?** 

Memorija se deli na particije fiksne velicine (staticke particije), svaki proces cija je velicina manja ili jednaka velicini particije moze da se ucita u particiju.

Ako su particije pune dok treba da se izvrsi neki novi proces, operativni sistem izbacuje proces iz neke pune i ubacuje u neki drugi proces.

Postoje dve vrste fiksnog particionisanja: na particije razlicite velicine i na particije iste velicine.

**Ukratko napiši šta znaš o dinamičkom particionisanju?**

Kada se neki proces ucita u memoriju, dodeljuje mu se tacno koliko mu treba. Nastaju rupe na mestima gde se procesi izbace iz memorije. To je lose zbog toga sto postoji deo memorije koji je slobodan, a mozda nije dovoljno veliki da se u njega smesti drugi proces.

**Šta znaš o fragmentaciji?**

Fragmentacija se odnosi na neiskoriscenu memoriju koju sistem ne moze da iskoristi (dodeli procesima). Postoje dva tipa fragmentacije: interna i eksterna

Interna fragmentacija je deo memorije koja je dodeljena datom procesu i ne koristi se od strane tog procesa, taj deo memorije nije paspoloziv za koriscenje drugim procesimasve dok dati proces ne zavrsi sa radom.

Eksterna fragmentacija podrazumeva da postoji deo memorije koji je slobodan, ali nije dovoljno veliki da se u njega smesti proces.

**Šta znaš o straničenju?** 

Stranicenje je jedan od nacina upravljana memorijom koji dozvoljava da memorija, koja je dodeljena procesu, ne bude u jednom komadu.

Glavna memorija je izdeljena na jednake delove fiksne velicine (frames). Memorija potrebna procesu je takodje izdeljena na takve delove.

Proces se ucitava tako sto se za njega nalazi odgovarajuci okvir, a informacije oko okvira cuva tabela stranica.


**Ukratko napiši šta je virtuelizacija?**

Virtuelizacija je tehnologija koja predstavlja kombinaciju hardvera i softvera, koja omogucava da se na istom racunaru pokrece vise razlicitih operativnih sistema koji dele zajednicke resurse.

**Šta je cilj virtuelizacije računarskih sistema? Navedi tehnike virtuelizacije.**

Cilj virtuelizacije racunarskih sistema je postići izolovano izvršavanje nekoliko razlicitih operativnih sistema na jednom fizičkom racunaru.

Tehnike:

\- Potpuna virtuelizacija

\- Hardverski podržana virtuelizacija

\- Para-virtuelizacija

\- Virtuelizacija na nivou operativnog sistema

\- Virtuelizacija aplikacija 

\- Virtuelizacija desktopa

\- Mrežna virtuelizacija

\- Memorijska virtuelizacija

\- Virtuelizacija podataka

\- Virtuelizacija storidža

**Ukratko objasni šta je BIOS i koja je njegova svrha?** 

BIOS (Basic Input / Output System) je low level upravljacki softber ugradjen u trajnu memoriju racunara koji  se pokrece sa pokretanjem racunara.

Osnovna svrha je da inicijalizuje i testira ispravnost hardvera.

**Kako se zove prvi program koji BIOS izvršava i koja je njegova funkacija?** 

Boot Loader, njegova funkcija je da ucita i pokrene operativni sistem/e sa trajne memorije.

**Koja je najčešće korišćena funkcija korisničkog interfejsa BIOS-a (engl. BIOS setup utility) i gde se on uglavnom čuva?** 

Najcesce se koristi za konfigurisanje hardvera, cuva se u Flash Memoriji BIOS-a.




**Ukratko objasni šta se dešava nakon što BIOS završi pokretanje samotestiranja i drugih važnih provera.**

Nakon POST-a, BIOS zapocinje process podizanja (Boot Processing) I pokusava da pronadje Boot Loader program koji ucitava I pokrece operativni sistem sa trajne memorije (pokrece se operativni sistem koji je prvi na Boot Order-u).

**Koje dve datoteke čine jezgro OS Windows?**

NTOSKRNL.EXE

HAL.DLL

**Ukratko objasni šta je Firmware?** 

Firmvare je softverski program koji se najčešće trajno ugrađuje u hardverski uređaj poput

tastature, tvrdog diska, BIOS-a ili video kartica i svrha mu je da omogući komunikaciju s drugim

uređajima i obavlja funkcije poput osnovnih zadataka ulaza / izlaza.

**Koja je najvažnija karakteristika UEFI-a?**

UEFI firmware je mnogo pametniji od BIOS-a. UEFI zna za sve instalirane diskove i instalirane operativne sisteme.
