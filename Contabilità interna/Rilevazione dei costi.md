>[!note]
>Tra i sistemi di rilevazione dei costi troviamo quattro metodi principali:
>- Process Costing
>- Operation Costing
>- Job Order Costing (JOC)
>- Activity Based Costing (ABC)
>
>![[Pasted image 20260707173433.png|center]]
>
>

### Process Costing
>[!note]
>Il Process Costing consiste nell'allocare le tipologie di costo utilizzando un criterio di tipo proporzionale al reparto/centro di riferimento. Viene usato per le produzioni omogenee, con processi produttivi di tipo a flusso.

>[!tip] Caso semplificato
>Consideriamo come ipotesi:
>- Produzioni mono-reparto
>- Produzioni mono-prodotto
>- Assenza di semilavorati
>
>Si ha che: $$\text{CPI}_\text{unitario}= \frac{C_\text{tot}}{Q}= \frac{C_\text{MD}+C_\text{LD}+C_{OVH}}{Q}$$
>Dove $\text{CPI}_\text{unitario}$ è il costo totale sostenuto per produrre una singola unità di prodotto, $C_\text{MD}$ è il costo dei materiali diretti, $C_\text{LD}$ è il costo della manodopera diretta, $C_\text{OVH}$ sono i costi indiretti di produzione e $Q$ è il volume totale di produzione.

Sia $\alpha$ il grado di completamento di un semilavorato, cioè la frazione dei costi complessivi che ha già accumulato, si ha che: $$\text{UE}=\sum\limits_{i}^{n}Q_{i}\cdot \alpha_{i}$$
Dove $Q_{i}$ è il numero di unità allo stadio $i$-esimo, $\alpha_{i}$ è il grado di completamento allo stadio $i$-esimo, e $\text{UE}$ è il numero di unità che sarebbe stato possibile produrre se tutte le risorse fossero state impiegate per la produzione di soli prodotti finiti.

Sia le unità completate che quelle in corso di lavorazione devono essere espresse tramite un'unica unità di misura, detta unità di produzione equivalente, usata per determinarne il costo. Se consideriamo presenze di semilavorati finali: $$\text{UE}=\text{U}_\text{PF}+\text{U}_\text{WIP,fin}\qquad \text{ con } \text{U}_\text{PF}=\text{UE}_\text{PF}\qquad \text{UE}_\text{WIP,fin}=\text{U}_{\text{WIP,fin}}\cdot \alpha_{\text{fin}}$$
Dove $\text{UE}_\text{PF}$ sono le unità equivalenti di prodotto finito, $\text{UE}_\text{WIP,fin}$ sono le unità equivalenti di semilavorati finali e $\alpha_\text{fin}$ è il coefficiente di completamento per semilavorati finali. Di conseguenza: $$\text{CPI}_\text{unitario,PF}= \frac{C_\text{tot}}{\text{UE}}\qquad\text{CPI}_{WIP,fin}= \frac{C_\text{tot}}{\text{UE}}\cdot \text{U}_\text{WIP,fin}\cdot \alpha_\text{fin}$$

In presenza di semilavorati in uscita e in entrata si ha che: $$C_\text{WIP,in}+\text{CA}=C_{\text{PF}}+C_{\text{WIP,fin}}$$
Dove $\text{CA}$ sono i costi aggiunti, cioè totale dei costi sostenuti nel periodo $t$, e $\text{CI}$ sono i costi incorporati, cioè il totale dei costi incorporati nel semilavorato iniziale.

Si usano due approcci nel calcolo del costo delle unità equivalenti:

