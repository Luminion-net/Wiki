---
title: Admin příkazy
description: Sekce adminů
published: true
date: 2024-05-12T15:51:55.078Z
tags: sekce adminů, příkazy
editor: markdown
dateCreated: 2024-04-24T17:47:40.538Z
---

| Příkaz | Vysvětlení |
|-----------|-----------|
| **/dupeip [hráč]**   | Zobrazí hráčovo alt účty a statusy těchto účtu (Online/Offline nebo Ban/Ipban)   |
| **/nlogin verify [hráč**]   | Zobrazí všechny hráčovo alt účty, UUID, poslední IP, email a jestli má origo přihlašování nebo warez
| **/ban [Hráč] [Důvod**] | Zabanuje pernamentně hráčovo Nick
| **/banip [Hráč] [Délka] [Důvod]** | Zabanuje pernamentně hráčovo Nick + IP
| **/tempban [Hráč] [Délka] [Důvod]**|  Zabanuje dočastne hráčovo Nick
| **/tempbanip [Hráč] [Délka] [Důvod]**| Zabanuje dočastne hráčovo IP + Nick
| **/kick [Hráč] [Důvod]**| Vyhodí hráče z celého networku
| **/mute [Hráč] [Důvod]**|  Pernamentně hráče umlčí, znemožní psát do chatu
| **/ipmute [Hráč] [Délka] [Důvod]**|  Pernamentně hráče + IP umlčí, znemožní psát do chatu
| **/tempmute [Hráč] [Délka] [Důvod]**| Umlčí hráče na určitý čas. znemožní psát do chatu
| **/tempmuteip [Hráč] [Délka] [Důvod]** | Umlčí hráče + IP , znemožní psát do chatu
|**/warn  [Hráč] [Důvod]**| Varuje hráče
| **/pingall**|  Zobrazí ping všech online hráčů
| **/tabtps toggle [bossbar/actionbar]**| Zobrazí informace o výkonu serveru (čím vyšší MSPT tím vyšší zatížení serveru, po cca 45+ MSPT se snižují TPS)
| **/staffchat [text]**| Pošle zprávu do Staff Chatu
| **/staffchathide [staff/admin/dev/all]**| Přepne skrývání určitého Admin Chatu
| **/weather [rain/storm/sun]**| Změní počasí ve světě kde se nacházíš na vybrané
| **/vanish [on/off]**| Zapne/Vypne zneviditelnění se a žádný hráč nemá šanci poznat že jsi na serveru
| **/vanish list** | Zobrazí všechny hráče kteří mají zapnutý vanish

> Na určitý příkazy se nachádzejí i alternativy.
{.is-info}

|----------|-------|
| **/time [day/night/atd.]**| Nastaví specifický čas ve světě kde se nacházíš
| **/clearchat**| Vymaže chat na serveru
| **/fly**| Aktivuje létání
| **/flyspeed [1-10]**|  Nastaví rychlost létání
| **/afk**| Nastaví pro tebe AFK režim
| **/god**| Aktivuje nesmrtelnost
| **/back**| vrátí tě na poslední místo (například na místo před teleportací)
| **/glist all**| Zobrazí všechny hráče na všech serverech
| **/tps**| Zobrazí TPS serveru
| **/tp [Hráč]**| Teleportuje tě na hráče
| **/tp [Hráč pro teleportaci] [Cílový hráč**]| Teleportuje hráče na jiného hráče
| **/tppos [X] [y] [z] [Svět]**| Teleportuje tě na zadané souřadnice 
| **/co lookup [Další příkazy]**| Prohledává svět nebo okolí podle zadaných požadavků
| **/co inspect**| Zapne režim kontroly, zobrazuje informace o interakcích specifického bloku na který klikáš rukou
| **/gmsp**| Nastaví pro tebe spectator mod
| **/gms**|  Nastaví pro tebe survival mod

> Nikdo nemá přístup k **/gmc** [Gamemode Creative] kromě stavebního světa (zatím není).
{.is-danger}
