# Bitcoin Trading Simulator

Český mobilní simulátor obchodování BTC v tmavém vzhledu podle schváleného návrhu.

## Spuštění
Otevřete soubor `index.html` v prohlížeči. Jde o první funkční webovou verzi připravenou pro další zabalení do Android APK.

## Funkce
- Simulovaný BTC/USD svíčkový graf (generované ceny, **nikoli živý kurz**)
- Virtuální kapitál 100 000 USD
- Long / Short pozice, uzavírání a výpočet zisku či ztráty
- Tržní, limitní a stop příkazy
- Historie, statistiky a výzvy
- Uložení stavu do localStorage a reset

**Upozornění:** pouze tréninková hra bez skutečných peněz. Nejde zatím o nativní Android APK ani burzovní data.

## Android APK

Automatické sestavení běží v GitHub Actions (`.github/workflows/android-apk.yml`) při každém push do `main`. Hotový debug APK je v artefaktu `Btc-simulator-APK` příslušného běhu. Jde o testovací verzi s virtuálními cenami.
