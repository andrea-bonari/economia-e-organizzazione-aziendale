>[!note]
>Le decisioni di breve periodo sono scelte di pianificazione operativa, che servono per tradurre indicazioni strategiche o di lungo termine in azioni e indicazioni pratiche di breve periodo.
>
>Queste hanno effetti limitati nel tempo e sono prese con risorse strutturali fissate.

Uno dei contesti decisionali più importanti nell'ingegneria industriale è quello della pianificazione della produzione. Per un'impresa è importante avere strumenti per decidere quanto produrre, quando e di che cosa, in funzione anche delle previsioni sulle vendite.

Nella pratica si richiede l'autorizzazione da parte dei manager di divisione, in quanto l'impatto sulla struttura dell'impresa non è duraturo, e nel prendere queste decisioni è importante la rapidità.

Per prendere queste decisioni si usano dei criteri decisionali semplici, tra cui fissare un limite massimo di spesa nel budget e si considerano costi e ricavi.

>[!tip] Costo nell'impresa
>Ricordando che i costi di produzione possono essere fissi o variabili, supponiamo per ipotesi che il costo variabile di interesse è un costo variabile unitario: $$\text{CV}=\text{CV}_{u}\cdot Q$$
>E dati costi fissi e variabili, definiamo il costo totale come: $$\text{CT}=\text{CF}+\text{CV}=\text{CF}+\text{CV}_{u}\cdot Q$$

Useremo l'intervallo di rilevanza, cioè un intervallo di attività o di volume produttivo all'interno del quale si suppone valida una specifica relazione tra volume e costo. Spesso coincide con la capacità produttiva esistente.

### Decisioni Make or Buy
>[!note]
>Le decisioni make or buy sono decisioni inerenti la scelta tra:
>- Produrre un determinato input/componente/prodotto all'interno dell'impresa
>- Acquistare l'input/componente/prodotto sul mercato
>
>Gli step della valutazione sono:
>1. Identificare le alternative di Make e Buy
>2. Si adotta una delle due alternative come caso base
>3. Si calcolano i costi e i ricavi differenziali al caso base
>4. Si preferisce l'alternativa che crea il maggior valore economico

### Break-Even
>[!note]
>L'analisi di break-even permette di individuare il punto di pareggio, o break-even point (BE), che è quel livello (o mix) produttivo che assicura all'impresa:
>- Copertura dei costi di produzione
>- Ottenere un certo livello di profitto obiettivo
>
>Generalmente, l'obiettivo dell'impresa è quello di raggiungere un volume produttivo superiore al BE, cioè determinare il minimo volume operativo ($Q_\text{BE}$): $$\begin{align*}
Q_\text{BE}:\qquad&\text{Ricavi}_\text{tot}-\text{Costi}_\text{tot}=\text{MON}=0\\
Q_\text{target}:\qquad&\text{Ricavi}_\text{tot}-\text{Costi}_\text{tot}=\text{MON}_\text{target}>0
\end{align*}$$

Il grado di leva operativa (DOL) è un parametro che cattura l'elasticità al margine di $\Pi$ rispetto a $Q$, ne cattura la sensibilità alla variazione delle vendite. Indica di quanto aumenta percentualmente il margine operativo $\Pi$ all'aumentare di un punto percentuale di $Q$: $$\text{DOL}=\frac{\frac{\Delta \Pi}{\Pi}}{\frac{\Delta Q}{Q}}$$