|                                 | Logica del costo medio                                                                                                                                                             | Logica FIFO                                                                                                                                                                                                                                                                                 |
| ------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Principio                       | Per determinare il costo unitario relativo a un periodo $t$, si considerano le unità completate e $\text{WIP}_\text{fin}$, incorporando anche i costi delle $\text{WIP}_\text{in}$ | Per determinare il costo unitario relativo a un periodo $t$, il costo della produzione deve far riferimento ai costi effettivamente sostenuti per produrre le unità completate ($\text{QC}$) e $\text{WIP}_\text{fin}$, mentre vengono trascurati i costi relativi a $\text{WIP}_\text{in}$ |
| Output                          | $\text{UE}=Q_{C}+\text{WIP}_\text{fin}\cdot\alpha_\text{fin}$                                                                                                                      | $\text{UE}=Q_{C}+\text{WIP}_\text{fin}\cdot\alpha_\text{fin}-\text{WIP}_\text{in}\cdot\alpha_\text{in}$                                                                                                                                                                                     |
| Costo totale                    | $C_\text{tot}=\text{CA}+\text{CI}$                                                                                                                                                 | $C_\text{tot}=\text{CA}$                                                                                                                                                                                                                                                                    |
| Costo unità equivalenti         | $C_\text{UE}=\frac{\text{CA}+\text{CI}}{\text{UE}}$                                                                                                                                | $C_\text{UE}= \frac{\text{CA}}{\text{UE}}$                                                                                                                                                                                                                                                  |
| Costo $\text{WIP}_{\text{fin}}$ | $C\text{WIP,fin}=C_\text{UE}\cdot\text{WIP}_\text{fin}\cdot \alpha_\text{fin}$                                                                                                     | $C\text{WIP,fin}=C_\text{UE}\cdot\text{WIP}_\text{fin}\cdot \alpha_\text{fin}$                                                                                                                                                                                                              |
| Costo complessivo               | $C_{Q_{C}}=C_\text{UE}\cdot Q_{C}$                                                                                                                                                 | $C_{Q_{C}}=\text{CA}-C_{\text{WIP,fin}}+\text{CI}$                                                                                                                                                                                                                                          |
>[!tip] Molteplici prodotti
>In presenza di più tipologie di prodotto è necessario ricorrere al concetto di coefficiente di equivalenza $\gamma$ tra prodotti. Prendendo un prodotto come riferimento, si riconducono tutti gli altri a questo tramite il coefficiente di equivalenza.

### Operation Costing
>[!note]
>L'Operation Costing è utilizzato dalle imprese che hanno un sistema produttivo in cui il processo è scomponibile in una serie di operazioni che vengono svolte dai diversi prodotti. Tali prodotti si differenziano soprattutto per il tipo di materiali diretti utilizzati.
>
>I costi di MP possono essere tracciati direttamente a singoli prodotti/servizi, mentre i costi di conversione (LD e OVH) relativi a ciascuna operazione vengono allocati in proporzione a volume produttivo di ciascun prodotto o tempo totale di LD impiegato da ciascun prodotto.
>
>Si trova quindi il costo unitario di un prodotto come somma del costo unitario delle MP e dei costi unitari di LD e OVH.

### Job Order Costing
>[!note]
>Il Job Order Costing (JOC) è utilizzato in organizzazioni il cui output è chiaramente quantificabile in unità/lotti (detti job), in cui ciascun reparto si occupa di più lotti omogenei nel periodo in esame.
>
>È il metodo più adatto quando i costi MP e LD rappresentano una componente preponderante dei costi di prodotto.
>
>Per usarlo si scrive il Job Order Record per ogni lotto, una scheda in cui vengono annotate tutte le voci di costo associabili al job durante la sua lavorazione.
>
>![[Pasted image 20260707184233.png|center]]

I costi diretti sono imputati in modo puntuale al lotto a cui fanno riferimento, mentre i costi indiretti sono allocati in modo proporzionale ad una certa base di allocazione, dove si misurano gli overhead realmente verificatisi nel periodo in esame, e si allocano tali costi sulla base del valore della base di allocazione.

### Activity Based Costing
>[!note]
>L'ABC alloca con un criterio causale tutti i costi, introducendo il un coefficiente di allocazione variabile a seconda delle attività che consumano le risorse.
>
>La base di allocazione è un'attività e non una risorsa, e le diverse attività possono consumare la risorsa in modo diverso per diversi prodotti.
>
>Si individuano quindi le attività che consumano risorse, i resource driver per ciascuna attività, si ripartiscono i costi in base al consumo dei resource driver e si aggregano le voci di costo.
>
>![[Pasted image 20260707184700.png|center]]



