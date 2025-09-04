# 📄 Software Requirements Specification (SRS)

## 1. Inngangur
### 1.1 Tilgangur
Helsti tilgangur kerfisins er að draga úr þörf fyrir starfsmanna kostnað á bókasafninu og þar með lækka rekstrarkostnað, en um leið tryggja notendum einfalt, skilvirkt og ánægjulega upplifun af útlánum og skilum bóka.

### 1.2 Umfang
Kerfið er sjálfvirkt bókasafnskerfi sem sér um útlán, skil og flokkun bóka með það markmið að bjóða notendum sjálfsafgreiðslu og gera bókasafnið nánast óháð starfsfólki.

### 1.3 Skilgreiningar
| Hugtak | Skýring |
|--------|---------|
| SRS | Software Requirements Specification |
| Issue | Umræða/atriði í GitHub sem tengist ákveðinni kröfu |

### 1.4 Tilvísanir
- IEEE 830 Standard (fyrirmynd að uppbyggingu SRS)

---

## 2. Almenn lýsing
### 2.1 Notendahópar
Almennir notendur bókasafnsins: Einstaklingar sem nýta kerfið til að fá lánaðar bækur, skila þeim og fletta upp upplýsingum án aðstoðar starfsmanna.

Stjórnendur bókasafnsins: Fá yfirsýn yfir útlán, skil, bókaflæði og nýtingu safnsins, auk þess að geta stillt og viðhaldið kerfinu.

### 2.2 Viðskiptaávinningur
Fyrir bókasafnið: Lækkaður rekstrarkostnaður vegna minni mannaflaþarfar, aukin skilvirkni í útlánum og skilum.

Fyrir notendur: Fljótleg og þægileg sjálfsafgreiðsla, minni biðraðir og aðgengilegt kerfi sem gerir bókasafnsupplifunina hraðari og notendavænni.

---

## 3. Kröfur fyrir kerfið

### 3.1 Viðskiptakröfur
| ID  | Lýsing | Issue |
|-----|--------|-------|
| BR1 | [Spara mannafla] | [#12](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/1#issue-3363417922) |
| BR2 | [Stytta biðtíma fyrir viðskiptavin] | [#13](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/11#issue-3363615584)|

### 3.2 Kerfiskrafa
| ID  | Lýsing | Issue |
|-----|--------|-------|
| SR1 | [Sjálfvirkt bókasafn sem skráir, raðar og afhendir bækur] | [#14](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/9#issue-3363566402) |

### 3.3 Fídusar (Features)
| ID  | Lýsing | Issue |
|-----|--------|-------|
| F1  | [Sjálfvirkt útlán bókar] | [#15](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/5#issue-3363561987) |
| F2  | [Sjálfvirk skil] | [#16](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/12#issue-3369192476) |
| F3  | [App fyrir notendur] | [#17](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/13#issue-3369195393) |

### 3.4 Notendakröfur
| ID  | Lýsing | Fídus | Issue |
|-----|--------|-------|-------|
| UR1 | [Skanna bók] | F1 | [#18](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/10#issue-3363567049) |
| UR2 | [Panta bók] | F2 | [#21](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/16#issue-3369246924) |
| UR3 | [Skila bók á færiband] | F1 | [#19](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/14#issue-3369243076) |
| UR4 | [Færiband skilar bók] | F2 | [#20](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/15#issue-3369244935) |
| UR5 | [Gefa notendur tilkynningar] | F3 | [#22](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/17#issue-3369248798) |
| UR6 | [Skoða lánasögu og núverandi lán] | F3 | [#23](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/18#issue-3369250660) |

### 3.5 Virknikröfur
| ID  | Lýsing | Notendakrafa | Issue |
|-----|--------|--------------|-------|
| FR1 | [Bókin fer í nýja stöðu (í útláni)] | UR1 | [#24](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/6#issue-3363564012) |
| FR2 | [Uppfæra byrgðarstöðu bókarinnar] | UR1 | [#25](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/19) |
| FR3 | [Notandi fær skilaboð] | UR1 | [#26](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/20) |
| FR4 | [Breyta stöðu bókar þegar hún er pöntuð] | UR2 | [#27](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/24) |
| FR5 | [Þegar pöntuð bók er skilað setja í pöntunarhólf] | UR2 | [#28](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/25) |
| FR6 | [Hafa forgangsröð ef margir panta sömu bók] | UR2 | [#29](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/26) |
| FR7 | [Auðkenning bókar] | UR3 | [#27](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/21) |
| FR8 | [Notandi fær staðfestingu] | UR3 | [#28](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/22) |
| FR9 | [Staðfesting á skilum] | UR3 | [#29](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/23) |
| FR10 | [Athuga hvort bók er í pöntun] | UR4 | [#33](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/27) |
| FR11 | [Athuga hvort bók er frá bókasafninu] | UR4 | [#34](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/28) |
| FR12 | [Finna viðeigandi staðsetningu fyrir bókina] | UR4 | [#35](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/29) |
| FR13 | [Tylkinning um of sein skil] | UR5 | [#36](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/30) |
| FR14 | [Tylkinning þegar pöntuð bók kemur í hús] | UR5 | [#37](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/31) |
| FR15 | [Tylkinning þegar það fer að koma að skiladegi] | UR5 | [#38](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/32) |
| FR16 | [Skoða lánasögu] | UR6 | [#39](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/33)) |
| FR17 | [Skoða núverandi lán] | UR6 | [#40](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/34) |
| FR18 | [Skoða hvenær þarf að skila bókum] | UR6 | [#41](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/35) |

### 3.6 Viðskiptareglur
| ID  | Lýsing | Issue |
|-----|--------|-------|
| BRG1 | [Skilaskylda] | [#42](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/2) |
| BRG2 | [Takmark á fjölda bóka í útláni] | [#43](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/36) |

### 3.7 Gæðaeiginleikar
| ID  | Lýsing | Issue |
|-----|--------|-------|
| QR1 | [Svörunartími] | [#50](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/37) |
| QR2 | [Áreiðanleiki] | [#51](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/38) |

### 3.8 Takmarkanir
| ID  | Lýsing | Issue |
|-----|--------|-------|
| C1 | [Takmörkuð stærð á bók] | [#52](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/39) |
| C2 | [Gillt skirteini] | [#53](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/40) |

### 3.9 Ytri skil (Interfaces)
| ID  | Lýsing | Issue |
|-----|--------|-------|
| IF1 | [Snertiskjár - leita að bók | [#54](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/41) |
| IF2 | [Ytra skil] | [#55](../../issues/55) |

---

## 4. Viðaukar
### 4.1 Orðalisti
- Skilgreina lykilhugtök.
- Bókasafn
- Áskrift
- Færiband
- Sjálfvirkt
- Röðun
- Lán
- Skil
- Sjálfsafgreiðsla

### 4.2 Samþykktir
- Kennari: ____________________  
- Nemandi: Arnþór Atli Atlason
- Nemandi: Kristín Sesselja Róbertsdóttir
