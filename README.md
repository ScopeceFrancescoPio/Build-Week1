Il report e' presente nella cartella REPORT con il nome di Progetto_CS24CL01

Traccia:

Siamo stati ingaggiati dalla compagnia Theta per eseguire delle valutazioni di sicurezza su alcune delle infrastrutture critiche dei loro data center.

Il perimetro delle attività si concentra principalmente su:
-Un Web server che espone diversi servizi su internet (e quindi accessibili al pubblico)
-Un Application server che espone sulla rete interna un applicativo di e-commerce accessibile dai soli impiegati della compagnia Theta (quindi non accessibile da resti esterne, ovvero internet)

In base alle informazioni sopra, il capo della sicurezza informatica di Theta, chiamato anche CISO (chief information security officer), ci richiede:

1. Di Diproporre un modello (design) di rete per mettere in sicurezza le due componenti critiche, includendo nell’analisi i dispositivi di sicurezza che potrebbero servire per aumentare la protezione della rete.
2. Di effettuare dei test puntuali sulle due componenti critiche per valutarne lo stato di sicurezza. Nella fattispecie, il CISO ci chiede di effettuare i controlli riportati nella slide successiva

Sul Web Server:
-Scan dei servizi attivi sulla macchina
-Eventuale enumerazione dei metodi HTTP abilitati sul servizio HTTP in ascolto sulla porta 80.

Sull'application server:
-Enumerazione dei metodi HTTP abilitati.
-Valutazione della robustezza della pagina di login agli attacchi di tipo Brute Force. 

Il CISO ci ha esplicitamente richiesto di non effettuare nessun test invasivo in ambiente di produzione, e quindi gli abbiamo proposto di riprodurre le due componenti nei nostri laboratori di test, così da poter effettuare i test in sicurezza, separando gli ambienti di test dagli ambienti di lavoro.
