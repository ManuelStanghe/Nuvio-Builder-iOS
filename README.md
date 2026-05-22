Nuvio Builder iOS
Builder automatico per Nuvio — genera la IPA Full per iOS (con plugin e P2P abilitati) e la pubblica come GitHub Release.
Come funziona
Un workflow GitHub Actions si avvia ogni ora e controlla se è stata rilasciata una nuova versione sul repository ufficiale di Nuvio. Se viene trovata una nuova versione, compila automaticamente la IPA Full e la pubblica qui nella sezione Releases.
Il codice sorgente viene scaricato direttamente da NuvioMedia/NuvioMobile all'ultimo tag rilasciato, quindi questo repo contiene solo il file del workflow.
Funzionalità abilitate (build Full)

✅ Plugin
✅ P2P
✅ Riproduzione trailer in-app

Queste funzionalità sono disabilitate nella distribuzione ufficiale via TestFlight.
Installazione

Scarica l'ultima .ipa dalla sezione Releases
Installala tramite SideStore o LiveContainer
SideStore rinnoverà automaticamente la firma dell'app ogni 7 giorni

Disclaimer
Questo progetto non è affiliato né approvato dagli sviluppatori di Nuvio. Si limita ad automatizzare il processo di build dal repository ufficiale open-source. Per l'app ufficiale usa TestFlight.
