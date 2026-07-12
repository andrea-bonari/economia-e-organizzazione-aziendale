>[!note]
>Definiamo un progetto di investimento come un insieme di attività implementate dall'impresa con un obiettivo sociale. Questo ha come obiettivo di generare benefici, a fronte di uno sforzo economici, cioè dei costi.

Un investimento ha tre caratteristiche:
- Difficile reversibilità: significativi impieghi iniziali di risorse, difficili da rivedere/ricontrattare
- Impatto di lungo periodo: mentre solitamente i costi sono concentrati all'inizio, i ricavi sono distribuiti su un orizzonte temporale
- Effetto incerto: i risultati economici generati non sempre sono perfettamente chiare e/o prevedibili. È quindi caratterizzato da rischio e incertezza

Per l'impresa è quindi cruciale capire se un progetto conviene, cioè se il trade off tra costi e vantaggi è vantaggioso.

### Tecniche finanziarie
>[!note]
>Per isolare e studiare l'effetto marginale dell'investimento sulla creazione dei flussi di cassa, si identificano i flussi di cassa differenziali generati dal progetto per l'impresa: $$\Delta\text{NCF}_{t}=\text{NCF}_{t}(\text{con investimento})-\text{NCF}_{t}(\text{senza investimento})$$
>Attualizzando tutti gli $\text{NCF}$ generati da un progetto, possiamo andare a definire il suo valore attuale netto: $$\text{VAN}=\sum\limits_{t=0}^{T}\frac{\Delta \text{NCF}_{t}}{(1+k)^{t}}$$
>Questo rappresenta il contributo marginale che il progetto genera per il valore dell'impresa, dove il tasso di attualizzazione $k$ è pari al rendimento minimo richiesto dall'impresa sul capitale che viene utilizzato per finanziare il progetto.
>
>Talvolta questa formula può diventare: $$\text{VAN}=\sum\limits_{t=0}^{T}\frac{\Delta \text{NCF}_{t}}{(1+k)^{t}}+\frac{V(t)}{(1+k)^{T}}-I_{0}$$
>Dove $I_{0}$ è l'investimento iniziale e $V(t)$ è il valore di terminale.

Par valutare un investimento bisogna considerare i flussi di cassa netti generati:
1. Si identificano gli effetti dell'investimento, valutando come influenza l'impresa
2. Si traduce e quantificano tali effetti in termini economici
3. Per ogni anno, si redige un conto economico differenziale
4. Per ogni anno, si ottengono i flussi di cassa netti associati a questo utile

>[!tip] Misura economica a calcolo dei NCF
>Gli effetti dello specifico investimento vanno isolati dalle restanti attività d'impresa. Consideriamo quindi la logica differenziale, che dice di considerare tutti e solo i flussi direttamente generati dall'investimento. Questi includono gli effetti collaterali: il progetto può impattare anche su altre parti dell'impresa (sinergie e erosioni).
>
>Utilizzando le variazioni individuate, possiamo redigere un CE differenziale, che include voci come:
>- Ricavi
>- Costo delle MP
>- Costo del lavoro
>- Costo dei servizi
>- Costo di manutenzione
>- Costo dell'energia
>- Imposte
>
>Possiamo poi passare da una logica economica ad una logica finanziaria, considerando solo le componenti che generano flussi di cassa nel periodo considerato.

>[!tip] Metodo indiretto
>Nel metodo indiretto si costruisce il rendiconto finanziario partendo dall'utile netto differenziale, e si correggono gli effetti delle componenti "non-cash", cioè si rettificano ammortamenti, accantonamenti e plusvalenze/minusvalenze e rettifiche di valore di attività non correnti.
>
>Si fanno inoltre rettifiche dovute alla variazione di capitale circolante netto operativo (CCNO), cioè la differenza tra attività e passività correnti, escludendo la cassa. Quindi l'utile lordo differenziale è: $$\begin{align*}
>\text{Utile lordo differenziale}= &\pm\text{Imposte differenziali}\\&+\text{Ammortamenti}\\&\pm\text{Investimenti (disinvestimenti) in immobilizzazioni}\\&\pm\text{Investimenti (disinvestimenti) in attività/passività correnti}
>\end{align*}$$

