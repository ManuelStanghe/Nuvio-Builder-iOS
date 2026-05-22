# Nuvio Builder iOS

Builder automatico di [Nuvio](https://github.com/NuvioMedia/NuvioMobile) — genera l'IPA in versione **Full** per iOS (con plugin e P2P abilitati).

## Come funziona

Un workflow controlla ogni ora la presenza di una nuova versione sul repository ufficiale di Nuvio. Se viene trovata una nuova versione, la compila automaticamente e la pubblica nella sezione [Releases](../../releases).

Il codice sorgente viene scaricato direttamente da `NuvioMedia/NuvioMobile` all'ultimo tag rilasciato, quindi questo repo contiene solo il file del workflow.

## Funzionalità abilitate (build Full)

- ✅ Plugin
- ✅ P2P
- ✅ Riproduzione trailer in-app

Queste funzionalità sono disabilitate nella distribuzione ufficiale via TestFlight.

## Installazione

1. Scarica l'ultima `.ipa` dalla sezione [Releases](../../releases)
2. Installala tramite sideload
3. SideStore rinnoverà automaticamente la firma dell'app ogni 7 giorni

## Disclaimer

Questo progetto non è affiliato né approvato dagli sviluppatori di Nuvio. Si limita ad automatizzare il processo di build dal repository ufficiale open-source. Per l'app ufficiale usa [TestFlight](https://testflight.apple.com/join/u4y7MHK9).
