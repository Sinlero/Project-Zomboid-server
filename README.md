Original server image: [afey/zomboid](https://hub.docker.com/r/afey/zomboid)

Before start create folder: ```server-data```

Start server

```bash
docker-compose up
```

---

# Installing mods

Open

```text
server-data/Server/{name-server}.ini
```

Find params

```text
Mods=
...
WorkshopItems=
```

In ```Mods=``` add Mod ID \
In ```WorkshopItems=``` add Workshop ID

Example

```text
Mods=NoLighterNeeded;wringclothes;DRK_1
WorkshopItems=2714198296;2696083206;2611652130
```

Restart server

```bash
docker-compose down; docker-compose up -d
```

---

# List of our server mods


[I Don't Need A Lighter](https://steamcommunity.com/sharedfiles/filedetails/?id=2714198296)

Подкуривать от всего

```text
Workshop ID: 2714198296
Mod ID: NoLighterNeeded
```

---

[Wring Out Clothing](https://steamcommunity.com/sharedfiles/filedetails/?id=2696083206)

Выжимать мокрую одежду

```text
Workshop ID: 2696083206
Mod ID: wringclothes
```

---

[USMC Armory](https://steamcommunity.com/sharedfiles/filedetails/?id=2611652130)

Броня морпехов

```text
Workshop ID: 2611652130
Mod ID: DRK_1
```

---

[Silencer / Suppressor Mod (Build 41)](https://steamcommunity.com/sharedfiles/filedetails/?id=639909479)

Глушители

```text
Workshop ID: 639909479
Mod ID: Silencer
```

---

[Rain Wash](https://steamcommunity.com/sharedfiles/filedetails/?id=2657661246)

Стираться под дождём

```text
Workshop ID: 2657661246
Mod ID: RainWash
```

---

[Craft Helper (41.x)](https://steamcommunity.com/sharedfiles/filedetails/?id=2186592938)

Более понятное мменю крафта

```text
Workshop ID: 2186592938
Mod ID: CraftHelper41
```

---

[Extra Map Symbols](https://steamcommunity.com/sharedfiles/filedetails/?id=2701170568)

Больше символов для карты

```text
Workshop ID: 2701170568
Mod ID: ExtraMapSymbols
Mod ID: ExtraMapSymbolsUI
```

---

[Clothes BOX (41)](https://steamcommunity.com/sharedfiles/filedetails/?id=2507488373)

Больше одежды

```text
Workshop ID: 2507488373
Mod ID: 2507488373
```

---

[Jump Through Windows](https://steamcommunity.com/sharedfiles/filedetails/?id=2688884240)

Паунс в окно

```text
Workshop ID: 2688884240
Mod ID: jumpThroughWindows
```

---

[Улучшенная буксировка](https://steamcommunity.com/sharedfiles/filedetails/?id=2241990680)

```text
Workshop ID: 2241990680
Mod ID: TowingCar
```

---

[SWAT & RIOT PACK for BUILD[41.53+]](https://steamcommunity.com/sharedfiles/filedetails/?id=2091564445)

Броня SWAT и др.

```text
Workshop ID: 2091564445
Mod ID: Swatpack
```

---

[Repair Any Clothes](https://steamcommunity.com/sharedfiles/filedetails/?id=2142622992)

Починка одежды

```text
Workshop ID: 2142622992
Mod ID: RepairAnyAuthenticZ
Mod ID: RepairAnyBrita
Mod ID: RepairAnyClothes
Mod ID: RepairAnySWAT
```

---

[Just Throw Them Out The Window](https://steamcommunity.com/sharedfiles/filedetails/?id=2659216714)

Кидать трупы в окно

```text
Workshop ID: 2659216714
Mod ID: OutTheWindow
```

---

[GK's Realistic Professions (Build 41)](https://steamcommunity.com/sharedfiles/filedetails/?id=2204106513)

Ребаланс профессий

```text
Workshop ID: 2204106513
Mod ID: GKRealisticProfessions41
```

---

[Better Sorting](https://steamcommunity.com/sharedfiles/filedetails/?id=2313387159)

Улучшенная сортировка

```text
Workshop ID: 2313387159
Mod ID: BetterSortCC
```

---

[Attach Items to Backpacks (build 41)](https://steamcommunity.com/sharedfiles/filedetails/?id=2048847068)

Крепим предметы на рюкзак

```text
Workshop ID: 2048847068
Mod ID: backpackattachments
```

---

['86 Oshkosh P19A + Military Trailers](https://steamcommunity.com/sharedfiles/filedetails/?id=2566953935)

Военные фуры

```text
Workshop ID: 2566953935
Mod ID: 86oshkoshP19A
```

---

['67 Cadillac Gage Commando](https://steamcommunity.com/sharedfiles/filedetails/?id=2478247379)

БТРы

```text
Workshop ID: 2478247379
Mod ID: 67commando
```

---

['92 AM General M998 + M101A3 Cargo trailer](https://steamcommunity.com/sharedfiles/filedetails/?id=2642541073)

Хамви с прицепами

```text
Workshop ID: 2642541073
Mod ID: 92amgeneralM998
```

---

[Expanded Helicopter Events](https://steamcommunity.com/sharedfiles/filedetails/?id=2458631365)

События с вертолетами

```text
Workshop ID: 2458631365
Mod ID: ExpandedHelicopterEvents
```

---

[Tsar's Common Library](https://steamcommunity.com/sharedfiles/filedetails/?id=2392709985)

Основа для ЦАРЬ модов

```text
Workshop ID: 2392709985
Mod ID: tsarslib
```

### ЦАРЬ моды

| Название |Описание|IDs|
|----------|--------|---|
|[ZuperCart - Carts & Trolleys][1]|Тележки из супермаркета и др.|```Workshop ID: 2478768005```<br /> ```Mod ID: TMC_Trolley```|
|[True Actions. Act 3 - Dancing [B41.56+MP]][2]|Танцульки|```Workshop ID:2648779556```<br />```Mod ID: TrueActionsDancing```|
|[True Actions. Act 2 - Lying [MP updated]][3]|Можно сидеть и лежать на мебели|```Workshop ID: 2487022075```<br />```Mod ID: TMC_TrueActions```|
|[True Music [MP updated]][4]|Музыка|```Workshop ID: 2613146550```<br />```Mod ID: truemusic```|
|[Autotsar Tuning Atelier - Jaap Wrungel [MP updated]][5]|Тюнинг джипов|```Workshop ID: 2636100523```<br />```Mod ID: ATA_Jeep```<br />```Mod ID: ATA_Jeep_x10```<br />```Mod ID: ATA_Jeep_x2```<br />```Mod ID: ATA_Jeep_x4```<br />|
|[Autotsar Tuning Atelier - Bus [MP update]][6]|Тюнинг автобусов|```Workshop ID: 2592358528```<br />```Mod ID: ATA_Bus```|
|[Autotsar Trailers [MP updated]][7]|Домики на колесах|```Workshop ID: 2282429356```<br />```Mod ID: autotsartrailers```|
|[Autotsar Tuning Atelier - Fjord [41.56+MP]][8]|Тюнинг фордов|```Workshop ID: 2681635926```<br />```Mod ID: ATA_Mustang```<br />```Mod ID: ATA_Mustang_x2```<br />```Mod ID: ATA_Mustang_x4```|

[1]: https://steamcommunity.com/sharedfiles/filedetails/?id=2478768005
[2]: https://steamcommunity.com/sharedfiles/filedetails/?id=2648779556
[3]: https://steamcommunity.com/sharedfiles/filedetails/?id=2487022075
[4]: https://steamcommunity.com/sharedfiles/filedetails/?id=2613146550
[5]: https://steamcommunity.com/sharedfiles/filedetails/?id=2636100523
[6]: https://steamcommunity.com/sharedfiles/filedetails/?id=2592358528
[7]: https://steamcommunity.com/sharedfiles/filedetails/?id=2282429356
[8]: https://steamcommunity.com/sharedfiles/filedetails/?id=2681635926
