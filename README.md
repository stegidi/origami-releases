# Ciao! Benvenuto su Origami 📐

Ho creato **Origami** per risolvere una delle cose più scomode su Mac: dover sempre usare il mouse per spostare, affiancare e ridimensionare le finestre.

Con Origami fai tutto da tastiera in un secondo:
* Tieni premuto **fn** (il tasto in basso a sinistra con il mappamondo 🌐).
* Premi **Tab** (o le frecce) per scegliere la disposizione della finestra (metà schermo, terzi, centrata, ecc.).
* Rilascia **fn** per applicare. Fine!

---

### 🚀 Download e Primo Avvio (Cosa fare)

👉 **[Scarica l'ultima versione di Origami (.zip)](https://github.com/stegidi/origami-releases/releases/latest/download/Origami.zip)**

#### 1. Trascina l'app
Scarica il file zip qui sopra, aprilo ed estrai **`Origami.app`**. Poi **trascinala nella cartella Applicazioni** del tuo Mac.

#### 2. Il primo avvio (Perché macOS mostra un avviso?)
Poiché ho sviluppato questa app per me e per voi amici, non pago ad Apple i 99$ all'anno per la licenza commerciale di "sviluppatore identificato". 

Per questo motivo, la primissima volta che provi ad aprire l'app, macOS ti mostrerà un messaggio di sicurezza dicendo che *«non è possibile verificare lo sviluppatore»*.

**Niente paura! Si sistema in un minuto e va fatto SOLO la prima volta:**

1. Apri **Origami** dalla cartella Applicazioni. Compare l'avviso: clicca **Fine** (non «Sposta nel Cestino»).
2. Apri **Impostazioni di Sistema → Privacy e sicurezza** e scorri in basso fino a *«Origami è stato bloccato…»*.
3. Clicca **Apri comunque** e conferma con la password del Mac (o Touch ID).
4. Origami si apre.

*(Oppure, se usi il Terminale, incolla questo comando, premi Invio e poi apri Origami normalmente:)*
```bash
xattr -cr /Applications/Origami.app
```

#### 3. Permesso di Accessibilità
Al primissimo avvio Origami ti mostrerà una finestra che ti chiede di concedere il permesso di **Accessibilità**:
1. Clicca sul pulsante nella finestra: ti porterà direttamente in *Impostazioni di Sistema → Privacy e sicurezza → Accessibilità*.
2. Attiva la levetta per **Origami**.
*(Questo serve all'app per intercettare la combinazione fn+Tab e poter spostare le finestre).*

---

### 🔄 E per i prossimi aggiornamenti?

**Non dovrai più fare nulla di tutto questo!**

Origami ha il sistema di aggiornamento automatico integrato:
* Quando pubblicherò nuove funzioni o correzioni, l'app se ne accorgerà da sola e ti mostrerà un avviso.
* Con un clic scaricherà la nuova versione e si riavvierà da sola.
* Puoi anche controllare manualmente in qualsiasi momento cliccando sull'icona di Origami nella barra dei menu in alto e premendo **«Controlla aggiornamenti…»**.
* Tutti i futuri aggiornamenti saranno già considerati sicuri dal tuo Mac e non mostreranno più alcun avviso di Gatekeeper!

---

<details>
<summary>🇬🇧 English version (Click to expand)</summary>

### Welcome to Origami 📐

I built **Origami** to make window management on macOS fast and effortless without touching the mouse.

* Hold **fn** (the 🌐 key on the bottom-left).
* Tap **Tab** (or arrows) to cycle through window layouts.
* Release **fn** to apply. Done!

#### 🚀 First-Time Installation

👉 **[Download the latest release (.zip)](https://github.com/stegidi/origami-releases/releases/latest/download/Origami.zip)**

1. Extract the zip and **drag `Origami.app` into your Applications folder**.
2. **First-launch macOS prompt**:
   Because I don't pay Apple $99/year for an enterprise developer certificate, macOS will say *“cannot verify developer”* on first open.
   * **Fix (once)**: open Origami, click **Done**, then go to **System Settings → Privacy & Security**, scroll down to *"Origami was blocked…"*, click **Open Anyway** and confirm.
   * *(Or in Terminal: `xattr -cr /Applications/Origami.app`)*.
3. **Grant Accessibility**: Click the prompt on launch to enable Origami in *System Settings $\to$ Privacy & Security $\to$ Accessibility*.

#### 🔄 Future Updates
Automatic! Whenever I publish an update, the app notifies you, updates itself, and restarts seamlessly. You can also click **“Controlla aggiornamenti…”** in the menu bar at any time.

</details>
