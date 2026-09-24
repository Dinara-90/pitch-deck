# Travely — Investor Pitch Deck 🌍

Claymorphism uslubidagi, **o'ngdan chapga suriladigan** (gorizontal) investor presentatsiyasi.
Ranglar: **to'q ko'k (navy) + yashil (mint)**. Bitta HTML fayl — internetga ulanish shart emas (rasmlar lokal).

> Live MVP: https://travely-smart-travel.lovable.app/

## Qanday ochish

`index.html` faylini brauzerda ochish kifoya:

```bash
# oddiy variant
open index.html          # macOS
xdg-open index.html      # Linux

# yoki lokal server bilan (tavsiya etiladi)
python3 -m http.server 8080
# brauzerda: http://localhost:8080
```

## Boshqarish

| Amal | Tugma |
|---|---|
| Keyingi slayd | `→` / `Space` / `PageDown` / pastga scroll / sichqoncha bilan chapga tortish |
| Oldingi slayd | `←` / `PageUp` / yuqoriga scroll / o'ngga tortish |
| Birinchi / oxirgi | `Home` / `End` |
| To'liq ekran | `F` yoki ⛶ tugmasi |
| PDF (A4, gorizontal) | 🖨️ PDF tugmasi → "Save as PDF" |
| Telefonda | chapga/o'ngga **swipe** |

Slaydning ichida kontent sig'masa — o'sha slayd ichida vertikal scroll ishlaydi.

## Slaydlar (13 ta)

1. **Muqova** — "Bilmasdan bormang" + asosiy ko'rsatkichlar
2. **Muammo** — scam, adashish, ishonchsiz ma'lumot, narx shaffof emas (+ statistika)
3. **Yechim** — Scam Radar, 7 kategoriyali sharhlar, Hidden Gems, narx shaffofligi, Ask Travelers, offline AI
4. **MVP** — live URL + QR kod + telefon maketi
5. **Foydalanuvchi yo'li** — 4 qadam, Travely javob beradigan 5 savol
6. **Biznes model** — Freemium + **Pro $4.99/oy** + B2B/API + affiliate
7. **TAM · SAM · SOM** — $622.6 mlrd → $15.07 mlrd → ≈$19.5M ARR
8. **SWOT tahlil** — kuchli/zaif tomonlar, imkoniyat va xavflar
9. **Raqobat** — Tripadvisor, Google Maps, OTA, ChatGPT bilan taqqoslash
10. **Investitsiya taklifi** — **$10 000** round va mablag' taqsimoti
11. **5 yillik reja** — 2026 → 2030: $96K dan $19.5M ARR ga
12. **Yo'l xaritasi** — investitsiyadan keyingi birinchi 12 oy
13. **Xulosa** — CTA, QR kod, aloqa

## Fayllar

```
index.html            # butun taqdimot (HTML + CSS + JS, bitta fayl)
assets/               # claymorphism rasmlar (webp, AI bilan generatsiya qilingan)
  hero.webp           # muqova
  problem.webp        # muammo
  scam-radar.webp     # yechim
  community.webp      # hamjamiyat
  ai-assistant.webp   # AI yordamchi
  market.webp         # bozor o'sishi
  qr-travely.png      # live saytga olib boruvchi QR kod
```

## Dizayn tizimi

- **Claymorphism**: `border-radius` 24–44px, ko'p qatlamli `box-shadow`
  (tashqi qorong'i soya + ichki yorug'/qorong'i soya) — "yumshoq loy" effekti.
- **Ranglar**: `--navy-900 #0B1E3F`, `--navy-950 #071230`, `--green-400 #2EE6A8`,
  `--green-600 #0DA874`, urg'u uchun `--amber #FFC24B` va `--sky #63B3FF`.
- **Shriftlar**: sarlavhalar — *Baloo 2*, matn — *Nunito* (Google Fonts).
- Animatsiya: suzuvchi rasmlar (`float`), slayd o'tish `cubic-bezier(.19,1,.22,1)`,
  hisoblagich barlar va 5 yillik o'sish diagrammasi animatsiyasi.

## Eslatma

Deckdagi moliyaviy prognozlar (ARR, foydalanuvchi soni, breakeven) — **maqsadli (target) ko'rsatkichlar**,
kafolat emas. Bozor hajmi raqamlari quyidagi manbalardan: IMARC (Online Travel Market, 2025–2034) va
Market Research Intellect (Travel App Market, 2025–2035). Scam statistikasi: McAfee (2024), FTC (2023),
GoCompare (2024).
