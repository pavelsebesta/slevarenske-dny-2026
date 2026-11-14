# Slévárenské dny v éře AI: od přednášek k druhému mozku — výklad po slidech

Pavel Šebesta, Slévárna Kuřim, a.s. · 62. Slévárenské dny, 11. 11. 2026, sekce E

Není to přepis slovo od slova. Ke každému slidu je tu shrnuto, co jsem k němu říkal. Text vznikl ze strojového přepisu nahrávky a z textu slidů; kde se přepis a slide v čísle lišily, platí slide. Samotný text slidů je v souboru `prezentace-prepis.md`.

---

## Slide 1 — Titul

Přemýšlel jsem, jak přednášku postavit, aby neopakovala obecné řeči o AI, které slyšíme ze všech stran: na LinkedInu, ve zprávách, všude. Chtěl jsem ukázat, že AI umí pracovat i jinak a že z ní může vypadnout něco jiného než lži a halucinace. A spojit to se Slévárenskými dny: jak zacházet s informacemi, které si odtud odnášíme.

Telefony nechte v kapse, fotit nic nemusíte. Celou přednášku i další materiály dostanete na konci přes QR kód.

## Slide 2 — Kolik si budete pamatovat za rok?

Včera byl první den, dnes druhý. Otázka je, jak si informace zaznamenáváme, a to nejen ze Slévárenských dnů. Na konferencích o AI to už funguje jinak: lidé si přednášky rovnou ukládají do svých systémů, do „druhých mozků“, a umí s nimi dál pracovat. O tom dnes bude řeč. Nejdřív ale krátká odbočka.

## Slide 3 — AI ve slévárenství: svět

Když se řekne AI ve výrobě, hned se nabízí, že bude řídit výrobu a předpovídat vady. Hledal jsem příklady přímo ze slévárenství. Moc jich zatím není, většinou se srovnáváme s jinými obory. První studie ale existují a čísla vypadají dobře: snížení zmetkovitosti o desítky procent, záchyt vad nad 90 %. (Zdroje jsou na slidu a v článku ve Slévárenských listech.)

Snadno by se řeklo: jdeme do toho, nasadíme to i u nás.

## Slide 4 — Proč se nehrnout: data

Podle mě tudy cesta zatím nevede. Problém jsou data, ať už z MES, nebo z ERP. Myslím, že v žádné z našich sléváren nejsou ve stavu, ve kterém by se na nich dala AI učit.

Příklad zmetkovitosti. Máme informace o tavbě, o chemii, o písku. Máme informace o tom, co jsme zmetkovali a na jakou vadu. Jenže kus, který se vyřadil jako uražený nebo rozplavený, už nikdo dál nezkoumá, takže nevíme, že měl i porezitu nebo jinou vadu, která s chemií souvisí. Když na takových datech AI naučíme, vezme je jako pravdivá a bude nám je vracet. Řídili bychom chaos dalším chaosem.

Druhá možnost je počkat na hotový systém od dodavatele. U něj ale nevíme, na čem byl trénovaný: jestli na datech z publikací, nebo ze skutečné slévárny.

Zbývá hledat, kde nám data utíkají, a udělat v nich pořádek. Čas na systémy přijde, teď ještě není.

## Slide 5 — Systémy počkají. Budujme lidi.

Dnes se bavíme hlavně o tom, že AI halucinuje a že jí nevěříme. Proto má podle mě teď smysl budovat lidi.

V červnu šel přes časopis Slévárenství dotazník pro slévače a slévárny. Asi měsíc předtím jsem stejný poslal u nás ve slévárně. Z 80 technickohospodářských pracovníků přišlo 50 odpovědí a 37 z nich AI používá.

Nabídl jsem, že se můžeme scházet, a vznikl program Early Adopters. Bavíme se o tom, jak AI používat a jak předcházet halucinacím. Nejdůležitější, co z toho vzešlo, je sdílení: každý týden někdo řekne „zkusil jsem tohle, nevyšlo to“ nebo „zkusil jsem tohle a funguje to“. Ostatní se tím inspirují. Tři příklady:

- **Kontrola:** příprava interních i externích auditů a sledování novinek v normách ISO.
- **Obchod:** týdenní podklad pro obchodní poradu. Dřív půl hodiny práce každý týden, po automatizaci pár minut.
- **Výroba:** turnusy a směny. Nejde jen o plán směn, ale i o to, že část lidí spolu dojíždí jedním autem a každý dělá jinde. Kolega sepsal pravidla, AI mu pomohla rozvrh sestavit na týdny dopředu a on už ho jen obnovuje.

### Mimo slidy: hlasování v sále