>[!tip] Caso mono prodotto
>In caso di imprese mono-prodotto, avremo: $$\begin{align*}
>\text{Ricavi}&= p\cdot Q\\
>\text{Costi di produzione}&= \text{CF}+\text{CV}_{u}\cdot Q\\
>\text{Margine operativo }\Pi&= \text{Ricavi}-\text{Costi}\\
>&= (p-\text{CV}_{u})Q-\text{CF}
>\end{align*}$$
>Definendo $p-\text{CV}_{u}=m$ come margine di contribuzione, ovvero il contributo al margine realizzato dalla vendita di un'unità aggiuntiva di prodotto, infatti: $$\frac{\partial\Pi}{\partial Q}=p-\text{CV}_{u}$$
>È ricavabile che la $Q_\text{BE}$ deve soddisfare un minimo: $$Q_\text{BE}= \frac{\text{CF}}{m}=\frac{\text{CF}}{p-\text{CV}_{u}}$$
>Se l'impresa puntasse a raggiungere un livello prefissato di margine operativo, si potrebbe generalizzare la formula precedente come: $$Q_\text{BE}=\frac{\text{CF}+\Pi_\text{target}}{m}$$
>Il punto di pareggio può anche essere espresso in termini percentuali sui ricavi totali (RT): $$\text{RT}_\text{BE}= \frac{\text{CF}}{\frac{m}{p}}=\frac{\text{CF}}{m\%}$$
>![[Pasted image 20260712130103.png|center]]
>
>In questo caso si ha che: $$\text{DOL}= \frac{1}{1-\frac{\text{CF}}{mQ}}$$

>[!tip] Caso multi prodotto
>Un'impresa è multi prodotto quando ha a catalogo un mix di $N$ prodotti diversi. In questo caso, per determinare il punto di break even è necessario definire il mix di produzione, cioè la quota $x_{i}$ di produzione da allocare a ciascun prodotto $i$-esimo: $$x_{i}= \frac{Q_{i}}{Q_\text{tot}}$$
>Definiamo poi il margine di contribuzione medio ponderato: $$\overline{m}=\sum\limits_{i=1}^{N}m_{i}x_{i}$$
>Dove $m_{i}$ è lo specifico margine di contribuzione del prodotto $i$-esimo. A questo punto il break even del prodotto $i$-esimo è dato da: $$Q_{\text{BE},i}= \frac{\text{CF}}{\overline{m}}\cdot x_{i}$$
>Si ha che: $$Q_\text{BE,tot}= \frac{\text{CF}}{\overline{m}}\qquad Q_{\text{BE},i}=Q_\text{BE,tot}\cdot x_{i}$$

### Mix produttivo
>[!note]
>In caso di azienda multi prodotto, l'obiettivo dell'ingegnere è cercare di capire come ottimizzare il mix produttivo, cioè capire quale prodotto è più opportuno realizzare e quanto conviene produrre di ciascuno dei prodotti sotto eventuali vincoli.
>
>Per farlo si calcola il margine di contribuzione di ciascun prodotto, in assenza di vincoli si produce il prodotto con margine di contribuzione maggiore, e in caso di vincoli si risolve un problema di ottimizzazione vincolata. In particolare:
>- In presenza di vincoli di consumo di risorse si massimizza il margine di contribuzione per risorsa scarsa
>- In presenza di vincoli di politiche aziendale si soddisfano gli eventuali vincoli di minimo di produzione e si massimizza il margine di contribuzione
>- In presenza di vincoli di mercato si massimizza secondo il margine di contribuzione senza superare i vincoli di massimo di produzione

In caso di quantità minima/massima di output producibile, si ricorre a tecniche di programmazione lineare, che massimizzano la funzione obiettivo, cioè il margine di profitto, rispettando i vincoli imposti.

In presenza di risorse in input limitate, andiamo a calcolare il margine di contribuzione per risorsa scarsa $m^{*}$, tendo conto del coefficiente tecnico di assorbimento della risorsa scarsa $\alpha$: $$m_{i}^{*}= \frac{m_{i}}{\alpha_{i}}$$
Dove $\alpha_{i}$ rappresenta il consumo standard della risorsa considerata, associato alla produzione di un'unità di output finito del prodotto $i$-esimo, cioè il costo di produzione in termini di unità della risorsa scarsa.

Andremo quindi a privilegiare il prodotto che offre il margine di contribuzione per risorsa scarsa più elevato.

