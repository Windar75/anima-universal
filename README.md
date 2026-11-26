# Anima∞ — anteprima 0.1.0-rc.2

Anima∞ è un profilo operativo eseguito dal modello dell'assistente che già usi. Il pacchetto contiene solo testo:
due skill, nessun programma, nessun server, nessun accesso ad account altrui.

- anima-universal-public: metodo operativo per verificare un'ipotesi, sviluppare un'idea o portare a termine un lavoro.
- anima-memory-drive: memoria personale che resta nel tuo Google Drive, letta e scritta dal connettore Drive del tuo
  assistente. La skill chiede il tuo consenso prima di creare la cartella. Nessun dato arriva all'autore.

## Archivi della release
| Archivio | Per |
|---|---|
| claude-skill | Claude, caricamento della skill del metodo |
| claude-skill-memory | Claude, caricamento della skill di memoria |
| claude-plugin | Claude Code, plugin con entrambe le skill |
| claude-code-marketplace | Claude Code, catalogo locale |
| chatgpt-codex | ChatGPT e Codex, plugin con entrambe le skill |
| codex-local-marketplace | Codex, catalogo locale |
| antigravity | Antigravity, plugin con entrambe le skill |

## Verifica prima di installare
Calcola l'impronta SHA-256 dell'archivio scaricato e confrontala con quella elencata nel manifest della release.
Se non coincide, non installarlo.

## Compatibilità
Verificata (prove registrate dall'autore il 25 e 26 novembre 2026):
- Claude (app): skill di memoria installata; lettura, scrittura, consolidamento e ripristino della memoria sul Drive.
  Verificata con il testo della skill installato nell'account dell'autore, non ancora installando questi archivi.
- ChatGPT: lettura della memoria sul Drive (indice, preferenze, decisioni). Solo lettura.

Sperimentale (non ancora provata, procedura prevista):
- Claude: caricamento dell'archivio claude-skill del metodo dalle impostazioni delle skill.
- Claude Code: catalogo locale dalla cartella estratta di claude-code-marketplace, poi installazione del plugin.
- Codex: catalogo locale dalla cartella estratta di codex-local-marketplace, poi installazione del plugin.
- ChatGPT: plugin chatgpt-codex dal portale dei plugin del tuo account, se il piano lo consente; scrittura della memoria.
- Antigravity: installazione del plugin dalla cartella estratta di antigravity.
- Attivazione spontanea della memoria senza istruzioni personali: non dimostrata su nessun host.
Per la memoria collega il tuo Google Drive all'assistente. Senza connettore Drive il metodo funziona senza memoria.

## Aggiornamento e disinstallazione
Sostituisci il plugin o la skill con la nuova versione. La memoria non sta nel pacchetto: aggiornare o rimuovere la
skill non tocca i tuoi dati nel Drive.

## Limiti dichiarati
Nessuna garanzia che l'assistente usi la skill in ogni conversazione. Nessuna memoria universale. Le capacità dipendono
dall'host e dal tuo piano.

## Licenza
© 2026 Manuel Bassanelli (Master Minder), creatore del progetto Anima∞.
Per contatti: manuel.bassanelli@gmail.com
I materiali di questa distribuzione pubblica (le due skill, i file di configurazione dei plugin, il manifest, gli archivi
e questo README) sono concessi con licenza Creative Commons Attribuzione 4.0 Internazionale (CC BY 4.0); i termini e il
riferimento al testo legale ufficiale sono nel file LICENSE. Sono esclusi infrastruttura privata, memoria personale, credenziali e componenti riservati, che non
fanno parte di questa distribuzione.
