# 🥛 MÆLK Sign Edit

**Copy, Paste og gemte skilte direkte i Minecrafts skilte-editor.**

Minecraft Java **26.3** · **Fabric** · Kun på klienten

### [📥 Download seneste version](https://github.com/RolfDenDanske/maelk-sign-edit-download/releases/latest)

## Sådan ser funktionerne ud

| Placering | Funktion |
| --- | --- |
| Til højre for skiltet | **Copy** kopierer alle fire tekstlinjer. **Paste** indsætter fra udklipsholderen. |
| Over skiltet | Et **gemmeikon** gemmer de fire linjer som en skabelon. |
| Til venstre | **Gemte skilte** viser dine skabeloner. Klik på en for at indsætte teksten. |

Scroll i listen for at se flere gemte skilte. Klik **×** på en skabelon for at fjerne den fra biblioteket. De nyeste skabeloner vises øverst, og identiske skilte gemmes ikke som dubletter.

**Gemmeikonet gemmer en lokal skabelon.** Når skiltets tekst er klar, bruger du Minecrafts almindelige **Færdig**-knap til at sende den til serveren.

## Installation

Kræver **Minecraft Java 26.3**, **Fabric Loader 0.20.1 eller nyere** og **Fabric API 0.166.2+26.3 eller nyere til 26.3**.

1. Installer [Fabric til Minecraft 26.3](https://fabricmc.net/use/installer/).
2. Hent [Fabric API til 26.3](https://modrinth.com/mod/fabric-api/versions?g=26.3&l=fabric).
3. Hent **`maelk-sign-edit-1.0.0.jar`** under Assets på [downloadsiden](https://github.com/RolfDenDanske/maelk-sign-edit-download/releases/latest).
4. Læg moddet og Fabric API i Fabric-profilens `mods`-mappe.
5. Genstart Minecraft, og åbn et skilt på normal vis.

Der er ingen keybind og ingen ekstra menu. Funktionerne vises automatisk i editoren på almindelige skilte og hængeskilte.

## Gemte skilte

Biblioteket ligger lokalt i **`config/maelk-sign-edit/saved-signs.json`** og bliver bevaret, når du lukker og åbner Minecraft. Dine gemte tekster uploades ikke til GitHub og deles ikke med andre spillere.

Moddet kopierer de fire tekstlinjer på den side, du redigerer. Træsort, farve, glow og den anden side ændres ikke. Tomme linjer og mellemrum bevares. Serverens normale regler for redigering af skilte gælder fortsat.

Ved Paste bruges de første fire linjer fra udklipsholderen. Hvis en linje er for bred til skiltet, afkortes den, og der vises en besked om tilpasningen. Et hængeskilt kan have mindre plads til tekst end et almindeligt skilt.

## Hjælp

[Opret en fejlrapport](https://github.com/RolfDenDanske/maelk-sign-edit-download/issues/new) med Minecraft-version, modversion og en beskrivelse af fejlen. Tilføj gerne et billede af editoren uden private oplysninger.

Version **1.0.0** er bygget og har bestået **20 automatiske tests** for tekst, Unicode, gemning, layout og integrationens Minecraft-metoder. Visningen og serverintegrationen skal stadig afprøves i spillet.

## Downloadsiden

Dette repository indeholder kun beskrivelsen, installationsguiden og licensen. **Moddets kildekode er privat.** GitHubs automatiske “Source code”-arkiver indeholder derfor kun sidens dokumenter; spillere skal hente **JAR-filen under Assets**.

Moddet distribueres under [MIT-licensen](LICENSE).

*Et uafhængigt modprojekt til MÆLK-spillere. Ikke et officielt Minecraft-produkt og ikke godkendt af eller tilknyttet Mojang eller Microsoft.*
