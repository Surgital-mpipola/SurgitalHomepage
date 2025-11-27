# SurgitalHomepage
Repo di Homepage Dashboard di Surgital


La cartella `config` di **HOMEPAGE Dashboard** contiene i file di configurazione che definiscono struttura, integrazioni, aspetto e comportamento del dashboard. Di seguito una descrizione professionale del ruolo di ciascun file.

**bookmarks.yaml**
Contiene la configurazione dei segnalibri visualizzati nella dashboard. Definisce gruppi, nomi, URL e icone associate ai link rapidi.

**custom.css**
Include le personalizzazioni grafiche aggiuntive tramite CSS. È utilizzato per modificare l’aspetto dell’interfaccia al di fuori delle opzioni standard fornite dall’applicazione.

**custom.js**
Permette di aggiungere logiche personalizzate o funzioni avanzate tramite codice JavaScript. È utile per estendere il comportamento del dashboard o integrare script esterni.

**docker.yaml**
Gestisce l’integrazione con istanze Docker. Contiene le informazioni necessarie per connettersi all’host Docker e visualizzare lo stato dei container all’interno del dashboard.

**kubernetes.yaml**
Configura l’accesso a uno o più cluster Kubernetes. Permette di visualizzare risorse come pod, deployment e nodi, fornendo una panoramica dello stato del cluster.

**proxmox.yaml**
Definisce la connessione a un ambiente Proxmox. Consente la visualizzazione di VM, container LXC, storage e nodi, integrando lo stato dell’infrastruttura nel dashboard.

**services.yaml**
Elenca i servizi monitorati dal dashboard, specificandone tipologia, endpoint, parametri di controllo e icone. Viene utilizzato per verificare la disponibilità e lo stato dei servizi configurati.

**settings.yaml**
Raccoglie le impostazioni generali dell’applicazione, tra cui tema, layout, lingua e preferenze globali. Determina il comportamento complessivo del dashboard.

**widgets.yaml**
Contiene la configurazione dei widget mostrati nella dashboard. Ogni widget include le proprie impostazioni specifiche e i parametri necessari al suo funzionamento.
