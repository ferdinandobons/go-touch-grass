# 🌾 go touch grass

> Una micro-skill **meme** per [Claude Code](https://claude.com/claude-code) che, nei momenti difficili della vita di un programmatore, ti ricorda quanta serenità c'è nel coltivare la terra e stare in mezzo alla natura — invece di sbatterci la testa su qualcosa di complicato.

`touch grass`, ma con l'orto. 🐓

---

## Cos'è

È una skill che **non rompe mai le scatole**. Resta zitta mentre lavori sereno.

Si sveglia **solo quando il lavoro si fa complicato e intenso** e tu inizi a mostrare i segni: il terzo "non funziona", l'ennesimo `merge conflict`, i test di nuovo rossi, le tre di notte sullo stesso stack trace, la frase "voglio fare il contadino".

In quel momento si attiva da sola, ti fa fermare un secondo, ti mostra un casolare in ASCII art, ti fa respirare — e poi ti riporta al lavoro più leggero.

Perché la terra ti aspetta. Ma solo quando serve davvero.

## Anteprima

```
                              \   |   /
                               \  |  /
                          ` ` `  \(_)/  ` ` `        il sole se ne frega
                        ` ` ` `  (   )  ` ` ` `      dei tuoi merge conflict
                               .--`|`--.
            ___              .'         '.            ___
          /'   '\          /  __      __  \         /'   '\
         |  []   |        /  |==|    |==|  \       |  [] []|
      ___|_______|___    /___|__|____|__|___\   ___|_______|___
     /  casolare    /\   |   |  |    |  |   |  /   pollaio   /\
    /______________/  \  |[] |  | [] |  |[] | /____________/  \
    |   |  ___  |   |  |  |   |  |    |  |   | |   |  o o  |   |
    |[] | |   | | []|  |  |___|__|____|__|___| |[] |  ___  | []|
 ~~~^^^^^^^^^^^^^^^^^^~~~~~~~~~~~~~~~~~~~~~~~~~~~^^^^^^^^^^^^^^^^^^~~~~
   ,,,,,,    ,,,,,,    qui non esistono i test rossi    ,,,,,,
  ,,,,,,,,  ,,,,,,,,         solo papaveri          ,,,,,,,,  ,,,,,,
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
        (\__/)        zappa > tastiera        ~o~  (la gallina
        (  o.o)                                     non sa cos'è Docker)
        ( >  < )  guarda l'orizzonte, non lo schermo
```

> Là fuori il cielo non ha versioni, le stagioni non fanno rollback, e il tramonto va sempre in produzione, ogni sera, senza un test. Il grano cresce senza pipeline. [...] Touch grass, amico. La zappa aspetta, il merge può aspettare un caffè. 🌾 ☀️ 🐓

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