Nechal jsem zvednout ruce. Čísla jsou můj odhad od řečnického pultu, v sále nás bylo zhruba 40 až 60.

- AI aspoň občas používá asi 60 % sálu.
- Asi deset lidí používá přímo nástroj typu ChatGPT nebo Gemini, ne jen vyhledávač.
- Asi čtyři lidé za nástroj platí nebo ho mají od firmy.
- Tři lidé mají AI nastavenou tak, že je zná: zapnutou paměť a uložené informace o tom, na čem pracují.

Takhle vypadá stav adopce ve slévárenství.

## Slide 6 — Základní nastavení

Často řešíme, kdo má Gemini, kdo ChatGPT a kdo Copilot. **Nástroj** je jen program od nějakého dodavatele a sám o sobě skoro nic neznamená. Zůstaňte u toho, na co jste zvyklí: ve firmě Copilot, doma třeba ChatGPT, když jste s ním začínali.

Přemýšlí **model** a ten rozhoduje o výsledku, i o tom, jak moc si AI vymýšlí. Neplacená verze dává to nejlevnější, co dodavatel má. Je to demo. Hodí se na dotaz, co dnes uvařit, ne na práci. Věta „používám AI, ptám se Googlu“ o práci s AI není. V placené verzi (od zhruba 200 Kč měsíčně) si volíte model i úroveň přemýšlení. Tolik výpočetního výkonu za tak málo peněz jsme nikdy k dispozici neměli.

Třetí je **kontext**: AI ví, na čem pracujete, jak s vámi má mluvit, jakými pravidly se má řídit a co má ověřovat.

V programu Early Adopters se snažím zavést tři návyky:

1. **AI-first.** Než cokoli začnu dělat, zeptám se, jestli mi s tím AI může pomoct. Nemusí to udělat za mě. Může navrhnout, jak to dělat automatizovaně, třeba jak si nastavit pravidlo v Outlooku.
2. **Sledovat, co dělám opakovaně.** To jsou první kandidáti na automatizaci.
3. **Hotové je lepší než dokonalé.** S tím sám zápasím: člověk věc pořád ladí, místo aby ji pustil ven.

## Slide 7 — AI nás musí znát

Zkuste se AI zeptat, s čím vám může pomoct. Bez kontextu dostanete obecnou odpověď: napíšu vám e-maily, zpracuji data. Ve chvíli, kdy vás zná, odpoví podle vašich projektů, procesů a opakovaných úkolů.

Přes QR kód dostanete prompt. Vložíte ho do své AI, ta s vámi povede krátký rozhovor nad pěti základními otázkami (kdo jste, kde pracujete a podobně) a sestaví váš kontext. Poradí i, kam ho uložit. Jedna kolegyně z naší skupiny to rozšířila: přidala popis své pracovní funkce a dostala přehled všech svých odpovědností.

## Slide 8 — Přechod

Nástroj tedy máme, o modelech víme a kontext si můžete udělat třeba ještě dnes. AI vás pak bude znát. Jsme tu ale proto, abychom si něco odnesli z konference. A to, co jste tady slyšeli, vaše AI nezná.

## Slide 9 — Kde končí znalosti z konference

Jak dnes pracujeme? S blokem. Dřív se sborníkem, ten už vlastně není. Hodně z vás si fotí slidy. A většinu si odnášíme v hlavě. K fotkám a poznámkám se pak skoro nikdo nevrátí.

## Slide 10 — Od kartotéky k druhému mozku

Druhý mozek není nic nového. Dřív to byly kartotéky, dnes složky na disku.

**Zettelkasten.** Sociolog Niklas Luhmann si vedl kartotéku, ve které jednu myšlenku rozvíjel další a vytvářel mezi nimi vazby. Zjistil něco nového, uložil to k příbuzné myšlence a ta se začala větvit. Na konci měl kolem 90 000 kartiček. Když psal knihu nebo článek, šel po vazbách a poskládal si z nich podklady. Kartotéka je dnes celá digitalizovaná.

**Chytré poznámky.** Sönke Ahrens ten systém v knize Jak si dělat chytré poznámky převedl do dnešní doby. Rozlišuje letmé zápisky, poznámky ze zdrojů vlastními slovy a trvalé poznámky. Hlavní je ukládání do systému a propojování, už digitálně.

**Obsidian a Markdown.** V roce 2020 přichází Obsidian, dnes je podobných nástrojů spousta. S ním přichází doba Markdownu. Je to obyčejný textový soubor, jaký znáte třicet let, jen s příponou .md. Je malý, jednoduchý a AI s ním umí pracovat. Kdo dnes dělá s AI, pracuje v Markdownu.

