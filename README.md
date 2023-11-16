# Tesi
Tesi di Laurea presso l'Università degli Studi di Torino, Novembre 2023.

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://www.unito.it/">
    <img src="Latex Project/img/logo_new_2022.png" alt="Logo" width="67" height="100">
  </a>

  <h3 align="center">TESI</h3>

  <p align="center">
    Tesi di Laurea presso l'Università degli Studi di Torino, Novembre 2023.
    <br />
    <a href="https://github.com/Magitman/Tesi/blob/main/Realizzazione%20di%20un%20servizio%20REST%20per%20la%20validazione%20dei%20codici%20bancari.pdf"><strong>Tesi</strong></a>
    <br />
    <br />
    <a href="https://github.com/Magitman/Tesi/blob/main/Presentazione/Presentazione%20Tesi.pdf">Presentazione</a>
    ·
    <a href="https://github.com/Magitman/Tesi/tree/main/Latex%20Project">Progetto Latex</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#Realizzazione-di-un-Servizio-REST-per-la-Validazione-dei-Codici-Bancari">Realizzazione di un Servizio REST per la Validazione dei Codici Bancari</a></li>
    <li><a href="#Stage">Stage</a></li>
    <li><a href="#Tecnologie">Tecnologie</a></li>
    <li><a href="#Architettura">Architettura</a></li>
    <li><a href="#Back-end">Back-end</a></li>
    <li><a href="#Front-end">Front-end</a></li>
    <li><a href="#Conclusioni">Conclusioni</a></li>
    <li><a href="#Crediti">Crediti</a></li>
  </ol>
</details>

<!-- TESI -->
## Realizzazione di un Servizio REST per la Validazione dei Codici Bancari
<div align="center">
  <img src="Presentazione/img/01.png" alt="Slide introduttiva. Include titolo, università, relatrice e tutor." />
</div>
Sono <a href="https://www.linkedin.com/in/luca-broggiato-639154188/" target="_blank">Luca Broggiato</a> e questa è la presentazione della mia tesi di laurea, intitolata “Realizzazione di un servizio REST per la validazione dei codici bancari”. La stesura è stata possibile anche grazie al prezioso aiuto e supporto della mia relatrice, la docente <a href="https://www.linkedin.com/in/liliana-ardissono-1007508/" target="_blank">Liliana Ardissono</a>, ed i tutor che si sono avvicendati in azienda, i dottori <a href="https://www.linkedin.com/in/paolo-mino-a284653b/" target="_blank">Paolo Mino</a> e <a href="https://www.linkedin.com/in/antonio-zollino-43638346/" target="_blank">Antonio Zollino</a>.
<br />
<br />

<!-- INDICE -->
<div align="center">
  <img src="Presentazione/img/02.png" alt="Indice della presentazione." />
</div>
La presentazione è composta da 6 sezioni, ognuna riguardante un tema specifico, per illustrare la mia esperienza di tirocinio curriculare ed il progetto che ho potuto realizzare.

<!-- STAGE -->
## Stage
<div align="center">
  <img src="Presentazione/img/03.png" alt="Stage." />
</div>
Si presenta innanzitutto l'esperienza di stage esterno.
<br />
<br />

<div align="center">
  <img src="Presentazione/img/04.png" alt="Contesto Lavorativo." />
</div>
Il tirocinio curriculare che ho svolto si è tenuto presso l’azienda multinazionale <a href="https://www.alten.it" target="_blank">Alten</a>. Si tratta di una società di consulenza informatica fondata in Francia a fine anni ‘80 e che attualmente è presente in oltre 30 Paesi in tutto il mondo. Anche in Italia, è presente nelle principali città del territorio, offrendo servizi di consulenza in ambito informatico, ingegneristico e delle scienze della vita. Il team in cui sono stato inserito è multidisciplinare, composto quindi da figure di sviluppatori back-end, front-end e full-stack, oltre che da manager di progetto e altre figure di team leading. Si tratta anche di un gruppo lavorativo dislocato sul territorio, con persone operative e connesse da varie città italiane. Infine, l’azienda cliente, che ha commissionato il progetto che ho realizzato, è un gruppo bancario che ricopre un ruolo importante all’interno del perimetro geografico europeo.
<br />
<br />

