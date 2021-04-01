# Esercitazione Git

Esercitazione da svolgere in coppia o individualmente.

## Svolgimento

1. Creare un **fork** della repository tramite GitHub.
    * In coppia è sufficiente che _una_ persona della squadra effettui il fork sul proprio profilo personale,
    * Assicurarsi di conferire accesso in scrittura alla repository all’altra persona della squadra.
1. Creare una **copia locale** (`git clone`) del fork.
1. Creare un nuovo **branch** di lavoro (per esempio con il nome `le-mie-modifiche` o simile), con il comando `git branch`.
    * In coppia, assicurarsi che il nome del branch di lavoro non coincida con il nome scelto dall’altra persona della squadra.
1. Effettuare *almeno* le seguenti **modifiche** (in uno o più commit, usando di volta in volta i comandi `git add` e `git commit`):
    1. Aggiungere una nuova ricetta,
    1. Modificare la ricetta dei cannoli, alterando a piacimento le quantità ed il procedimento.
1. Allineare la repository remota su GitHub con le modifiche effettuate, usando il comando `git push` sul branch di lavoro creato al punto 3.
1. Accedere alla propria repository su GitHub tramite interfaccia Web e richiedere una **pull request** dei propri contributi al secondo membro del team.
1. Attendere che l'altro membro del team effettui le stesse operazioni, visualizzare la sua *pull request*, esaminarla ed approvarla.
    * È possibile che ci siano conflitti sulla ricetta dei cannoli, essendo stata alterata da entrambi i membri della squadra. In tal caso, risolvere i conflitti e poi approvare le pull request.
1. A questo punto il fork dovrebbe contenere tutte le modifiche effettuate da entrambe le persone della squadra.
1. **Consegnare** l’esercitazione creando una _pull request_ dal fork alla repository originale dell’esercitazione.

## Conclusione

L'esercitazione può considerarsi conclusa quando è stata creata la _pull request_ alla repository originale con tutte le modifiche effettuate da entrambi i membri del team.

Se si svolge l’esercitazione **individualmente**, si svolgeranno entrambi i ruoli dei membri della squadra: si creeranno quindi _due_ branch di lavoro in locale e poi si integreranno sempre tramite delle _pull request_ su GitHub.
Sarà necessario approvare le proprie _pull request_, in assenza di una seconda persona della squadra che possa farlo.