**Dnes.** Princip je stejný, nové je, že poznámky čte i AI. Vazby mezi nimi navrhne sama a umí v nich hledat, takže je nemusíte procházet vy.

## Slide 11 — Můj druhý mozek

Začal jsem tak, že jsem ukládal soubory do složek a připojil k nim AI. Ta začala hledat, co s čím souvisí. Jsou tam konference, věci z domu (třeba návody k fotovoltaice), věci ze slévárny, prompty, poznámky z knih.

Dnes posílám do mozku všechno, co mi přijde pod ruku. AI z toho vybere podstatné, zařadí to do oblastí a propojí s tím, co už tam je. Na grafu je vidět oblast Adopce: jednotlivé soubory a vazby na další, třeba na konference, odkud informace pochází.

## Slide 12 — Od přednášky do mozku

Tak jsem pracoval i včera. Dělám si poznámky, fotím slidy, nahrávám na diktafon. Na přepis mluveného slova dnes fungují běžné nástroje. Z přepisu vznikne jednoduchý .md soubor, AI ho zařadí do mapy a vytěží. Kdykoli si pak vzpomenu, zeptám se a dostanu z něj to, co mě zajímá.

Nahrává se i tahle přednáška. Její přepis dostanete k ostatním materiálům.

## Slide 13 — Témata ročníků 2011–2025

Tohle je záznam Slévárenských dnů od roku 2011: všechny přednášky ze sborníků, v posledních letech z abstraktů. Zatím mám načtené hlavně názvy a abstrakty. Starší ročníky vytěžuji postupně, nejdřív to, co mě zajímá. Loni jsem tu nebyl, takže z ročníku 2025 toho mám málo.

Nejvíc mě zaujala přednáška pana Krále z roku 2019. Mimochodem v ní říká, že procesy je potřeba změřit a popsat a že data a archivy nemáme zahazovat, protože se jednou budou hodit pro umělou inteligenci. To bylo dřív, než přišly první nástroje, které dnes používáme. Je to stejná věc jako na začátku: data nemáme, a když je máme, nejsou pravdivá. Moc se od té doby neudělalo.

Souvisí s tím i odchody technologů, o kterých se mluvilo včera v plenární sekci. S každým odchází z firmy znalost. Čeká nás to v příštích letech a pomalu se to děje už teď.

## Slide 14 — Zpět k první otázce

Díval jsem se, jak si lidé v sále přednášky zaznamenávají. Hlavně fotí slidy, bloků jsem viděl málo. Většina informací tedy skončí ve fotkách v mobilu, nebo v hlavě.

## Slide 15 — Můžeme jít dál

Co s tím jde dělat:

- **Přednášející** mohou přednášku sdílet, doplnit ji a přidat k ní přepis.
- **Časopisy.** Letos jsem psal dva články. U druhého jsem každý týden sledoval, co už neplatí, a než vyšel, velká část informací o AI byla zastaralá. Vychází ale i články, které mají váhu dlouho. Slévárenské listy jsou digitální a dá se s nimi pracovat. Slévárenství je tištěné, leží ve skříni a za pár let v něm nic nenajdu. Ke svému článku jsem proto přidal textový přepis. S redakcí Slévárenství jsem se včera domluvil, že přepis článku můžu dát i vám. Časopis by mohl dávat odkaz na přepis přímo do článku.
- **Vy.** Zachytávejte informace tak, abyste je dokázali někam přenést. Když už si slide vyfotíte, zpracujte fotku do svého mozku, ať vám tam zůstane.

### Mimo slidy: živé ukázky

Tyhle části jsem ukazoval naživo, ve veřejné prezentaci nejsou.

**Co zaznělo včera.** Byl jsem na plenární sekci a na formovacích materiálech, kolega na litinách. Všechny záznamy a fotky slidů jsem poslal do mozku. Ten už ví, že má ke každému materiálu přidat doporučení, takže z nich vybral, co stojí za pozornost. Ne všechno bych zachytil sám, třeba část přednášky pana Dobosze o spojování oborových svazů na evropské úrovni. Podstatné je, že mi ty informace zůstanou. Až budeme řešit třeba problém s jádry, zeptám se a mozek připomene, že o tom byla přednáška, co se zkoušelo a jak to dopadlo.

**Jak vypadá Markdown.** Ukázal jsem jeden zápis v surové podobě. Stránka, na kterou se hezky kouká, je jen jeho zobrazení. Tabulky jsou zapsané textem, AI v nich čte a umí je znovu vykreslit.

