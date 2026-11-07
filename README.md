# Ultimate Amiibo Collection (Archive - October 2026)

A complete archive of amiibo dumps organized by franchise, series, and release type.

---

## Overview & File Formats

This repository contains full dumps across all major amiibo releases up to **October 2026**.

* **`.bin` Files:** Raw binary dumps ready to be written to standard **NTAG215** tags/cards using NFC tools such as TagMo (Android), Ally / Plamiibo (iOS), or standalone NFC writers.
* **`.nfc` Files:** Formatted for direct emulation on NFC-capable devices, including the **Flipper Zero**, ChameleonUltra, AmiiboLink, and compatible multi-tools.

> **Note:** Only genuine NTAG215 chips are hardware-compatible with Nintendo Switch, Wii U, and 3DS amiibo readers. NTAG213 and NTAG216 tags will **not** work.

---

## Included Franchises & Sets

* **Animal Crossing** (Figures, Happy Home Designer Items, Sanrio, Promo, and Series 1–5 Cards)
* **BoxBoy!**
* **Chibi-Robo**
* **Dark Souls**
* **Detective Pikachu**
* **Diablo**
* **Donkey Kong**
* **Fire Emblem**
* **Jikkyou Powerful Pro Baseball**
* **Kirby**
* **Mario** (Figures, 30th Anniversary, Cereal, Sports Superstars, Super Nintendo World Power-Up Bands)
* **Mega Man**
* **Metroid** (Classic, Dread, Metroid Prime 4)
* **Monster Hunter** (Rise / Sunbreak, Stories 1, Stories 2, Stories 3)
* **My Mario**
* **Pikmin**
* **Pokkén Tournament**
* **Pragmata**
* **Resident Evil**
* **Shovel Knight**
* **Skylanders SuperChargers**
* **Splatoon** (Splatoon 1–3, Side Order, Alterna, Raiders)
* **Street Fighter** (SF6 Cards & Figures)
* **Super Mario Bros. Wonder**
* **Super Mario Galaxy**
* **Super Smash Bros.** (Full roster including all DLC up through Sora)
* **The Legend of Zelda** (30th Anniversary, Breath of the Wild, Link's Awakening, Ocarina of Time, Skyward Sword HD, Tears of the Kingdom, Twilight Princess)
* **Xenoblade Chronicles**
* **Yoshi's Woolly World**
* **Yu-Gi-Oh!**

---

## Directory Tree

<details>
<summary><strong>Click to expand full file list</strong></summary>

```text
├── Animal Crossing
│   ├── Cards
│   │   ├── Animal Crossing x Sanrio Series
│   │   │   ├── [AC] XS1 - Rilla.bin
│   │   │   ├── [AC] XS2 - Marty.bin
│   │   │   ├── [AC] XS3 - Étoile.bin
│   │   │   ├── [AC] XS4 - Chai.bin
│   │   │   ├── [AC] XS5 - Chelsea.bin
│   │   │   └── [AC] XS6 - Toby.bin
│   │   ├── Promo
│   │   │   ├── [AC] AF1 - Stitches.bin
│   │   │   ├── [AC] AF2 - Rosie.bin
│   │   │   ├── [AC] AF3 - Goldie.bin
│   │   │   ├── [AC] CP1 - Isabelle.bin
│   │   │   └── [AC] CP2 - K.K Slider.bin
│   │   ├── Series 1
│   │   │   ├── [AC] 001 - Isabelle.bin ... [AC] 100 - Walker.bin (100 files)
│   │   ├── Series 2
│   │   │   ├── [AC] 101 - K.K. Slider.bin ... [AC] 200 - Rocket.bin (100 files)
│   │   ├── Series 3
│   │   │   ├── [AC] 201 - Rover.bin ... [AC] 300 - Chrissy.bin (100 files)
│   │   ├── Series 4
│   │   │   ├── [AC] 301 - Isabelle.bin ... [AC] 400 - Robin.bin (100 files)
│   │   ├── Series 5
│   │   │   ├── [AC] 401 - Tom Nook.bin ... [AC] 448 - Faith.bin (48 files)
│   │   └── Welcome amiibo Series
│   │       ├── [AC] W01 - Vivian.bin ... [AC] W50 - Tasha.bin (50 files)
│   ├── Figures
│   │   ├── [AC] 01 - Isabelle.bin
│   │   ├── [AC] 02 - K.K. Slider.bin
│   │   ├── [AC] 03 - Lottie.bin
│   │   ├── [AC] 04 - Reese.bin
│   │   ├── [AC] 05 - Cyrus.bin
│   │   ├── [AC] 06 - Tom Nook.bin
│   │   ├── [AC] 07 - Mabel.bin
│   │   ├── [AC] 08 - Digby.bin
│   │   ├── [AC] 09 - Resetti.bin
│   │   ├── [AC] 10 - Blathers.bin
│   │   ├── [AC] 11 - Kicks.bin
│   │   ├── [AC] 12 - Celeste.bin
│   │   ├── [AC] 13 - Timmy & Tommy.bin
│   │   ├── [AC] 14 - Rover.bin
│   │   ├── [AC] 15 - Kapp'n.bin
│   │   └── [AC] 16 - Isabelle (Summer Outfit).bin
│   └── Happy Home Designer Items
│       ├── !HHD Items List.docx
│       └── -HHD- Items - 01.bin ... -HHD- Items - 91.bin (91 files)
├── BoxBoy!
│   └── [BB] 01 - Qbby.bin
├── Chibi-Robo
│   └── [CR] 01 - Chibi-Robo.bin
├── Dark Souls
│   └── [DS] 01 - Solaire of Astora.bin
├── Detective Pikachu
│   └── [DEP] 01 - Detective Pikachu.bin
├── Diablo
│   └── [D] 01 - Loot Goblin.bin
├── Donkey Kong
│   └── [DK] 01 - Donkey Kong and Pauline.bin
├── Fire Emblem
│   ├── [FE] 01 - Alm.bin
│   ├── [FE] 02 - Celica.bin
│   ├── [FE] 03 - Chrom.bin
│   └── [FE] 04 - Tiki.bin
├── Jikkyou Powerful Pro Baseball
│   ├── [JPPB] 01 - Pawapuro.bin
│   ├── [JPPB] 02 - Ikari.bin
│   ├── [JPPB] 03 - Yabe.bin
│   ├── [JPPB] 04 - Hayakawa.bin
│   ├── [JPPB] 05 - Ganda.bin
│   └── [JPPB] 06 - Daijobu.bin
├── Kirby
│   ├── [Kirby] 01 - Kirby.bin
│   ├── [Kirby] 02 - Meta Knight.bin
│   ├── [Kirby] 03 - King Dedede.bin
│   └── [Kirby] 04 - Waddle Dee.bin
├── Mario
│   ├── Mario Sports Superstars
│   │   └── [MSS] 01 - Mario (Soccer).bin ... [MSS] 90 - Pink Gold Peach (Horse Racing).bin (90 files)
│   ├── Super Mario Bros. 30th Anniversary
│   │   ├── [3AM] 01 - Mario Classic Colors.bin
│   │   └── [3AM] 02 - Mario Modern Colors.bin
│   ├── Super Mario Cereal
│   │   └── [SMC] 01 - Super Mario Cereal.bin
│   ├── Super Mario Figures
│   │   ├── [SM] 01 - Mario.bin ... [SM] 22 - Cat Peach.bin (22 files)
│   └── Super Nintendo World Power-Up Bands
│       ├── [SNW] 01 - Mario Power-Up Band.bin ... [SNW] 10 - Invincible Power-Up Band.bin (10 files)
├── Mega Man
│   └── [MM] 01 - Mega Man.bin
├── Metroid
│   ├── [MET] 01 - Samus Aran.bin
│   └── [MET] 02 - Metroid.bin
├── Metroid dread
│   ├── [METD] 01 - SAMUS.bin
│   └── [METD] 02 - E.M.M.I.bin
├── Metroid Prime 4
│   ├── [MP4] 01 - Samus.bin
│   ├── [MP4] 02 - Samus & Vi-O-La.bin
│   └── [MP4] 03 - Sylux.bin
├── Monster Hunter Rise
│   ├── [MHR] 01 - Palamute.bin
│   ├── [MHR] 02 - Magnamalo.bin
│   ├── [MHR] 03 - Palico.bin
│   └── Sunbreak
│       ├── [MHR] 01 - Malzeno.bin
│       ├── [MHR] 02 - Palamute Canyne Malzeno.bin
│       └── [MHR] 03 - Palico Felyne Malzeno.bin
├── Monster Hunter Stories
│   ├── [MHS] 01 - One-Eyed Rathalos and Rider (Female).bin
│   ├── [MHS] 02 - One-Eyed Rathalos and Rider (Male).bin
│   ├── [MHS] 03 - Nabiru.bin
│   ├── [MHS] 04 - Rathian and Cheval.bin
│   ├── [MHS] 05 - Barioth and Ayuria.bin
│   └── [MHS] 06 - Qurupeco and Dan.bin
├── Monster Hunter Stories 2
│   ├── [MHS] 01 - Ena.bin
│   ├── [MHS] 02 - Razewing Ratha.bin
│   └── [MHS] 03 - Tsukino.bin
├── Monster Hunter Stories 3
│   ├── [MHS] 01 - Rudy.bin
│   ├── [MHS] 02 - Ratha.bin
│   └── [MHS] 03 - Ratha V.bin
├── My Mario
│   ├── [MM] 01 - Tsumiki Mario.bin
│   ├── [MM] 02 - Tsumiki Luigi.bin
│   ├── [MM] 03 - Tsumiki Peach.bin
│   ├── [MM] 04 - Tsumiki Yoshi.bin
│   ├── [MM] 05 - Tsumiki Mario.bin
│   └── [MM] 06 - Tsumiki Toad.bin
├── Pikmin
│   └── [PIK] 01 - Pikmin.bin
├── Pokkén Tournament
│   └── [PT] 01 - Shadow Mewtwo.bin
├── Pragmata
│   └── [PMA] 01 - Diana.bin
├── Resident Evil
│   ├── [RE] 01 - Grace Ashcroft.bin
│   └── [RE] 02 - Leon S. Kennedy.bin
├── Shovel Knight
│   ├── [SN] 01 - Shovel Knight.bin
│   ├── [SN] 02 - Plague Knight.bin
│   ├── [SN] 03 - Specter Knight.bin
│   ├── [SN] 04 - King Knight.bin
│   └── [SN] 05 - Shovel Knight (Gold Edition).bin
├── Skylanders SuperChargers
│   ├── [SS] 01 - Hammer Slam Bowser.bin
│   ├── [SS] 02 - Turbo Charge Donkey Kong.bin
│   ├── [SS] 03 - Dark Hammer Slam Bowser.bin
│   └── [SS] 04 - Dark Turbo Charge Donkey Kong.bin
├── Splatoon
│   ├── [Splatoon] 01 - Inkling Boy.bin ... [Splatoon] 26 - Callie (Alterna).bin (26 files)
│   └── Raiders
│       ├── [Splatoon] 01 - Big Man (Raiders).bin
│       ├── [Splatoon] 02 - Shiver (Raiders).bin
│       └── [Splatoon] 03 - Frye (Raiders).bin
├── Street Fighter
│   ├── Cards
│   │   └── [SF6] 01 - Luke [Card].bin ... [SF6] 60 - Ingrid.bin (60 files)
│   └── Figures
│       ├── [SF6] 01 - Luke [Fig].bin
│       ├── [SF6] 02 - Jamie [Fig].bin
│       └── [SF6] 03 - Kimberly [Fig].bin
├── Super Mario Bros Wonder
│   ├── [MBW] 01 - Elephant Mario.bin
│   ├── [MBW] 02 - Poplin & Prince Florian.bin
│   └── [MBW] 03 - Captain Toad & Talking Flower.bin
├── Super Mario Galaxy
│   ├── [SMG] 01 - Mario and Luma.bin
│   └── [SMG] 02 - Rosalina and Lumas.bin
├── Super Smash Bros
│   └── [SSB] 01 - Mario.bin ... [SSB] 93 - Sora.bin (94 files total)
├── The Legend of Zelda
│   ├── The Legend of Zelda 30th Anniversary
│   │   ├── [3AZ] 01 - 8-bit Link (The Legend of Zelda).bin
│   │   ├── [3AZ] 02 - Link (Ocarina of Time).bin
│   │   ├── [3AZ] 03 - Toon Link (The Wind Waker).bin
│   │   ├── [3AZ] 04 - Toon Zelda (The Wind Waker).bin
│   │   ├── [3AZ] 05 - Link (Majora's Mask).bin
│   │   ├── [3AZ] 06 - Link (Twilight Princess).bin
│   │   └── [3AZ] 07 - Link (Skyward Sword).bin
│   ├── The Legend of Zelda Breath of the Wild
│   │   ├── [ZBW] 01 - Bokoblin.bin ... [ZBW] 09 - Urbosa (Gerudo Champion).bin (9 files)
│   ├── The Legend of Zelda Link's Awakening
│   │   └── [ZLA] 01 - Link.bin
│   ├── The Legend of Zelda Ocarina of Time
│   │   ├── [OOT] 01 - Young Zelda.bin
│   │   └── [OOT] 02 - Young Link.bin
│   ├── The Legend of Zelda Skyward Sword HD
│   │   └── [SS] 01 - Zelda & Loftwing.bin
│   ├── The Legend of Zelda Tears of the Kingdom
│   │   ├── [TotK] 01 - Link.bin ... [TotK] 08 - Mineru's Construct.bin (8 files)
│   └── The Legend of Zelda Twilight Princess
│       ├── important.txt
│       └── [ZTP] 20H Wolf Link.bin
├── Xenoblade Chronicles
│   ├── [XBC] 01 - Noah.bin
│   └── [XBC] 02 - Mio.bin
├── Yoshi's Woolly World
│   ├── [YWW] 01 - Green Yarn Yoshi.bin
│   ├── [YWW] 02 - Pink Yarn Yoshi.bin
│   ├── [YWW] 03 - Light-Blue Yarn Yoshi.bin
│   ├── [YWW] 04 - Mega Yarn Yoshi.bin
│   └── [YWW] 05 - Poochy.bin
└── Yu-Gi-Oh
    ├── [YU-GI-OH] 01 - Yuga Ohdo.bin
    ├── [YU-GI-OH] 02 - Tatsuhisa Luke Kamijo.bin
    ├── [YU-GI-OH] 03 - Gakuto Sogetsu.bin
    ├── [YU-GI-OH] 04 - Romin Kirishima.bin
    ├── [YU-GI-OH] 05 - Roa Kirishima.bin
    ├── [YU-GI-OH] 06 - Nail Saionji.bin
    └── [YU-GI-OH] 07 - Asana Mutsuba.bin
