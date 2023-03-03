# Login System

Lukas Johansson | 2023-03-03

## Inledning

I detta arbete jobbade vi som en grupp för att skapa ett login system till vårt forum som vi har byggt ifrån en guide. Vi gör detta arbete för att lära oss om MYSQL databaser och hur man använder sessions för att skapa profiler för att spara användarens data.

För att få ihop detta system så jobbar vi som en grupp för att kunna dela våra kunskaper och för att få en bättre förståelse för javascript och hur man kan ändra på databasen. Vi har främst jobbat med hur man hämtar information från databasen och hur tar bort eller lägger till information. Detta har vi gjort med hjälp av javascript där req, res, och post har varit olika typer av hämtnings och inlämnings metoder av data.

I detta arbete har vi också använt oss av tester för att se till att system fungerar som det ska och har varit en väldigt stor hjälp till vad som fattas och vad som inte fungerar. Tester fungerar som ett säkerhetsnät så att inga större buggar eller problem ska uppstå. Detta är väldigt viktigt för framtiden och kommer mest troligen vara ett arbetssätt för större arbeten så att man inte råkar lägga till stora bugg som kan förstöra stora system eller databaser. 


## Bakgrund

Vi började med att forka arbetet för att få tag på testerna och en fungerande grund så man slipper göra alla tråkiga start saker.

Sedan var det bara att börja. Vi använde så klart oss av testerna som fanns i uppgiften vilket gav oss en tydligt väg på vad vi skulle lägga till eller fixa. Eftersom testerna var så tydliga så kunde man utan några större problem hitta vad som fattades och vad man faktiskt behöver göra för att det skulle funka vilket ledde till ett arbetssätt där man testade systemet väldigt ofta för att se vad som fattas och vad som fungerade.

Det fanns 4 olika typer av tester dessa är server, login, authentication och registrering. Vilket alla hade olika viktiga delar som första där man behövde så klart sätta upp en databas för att kunna hålla informationen som lösenord och användarnamn som man senare kunna använda för att skapa en profil. Detta ledde senare till att man skapade en login där om man hade sin profil i databasen och skrev in korrekt login information på sidan så skulle man komma till en profilsida som visade på att loginen var korrekt.

Efter att man hade fått det att fungera så gjorde vi en lite jobbigare del vilket var authentications som kollade så att man använder korrekt information och att det till exempel inte kan skapas flera konton med samma användarnamn så att inte databasen blir full av konton med exakt samma namn vilket kan skapa väldigt stora problem om någon till exempel skulle använda samma namn och lösenord. Detta kan leda till att dess första konto blir överskriven eller att ligger över varandra och blir buggade.

Sist men inte minst så gjorde vi registrering delen där man faktiskt kunde lägga till profiler i databasen så man kunde skapa sina egna konton från sidan istället för att manuellt behöva lägga till kontot i databasen. Detta kommer så klart med sina egna problem och lösningar med vi fick det att fungera relativt fort.


## Positiva erfarenheter

Jag tycker att relativt mycket gick bra eftersom vi hade bra kommunikation i gruppen och en tydligt guide eller test för hur vi skulle fortsätta projektet framåt. Även om det var lite svårt ifrån börjar att förstå vad testerna faktiskt sa så tog det inte lång tid innan det klickade till och man förstod vad de skulle användas till och hur man kunde använda testerna för att hjälpa än mer än att den skiter på dig för att du har fel eller missar 72 olika saker. 

Man lärde sig mycket om hur databasen fungerar och hur man kunde mer simpla komman kan ändra databasen och lägga till samt ta bort information vilket kommer spela en viktig roll i framtida projekt och fortsättningen av våra forum. 

Många delar av detta lila projekt fungerade väldigt bra eftersom att diskutera en situation är oftast en av de bästa sätten för att förstå saker och för att komma på olika lösningar.


## Negativa erfarenheter

jag tycker att gruppstorleken kan ha varit lite för stor eftersom vissa medlemmar kunde bara sitta bak och inte riktigt göra någonting medan vissa fick göra väldigt mycket mer. Detta skulle kunna lösas med en mindre gruppstorlek med kanske tre personer för att alla ska får en chans att prata och diskutera projektet.

På Grund av att det är en grupp så blir det så klart vissa som gör mer än andra så specifikt i våran grupp så använde vi oss den visste mest som en hjälp get för att hjälpa resten av gruppen med allt som inte fick att fungera istället för att diskutera som en grupp och komma fram med en lösning tillsammans. Vilket så klart inte är så jätte schysst mot alla medlemmar eftersom man tvingar nästan på en större roll på vissa vilket kan vara väldigt stressande om den personen i fråga inte orkar eller inte riktigt var själv vad svaret är.

Alla dessa negativa saker kan lösas med antingen mindre grupper eller mer personliga arbeten. Båda dessa sätt kommer leda till bättre förståelse och positiva arbetssätt som kommer leda till en bättre produkt och gemenskap.


## Sammanfattning

Själva projektet var väldigt spännande man fick lära sig en hel del nya saker och fick ett fungerande login system som kommer fungera på sin egna forum vilket kommer göra det till ett ännu större och bättre projekt vilket är alltid bra att ha till framtidens cv som en bra lärdom och förståelse av databaser och login system.

Arbetssättet kan nog arbetas på för att få ett bättre få mer inklusion i gruppen och förhoppningsvis en bättre produkt som alla förstår lite bättre och kan diskutera kring. 

Annars så har jag inga riktigt större kritik jag gillade att arbeta i grupp det var skönt att få byta ifrån personligt arbete till att man kan diskutera sina tankar och få hjälp med förståelse då man behöver. Det var ett bra projekt med hjälpsamma tester vilket ledde till en tydligt och säker guide.
