---
description: SmFF:s färger är hämtade ur det småländska landskapet. Varje färg bär en berättelse.
---

# Färg

SmFF:s färgpalett är inte ett estetiskt val – den är en identitetsbärare. Paletten är uppdelad i fyra lager: **primär**, **accent**, **bas** och **koppling** (SvFF:s nationella färger).

---

## Primärfärger

SmFF ska primärt upplevas som **röd**. Det gröna är stödjande – alltid komplement, aldrig dominant.

<figure>

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                  │
│   ████████████████████████████████  ██████████████████          │
│   Smålandsröd #A91C1C               Skogsgrön #2F5731           │
│   Primär identitetsfärg             Stödjande primärfärg        │
│   Pantone 1807 C                    Pantone 357 C               │
│   CMYK: C20 M100 Y100 K20           CMYK: C60 M0 Y70 K60        │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

</figure>

### 🔴 Smålandsröd `#A91C1C`

*Inspirerad av de traditionella röda stugorna och lejonet i Smålands vapen.*

| | Värde |
|---|---|
| **HEX** | `#A91C1C` |
| **RGB** | 169 · 28 · 28 |
| **CMYK** | C20 M100 Y100 K20 |
| **Pantone** | 1807 C |

**Används till:** Logotyp, rubriker, knappar, primära bakgrundsfärger i SmFF-primärt läge.

{% hint style="warning" %}
**OBS vid screentryck:** Kontrollera alltid Smålandsröd mot ett tryckt referensprov. Skärmfärg och screentryckt färg kan skilja sig, och befintlig EPS-logotyp kan ha en marginellt avvikande röd ton.
{% endhint %}

### 🌲 Skogsgrön `#2F5731`

*Hämtad från de djupa småländska skogarna.*

| | Värde |
|---|---|
| **HEX** | `#2F5731` |
| **RGB** | 47 · 87 · 49 |
| **CMYK** | C60 M0 Y70 K60 |
| **Pantone** | 357 C |

**Används till:** Rubriker, grafiska element, ikoner, hållbarhetsrelaterade budskap.

---

## Proportioner

SmFF ska upplevas som röd. Skogsgrön är alltid kompletterande.

{% hint style="info" %}
**Riktlinje:** Röd max 60 % av ytan · Grön max 40 % · Aldrig 50/50 · Röd är alltid primär
{% endhint %}

---

## Accentfärger

### 🌾 Torparbeige `#E2DBD0`
*Inspirerad av torpargrus, linnevävar och gamla landsvägar.*

| HEX | RGB | CMYK |
|---|---|---|
| `#E2DBD0` | 226 · 219 · 208 | C10 M11 Y18 K0 |

Bakgrunder, stora ytor, presentationsytor. Förmedlar samarbete, tålamod och samhörighet.

### 🌿 Ängsgrön `#99C1A2`
*Inspirerad av öppna landskap och vårens skiftningar.*

| HEX | RGB | CMYK |
|---|---|---|
| `#99C1A2` | 153 · 193 · 162 | C30 M0 Y25 K15 |

Markeringar, illustrationer, stödjande detaljer. Förmedlar tillgänglighet och hopp.

---

## Basfärger

| Namn | HEX | RGB | Användning |
|---|---|---|---|
| **Kolsvart** | `#333333` | 51 · 51 · 51 | Brödtext, starka kontraster |
| **Stenmursgrå** | `#F2F2F2` | 242 · 242 · 242 | Bakgrundsfärg, blockytor |
| **Linnevit** | `#FFFFFF` | 255 · 255 · 255 | Primär bakgrund |

{% hint style="info" %}
Använd `#333333` framför ren svart `#000000` – det ger ett mjukare tryckt intryck och bättre skärmläsbarhet.
{% endhint %}

---

## Kopplingsfärger (SvFF)

Dessa färger används **enbart** när SmFF kommunicerar i det nationella fotbollssystemet. De ersätter aldrig SmFF:s primärfärger i SmFF-primärt läge.

| Namn | HEX | Pantone | Sammanhang |
|---|---|---|---|
| **Nationell mörkblå** | `#005293` | 301 C | smalandsfotbollen.se, SvFF-samprofilering |
| **Nationell ljusblå** | `#4A90E2` | – | Digitala kopplingselement |
| **Nationell gul** | `#FECB00` | 116 C | SvFF-samprofilering |

