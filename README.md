# 🌾 go touch grass

> Una micro-skill **meme** per [Claude Code](https://claude.com/claude-code) che, nei momenti difficili della vita di un programmatore, ti ricorda quanta serenità c'è nel coltivare la terra e stare in mezzo alla natura — invece di sbatterci la testa su qualcosa di complicato.

`touch grass`, ma con l'orto. 🐓

---

## Cos'è

È una skill che **non rompe mai le scatole**. Resta zitta mentre lavori sereno.

Si sveglia **solo quando il lavoro si fa complicato e intenso** e tu inizi a mostrare i segni: il terzo "non funziona", l'ennesimo `merge conflict`, i test di nuovo rossi, le tre di notte sullo stesso stack trace, la frase "voglio fare il contadino".

In quel momento si attiva da sola e fa **una cosa sola**: scrive una frase. Una frase meme, cucita in tempo reale su ciò che stai facendo di complesso, messa a confronto con la pace di un mestiere legato alla terra. Niente altro.

Perché la terra ti aspetta. Ma solo quando serve davvero.

## Anteprima

Quando scatta, l'output è soltanto questo (l'esempio cambia in base a cosa stai facendo):

```
—————-
Go Touch Grass

È un'ora che combatti con un merge conflict in auth.ts, ma un filare di vite non ha mai litigato con quello accanto. Lascia perdere il rebase: il mosto fermenta lo stesso, e domani il sole sorge anche se questo branch non va in merge.
—————-
```

```
—————-
Go Touch Grass

Test di nuovo rossi, le tre di notte, e il mondo intanto? Continua a girare uguale. Le galline alle sei hanno fame comunque, questo deploy no. Forse è ora di una vita con più terra sotto le unghie e meno stack trace negli occhi.
—————-
```

Ogni frase mescola **quello che stai facendo di complicato** con **un'immagine di pace contadina**, per ricordarti che quella complessità non esiste con le mani nella terra — e che il mondo non cambia se la task urgentissima resta lì un altro po'.

## Installazione

La skill è una semplice cartella con dentro `SKILL.md`. Mettila tra le tue skill personali di Claude Code:

```bash
git clone https://github.com/ferdinandobons/go-touch-grass.git \
  ~/.claude/skills/go-touch-grass
```

Oppure copia solo il file:

```bash
mkdir -p ~/.claude/skills/go-touch-grass
curl -fsSL https://raw.githubusercontent.com/ferdinandobons/go-touch-grass/main/SKILL.md \
  -o ~/.claude/skills/go-touch-grass/SKILL.md
```

Riavvia Claude Code (o apri una nuova sessione) e la skill è attiva. Non devi configurare nulla.

## Come si attiva

Claude invoca la skill **da solo** quando dal contesto capisce che sei in difficoltà: frustrazione, sfinimento, blocco, debugging infinito, voglia di mollare. Vedi il campo `description` dentro [`SKILL.md`](./SKILL.md) per la lista completa dei segnali.

Non si attiva durante il lavoro tranquillo e produttivo. È il suo unico patto con te.

## Filosofia

Nessuno è mai morto per un build fallito. Te lo dice il nonno. 🌅

## Licenza

[MIT](./LICENSE) — coltiva, fai fork, regala. Come le talee.