### Indice di profittabilità
>[!note]
>L'indice di profittabilità (PI) è dato dal rapporto fra il valore attuale dei flussi di cassa generati dall'investimento e il valore tutte le somme investite: $$\text{PI}=\frac{\text{VAN dei flussi di cassa futuri}}{\text{Flussi di cassa iniziali}}= \frac{\text{PV}}{N_{0}}$$
>Ed indica il rendimento assicurato dal progetti di investimento per ogni euro di capitale investito, cioè la produttività marginale dell'investimento effettuato.
>
>All'impresa conviene investire se $\text{PI}>1$, questo perché tra PI e VAN c'è una relazione diretta, e in tal caso c'è VAN positivo.
>
>Il PI permette inoltre di classificare i progetti secondo la loro capacità di generare valore.

### Tasso di rendimento interno
>[!note]
>Il tasso di rendimento interno (TIR) è il valore del costo di capitale $k^{*}$ che rende il VAN nullo: $$\text{VAN}(k=k^{*})=0$$
>Questo è quindi una misura della redditività intrinseca (rendimento annuo intrinseco) del progetto.
>
>Per $\text{TIR}>k$ il progetto ha redditività superiore a quella richiesta dagli investitori, per $\text{TIR}=k$ è indifferente e per $\text{TIR}<k$ il progetto non rende a sufficienza.

Il TIR ha come pro:
- Permette di individuare il tasso di 'break-even' finanziario
- Permette ad analisti ed investitori di valutare la performance di diversi progetti in termini relativi
- È preferibile al VAN quando il tasso di attualizzazione dei flussi è noto oppure variabile

Tuttavia, ha come contro:
- Se il VAN è sempre positivo, il TIR non esiste
- Può non distinguere tra operazioni di investimento e finanziamento
- In caso di flussi di cassa futuri non convenzionali, esistono più TIR

### Tempo di restituzione
>[!note]
>Il tempo di restituzione (PB) definisce l'orizzonte temporale oltre il quale il progetto crea valore: $$\text{PB}=\min_{t}(\text{VAN}>0)$$
>Questo parametro misura la rischiosità del progetto. In altri termini, dato $t$ l'orizzonte temporale ultimo di un ipotetico investimento, per $\text{PB}>t$ questo conviene.

Il PB ha come pro:
- Cattura il grado di liquidità del progetto
- Permette di individuare il tempo massimo di recupero, dando valore decisionale al momento entro cui l'impresa prevede di recuperare l'investimento iniziale
- Molto utile quando c'è forte incertezza futura

Tuttavia, ha come contro:
- Non misura l'economicità dell'investimento
- Enfattizzare troppo il breve termine può essere limitante

### Capitale di terzi
>[!note]
>L'azienda può decidere e finanziare l'investimento utilizzando capitale proprio, o anche di terzi, quindi indebitandosi.
>
>Se utilizza interamente il proprio capitale, il costo opportunità del capitale $k_{e}$ è rappresentato dal costo di opportunità di un investimento con rischio simile: $$k_{e}=i+d$$
>Dove $i$ è il tasso di rendimento privo di rischio e $d$ è il premio per un rischio comparabile.
>
>Se utilizza capitale di terzi, deve ripagare i finanziatori per il costo del capitale di debito $k_{d}$ da loro richiesto. Spesso le aziende adottano un mix di entrambi. In questo caso il costo del capitale è il Weighted Average Cost of Capital (WACC): $$\text{WACC}= \frac{E}{D+E}k_{e}+ \frac{D}{D+E}k_{d}$$
>