**Dotaz na mozek.** Ukázal jsem 3D znázornění. Každá tečka je uložený soubor, „mícha“ je základní mapa. Zadali jsme dotaz „jak digitalizovat výrobu, jak zavádět AI a kdo mi s tím může pomoct“. AI se nejdřív zeptá základní mapy, kde hledat, ta ji pošle do tematických map a z nich k jednotlivým souborům. Na výběr jsou dva modely od Anthropicu: Sonnet je rychlejší, Opus víc přemýšlí. Po chvíli přišla odpověď i se zdroji: poznámky z konferencí o AI, podklady k adopci ve výrobě, firmy z Mezinárodního strojírenského veletrhu (z jeho webu jsem si vytěžil vystavovatele a čím se zabývají, takže vím, koho oslovit, když budu hledat dodavatele robotů nebo systémů), lidé z vysokých škol.

**Jak to funguje v praxi.** Je to složka v počítači. K ní je připojený Obsidian propojený s telefonem, abych mohl ukládat hned. Jedna složka sbírá všechno nezpracované. Když mám čas, projdeme ji s AI: co má smysl, co ne, co jsou úkoly z porady. AI navrhuje, rozhodnutí je moje. V mozku jsou i pravidla, jak má pracovat. Třeba u uloženého příspěvku z LinkedInu má přečíst i diskuzi pod ním, protože ta často ukáže, co v příspěvku neplatí.

## Slide 16 — Nebudujte systémy. Budujte lidi.

Začínal jsem tím, že teď není čas budovat systémy, ale lidi, a tím i končím. Svůj mozek mám hotový. Čím může být přínosem pro slévárnu? Slévárna může mít vlastní.

Mohou v něm být směrnice, výrobní postupy, opatření proti zmetkovitosti, návody. Záleží na tom, jak je to zabezpečené. Že je ve směrnici úsek, účetní a technolog, nikomu neuškodí. Co nám pomohlo se zmetky nebo jak vypadají výrobní postupy, ven posílat nechceme. Tam jsou jednou z možností lokální modely.

Je to můj další projekt. Představuji si ho třeba při nástupu nového člověka: místo podpisu „seznámil jsem se, pochopil jsem“ pod směrnicí, kterou nečetl, se zeptá, jak má něco udělat, a dostane odpověď.

## Slide 17 — Děkuji za pozornost

Pod QR kódem najdete prezentaci, oba letošní články (ne v podobě z časopisu, ale jako textový přepis pro vaši AI), výsledky dotazníků a po akci i přepis dnešní přednášky. Můžete tam nechat e-mail a dám vám vědět, až přibude. Časem by to mohl být i prostor, kde slévači sdílejí své práce a dokumenty.

Přednášky ostatních řečníků tam nejsou. Zpracoval jsem si je pro sebe. Kdo z přednášejících bude souhlasit se zveřejněním, stačí napsat a doplním je.

---

## Diskuze

**Bezpečnost dat: nemůžou uniknout?** Může se to stát. Používám nástroj od Anthropicu, vlastní řešení nemám. Citlivé věci tam nedávám: žádné zdravotní zprávy, smlouvy jen bez rodných čísel. Dodavatelé se zavazují, že data dál nepoužijí, ale pořád leží na cizím serveru. Ve firmách je to téma shadow AI: kdo ve firmě používá vlastní nástroj, vynáší data mimo její kontrolu. Firma si může pořídit licence se smluvním závazkem mlčenlivosti. Další cesta jsou lokální modely. Zkoušel jsem je, jsou náročné na hardware a práce s nimi je pomalá. Každý si musí zvážit možný únik proti tomu, co mu to přináší.

**Poznámka z publika:** mozek slévárny bez citlivých dat bude obsahovat jen obecné věci. Citlivé je právě know-how, třeba jakou úpravou vsázky nebo jakým modifikátorem se podařilo vyřešit konkrétní vadu. Konkurenci by to ušetřilo celý postup hledání. Souhlasím. Pak je na místě lokální řešení, nebo to tam nedávat.

**Co používáte?** Hlavní nástroj je Claude. Na běžné dotazy a přepisy ChatGPT s nižším předplatným. V práci máme Copilot. Rozhoduje u mě paměť nástroje a to, jestli jde vypnout trénování na mých datech.

**Stavěl byste mozek slévárny v Claude, nebo v Copilotu?** To je jedno. Důležité je mít informace na jednom místě a jeden nástroj, který je zpracuje a propojí.

**Komentář z publika (názor posluchače, neověřeno):** AI je dnes levná a dostupná, ale dodavatelé budou muset vydělávat a datacentra jsou ztrátová, takže během roku až dvou lze čekat výrazné zdražení tarifů. Moje odpověď: kdo začne, až to bude drahé, už si systémy nepostaví, nebo je postaví draho. Kdo staví teď, bude je mít hotové.
