<div align="center">

# 💀 HANGMAN · The Game

### *Una parola. Sei errori. Nessuna pietà.*

![Java](https://img.shields.io/badge/Java-17-orange?logo=openjdk&logoColor=white)
![Swing](https://img.shields.io/badge/GUI-Swing-blue)
![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?logo=windows&logoColor=white)
![License](https://img.shields.io/github/license/Emadol/hangman_the_game_PC_version)

[**⬇️ Scarica Hangman.exe**](../../releases/latest)

</div>

---

## 🎭 La sfida

Il boia è pronto. La corda è già appesa.
Davanti a te, una parola italiana scelta a caso tra **migliaia**, nascosta dietro una fila di caselle vuote.

Ogni lettera giusta ti salva. Ogni errore **stringe il cappio**.
Se ti senti sicuro puoi giocarti tutto e tentare di indovinare **l'intera parola in un colpo solo**... ma se sbagli, paghi.

## 🕹️ Come si gioca

1. Avvia il gioco e premi **Play**
2. Scrivi una lettera e conferma con il pulsante di invio
3. Se è giusta, compare al suo posto. Se è sbagliata, l'omino perde un pezzo, con tanto di **grido di dolore** 🔊
4. Hai poche vite: finiscono, perdi e la parola viene svelata
5. Vinci e il **punteggio sale**. Si salva da solo, quindi la sfida continua anche domani 🏆

## ✨ Cosa c'è dentro

| | |
|---|---|
| 📖 | Dizionario italiano con migliaia di parole |
| 🧍 | Omino che si completa errore dopo errore |
| 🔊 | Effetti sonori per errori e vittoria |
| 🏆 | Punteggio persistente tra una partita e l'altra |
| 🔄 | Nuova partita con un solo click |
| 📦 | Un solo `.exe`, **Java incluso**, zero installazioni |

## 🚀 Giocare subito

1. Vai nella sezione [**Releases**](../../releases/latest)
2. Scarica **`Hangman.exe`**
3. Doppio clic. Fine.

> ⚠️ Windows potrebbe mostrare l'avviso *SmartScreen* perché l'app non è firmata.
> Clicca su **Ulteriori informazioni → Esegui comunque**.

## 🛠️ Per gli sviluppatori

Il gioco è scritto in **Java + Swing**, con aspetto grafico [JTattoo](http://www.jtattoo.net/) e lettura del dizionario con [opencsv](https://opencsv.sourceforge.net/).

```text
hangman/
 ├─ src/        codice sorgente Java
 ├─ srcImg/     immagini
 ├─ srcSound/   effetti sonori
 ├─ srcTxt/     dizionario italiano (CSV)
 └─ librs/      librerie (JTattoo, opencsv)
launcher/       script per creare l'exe autonomo
```

Per generare tu stesso l'eseguibile, con un JDK 17:

```powershell
.\launcher\build-single-exe.ps1 -JdkHome "C:\percorso\jdk-17"
```

L'exe contiene gioco, risorse e runtime Java minimale, e al primo avvio si prepara in `%LOCALAPPDATA%\Hangman`.

## 📜 Licenza

Distribuito con la licenza indicata nel file [LICENSE](LICENSE).

---

<div align="center">

Fatto con ☕ e un pizzico di crudeltà da **Emanuele Dolce**

*Riuscirai a salvare l'omino?*

</div>
