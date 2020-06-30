# WAX Protocol White Paper Value Proposition - Swedish Translation


> **August 30, 2019**

By William Quigley, CEO, WAX | Jonathan Yantis, COO, WAX | Lukas Sliwka, CTO, WAX | Malcolm CasSelle, Strategic Advisor, WAX

Translated By GreenEOSIO Team together with help from external partners. (June 30, 2020)

**PLEASE NOTE: THE CRYPTOGRAPHIC TOKENS REFERRED TO IN THIS WHITE PAPER REFER TO TOKENS CREATED ON THE WAX PROTOCOL BLOCKCHAIN. THEY DO NOT REFER TO THE ERC-20 TOKENS DISTRIBUTED IN THE PRIOR TOKEN GENERATION EVENT.**

Copyright © 2019 WAX, Worldwide Asset eXchange
 
*Disclaimer. This WAX Protocol White Paper Swedish Version is for information purposes only and expected to have mistakes. We do not guarantee the accuracy of the white paper and is translated “as is” from the original English version. WAX does not make and expressly disclaims all representations and warranties, express, implied, statutory or otherwise, whatsoever, including, but not limited to: (i) warranties of merchantability, fitness for a particular purpose, suitability, usage, title or noninfringement; (ii) that the contents of this white paper are free from errors and omissions; and (iii) that such contents will not infringe third-party rights. WAX and its affiliates shall have no liability for damages of any kind arising out of the use, reference to, or reliance on this white paper or any of the content contained herein, even if advised of the possibility of such damages. In no event will WAX or its affiliates be liable to any person or entity for any damages, losses, liabilities, costs or expenses of any kind, whether direct or indirect, consequential, compensatory, incidental, actual, exemplary, punitive or special, for the use of, reference to, or reliance on this white paper or any of the content contained herein, including, without limitation, any loss of business, revenues, profits, data, use, goodwill or other intangible losses or unrealized savings.*

If you see any mistakes in the translation or the text, please create a pull request and we will handle it accordingly. Thanks for your understanding!

**Contents**

<!-- TOC -->

