# Návod na použitie repozitára

Tento repozitár je určený na dokumentovanie ArchiMate modelov a súvisiacich metodických podkladov k dizertačnej práci.

## 1. Základné použitie

Používateľ môže repozitár využiť na:

- oboznámenie sa s návrhovými modelmi,
- kontrolu štruktúry ArchiMate prvkov,
- rozšírenie modelov v nástroji Archi,
- export modelov do obrázkových alebo dokumentačných formátov,
- prípravu podkladov pre odbornú diskusiu alebo obhajobu.

## 2. Odporúčaný pracovný postup

1. Otvoriť súbor `README.md` a oboznámiť sa s účelom repozitára.
2. Prečítať dokument `docs/01-kontext-dizertacnej-prace.md`.
3. Pokračovať dokumentmi k jednotlivým modelom:
   - `docs/02-motivacny-model.md`,
   - `docs/03-realizacny-model.md`.
4. Skontrolovať štruktúrované tabuľky prvkov v priečinku `tables/`.
5. Vložiť alebo aktualizovať zdrojové súbory modelov v priečinku `models/`.
6. Exportované obrázky alebo PDF výstupy ukladať do `models/export/`.

## 3. Práca s modelmi v Archi

Na prácu s modelmi odporúčame použiť nástroj Archi. Zdrojové súbory modelov ukladajte do priečinka `models/`. Exporty modelov ukladajte do priečinka `models/export/`.

Odporúčané názvy súborov:

```text
models/motivacny-model.archimate
models/realizacny-model.archimate
models/export/obrazok-12-motivacny-model.png
models/export/obrazok-13-realizacny-model.png
```

## 4. Verzionovanie

Pri každej významnej úprave modelu odporúčame vytvoriť nový commit s opisom zmeny. Vhodné správy commitov:

```text
Update motivational model elements
Update implementation model relationships
Add exported ArchiMate diagrams
Revise MetaIS documentation
```

## 5. Odporúčanie pre akademické použitie

Pri citovaní repozitára odporúčame uviesť, že ide o podporný výskumný artefakt k dizertačnej práci. Primárnym vedeckým zdrojom zostáva samotná dizertačná práca.
