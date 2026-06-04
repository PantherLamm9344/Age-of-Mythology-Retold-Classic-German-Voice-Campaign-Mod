# 🎮 Age of Mythology: Retold – Classic German Voice Mod

## 📌 Projektübersicht
Diese Modifikation für das Echtzeitstrategiespiel *Age of Mythology: Retold* ersetzt sämtliche neu vertonten deutschen Sprachausgaben der Kampagne durch die klassischen Originalsprecher der ursprünglichen Version. Das Projekt fokussiert sich auf eine saubere technische Integration, die das Basisspiel nicht beschädigt oder modifiziert.

**Erfolg & Community-Feedback:**
* 👥 **Abonnenten:** 11.100+ aktive Nutzer
* ⭐ **Bewertung:** 5/5 Sterne (bei >350 Rezensionen)
* 🔄 **Wartung:** Kontinuierlicher Support mit bisher 7 Major-Updates

🔗 **[Hier geht es zur Live-Version der Mod auf der offiziellen Plattform] (https://www.ageofempires.com/mods/details/286715/)**

---

## ⚙️ Technische Umsetzung (Non-Destructive Modding)

Das Kernziel bei der Entwicklung war es, das "Asset Overriding" so umzusetzen, dass die Integrität der Original-Spieldateien zu 100 % erhalten bleibt. 

Anstatt Kern-Audiodateien hart zu überschreiben, nutzt die Mod das Virtual File System der Engine. Die Architektur spiegelt exakt die Verzeichnisstruktur des Hauptspiels wider. Das Spiel mappt die neuen Audio-Strukturen zur Laufzeit dynamisch über die Vanilla-Dateien. 

**Der technische Vorteil:**
Sobald der Nutzer die Mod im Menü deaktiviert, greift das System sofort wieder auf das Original zurück. Es entsteht kein permanenter Datenverlust und das Spiel erfordert keine fehleranfälligen Reparaturen durch den Client.
