# Bitcoin Trading Simulator

Český mobilní simulátor obchodování BTC v tmavém vzhledu podle schváleného návrhu.

## Spuštění
Webovou verzi lze otevřít přes `index.html`. Android verze používá WebView a načítá stejný simulátor z lokálních assets.

## Funkce
- BTC/USD kurz z veřejného CoinGecko API (obnovení každých 60 sekund, čas zdrojové aktualizace a stav chyby)
- Virtuální kapitál 100 000 USD
- Long / Short pozice, uzavírání a výpočet zisku či ztráty
- Tržní, limitní a stop příkazy
- Historie, statistiky a výzvy
- Uložení stavu do localStorage a reset

**Upozornění:** pouze tréninková hra bez skutečných peněz a se skutečným spotovým kurzem, nikoli se skutečnými obchody.

## Android APK

Workflow `.github/workflows/android-apk.yml` se automaticky spouští po změnách v `main` a sestavuje debug APK. V GitHub Actions otevřete úspěšný běh a v sekci Artifacts stáhněte `Btc-simulator-APK` (ZIP obsahující `app-debug.apk`). Instalace může vyžadovat povolení instalace z daného zdroje v Androidu.