{% hint style="danger" %}
**PPT-avvikelse:** SmFF.thmx innehåller `#004B87` och `#1A75BB`. Dessa avviker från SvFF:s officiella `#005293`. Vid revision av PPT-mallen ska `#005293` användas.
{% endhint %}

---

## Tillgänglighet – kontrastkrav (WCAG AA)

Minst **4,5:1** för normal text · Minst **3:1** för stor text (18 pt+) och grafik.

| Text | Bakgrund | Kontrast | Status |
|---|---|---|---|
| Kolsvart `#333333` | Linnevit `#FFFFFF` | 12,6:1 | ✅ |
| Linnevit `#FFFFFF` | Smålandsröd `#A91C1C` | 5,9:1 | ✅ |
| Linnevit `#FFFFFF` | Skogsgrön `#2F5731` | 8,1:1 | ✅ |
| Kolsvart `#333333` | Torparbeige `#E2DBD0` | 7,2:1 | ✅ |
| Linnevit `#FFFFFF` | Nationell mörkblå `#005293` | 9,4:1 | ✅ |
| Linnevit `#FFFFFF` | Stenmursgrå `#F2F2F2` | 1,1:1 | ❌ Aldrig |

> Kontrollera alltid nya kombinationer på [webaim.org/resources/contrastchecker](https://webaim.org/resources/contrastchecker)

---

## Färger vid screentryck och brodyr

- Pantone Textile (inte Pantone Coated) för textilmatchning
- Brodyr på mörkt underlag: alltid ljus tråd – aldrig röd på röd
- Screentryck med ett färgsystem: välj Smålandsröd eller vit – aldrig blanda primärfärger i enfargsscreentryck

#### Primärfärger

<table data-view="cards"><thead><tr><th></th><th></th><th></th><th></th><th></th><th data-hidden data-card-cover data-type="image">Cover image</th></tr></thead><tbody><tr><td><sup><sub>C20 M100 Y100 K20</sub></sup></td><td><sup><sub>R169 G28 B28</sub></sup></td><td><sup><sub>#A91C1C</sub></sup></td><td><strong>Smålandsröd</strong></td><td><p>Inspirerad av de traditionella röda stugorna och vapnets lejon. Den förkroppsligar envishet, mod och det folkliga hjärtat i rörelsen.</p><p>Står för identitet, tradition, mod, beslutsamhet och folklighet. Kan med fördel användas till rubriker, knappar, viktiga markeringar och som identitetsbärare.</p></td><td><a href="https://singlecolorimage.com/get/a91c1c/300x175">https://singlecolorimage.com/get/a91c1c/300x175</a></td></tr><tr><td><sup><sub>C60 M0 Y70 K60</sub></sup></td><td><sup><sub>R47 G87 B49</sub></sup></td><td><sup><sub>#2F5731</sub></sup></td><td><strong>Skogsgrön</strong></td><td><p>Hämtad från de djupa småländska skogarna. Symboliserar trygghet, hållbarhet och framtidstro.</p><p>Står för trygghet, tillväxt, hållbarhet och utveckling. Kan med fördel användas till rubriker, grafik, ikoner och hållbarhetsbudskap.</p></td><td><a href="https://singlecolorimage.com/get/2f5731/300x175">https://singlecolorimage.com/get/2f5731/300x175</a></td></tr></tbody></table>

#### Accentfärger

<table data-view="cards"><thead><tr><th></th><th></th><th></th><th></th><th></th><th data-hidden data-card-cover data-type="image">Cover image</th></tr></thead><tbody><tr><td><sup><sub>C10 M11 Y18 K0</sub></sup></td><td><sup><sub>R226 G219 B208</sub></sup></td><td><sup><sub>#E2DBD0</sub></sup></td><td><strong>Torparbeige</strong></td><td><p>Inspirerad av torpargrus, linnevävar och gamla landsvägar. Förmedlar samarbete, tålamod och samhörighet.</p><p>Står för samarbete, stabilitet, tålamod, perspektiv, förtroende och struktur. Kan med fördel användas till bakgrunder, kontraster och stora ytor i presentationer.</p></td><td><a href="https://singlecolorimage.com/get/e2dbd0/300x175">https://singlecolorimage.com/get/e2dbd0/300x175</a></td></tr><tr><td><sup><sub>C30 M0 Y25 K15</sub></sup></td><td><sup><sub>R153 G193 B162</sub></sup></td><td><sup><sub>#99C1A2</sub></sup></td><td><strong>Ängsgrön</strong></td><td><p>Inspirerad av öppna landskap och vårens skiftningar. Ger en känsla av öppenhet och ungdomlighet.</p><p>Står för tillgänglighet, hopp, framtidsoptimism och ungdomlighet. Kan med fördel användas till markeringar, illustrationer och stödjande detaljer.</p></td><td><a href="https://singlecolorimage.com/get/99c1a2/300x175">https://singlecolorimage.com/get/99c1a2/300x175</a></td></tr></tbody></table>

#### Basfärger

<table data-view="cards"><thead><tr><th></th><th></th><th></th><th></th><th></th><th data-hidden data-card-cover data-type="image">Cover image</th></tr></thead><tbody><tr><td><sup><sub>C0 M0 Y0 K80</sub></sup></td><td><sup><sub>R51 G51 B51</sub></sup></td><td><sup><sub>#333333</sub></sup></td><td><strong>Kolsvart</strong></td><td><p>Inspirerad av järn och småländsk verkstadstradition.</p><p>Står för tyngd, läsbarhet och förankring. Används som text, starka kontraster och grafiska element.</p></td><td><a href="https://singlecolorimage.com/get/333333/300x175">https://singlecolorimage.com/get/333333/300x175</a></td></tr><tr><td><sup><sub>C4 M3 Y3 K0</sub></sup></td><td><sup><sub>R242 G242 B242</sub></sup></td><td><sup><sub>#F2F2F2</sub></sup></td><td><strong>Stenmursgrå</strong></td><td><p>Inspirerad av gamla stenmurar.</p><p>Står för tydlighet, struktur och balans. Kan med fördel användas till bakgrundsfärg, blockytor alternativ till vitt.</p></td><td><a href="https://singlecolorimage.com/get/f2f2f2/300x175">https://singlecolorimage.com/get/f2f2f2/300x175</a></td></tr><tr><td><sup><sub>C0 M0 Y0 K0</sub></sup></td><td><sup><sub>R255 G255 B255</sub></sup></td><td><sup><sub>#FFFFFF</sub></sup></td><td><strong>Linnevit</strong></td><td><p>Inspirerad av ljusa linnevävar.</p><p>Står för klarhet, öppenhet och rymd. Används som primär bakgrund i presentationer, webb och tryck.</p></td><td><a href="https://singlecolorimage.com/get/ffffff/300x175">https://singlecolorimage.com/get/ffffff/300x175</a></td></tr></tbody></table>

#### Kopplingsfärger

<table data-view="cards"><thead><tr><th></th><th></th><th></th><th></th><th></th><th data-hidden data-card-cover data-type="image">Cover image</th></tr></thead><tbody><tr><td><sup><sub>C100 M54 Y4 K19</sub></sup></td><td><sup><sub>R0 G82 B147</sub></sup></td><td><sup><sub>#005293</sub></sup></td><td><strong>Nationell mörkblå</strong></td><td>Den centrala blåtonen i svensk fotboll, bärande i både SvFF:s och SmFF:s visuella uttryck. Förmedlar stabilitet, professionalism och nationell samhörighet.</td><td><a href="https://singlecolorimage.com/get/005293/300x175">https://singlecolorimage.com/get/005293/300x175</a></td></tr><tr><td><sup><sub>C68 M34 Y0 K0</sub></sup></td><td><sup><sub>R74 G144 B226</sub></sup></td><td><sup><sub>#4A90E2</sub></sup></td><td><strong>Nationell ljusblå</strong></td><td>En mjukare blåton som kompletterar den mörkare basfärgen. Används för att skapa variation, balans och ljusare uttryck i presentationer och digitala miljöer.</td><td><a href="https://singlecolorimage.com/get/4A90E2/300x175">https://singlecolorimage.com/get/4A90E2/300x175</a></td></tr><tr><td><sup><sub>C0 M14 Y100 K0</sub></sup></td><td><sup><sub>R254 G203 B0</sub></sup></td><td><sup><sub>#FECB00</sub></sup></td><td><strong>Nationell gul</strong></td><td>Inspirerad av solen och de svenska fälten. En färg som för in energi och glädje.</td><td><a href="https://singlecolorimage.com/get/FECB00/300x175">https://singlecolorimage.com/get/FECB00/300x175</a></td></tr></tbody></table>
