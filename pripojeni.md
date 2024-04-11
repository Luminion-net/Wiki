---
title: Jak se připojit?
description: Základní informace
published: true
date: 2024-04-11T11:03:13.113Z
tags: připojení, ip, verze
editor: markdown
dateCreated: 2024-04-09T16:06:43.579Z
---

> Server podporuje verze 1.8.x-1.20.x Java Edition.
{.is-success}

Na server se lze připojit zadáním adresy `play.luminion.net` do adresního řádku serveru. Server si můžeš přidat do svého seznamu nebo se připojit přímo.

# FAQ
> Zde najdeš nejčastější dotazy hráčů ohledně připojení.
{.is-info}

Pokud žádný z těchto dotazů neobsahuje odpověď na tvoji otázku, neváhej založit ticket na našem [Discordu](https://discord.luminion.net) nebo [Webu](https://luminion.net). Rádi ti na tvoji otázku odpovíme. Další možností je napsat na email support@luminion.net.

## Mám Pocket Edition. Mohu se připojit?
> Server je dostupný pouze pro Java Edition.
{.is-danger}

Bohužel, server je v současnosti dostupný pouze pro **Java Edition**, tedy jen pro PC. Existuje sice možnost si Java Edition nainstalovat do mobilního zařízení pomocí aplikace *PojavLauncher*, ale tento způsob připojení rozhodně nedoporučujeme. Aplikace je nestabilní a mobilní zařízení nemá na plnohodnotnou hru dostatek výkonu. Hráči herních konzolí mají smůlu, pro ně neexistuje žádný, ani neoficiální způsob, jakým se mohou na server připojit.

## Server odmítl moje připojení.
Je několik důvodů, proč se tak stalo. Nejčastějším důvodem je AntiBot, který analyzuje podezřelé IP adresy. Na server se můžeš znovu připojit, neměl by tě znovu vykopnout. Pokud by se tak ovšem stalo, a neznáš příčinu (příčina se běžně ukáže na obrazovce), zkontroluj si postupně následující seznam:
1. **Nepřipojuješ se přes VPN?** VPN servery umožňují hráčům maskovat jejich IP adresy. To sice může být užitečné pro zachování soukromí, nicméně existuje riziko, že VPN služeb budou zneužívat nepoctiví hráči, kteří chtějí obcházet udělený ban a dále škodit, a proto VPN služby (včetně sítě Tor) blokujeme.
2. **Nemáš aktivní proxy?** Proxy servery jsou do určité míry podobné VPN. Vlastně VPN je proxy server, který připojení navíc šifruje, a tím více maskuje identitu uživatele. Pokud jsi připojen na veřejnou proxy, IP adresa je s největší pravděpodobností blokována.
3. **Zkontroluj si připojení k internetu.** Tvé připojení může být extrémně pomalé, že server nedokáže připojení zpracovat. Změř si ping a rychlost připojení. Užitečným pomocníkem může být např. Speedtest.net.
4. **Zkontroluj si propustnost sítě.** Někdy může být příčinou pomalého připojení samotná domácí síť. Pokud máš přístup k nastavení routeru, můžeš provést test propustnosti sítě. Případně požádej svého rodiče o pomoc.

## Mám lagy.
Lagy jsou nepříjemné a někdy mohou způsobit samovolné odpojení ze serveru. Příčinou je téměř vždy připojení k internetu. Zkontroluj si ping a rychlost připojení. Ping ti většinou ukáže přímo server, ale rychlost připojení už si musíš změřit sám/sama. Užitečným pomocníkem v tomto případě může být Speedtest.net.

## Nedaří se mi přihlásit/registrovat
Server má možnost přihlašování s platnou placenou licencí hry. To znamená, že hráč, který si hru koupil, se nemusí přihlašovat pomocí hesla. Jeho účet je automaticky chráněn. Hráči se musí při každém připojení registrovat a zvolit si heslo.  Stejné heslo by mělo být platné i na webu Luminion.net. Další připojení si žádá poté zadání zvoleného hesla. Pokud jsi zapomněl/-a své heslo a máš nastavený email u svého účtu, otevři [Web](https://luminion.net/recover-account), vyplň údaje a po potvrzení ti přijde email s odkazem pro obnovení hesla, v opačném případě, napiš na podporu.

# Servery
> Náš server je tzv. multi-server. To znamená, že máme proxy server, přes který se lze připojit na další dílčí servery v naší nabídce. Nabídku hodláme v budoucnu rozšiřovat podle zájmu.
{.is-info}

## Lobby
Tento server je vstupní branou do naší nabídky. Je zde pouze spawn s několika NPC, které poskytují přístup na další servery. Každý hráč se při připojení ocitne vždy na spawnu a v jejich inventáři v hotbaru se nachází předměty, kterými lze ovládat GUI. Nejdůležitějším předmětem je netherová hvězda, která otevírá menu s výběrem serverů.

![lobby_npcs.png](/lobby_npcs.png)
Lobby spawn a NPC

![lobby_server_selector.png](/lobby_server_selector.png)
GUI menu výběru serveru

## Survival
> Více informací se dozvíš na stránce [Survival](/survival).
{.is-info}

Pestrý server s rozšířenou generací světa, herní ekonomikou a MMO-RPG prvky, které z hrani vytváří neobyčejný zážitek. Plň questy, obchoduj s ostatními hráči, nebo prostě jen prozkoumávej svět.

> Server má zapnuté PVP. Chceš-li své věci chránit, zvaž vytvoření nebo přihlášku do nějakého [pozemku](/pozemky).
{.is-warning}

## PVP Practice
> Více informací se dozvíš na stránce [PVP Practice](/pvp-practice).
{.is-info}

Miniherní server určený pro fanoušky PVP. Jedná se o cvičební server, kde si hráči mohou vyzkoušet různé PVP duely nebo týmové souboje, nebo se mohou zkrátka navzájem mlátit (režim *Free For All*).

## Vanilla
> Server je momentálně uzavřen. Podle zájmu plánujeme server v budoucnu znovu otevřít.
{.is-danger}

Semi-vanilla server s minimem pluginů. Na serveru se nachází jen nutné minimum k zajištění zabezpečení světa a hráčů. Hra samotná je velmi blízko k výchozí hře v single player světě.