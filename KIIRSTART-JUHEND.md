# Kiirstart-juhend — Kasulik AI Plugins

Seadista oma AI töökeskkond enne koolitust. Kokku ~15 minutit.

---

## 1. Loo Claude konto (2 min)

Mine [claude.ai](https://claude.ai) ja loo tasuta konto. Võid kasutada Google'i, Apple'i või e-posti kontot. Tasuta plaan (Free) sobib alustamiseks, Pro plaan ($20/kuu) annab rohkem sõnumeid ja ligipääsu Cowork režiimile.

## 2. Ava Cowork režiim (1 min)

Claude töölauarakenduses (macOS / Windows) vali vasakult menüüst **Cowork**. Kui kasutad claude.ai veebis, on Cowork saadaval Pro plaanil.

## 3. Paigalda pluginad (5 min)

Kirjuta Cowork vestlusse:

```
/plugin marketplace add kasulik-ai/plugins
```

Seejärel paigalda kõik 5 pluginat:

```
/plugin install kasulik-tööruum@kasulik-ai-plugins
/plugin install kasulik-turundus@kasulik-ai-plugins
/plugin install kasulik-müük@kasulik-ai-plugins
/plugin install kasulik-strateegia@kasulik-ai-plugins
/plugin install kasulik-turism@kasulik-ai-plugins
```

Iga plugin paigaldub mõne sekundiga. Kokku saad 24 skilli.

## 4. Seadista töökeskkond (5 min)

Kirjuta Cowork vestlusse:

```
/alusta
```

See käsk tuvastab sinu praeguse olukorra ja juhendab sind edasi. Kui oled täitsa uus, aitab sul luua CLAUDE.md konfiguratsioonifaili ja seadistada mälu.

## 5. Loo oma AI assistent (5 min, valikuline)

```
/agendid
```

AI küsib sinult 8 küsimust ettevõtte kohta, skanneerib sinu veebilehe ja loob personaalse assistendi. See samm teeb kõik järgmised käsud paremaks, sest AI tunneb sinu äri konteksti.

## 6. Kontrolli, et kõik töötab

Proovi mõnda käsku:

```
/töövood
```

Peaksid nägema 12 eelseadistatud töövoogu. Kui näed, oled valmis!

---

## Levinumad probleemid

**"Plugin not found"** — kontrolli, et marketplace on lisatud (samm 3 esimene käsk).

**Käsk ei käivitu** — kontrolli kirjapilti. Kõik käsud algavad kaldkriipsuga ja on eesti keeles (nt `/arvustus`, mitte `/review`).

**Cowork pole saadaval** — Cowork nõuab Claude Pro plaani ($20/kuu) ja töölauarakendust.

**Tühi kirjeldus skilli juures** — uuenda pluginad uusimale versioonile.

---

## Ettevalmistus koolituseks

Hea, kui sul on enne koolitust valmis:

1. **Üks arvustus** (Google, Booking vms) — proovime sellele vastata
2. **Üks kliendi e-kiri** — harjutame vastuse koostamist
3. **Oma kodulehe aadress** — AI saab sinu äri kohta konteksti

Koolituse ajal kasutame peamiselt: `/arvustus`, `/klient`, `/tekst`, `/agendid`

---

*Kasulik AI · kasulik.ai · v3.1*
