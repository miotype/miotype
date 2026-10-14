<p align="center">
  <img src="assets/icon.png" width="96" height="96" alt="Icona di MioType">
</p>

<h1 align="center">MioType</h1>

<p align="center">
  <b>Parla, non scrivere.</b> Dettatura vocale e traduzione istantanea per Mac.<br>
  Premi <kbd>Fn</kbd>, parla, premi di nuovo <kbd>Fn</kbd>: il testo compare al cursore, in qualsiasi app.
</p>

<p align="center">
  <a href="https://miotype.com/download"><b>Scarica per macOS</b></a> ·
  <a href="https://miotype.com">Sito web</a> ·
  <a href="https://miotype.com/pricing">Prezzi</a>
</p>

<p align="center"><sub><a href="README.md">English</a> · <a href="README.zh-CN.md">简体中文</a> · <a href="README.de.md">Deutsch</a> · <a href="README.es.md">Español</a> · <a href="README.fr.md">Français</a> · <a href="README.it.md">Italiano</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.pt.md">Português</a> · <a href="README.ru.md">Русский</a></sub></p>

---

Il cursore può essere in un terminale, in VS Code, in Cursor, nel prompt di Claude Code o Codex, in un thread di Slack o in un messaggio di commit: MioType scrive dove si trova il focus.

## Scorciatoie

| Tasti | Cosa succede |
|---|---|
| <kbd>Fn</kbd> | Premi per iniziare a parlare, di nuovo per scrivere. <kbd>Esc</kbd> annulla |
| <kbd>Fn</kbd> + <kbd>Space</kbd> | Chiedi qualsiasi cosa. Seleziona prima un testo per chiedere su quello, oppure di' «rendilo più breve» per riscriverlo sul posto |
| <kbd>Fn</kbd> + <kbd>Left Shift</kbd> | Parla in cinese e ottieni l'inglese, e viceversa |
| <kbd>Fn</kbd> + <kbd>Control</kbd> | Traduce la selezione. Una singola parola inglese apre una scheda del dizionario |
| <kbd>Fn</kbd> + <kbd>R</kbd> | Rifinisce la selezione sul posto |
| <kbd>Fn</kbd> + <kbd>S</kbd> | Cerca una parola o un'espressione |

Tutte le scorciatoie si possono cambiare nelle Impostazioni.

## Perché piace agli sviluppatori

- **Scrive dove si trova il cursore.** Nessuna finestra a parte, nessun copia e incolla. Detta un prompt lungo per il tuo agente di programmazione, la descrizione di una PR o la risposta a una issue direttamente dove serve.
- **Il cinese misto all'inglese resta misto.** Se dici «把这个 function 改成 async», ottieni esattamente questo. I termini inglesi non vengono tradotti in cinese.
- **Impara il tuo vocabolario.** Correggi una parola riconosciuta male subito dopo la dettatura (`kubectl`, `useEffect`, il nome di un collega) e MioType la aggiunge al dizionario, così la prossima volta è giusta. Puoi anche importare un dizionario.
- **Offline con un solo interruttore.** Scegli il modello Whisper locale nelle Impostazioni e la tua voce non lascia mai il Mac. Funziona senza rete e senza account.
- **Usa la tua chiave.** Riconoscimento e rifinitura possono passare dal tuo fornitore di API invece che da MioType Cloud.

## Gratis e a pagamento

| | |
|---|---|
| **Locale** | Gratis per sempre. Dettatura offline con Whisper, traduzione e rifinitura con la tua chiave API. Cronologia, dizionario e impostazioni restano sul tuo Mac |
| **Cloud gratuito** | Accedi e ricevi 3.000 parole cloud ogni settimana |
| **MioType Cloud** | 100.000 parole cloud al mese per riconoscimento nel cloud, rifinitura e traduzione con IA, senza chiave API. 9,99 US$ al mese, 59,99 US$ all'anno o 149 US$ una tantum |

Dettagli nella [pagina dei prezzi](https://miotype.com/pricing). Ogni acquisto è rimborsabile entro 14 giorni, senza domande.

## Privacy

- Whisper locale funziona interamente sul tuo Mac.
- In modalità cloud, l'audio o il testo di ogni richiesta passa dal nostro server ad Alibaba Cloud Model Studio e il risultato torna direttamente a te. Il nostro server non conserva audio né testo: registra solo numero di parole, tipo e ora della richiesta, per calcolare la tua quota.
- Con la tua chiave, le richieste vanno direttamente dal tuo Mac al fornitore scelto.
- Non addestriamo modelli sui tuoi contenuti e non usiamo pubblicità né tracker.
- Informativa completa (in inglese): [miotype.com/privacy](https://miotype.com/privacy)

## Requisiti

- Un Mac con Apple silicon (M1 o successivo)
- Permessi per Microfono e Accessibilità. MioType li chiede durante la configurazione

## Feedback

Hai trovato un bug o vuoi una funzione? [Apri una issue](https://github.com/miotype/miotype/issues/new/choose). Per questioni private, scrivi a [hi@miotype.com](mailto:hi@miotype.com).

Le note di ogni versione sono pubblicate in [Releases](https://github.com/miotype/miotype/releases). Fai clic su **Watch → Custom → Releases** per ricevere gli avvisi.

---

MioType non è open source. Questo repository ospita il tracker pubblico delle issue e le note di versione.