- [Värdeproposition för WAX blockkedja](#solution-the-value-proposition-of-wax)
- [Vad är W.A.S.P. strategin](#what-is-the-wasp-strategy)
- [Hur fungerar WAX-plattformen?](#how-the-wax-platform-works)
  - [WAX-protokollblockkedja](#wax-protocol-blockchain)
    - [Konsensusmodell](#consensus-model)
    - [WAX Token modell](#wax-token-model)
      - [WAX  Insatsbelöningar](#wax-staking-rewards)
      - [Vilka funktioner kan jag utföra genom att satsa min WAX?](#what-functions-can-i-perform-by-staking-my-wax)
      - [Hur tjänar jag belöningar för WAX-insatser genom att satsa mina WAX-tokens?](#how-do-i-earn-wax-staking-rewards-by-staking-my-wax-tokens)
      - [WAX Guilds och WAX Guild Belöningar](#wax-guilds-and-wax-guild-rewards)
    - [WAX Kärna Prestanda Metrik](#wax-core-performance-metrics)
    - [Delegerad Proof of Stake (DPoS)](#delegated-proof-of-stake-dpos)
    - [Bysantisk feltolerans](#byzantine-fault-tolerance)
    - [Guilds, blockproducenter, satsning och röstning - förbättrade funktioner för styrning](#guilds-block-producers-staking-and-voting---enhanced-governance-features)
      - [WAX Guilds](#wax-guilds)
      - [Standby Guilds](#standby-guilds)
      - [WAX Insatsbelöningar som en lösning för väljarapati](#wax-staking-rewards-as-a-solution-for-voter-apathy)
      - [WAX Insatsbelöningar](#wax-staking-rewards-1)
      - [Insatsbelöningar är baserat på prestanda / påföljder för underprestanda](#staking-rewards-are-based-on-performance--penalties-for-underperformance)
    - [Genesis Block-medlemsbelöningar](#genesis-block-member-rewards)
    - [Deflation / Inflation](#deflation--inflation)
    - [Transaktioner](#transactions)
      - [Providing Cost Efficiency in Terms of Fee Elimination](#providing-cost-efficiency-in-terms-of-fee-elimination)
    - [Smarta kontrakt + RNG](#smart-contracts--rng)
      - [WAX Slumptalsgenerator smarta kontrakt - Random Number Generator (RNG)](#wax-random-number-generator-rng-smart-contract)
      - [Hur WAX RNG naturliga blockkedje-tjänst löser viktiga problem](#how-wax-rng-native-blockchain-service-solves-important-problems)
  - [NFT Standarder / NFT Integrering med WAX ExpressTrade](#nft-standards--nft-integration-with-wax-expresstrade)
  - [Arbetarförslagssystem (Worker Proposal System)](#worker-proposal-system)
    - [Varför behöver vi WWPS?](#why-do-we-need-the-wwps)
    - [Föreslagit WWPS-kategorier](#proposed-wwps-categories)


<!-- /TOC -->


# Värdeproposition för WAX blockkedja 
WAX-plattformen löser ett problem för företag och entreprenör som vill tjäna pengar och delta i den snabbt växande globala marknaden för digitala varor. Den globala marknaden för digitala varor fortsätter att expandera eftersom människors tid och uppmärksamhet fortsätter att gå till online-former av underhållning, som videospel, sociala medier, filmer, musik och digitala böcker. Dessutom förväntas över miljarder människor få tillgång till internet under de kommande fem åren.


# What is the W.A.S.P. Strategy
WAX blockkedja använder **W.A.S.P.** strategin för att göra det möjligt för decentraliserade applikationer (dApps) att bygga och växa snabbt. **W.A.S.P.** strategin består av:

**W**AX blockkedja +

decentraliserad marknadsplats (liknande **A**mazon) +

decentraliserad handel och produktion av digital varor (liknande **S**team) +

decentraliserad konto (liknande **P**ayPal)

WAX blockkedja erbjuder en token-baserad ekonomi som arbetar med nätverksresurser, leverantörer och konsumenterna av dessa resurser. På detta sätt betalar ekosystemet sig självt, och deltagarna styr dess utveckling och drar fördel direkt av dess tillväxt.

WAX microservice-skikt levererar alla funktioner som krävs av en marknadsplats för att skala och växa utan massiva investeringar i infrastruktur och utveckling.

Vi beskriver hela WAX-plattformen, WAX-protokoll, blockkedje-funktioner och microservice-skiktet i nästa avsnitt.


# Hur fungerar WAX-plattformen?
Med kombinationen av WAX-protokollblockkedja och microservice-skiktet ger WAX-plattformen kunderna en komplett svit blockkedjebaserade verktyg. WAX-plattformen är säker och bekväm för att skapa, köpa, sälja och handla virtuella varor till vem som helst, var som helst.


<a id="markdown-wax-protocol-blockchain" name="wax-protocol-blockchain"></a>

## WAX protokollblockkedja 


<a id="markdown-consensus-model" name="consensus-model"></a>

### Konsensusmodell
WAX använder en delegerad Proof of Stake (DPoS) konsensusalgoritm som förlitar sig på en grupp av WAX-guilder (även kända som blockproducenter) för att hantera blockproduktion.  


<a id="markdown-wax-token-model" name="wax-token-model"></a>

### WAX Token modell 
WAX Token-modellen är utformad för att driva flera aktiviteter till att utöka WAX-ekosystemet: insatser, belöningar och röstning.


<a id="markdown-wax-staking-rewards" name="wax-staking-rewards"></a>

#### WAX  insatsbelöningar
WAX Staking Rewards is the voting and rewards system we designed to increase community participation in the selection of guilds and blockchain improvement proposals. Here is what token holders can do with their WAX Tokens:

1.  **Satsade WAX Tokens** Om tokenägare har icke-satsade WAX-tokens måste de satsa dem med en Lynx, Sqrl, Scatter eller en annan kompatibel wallet. Genesis WAX-protokolltoken är automatiskt satsade.  

2.  **Rösta via en kompatibel wallet.** Om tokenägare har Genesis WAX-protokolltokens i ett WAX Blockkedja-konto, måste de ansluta sin kompatibla wallet till kontot för att rösta. Alla ägare av WAX-tokens kan rösta på upp till 30 WAX-guilder. Styrkan i deras röst för varje guild beror på antalet WAX-tokens de insats. 

3.  **Tjäna WAX insatsbelöningar.** WAX tokenägare som satsat sina tokens och sedan röstar med dem tjänar ytterligare WAX-tokens. Dessa intäkter kallas WAX insatsbelöningar (WAX Staking Rewards) och ges ut direkt från WAX-blockkedjan.

dApp-utvecklare kan också dra nytta av att satsa sina WAX-tokens eftersom det hjälper till att reservera systemresurser (CPU och nätverk). RAM-allokering kan köpas och säljas för att möta utvecklarens behov. Insatsmekanismen och WAX insatsbelönings-kombinationen möjliggör transaktioner utan avgift. Vi debiterar inte dApp-utvecklare för att köra infrastrukturen som möjliggör bearbetning av transaktioner på grund av Guild Rewards. Så genom att satsa tokens, kan dApp utvecklare allokera nödvändigt RAM. Det förhindrar också nätverksskräp från att låsa ut legitima transaktioner eftersom alla är hastighetsbegränsade och baserade på deras tilldelning.


<a id="markdown-what-functions-can-i-perform-by-staking-my-wax" name="what-functions-can-i-perform-by-staking-my-wax"></a>

#### Vilka funktioner kan jag utföra genom att satsa min WAX?
WAX tokenägare som satsat sina tokens kan rösta på WAX-blockkedjan och tjäna WAX insatsbelöningar för att göra det. Tokenägare måste rösta varje vecka för att bibehålla den starkaste röststyrkan och tjäna maximala belöningar (hitta mer information om röststyrkan i nästa avsnitt). Det finns tre typer av omröstningar om WAX:

-   **Guildröstning:** Satsa ett fast belopp av WAX-tokens att rösta för guilder. Till exempel, om du satsar 1000 WAX-tokens, kan tokenägare tilldela 1000 röster vardera för upp till 30 olika guildkandidater.

-   **Proxy-omröstning:** Ange en fullmakt, som sedan röstar på uppdrag av tokenägare med deras satsade WAX, som ger dem WAX insatsbelöningar. Om en fullmakt inte röstar påverkar det inte tokenägarnas röststyrka. De måste däremot hålla sina röster uppdaterade för att behålla full röststyrka som liknar Guild röstning.

-   **Arbetarförslagets röstning (lansering efter mainnet):** Insats av WAX-tokens för att rösta för förslag som läggs fram av andra WAX token ägare.


<a id="markdown-how-do-i-earn-wax-staking-rewards-by-staking-my-wax-tokens" name="how-do-i-earn-wax-staking-rewards-by-staking-my-wax-tokens"></a>

#### Hur tjänar jag belöningar för WAX-insatser genom att satsa mina WAX-tokens?
Tokenägare kan tjäna fler WAX tokens varje dag med WAX insatsbelöningar bara genom att rösta. Varje dag avsätts ett fast antal WAX-tokens för WAX insatsbelöningar. Antalet tokens som varje WAX-token ägare får dagligen beror på deras insatsvikt, i förhållande till andra ägare. Om till exempel en tokenägares insatsvikt är 0,5% av den sammanlagda insatsvikten på en dag, får de 0,5% av WAX insatsbelöningar-beloppet. Väljarens aktuella insatsvikt bestämmer mängden WAX-insatsbelöningar som de kan tjäna.

![Voter's stake weight determines the amount of WAX Staking Rewards given to them](media/voters-stake-weight-calculation.png)

-   **Insatsvikt** är antalet WAX-tokens som för närvarande satsade multiplicerat med röststyrka.

-   **Röststyrka** är ett tal mellan 0 och 1, till exempel 0,08 eller 0,25, där 1 är full styrka. Om en token ägare röstar varje vecka, behåller de högsta möjliga röststyrka. Om de inte röstar varje vecka minskar deras röststyrka. Insatsvikten börjar på och återstår på 0 tills de röstar, då det ökar till 1.

Till exempel, om en token ägare röstar i en viss vecka, är deras röststyrka då 1. Om de inte röstar igen, då deras röststyrka förfaller tills den når noll. De kan öka den tillbaka till 1 bara genom att rösta.

![Voter strength](media/voter-strength.png)

Därför maximerar röstningen WAX insatsbelöningar. Dessutom bidrar tokenägare till urvalet av kvalitetguilds och förslag - som stödjer WAX-blockkedjans hälsa.


<a id="markdown-wax-guilds-and-wax-guild-rewards" name="wax-guilds-and-wax-guild-rewards"></a>

#### WAX Guilds och WAX Guild Belöningar
WAX-blockkedjan har 21 WAX-guilder som tjänar belöningar för att producera block. Dessa WAX Guild-belöningar beviljas baserat på antalet block som produceras av varje WAX Guild. Standby Guilds, eller reservera guilder, fungerar som "backupoperatörer" som tjänar en del av WAX Guild-belöningar för att delta och visa sin förmåga att bearbeta ett block när slumpmässigt begärs.


<a id="markdown-wax-core-performance-metrics" name="wax-core-performance-metrics"></a>

### WAX Kärna Prestanda Metrik 
WAX-blockkedjan producerar ett block exakt var 0,5 sekund, och en WAX Guild är behörig att producera ett block i taget. Om ett block inte produceras vid den schemalagda tiden hoppas blocket för den tidsrymden över. Transaktionerna kvar i minnespoolen väntar på nästa guild att inkludera dem. Liknande blockkedjor har uppnått 3000 transaktioner per sekund, vilket överstiger de genomsnittliga transaktioner per sekund som Visa behandlar med nästan 2x. WAX kan uppnå samma hastighet och som sådan är WAX en av de snabbaste, potentiellt högsta kapaciteten blockkedjor på marknaden.


<a id="markdown-delegated-proof-of-stake-dpos" name="delegated-proof-of-stake-dpos"></a>

### Delegerad Proof of Stake (DPoS)
WAX använder DPoS decentraliserade konsensusalgoritm för att optimera prestanda för applikationer på blockkedja. DPoS optimerar också det nominella villkoret för 100% deltagande av ärliga noder med robusta nätverksanslutningar. Incitament för WAX Guilds hjälpa till att hålla dem ärliga, vilket resulterar i trovärdighet i nätverket. Annars riskerar WAX Guild att förlora sin position i nätverket och gå miste om att tjäna WAX Guild-belöningar. 

DPoS är säkert inför korruptionen hos en betydande minoritet av producenterna. Token-ägare kan välja WAX Guilds genom ett kontinuerligt godkännande röstningssystem. För att få möjlighet att producera blocks kan tokenägare övertala andra tokenägare att rösta på dem.

Var 0,5 sekund produceras block på WAX-blockkedjan, och en WAX Guild får tillstånd att producera ett block vid en viss tidpunkt. Om ett block inte produceras vid den schemalagda tiden hoppas block för den tidsrymden över. När ett eller flera block hoppas över, det finns en 0,5 eller mer andra lucka i blockkedja. För att motarbeta överhoppade block, får inte Wax Guilds sina WAX Guild-belöningar om de producerar 50% eller mindre av sina schemalagda block.


<a id="markdown-byzantine-fault-tolerance" name="byzantine-fault-tolerance"></a>

### Bysantisk feltolerans
[Bysantinsk feltolerans (BFT)](https://en.wikipedia.org/wiki/Byzantine_fault) uppnås genom en regel som starkt avskräcker WAX Guilds från att signera två block på samma blockhöjd eller tidsstämpel. Eftersom en central myndighet inte kontrollerar blockkedjor utgör frånvaron av BFT en risk för att en peer-överföring och publicerar falska transaktioner, vilket upphäver blockkedjans tillförlitlighet. I första hand, skyddar BFTs mot katastrofala fel och mildrar påverkan av dessa skadliga noder.

Alla WAX Guild-signering av två block på samma block höjd eller tidsstämpel kommer sannolikt röstas ut av WAX Token-ägare. Femton guilds som signerar ett block gör ett block permanent och oföränderligt.


<a id="markdown-guilds-block-producers-staking-and-voting---enhanced-governance-features" name="guilds-block-producers-staking-and-voting---enhanced-governance-features"></a>

### Guilds, blockproducenter, satsning och röstning - förbättrade funktioner för styrning


<a id="markdown-wax-guilds" name="wax-guilds"></a>

#### WAX Guilds
WAX Blockkedja har 21 WAX-guilder vid en viss tidpunkt, varvid ett guild väljs för att producera ett block vid en schemalagd tid. De 21 WAX Guilds väljs för att producera block i omgångar av 126, baserat på sex block för var och en av dessa 21 WAX Guilds. WAX Token-ägare rösta på WAX Guilds för att avgöra vilka kvalificerade guilds som blir en del av topp 21. De som röstar på WAX Guilds som missar block är motiverade att rösta ut dessa producenter ut eftersom missade block resulterar i missade belöningar.



<a id="markdown-standby-guilds" name="standby-guilds"></a>

#### Standby Guilds
Standby guilds är avgörande för att säkerställa ett robust nätverk med maximal block-produktionskapacitet. WAX fördelar 1% av alla block som skall produceras av standby guilds. Dessa block får tilldelas på ett pseudorandom sätt till standby guilds. Till skillnad från EOS, där vem som helst kan representera sig själva som en standby block-producent, har WAX en annan strategi. I WAX ekosystem, är standby guilds  tvungna att upprätthålla 24/7 upptid eftersom de inte kan förutsäga när de är tilldelade att producera ett block. Det gör det också möjligt att rösta på standby guild-medlemmar.

Det kände vi igen att EOS inte har någon mekanism för att avgöra om alla producenter kvalificerar sig för att producera block. Om till exempel en reservproducent av lägre kvalitet röstas in kanske den här tillverkaren inte kan producera sina tilldelade blocks, vilket resulterar i lägre prestanda. Denna standby producent skulle fortfarande få en del av blockbelöningen. EOS blockproducenter och standby-producenter delar 0.75% inflation baserat på antalet röster de får. Det är sannolikt att ge incitament för lägre kvalitet producenter att marknadsföra sig själva som producent utan att ha tillräcklig kapacitet för blockproduktion.

För att hantera detta använder WAX blockkedja tre mekanismer:

-   WAX standby-guilder måste bevisa sin förmåga att producera block som skall ingå i poolen med 57 kvalificerade guilds (21 WAX Guilds + 36 standby-guilds).

-   Som med WAX Guilds, WAX kan standby-guilder  straffas om de inte kan producera minst 50% av de block som tilldelats dem.

-   Eftersom insats-incitamentet blir bunden till guild-prestandan, blir WAX Token-ägare mer ekonomiskt motiverade att rikta sina röster till WAX Guilds med högre prestanda WAX Guilds.


<a id="markdown-wax-staking-rewards-as-a-solution-for-voter-apathy" name="wax-staking-rewards-as-a-solution-for-voter-apathy"></a>

#### WAX Insatsbelöningar som en lösning för väljarapati
Väljarapati är ett bekymmer för DPoS-blockkedjor eftersom andra DPoS-blockkedjor har påverkats negativt av bristande röstning. Systematiskt låga röstningshastigheter på en kedja förhindrar decentralisering, som kedjan var utformad för. Vi utvecklade WAX Insatsbelöningar för att driva samhällets intresse för röstningsprocessen. WAX Token-ägare som satsar sina WAX Tokens och rösta på WAX Guilds får dessa insatsbelöningar.


<a id="markdown-wax-staking-rewards" name="wax-staking-rewards"></a>

#### WAX Insatsbelöningar
WAX Token-ägare som satsat sina tokens och sedan röstar med dem tjänar ytterligare WAX tokens. Dessa intäkter kallas WAX Insatsbelöningar (WAX Staking Rewards) och ges ut direkt från WAX Blockkedja.

dApp utvecklare kan också dra nytta av att satsa sina WAX-tokens eftersom det hjälper till att reservera systemresurser (CPU och nätverk). RAM-allokering kan köpas och säljas för att möta utvecklarens behov. Insatsmekanismen och WAX Insatsbelöningar-kombinationen möjliggör transaktioner utan avgift. Vi debiterar inte dApp-utvecklare för att köra infrastrukturen som möjliggör bearbetning av transaktioner på grund av Guild Rewards. Så genom att satsa tokens, kan dApp-utvecklare allokera nödvändigt RAM. Det förhindrar också nätverksskräp från att låsa ut legitima transaktioner eftersom alla är hastighetsbegränsade och baserade på deras tilldelning..


<a id="markdown-staking-rewards-are-based-on-performance--penalties-for-underperformance" name="staking-rewards-are-based-on-performance--penalties-for-underperformance"></a>

#### Insatsbelöningar är baserat på prestanda / påföljder för underprestanda
För att motivera WAX Token-ägare att rösta för WAX Guilds av högsta kvalitet för att producera blocks, är WAX Insatsbelöningar bundna till WAX Guilds prestanda. Om en WAX Guild som en WAX Token-ägare röstade för underpresterar, minskar deras WAX Insatsbelöningar:

![WAX Staking Rewards decrease](media/math3.jpg)


WAX Insats Belöningar skalas av resultatet av WAX Guilds väljarna rösta på:

![WAX Staking Rewards are scaled by the performance of the WAX Guilds voters vote for](media/math2.jpg)


Funktionen för att bestämma en väljares WAX Insats Belöningar andel:

![he function to determine a voter’s WAX Staking Rewards proportion](media/math1.jpg)


Därför, om token-ägaren röstar för WAX Guilds som endast producerar 90% av block som är schemalagda för dem, är väljarens WAX Insatsbelöningar 90% av det minsta möjliga beloppet. Om väljaren röstar för WAX Guilds som producerar 50% eller mindre av block som planeras till dem, får väljaren inte WAX Insatsbelöningar i utbyte mot att rösta för dem. Dessa guilder som producerar 50% eller mindre av sina schemalagda block får inte heller betala sina WAX Guild-belöningar.

Formeln gäller även Standby Guilds. Det betyder att omröstningen för en Standby Guild får samma potentiella belöning som rösterna för ett guild som har blivit en av de 21 (dvs. en WAX Guild). Det gör väljaren agnostisk till huruvida en guild som väljaren röstar för sannolikt (eller inte) kommer att vara en av de 21 WAX Guilds. Vi vill att innehavare av WAX-tokens ska rösta för den guild som de tror bäst representerar dem, utan att bli straffad.

En väljare kan ge fullmakt för en en röst till alla som röstar för underpresterande WAX Guilds. I så fall WAX Insatsbelöningar för dem som röstar på underpresterande WAX Guilds få minskat eftersom deras belöningar beräknas baserat på WAX Guilds som hamnar få utvalda. En fullmakt kan inte uppdatera en väljares röstvikt när dess röster för väljarnas fördel. Istället måste väljarna uppdatera sin röst för den fullmakt den väljer att återfå full röstvikt-kapacitet och full WAX Insatsbelöningar-kapacitet.


<a id="markdown-genesis-block-member-rewards" name="genesis-block-member-rewards"></a>

### Genesis Block-medlemsbelöningar
Som en del av ‘WAX Token Swap’ skapade vi **Genesis Block Member (GBM)** programmet. Brett samhällsdeltagande är viktigt för en välfungerande delegerat proof of stake (DPoS)-blockkedja. GBM programmet är utformat för att motivera och belöna våra långsiktiga WAX medlemmar som deltar i WAX blockkedjor hälsosamma utveckling.

För att motivera token ägare att hålla sina tokens investerade med WAX, har vi utvecklat Genesis Block-medlemsbelöningarprogrammet. GBM deltagare får dagliga tokenbelöningar i 3 år (1 juli 2019 till 1 juli 2022). WAX Tokens som intjänats från WAX Token Swap, WAX Guild Belöninga och Insats Belöningar är alla kvalificerade till GBM tokens.

-   Genesis WAX protokoll Tokens fortsätter att producera WAX protokoll Token GBM belöningar varje dag så länge de förblir satsade.

-   Genom att lämna Genesis WAX protokoll Tokens som varit oavbrutet i 3 år dubblar WAX Token ägare sina WAX-protokoll Tokens. Om en WAX Token-ägare upphör att satsa sina WAX Tokens innan tre år har förflutit, fördelas belöningarna proportionellt.

-   Om ett Genesis WAX-protokoll Token är icke satsad, slutar det permanent att producera WAX-protokoll Token GBM belöningar. När detta händer kan det inte ångras.

-   En WAX Token ägare kan när som helst satsa hela eller en del av sina Genesis WAX Protokoll Tokens. Dessa tokens blir WAX-protokoll Tokens och slutar permanent att producera dagliga GBM-belöningar.

-   GBM belöningarna bränns i stället för intjänade, vilket skapar en deflationistisk effekt på token utbudet som nedan.


<a id="markdown-deflation--inflation" name="deflation--inflation"></a>

### Deflation / Inflation
På grund av GBM programmet som beskrivs ovan finns det en 50% deflationspotential från WAX Token Swap, som beskrivs i följande diagram:

| Token Beskrivning                        | Inledande tokenförsörjning |
|------------------------------------------|----------------------------|
| Antal ERC-20 WAX Tokens                  | 1,85 miljarder             |
| Systemresurser                           | 20,000,000                 |
| Pre-minted GBM Tokens för WAX Token Swap | 1,85 miljarder             |
| Max. total utbud (exklusive inflation)   | 3,72 miljarder             |
| Min. total utbud (exklusive inflation)   | 1,87 miljarder             |
| Total potentiell deflation%              | 50%                        |

> **Obs:** Framtida GBM oförtjänta belöningar från icke satsande WAX Tokenägare bränns proportionellt när WAX Tokenägare satsar sina GBM-tokens.

Samtidigt finns det en inflationsmodell från Token-belöningar, som beskrivs i följande diagram:


![Inflation Model Token Rewards](media/inflation-model-token-rewards.png)



<a id="markdown-transactions" name="transactions"></a>

### Transaktioner
För att e-handel ska fungera måste transaktioner vara fria att förhindra flaskhalsar som annars skulle uppstå på grund av avgiftspålägg under tider av prisinflation av tokens och ökad volym. Men med gratis transaktioner, blir skräppost problemet. För att förhindra skräppost på WAX Blockkedja måste transaktionsavsändare satsa systemresurser som krävs för att bearbeta transaktionen. De systemresurser som ska satsas är NET (nätverk), CPU och RAM. Genom att satsa WAX för CPU och NET (bandbredd) får en användare en proportionell andel av de totala blockchain-resurserna, vilket garanterar att transaktioner behandlas i motsvarande takt. 

I en nyligen uppgraderad flyttning av systemresurser för att få en transaktion behandlad från avsändaren till en annan part, till exempel en dApp underhållare. Genom att göra detta underlättas användarna ombord i systemet enkelt eftersom användarna inte behöver förstå insatser för resurser. Beroende på transaktionen kan en kund kräva ägande av ett visst RAM minne. I det här fallet kan kunden köpa mer RAM från en WAX Blockkedja marknadsplats som byter WAX mot RAM enligt Bancor algoritmen.



<a id="markdown-providing-cost-efficiency-in-terms-of-fee-elimination" name="providing-cost-efficiency-in-terms-of-fee-elimination"></a>

#### Tillhandahålla kostnadseffektivitet när det gäller eliminering av avgift
WAX erbjuder en gratis, flexibel plattform för att skicka transaktioner där kunderna inte betalar för transaktioner. Tanken bakom denna mer enkla användnings politik är att skapa en högre grad av antagande. Det är också möjligt för organisationer, företag och utvecklare att skapa ett brett utbud av intäktsstrategier.



<a id="markdown-smart-contracts--rng" name="smart-contracts--rng"></a>

### Smarta kontrakt + RNG
Kontrakt i verksamheten är tänkt att säkerställa ett avtal mellan parterna om en viss tjänst eller att uppfylla en uppsättning standardkrav. Kontrakt är en uppsättning villkor eller regler som båda parter måste följa. Så länge dessa krav uppfylls är genomförande möjligt.

WAX smarta kontrakt är liknande på det att de ger en struktur för skyldigheter mellan alla deltagare att behandla finansiella transaktioner på WAX Blockkedja. WAX smarta kontrakt genomförs när uppsättningen av villkor eller regler uppfylls, men dokumenten för laglig överföring och aktivitet lagras på WAX Blockkedja med öppenhet.

WAX smarta kontrakt finns på ett WAX konto och har en etikett med 12 tecken, som kan läsas av människor och som väljs av kontots skapare. Inom WAX-ekosystemet kan alla konton skicka åtgärder till andra konton där transaktionen hanteras av den smarta kontraktskoden som finns på målkontot. Flera konton kan ta emot flera åtgärder för en enda transaktion.

WAX smarta kontrakt definierar:

-   Skyldigheter

-   Parametrar

-   Nödvändiga åtgärder

-   Informationsstruktur

-   Gränssnittskod



<a id="markdown-wax-random-number-generator-rng-smart-contract" name="wax-random-number-generator-rng-smart-contract"></a>

#### WAX Slumptalsgenerator smarta kontrakt - Random Number Generator (RNG)
I generiska termer, är en slumptalsgenerator (RNG) en algoritm som genererar slumpmässiga värden. I blockkedje-termer använde dApp utvecklarer RNGs att införa ett slumpmässigt resultat , till exempel att generera en digital samlarobjekt eller NFT. För närvarande integrerar slumpmässiga värden i smarta kontrakt processfel, som skapar potentiella vektorer för orättvisa eller icke slumpmässiga värden, vilket minskar kundens förtroende för att använda dApps.  

De **tre** huvudproblemen som utvecklarna upplever när de försöker generera och ta in slumpmässiga värden i sina dApps inkluderar:  

1.  Blockkedje naturliga RNG tjänster finns inte, vilket lämnar dApp utvecklare att bygga sina egna. Detta minskar tiden som dApp utvecklarna kan spendera på andra områden i sina dApps, till exempel design och funktioner som skulle förbättra kundupplevelsen.

2.  Det är inte ovanligt att de flesta dApp utvecklare inte är experter med RNG, så det finns designbrister med de flesta dApp-specifika RNG tjänster. 

3.  Ibland har dApp kunder svårt att avgöra om en dApps RNG tjänst genererar ett slumpmässigt resultat eller inte, vilket minskar kundernas förtroende.


<a id="markdown-how-wax-rng-native-blockchain-service-solves-important-problems" name="how-wax-rng-native-blockchain-service-solves-important-problems"></a>

#### Hur WAX RNG naturliga blockkedje-tjänst löser viktiga problem
Den i öppen källkod WAX RNG naturliga Blockkedje-Tjänst tillåter dApp-utvecklare enkelt integrera tjänsten i sina dApps. Vi valde[Signidice algorithm](https://github.com/gluk256/misc/blob/master/rng4ethereum/signidice.md) och [RSA](https://en.wikipedia.org/wiki/RSA_(cryptosystem)) verifiering för den här tjänsten eftersom:

-   **Signidice algorithm:** Utmärkt randomisering, icke spelbara egenskaper, renare arbetsflöde för dApp utvecklare och bevisligen rättvis.

-   **RSA verification:** Säkerställer unik signatur och tar bort möjligheten att manipulera resultaten. OBS: om du använder andra typer av signeringsalgoritmer kan det tillåta många giltiga signaturer för samma signeringsvärde, vilket kan resultera till manipulation. 

Den självverifierande WAX RNG Naturlig Blockkedja Tjänst bekräftar att RSA signaturen som kommer tillbaka från WAX RNG oraklet är giltig och autentisk innan den används av dApp. När dApp kunder snabbt kan upprätta rättvisa har de ett högre grad av förtroende för att använda dApp.


<a id="markdown-nft-standards--nft-integration-with-wax-expresstrade" name="nft-standards--nft-integration-with-wax-expresstrade"></a>

## NFT Standarder / NFT Integrering med WAX ExpressTrade
WAX stöder icke-fungibel tokens med hjälp av öppen källkod-standarden [Simple Assets](https://github.com/CryptoLions/SimpleAssets). WAX ExpressTrade utnyttjar WAX Blockkedja via en microservice som kallas WAX-On för att generera, mynta och lagra NFTs som den hanterar. Med detta har vi WAX-On-microservice:

1.  Alla användare ser sina transaktioner på kedjan.

2.  Kunder kan bevisa sig själva att de har valts för slumpmässiga val rättvist.

3.  dApp-utvecklare har tillgång till en stor användarbas av OPSkins kunder.

4.  Tjänsten utnyttjar NFT-implementering med öppen källkod.

Fullständig integrering med andra NFT standarder som dGoods på EOS, Ethereum och Tron är en del av färdplanen. Interoperabilitet maximerar likviditeten för köpare och säljare och är det viktiga värdet proposition av WAX-protokollet.


<a id="markdown-worker-proposal-system" name="worker-proposal-system"></a>

## Arbetarförslagssystem (Worker Proposal System)
WAX Worker Proposal System (WWPS) är ett föreslaget program som är utformat för att motivera och kompensera samhällets utvecklare som bygger på WAX Blockkedja. WWPS skulle tilldela WAX Tokens (denominerade i WAX Tokens och betalas i WAX Tokens) för att delas ut till utvecklare som arbetar med samhällets behov, patchar och uppgraderingar. I utbyte mot sin tid och ansträngning som bidrar till utvecklingen av WAX, skulle dessa utvecklare bli berättigade att få WAX Tokens från WWPS.

En procent (1%) WAX årliga inflationen skulle finansiera WWPS och skulle inte vara berättigade till GBM Belöningar, för att uppmuntra till aktiv distribution av medel till utvecklare.


<a id="markdown-why-do-we-need-the-wwps" name="why-do-we-need-the-wwps"></a>

### Varför behöver vi WWPS?
WAX har flera förbättringar att göra, och vissa önskade funktioner saknas fortfarande. I blockchains decentraliserade natur finns det inte tillräckligt med incitament för samhällsutvecklare att spendera sin tid på att bidra med patchar och uppgraderingar som behövs för effektiva och skalbara framsteg.

För att se till att WAX förblir uppdaterat med samhällets förändrade behov kommer vi snart att införa ett arbetsförslagssystem (WPS). Den planerade WPS kommer att möjliggöra en fördelning av medel för att reservera för att incitament utvecklare att arbeta med samhällets behov, till exempel kritiska patchar eller framåtblickande uppgraderingar. Tanken bakom WPS är att utnyttja styrkorna hos ett decentraliserad samhälle framöver, vilket minskar beroendet av en enda källa för nya tillägg. WPS skulle också göra det möjligt för samhället att vårda och växa verktyget.


<a id="markdown-proposed-wwps-categories" name="proposed-wwps-categories"></a>

### Föreslagit WWPS-kategorier
1.  **Övervakning:** Stödjer den underliggande kodbasen för blockkedja, som inkluderar säkerhetsrevisioner, Distribuerad denial of Service (DDoS) -skydd, felpatcher och underhåll av mainnet-arkiv.

2.  **Infrastruktur:** Stödjer den underliggande kodbasen för blockkedja, som inkluderar säkerhetsrevisioner, Distribuerad denial of Service (DDoS) skydd, felpatcher och underhåll av mainnet arkiv.

3.  **Samhället:** Stödjer resurser och utrymmen som samlar människor, till exempel möten, utbildningsinnehåll och plattformar, PR, advokater, förespråkare och lobbyister. 

4.  **Utveckling:** Stödjer utvecklare och idéer, till exempel dApps och applikationer som kan vara nödvändiga för underserverade minoriteter.

5.  **Miscellaneous:** Stödjer swag, bränning och projekt som kanske inte passar in i andra kategorier.

En procentandel av WWPS medlen skulle allokeras till varje kategori samtidigt som de ser till att de är rätt fördelade. Däremot fonden skulle behov övervakning för att granska förslagen och för att undvika eventuella missbruk.
