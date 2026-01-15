# gitHub_user_name_vje-ba_jedan
1. vježba github 
## 1. Što je Visual Studio Code i za što se najčešće koristi?

**Visual Studio Code (VS Code) je lagani, ali moćan editor koda koji podržava mnogo programskih jezika. Najčešće se koristi za pisanje, uređivanje i debugiranje koda, rad s Gitom i upravljanje projektima.**

## 2. Kako se zove panel u kojem vidiš sve datoteke i mape svog projekta?

**Panel se zove Explorer (File Explorer).**

## 3. Kako možeš instalirati ekstenzije u VS Codeu i čemu one služe?

**Ekstenzije instaliraš preko Extensions panela (ikona kvadratića s četiri kockice na lijevoj traci).**
**One dodaju dodatne mogućnosti kao što su:**
**– podrška za nove jezike,**
**– teme,**
**– alati za rad s Gitom,**
**– automatsko formatiranje itd.**

## 4. Kako otvoriti postojeći projekt ili mapu u VS Codu?

**Klikneš File → Open Folder i izabereš željenu mapu.**

## 5. Što se sve može raditi u Exploreru?

**U Exploreru možeš:**
**– pregledavati datoteke i mape,**
**– stvarati nove datoteke/mape,**
**– brisati, preimenovati i premještati datoteke,**
**– brzo otvarati datoteke za uređivanje.**

## 6. Kako možeš brzo pronaći određenu datoteku u projektu?

**Pritiskom Ctrl + P i upisivanjem imena datoteke.**

## 7. Kako možeš istovremeno gledati dvije različite datoteke u editoru?

**Desni klik na datoteku → Open to the Side, ili povučeš tab desno.**

## 8. Kako pokrećeš automatsko formatiranje koda u VS Codeu?

**Pritiskom Shift + Alt + F**
**Ili: Right click → Format Document.**

## 9. Što je version control i zašto se koristi?

**Version control (sustav za upravljanje verzijama) omogućava:**
**– praćenje promjena u projektu,**
**– vraćanje na starije verzije,**
**– kolaboraciju više programera.**
**Najčešći alat je Git.**

## 10. Kako se u VS Codeu otvara panel za Git (Source Control)?

**Klikneš ikonu Source Control (treća ikona na lijevoj traci) ili tipkaš Ctrl + Shift + G.**

## 11. Što znače commit, push, pull?

**Commit – sprema tvoje lokalne promjene u Git povijest.**

**Push – šalje lokalne commitove na GitHub.**

**Pull – preuzima najnovije promjene s GitHuba u tvoj lokalni projekt.**

## 12. Čemu služi commit poruka i kako treba izgledati?

**Commit poruka opisuje što si promijenio.**
**Treba biti kratka, jasna i precizna.**
**Npr.: "Dodana funkcija za izračun prosjeka".**

## 13. Kako možeš vidjeti koje si promjene napravio u pojedinoj datoteci?

**Klikneš na datoteku u Source Control panelu → prikaže se diff (usporedba starih i novih linija).**

## 14. Kreiraš novu datoteku. Koji su koraci da se promjena pošalje na GitHub?

**Napraviti datoteku / promjenu.**

**Otvoriti Source Control.**

**Oznaka će pokazati promjene – kliknuti + (stage).**

**Upisati commit poruku.**

**Kliknuti Commit.**

**Kliknuti Push da pošalješ na GitHub.**

## 15. Kako se vraćaš na stariju verziju datoteke ako si pogriješio?

**U Source Control panelu:**
**– klikneš na datoteku → … → Restore**
**ili koristiš Git naredbe:**
**git checkout -- naziv_datoteke**

## 16. Na koji način možeš provjeriti status projekta i koje datoteke su izmijenjene?

**U Source Control panelu vidiš listu svih izmijenjenih, dodanih i obrisanih datoteka.**
**Možeš i otvoriti terminal i upisati:**

**git status**
Assets – sadrži sve skripte, modele, scene i resurse projekta

Library – cache datoteke koje Unity generira (ne verzionira se)

Logs – zapisnici rada Unity editora

Packages – popis Unity paketa i ovisnosti

ProjectSettings – postavke projekta

UserSettings – lokalne korisničke postavke

.vsconfig – Visual Studio konfiguracija

.gitignore je datoteka u kojoj specificiraš koje datoteke ili direktorije Git treba ignorirati, tj. ne dodavati u verzionirani sustav (repository). To znači da će te datoteke ostati lokalne na tvom računaru i neće biti dijeljene s ostalim suradnicima (ili na GitHubu).

Koje datoteke Unity automatski stavlja u .gitignore?

Unity koristi vlastitu verziju .gitignore datoteke, koja već sadrži mnoge stvari koje ne želimo pratiti u Git-u. Evo nekoliko primjera:

1. Library/ direktorij:

Unity koristi direktorij Library za pohranu svih privremenih datoteka koje su potrebne za rad unutar Unity editora. Ovo uključuje cache, skenirane assete, i privremene postavke.

Zašto ignorirati?

Ove datoteke se automatski generiraju kad pokreneš projekt na svom računaru i nisu korisne drugima jer su specifične za tvoje računalo.

2. Temp/ direktorij:

Temp sadrži privremene datoteke koje Unity koristi za razne operacije (npr. za buildove ili za uređivanje scena).

Zašto ignorirati?

Iako se mogu mijenjati tijekom razvoja, nisu korisne za verzioniranje jer se mogu lako ponovno generirati.

3. Build/ ili slični direktoriji:

Ako koristiš Unity za izgradnju aplikacija (buildove) za različite platforme, ti direktoriji sadrže izgrađene verzije igre ili aplikacije.

Zašto ignorirati?

Build datoteke mogu biti velike i specifične za platformu. Također, uvijek ih možeš ponovno izgraditi iz izvornog koda, tako da nema potrebe da budu u Git repozitoriju.

4. Logs/ direktorij:

Sadrži zapisnike i logove rada Unity editora.

Zašto ignorirati?

Log datoteke ne sadrže korisne informacije za projekt, osim ako ne želiš podijeliti specifične greške u procesu.

5. UserSettings/ direktorij:

Ovdje Unity pohranjuje lokalne postavke korisnika koje se ne dijele među članovima tima (npr. korisničke preferencije).

Zašto ignorirati?

Ove datoteke su specifične za korisnika i ne bi trebale biti u repozitoriju, jer ne utječu na sam projekt.

6. vsconfig (Visual Studio konfiguracijska datoteka):

.vsconfig datoteka se koristi za konfiguraciju Visual Studio okruženja.

Zašto ignorirati?

Ove datoteke su specifične za tvoje razvojno okruženje, a nisu bitne za ostatak tima.
Na kraj README.md dodaj:

Zašto koristimo feature branch?

Zašto je main branch protected?

Što si naučio kroz Pull Request i review proces?

Feature branch omogućuje izolirani razvoj bez ugrožavanja main grane

Protected main sprječava greške i prisiljava code review

Pull Request uči timskom radu, komunikaciji i kontroli kvalitete