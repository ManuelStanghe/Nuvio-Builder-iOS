# Nuvio Builder iOS

Builder automatico di [Nuvio](https://github.com/NuvioMedia/NuvioMobile) — genera il file `.ipa` in versione **Full** per iOS.

## Come funziona

Un workflow controlla ogni ora la presenza di una nuova versione sul repository ufficiale di Nuvio. Se viene trovata una nuova versione, la compila automaticamente e la pubblica nella sezione [Releases](../../releases).

Il codice sorgente viene scaricato direttamente da `NuvioMedia/NuvioMobile` all'ultimo tag rilasciato, quindi questo repo contiene solo il file del workflow.

## Funzionalità abilitate (build Completa/Full)

- ✅ Plugin
- ✅ Riproduzione trailer in-app

Le build ufficiali di TestFlight rimuovono le funzionalità dei plugin e dei trailer in-app. Ho compilato utilizzando il flag di distribuzione completo, il che significa che i Plugin e i Trailer sono completamente sbloccati.

## Installazione

1. Scarica l'ultima `.ipa` dalla sezione [Releases](../../releases)
2. Installala tramite sideload

## Disclaimer

Questo progetto non è affiliato né approvato dagli sviluppatori di Nuvio. Si limita ad automatizzare il processo di build dal repository ufficiale open-source. Per l'app ufficiale usa [TestFlight](https://testflight.apple.com/join/u4y7MHK9).

Non sono un sviluppatore, quindi non posso risolvere bug o aggiungere nuove funzionalità. Compilato solamente il file `.ipa` direttamente dal codice sorgente originale.
