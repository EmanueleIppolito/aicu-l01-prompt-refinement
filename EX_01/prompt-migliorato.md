# Prompt Refinement L01

## Prompt Di Partenza

Incolla qui il prompt scelto.

```txt
Aggiungi un messaggio carino quando non ci sono ticket aperti.
...
```

## Prompt Usato Per Migliorare

```txt
Aiutami a migliorare il "prompt di partenza" nel file prompt-migliorato.md
Non hai bisogno di leggere altro se non quello.
Il contesto è un'app didattica di ticket.
Ho bisogno che sia ci sia un messaggio chiaro e VERIFICABILE quando l'app si trova in fase di empty-state.
Non scrivere codice.
Sii sintetica e non mostrarmi la chain-of-thought. 
Elenca solo assunzioni, criterio, e verifica proposta.
Se manca qualche informazione prima di proporre una risposta chiedimelo

Non scrivere codice né creare alcun file.
```

## Strategia Del Prompt Finale

- Zero-shot o few-shot:
- Motivo della scelta:
- Se few-shot, cosa dimostrano gli esempi:
- Evidenze richieste all'AI: assunzioni / criterio / verifica

## Prompt Migliorato

```txt
Nell’app didattica di ticket, gestisci lo stato vuoto della lista dei ticket aperti.

Quando non ci sono ticket aperti, mostra in modo visibile il seguente messaggio esatto:

“Nessun ticket aperto al momento. Ottimo lavoro!”

Il messaggio deve comparire solo quando la lista dei ticket aperti è vuota. Non deve essere mostrato durante caricamento, errore o quando esiste almeno un ticket aperto.

Criteri di verifica:
- Con zero ticket aperti, il testo “Nessun ticket aperto al momento. Ottimo lavoro!” è visibile.
- Con almeno un ticket aperto, il testo non è visibile.
- Durante caricamento o errore, viene mostrato uno stato distinto.
```

## Controllo Qualita'

- Contesto presente: 
- Confini espliciti: 
- Output atteso:
- Prova di controllo:
- Cosa chiede all'AI di non fare:
- Esempi necessari e proporzionati:
- Evita chain-of-thought estesa:
- E' piu' specifico perche':
- Limita meglio il lavoro perche':
- Produce un output piu' verificabile perche':
- Lo classificherei come: Vago / Utilizzabile / Controllabile / Consegnabile