<div align="center">
  <img src="Presentazione/img/05.png" alt="Presentazione del Progetto." />
</div>
Per quanto riguarda il progetto, l’obiettivo principale era quello di realizzare un servizio che fosse in grado di validare codici IBAN, implementando anche un’interfaccia web che permettesse ad utenti ed operatori del gruppo bancario di interagire con l’applicativo. In particolare, il servizio back-end espone un API REST che valida l’ID bancario inviato e tiene traccia delle richieste dei client in un database. Il punto d’ingresso del servizio, utilizzabile dagli utenti, ha richiesto lo sviluppo front-end di una pagina web per l’immissione dei dati e la visualizzazione dell’output, in modo che risultasse semplice, intuitivo e affidabile. Come si evince, la realizzazione del progetto ha richiesto la convergenza di competenze provenienti da diversi campi dello sviluppo software, da back-end a front-end. Questo approccio multidisciplinare è stato reso possibile anche dal contesto lavorativo mostrato nella slide precedente.
<br />
<br />

<!-- TECNOLOGIE -->
## Tecnologie
<div align="center">
  <img src="Presentazione/img/06.png" alt="Tecnologie Utilizzate." />
</div>
Passando alle tecnologie utilizzate nella realizzazione dell’applicativo, ho voluto suddividerle in modo da separare quelle usate per lo sviluppo front-end da quelle usate per il back-end.
<br />
<br />

<div align="center">
  <img src="Presentazione/img/07.png" alt="Grafico delle Tecnologie Utilizzate." />
</div>
Cominciando dal front-end, il framework su cui si basa la web-application è Angular, utilizzato per creare l’interfaccia utente dell’applicazione come Single Page Application. Questa è stata realizzata focalizzandosi sulla creazione e comunicazione dei componenti, elementi fondamentali per Angular che contengono la definizione di una vista all’interno della pagina. Ognuno è formato da un file di script TypeScript decorato con l’annotazione @Component, un modello HTML e stili CSS opzionali. La collaborazione tra questi elementi definisce l’aspetto ed il comportamento di ogni componente, e quindi della pagina stessa. La realizzazione del back-end, invece, è stata messa in pratica utilizzando il framework Spring Boot, che semplifica e velocizza lo sviluppo di applicazioni web basate su Spring, e quindi sul linguaggio di programmazione Java. Spring Boot consente allo sviluppatore di concentrarsi sulle funzionalità di business, occupandosi automaticamente della gestione delle risorse del sistema e fornendo supporto all’infrastruttura dell’applicazione. Inoltre, mette a disposizione i cosiddetti “starter”, ovvero set di dipendenze configurate automaticamente. Uno di questi è “spring data jpa”, parte del progetto Spring Data e che include tutte le dipendenze necessarie per comunicare con il database tramite JPA, acronimo di Java Persistence API. Spring Data JPA è un framework che fornisce un modello di programmazione per l’accesso ai dati in database relazionali e non, semplificando l’implementazione dei repository, ovvero le interfacce preposte alla comunicazione con la base dati. Oltre alle tecnologie citate, è stata realizzata una suite di test con Junit mentre il database è stato implementato in modalità in-memory con H2, un database management system relazionale scritto in Java e supportato da Spring Boot. Inoltre, il linguaggio SQL è stato utilizzato per dichiarare la struttura del database, nonostante questo sia formato da un’unica tabella in cui vengono memorizzate le richieste dei client. Per concludere, lo strumento di build utilizzato è Maven, che si occupa della compilazione dei file sorgenti in eseguibili e gestisce l’integrazione ed il download delle dipendenze esterne all’interno del progetto.
