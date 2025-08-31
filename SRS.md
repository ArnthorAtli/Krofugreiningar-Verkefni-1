# 📄 Software Requirements Specification (SRS)

## 1. Inngangur
### 1.1 Tilgangur
Stutt lýsing á tilgangi kerfisins og hverju það á að skila.

### 1.2 Umfang
Hvað á kerfið að gera? Afmörkun verkefnisins.

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
- Lýsa helstu notendahópum kerfisins (t.d. notendur, stjórnendur).

### 2.2 Viðskiptaávinningur
- Hver er ávinningurinn fyrir fyrirtæki eða notendur?

---

## 3. Kröfur fyrir kerfið

### 3.1 Viðskiptakröfur
| ID  | Lýsing | Issue |
|-----|--------|-------|
| BR1 | [Spara mannafla] | [#12](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/1#issue-3363417922) x|
| BR2 | [Stytta biðtíma fyrir viðskiptavin] | [#13](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/11#issue-3363615584)x|

### 3.2 Kerfiskrafa
| ID  | Lýsing | Issue |
|-----|--------|-------|
| SR1 | [Sjálfvirkt bókasafn sem skráir, raðar og afhendir bækur] | [#14](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/9#issue-3363566402) x|

### 3.3 Fídusar (Features)
| ID  | Lýsing | Issue |
|-----|--------|-------|
| F1  | [Sjálfvirkt útlán bókar] | [#15](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/5#issue-3363561987) x|
| F2  | [Sjálfvirk skil] | [#16](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/12#issue-3369192476)x |
| F3  | [Sjálfvirk röðun í hillur] | [#17](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/13#issue-3369195393) x|

### 3.4 Notendakröfur
| ID  | Lýsing | Fídus | Issue |
|-----|--------|-------|-------|
| UR1 | [Skanna bók] | F1 | [#18](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/10#issue-3363567049) x|
| UR2 | [Skila bók á færiband] | F1 | [#19](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/14#issue-3369243076)x |
| UR3 | [Leita að bók í kerfinu] | F2 | [#20](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/15#issue-3369244935) x|
| UR4 | [Panta bók] | F2 | [#21](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/16#issue-3369246924) x|
| UR5 | [Lesa tilkynningu í tölvupósti] | F3 | [#22](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/17#issue-3369248798) x|
| UR6 | [Skoða lánasögu og núverandi lán] | F3 | [#23](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/18#issue-3369250660) x|

### 3.5 Virknikröfur
| ID  | Lýsing | Notendakrafa | Issue |
|-----|--------|--------------|-------|
| FR1 | [Bókin fer úr láni hjá notanda] | UR1 | [#24](https://github.com/ArnthorAtli/Krofugreiningar-Verkefni-1/issues/6#issue-3363564012) x|
| FR2 | [Bókin bætist inn í kerfið] | UR1 | [#25](../../issues/25) |
| FR3 | [Notandi fær skilaboð um að bókin hefur verið skiliað] | UR1 | [#26](../../issues/26) |
| FR4 | [Virkni] | UR2 | [#27](../../issues/27) |
| FR5 | [Virkni] | UR2 | [#28](../../issues/28) |
| FR6 | [Virkni] | UR2 | [#29](../../issues/29) |
| FR7 | [Virkni] | UR3 | [#30](../../issues/30) |
| FR8 | [Virkni] | UR3 | [#31](../../issues/31) |
| FR9 | [Virkni] | UR3 | [#32](../../issues/32) |
| FR10 | [Virkni] | UR4 | [#33](../../issues/33) |
| FR11 | [Virkni] | UR4 | [#34](../../issues/34) |
| FR12 | [Virkni] | UR4 | [#35](../../issues/35) |
| FR13 | [Virkni] | UR5 | [#36](../../issues/36) |
| FR14 | [Virkni] | UR5 | [#37](../../issues/37) |
| FR15 | [Virkni] | UR5 | [#38](../../issues/38) |
| FR16 | [Virkni] | UR6 | [#39](../../issues/39) |
| FR17 | [Virkni] | UR6 | [#40](../../issues/40) |
| FR18 | [Virkni] | UR6 | [#41](../../issues/41) |

### 3.6 Viðskiptareglur
| ID  | Lýsing | Issue |
|-----|--------|-------|
| BRG1 | [Viðskiptaregla] | [#42](../../issues/42) |
| BRG2 | [Viðskiptaregla] | [#43](../../issues/43) |

### 3.7 Óvirknikröfur
| ID  | Lýsing | Issue |
|-----|--------|-------|
| NFR1 | [Óvirknikrafa] | [#44](../../issues/44) |
| NFR2 | [Óvirknikrafa] | [#45](../../issues/45) |
| NFR3 | [Óvirknikrafa] | [#46](../../issues/46) |
| NFR4 | [Óvirknikrafa] | [#47](../../issues/47) |
| NFR5 | [Óvirknikrafa] | [#48](../../issues/48) |
| NFR6 | [Óvirknikrafa] | [#49](../../issues/49) |

### 3.8 Gæðaeiginleikar
| ID  | Lýsing | Issue |
|-----|--------|-------|
| QR1 | [Gæðaeiginleiki] | [#50](../../issues/50) |
| QR2 | [Gæðaeiginleiki] | [#51](../../issues/51) |

### 3.9 Takmarkanir
| ID  | Lýsing | Issue |
|-----|--------|-------|
| C1 | [Takmörkun] | [#52](../../issues/52) |
| C2 | [Takmörkun] | [#53](../../issues/53) |

### 3.10 Ytri skil (Interfaces)
| ID  | Lýsing | Issue |
|-----|--------|-------|
| IF1 | [Ytra skil] | [#54](../../issues/54) |
| IF2 | [Ytra skil] | [#55](../../issues/55) |

---

## 4. Viðaukar
### 4.1 Orðalisti
- Skilgreina lykilhugtök.

### 4.2 Samþykktir
- Kennari: ____________________  
- Nemandi: ____________________
