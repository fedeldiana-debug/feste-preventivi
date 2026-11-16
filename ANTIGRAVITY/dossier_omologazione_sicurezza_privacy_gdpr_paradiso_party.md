# Dossier di Omologazione, Sicurezza e Conformità Normativa GDPR
## Paradiso Party • Area Feste Esclusiva per Bambini & Famiglie
*Documento di Conformità Legale, Protezione Dati e Requisiti di Sicurezza Operativa*
*Data di Redazione: 13 Novembre 2026*

---

## 1. Premessa & Finalità del Documento

Il presente dossier costituisce il **Manuale Operativo e di Accountability** (ex Art. 5, par. 2 del Regolamento UE 2016/679 - GDPR) per la gestione della Web App, del sito di prenotazione e delle attività operative dell'area feste **Paradiso Party**.

La piattaforma è stata progettata seguendo i principi di:
1. **Privacy by Design & by Default (Art. 25 GDPR)**: raccolta dei soli dati strettamente necessari all'elaborazione del preventivo e all'organizzazione dell'evento.
2. **Minimizzazione dei dati (Art. 5.1.c GDPR)**: zero cookie di profilazione pubblicitaria, archiviazione tecnica su dispositivo locale (`localStorage`) e canali di comunicazione cifrati end-to-end.
3. **Tutela Rafforzata dei Minori (Art. 8 GDPR & Codice Privacy)**: conferimento dati subordinato all'assenso esplicito del titolare della responsabilità genitoriale.
4. **Conformità Tecnica e di Sicurezza delle Attrezzature**: rispetto delle norme europee UNI EN 1176 (parchi gioco) e UNI EN 14960 (gonfiabili).

---

## 2. Quadro Normativo di Riferimento

| Settore Normativo | Norma / Provvedimento Applicabile | Oggetto e Prescrizioni Chiave |
| :--- | :--- | :--- |
| **Protezione Dati Personali** | **Regolamento (UE) 2016/679 (GDPR)** | Trasparenza, liceità, consenso informato, diritti degli interessati (Artt. 12-22). |
| **Dati Sanitari & Allergie** | **Art. 9 GDPR (Dati Particolari)** | Divieto di trattamento salvo consenso esplicito a tutela della salute del minore. |
| **Immagini & Riprese Minori** | **L. 633/1941 (Artt. 96-97)** & Provv. Garante Minori | Divieto di diffusione immagini senza consenso espresso del genitore; divieto di pregiudizio al decoro. |
| **Cookie & Archiviazione Web** | **Linee Guida Garante Privacy 10/06/2021 (n. 231)** | Esenzione da consenso per storage tecnico; divieto di tracker terze parti non autorizzati. |
| **Sicurezza Aree Gioco** | **Norma UNI EN 1176 & UNI EN 1177** | Requisiti di sicurezza, altezze di caduta, pavimentazione antitrauma e manutenzione parchi gioco. |
| **Gonfiabili & Giochi Dinamici** | **Norma UNI EN 14960** | Ancoraggi al suolo certificati, collaudi statici, soffiatori protetti e sorveglianza dedicata. |
| **Igiene Alimentare** | **Regolamento (CE) n. 852/2004 (HACCP)** | Protocolli di igiene, catena del freddo e tracciabilità buffet / convenzioni pizzerie. |
| **Prevenzione Incendi & Emergenza** | **D.M. 03/09/2021 & D.Lgs. 81/2008** | Estintori omologati revisionati, cassetta pronto soccorso allegato 2, vie di fuga libere. |

---

## 3. Registro dei Trattamenti Dati Semplificato (Art. 30 GDPR)

### 3.1. Dati del Titolare del Trattamento
* **Denominazione:** Paradiso Party • Area Feste
* **Referente Privacy & Legale:** Diana di Paradiso Party
* **Email Ufficiale Notifiche & Privacy:** fedeldiana@gmail.com
* **Recapito Telefonico / WhatsApp:** +39 338 684 6195
* **Piattaforma Web / PWA:** `paradisoparty.netlify.app` / Web App Booking locale

### 3.2. Scheda Trattamento 1: Gestione Preventivi & Prenotazione Feste
* **Finalità:** Riscontro alle richieste di disponibilità, calcolo preventivo trasparente, invio listini convenzionati ed erogazione del servizio di noleggio struttura.
* **Base Giuridica:** *Art. 6, par. 1, lett. b) GDPR* (Esecuzione di misure precontrattuali e contrattuali adottate su richiesta dell'interessato).
* **Categorie di Dati:** Nome del genitore, recapito telefonico WhatsApp, data e turno festa, format prescelto, numero invitati.
* **Periodo di Conservazione:** 180 giorni per i preventivi non confermati; 10 anni (normativa fiscale ex art. 2220 c.c.) per le prenotazioni confermate.

### 3.3. Scheda Trattamento 2: Dati dei Minori (Nome & Fascia d'Età)
* **Finalità:** Assegnazione operatore di animazione dedicato, dimensionamento attività ludiche in base all'età, personalizzazione accoglienza.
* **Base Giuridica:** *Art. 8 GDPR* e *Art. 2-quinquies D.Lgs. 196/2003* (Consenso prestato o autorizzato dall'esercente la responsabilità genitoriale).
* **Misure di Sicurezza:** Dati non divulgati a soggetti esterni non coinvolti nell'erogazione diretta della festa.

### 3.4. Scheda Trattamento 3: Dati Sensibili Sanitari (Allergie & Intolleranze Alimentari)
* **Finalità:** Tutela della salute e dell'incolumità alimentare dei bambini durante la somministrazione del rinfresco (es. celiachia, allergie a frutta a guscio, favismo, intolleranza al lattosio).
* **Base Giuridica:** *Art. 9, par. 2, lett. a) GDPR* (Consenso esplicito dell'interessato).
* **Misure di Sicurezza:** Comunicazione esclusivamente ai laboratori alimentari / pizzerie partner incaricate della fornitura, limitatamente al singolo evento.

### 3.5. Scheda Trattamento 4: Foto & Video Promozionali
* **Finalità:** Creazione archivio ricordo famiglia e promozione delle attività dell'area feste sui canali social ufficiali.
* **Base Giuridica:** *Art. 6, par. 1, lett. a) GDPR* e *Artt. 96-97 Legge 633/1941*.
* **Misure di Tutela:** Consenso facoltativo, separato e revocabile in qualsiasi momento. Divieto tassativo di riprese lesive della reputazione o del decoro dei minori.

---

## 4. Architettura Tecnica di Sicurezza dell'App (Security by Design)

L'applicazione web implementa i seguenti standard di sicurezza informatica:

1. **Zero Profilazione & Privacy Compliant:**
   * Nessun cookie di profilazione pubblicitaria di terze parti installato.
   * Conforme al Provvedimento del Garante Privacy del 10 giugno 2021 (non richiede banner bloccante a pagamento, ma informativa trasparente e banner tecnico di prima visita).
2. **Archiviazione Protetta su Dispositivo (HTML5 LocalStorage):**
   * Il preventivo della mamma rimane memorizzato nel browser locale del cliente.
   * I dati non transitano su server non protetti né database aperti a terzi.
3. **Canale di Trasmissione Cifrato WhatsApp (End-to-End Encryption):**
   * Quando la mamma clicca su *"Invia Richiesta su WhatsApp"*, il riepilogo viaggia direttamente sul protocollo crittografico Signal di WhatsApp: nessun intermediario o broker pubblicitario può intercettare la conversazione.
4. **Sanitizzazione Input & Protezione XSS:**
   * I campi di testo (nomi, note allergie) sono filtrati e codificati per prevenire injection di script malevoli all'interno dell'interfaccia.

---

## 5. Checklist Autorizzazioni Amministrative & Sicurezza Location

Per la piena conformità legale dell'area feste e dell'attività di noleggio/intrattenimento, sono presidiati i seguenti requisiti operativi:

### 5.1. Requisiti Strutturali & Omologazione
* [x] **Agibilità e Stabilità Strutture Ombreggianti:** Tettoia e porticato conformi alle norme edilizie locali e ancorati in sicurezza contro raffiche di vento.
* [x] **Certificazione Attrezzature Ludiche (UNI EN 1176):** Giostrine e arredi esterni con marcatura CE, assenza di spigoli metallici vivi e superfici antinfortunistiche.
* [x] **Collaudo Gonfiabili (UNI EN 14960):** Certificato di conformità annuale rilasciato da tecnico abilitato, zavorre di ancoraggio a terra e soffiatori a norma con differenziale salvavita 30mA.
* [x] **Gabbia Calcio 1v1 DIY (se installata):** Rivestimento dei tubolari con gommapiuma ad alta densità protetta da PVC nautico 650 g/m² e reti elastiche prive di spigoli sporgenti (UNI EN 15312).

### 5.2. Igiene & Sanificazione (HACCP)
* [x] Registro di pulizia e sanificazione di tavoli, panche e servizi igienici al termine di ogni turno.
* [x] Frigoriferi dedicati per bibite e torte conformi alla temperatura di conservazione (+4°C).
* [x] Fornitori convenzionati in possesso di regolare registrazione sanitaria alimentare (SCIA sanitaria).

### 5.3. Prevenzione Emergenze & Sanità
* [x] **Cassetta di Pronto Soccorso:** A norma D.M. 388/2003 costantemente rifornita con disinfettanti, garze sterili, ghiaccio istantaneo e cerotti per bambini.
* [x] **Estintori Antincendio:** Almeno un estintore a polvere 6 kg omologato, revisionato semestralmente e posizionato in punto visibile e accessibile.
* [x] **Cartellonistica di Sicurezza:** Segnalazione uscite di emergenza, divieto di fumo e numero unico di emergenza europeo (112) ben visibile.

### 5.4. Copertura Assicurativa
* [x] **Polizza R.C.T. (Responsabilità Civile verso Terzi):** Polizza assicurativa per danni involontariamente cagionati a terzi (persone e cose) nell'ambito dell'esercizio dell'attività ricreativa dell'area feste.

---

## 6. Modello Cartaceo di Liberatoria & Privacy (Pronto per Firma in Sede)

Nel caso in cui il titolare desideri far firmare una ricevuta cartacea al genitore al momento dell'ingresso in struttura, si allega il modulo standard conforme:

```text
================================================================================
PARADISO PARTY • MODULO DI ACCETTAZIONE REGOLAMENTO & LIBERATORIA PRIVACY
================================================================================

Io sottoscritto/a: ___________________________________________________________
Nato/a a: __________________________________________ il: _____ / _____ / _______
Codice Fiscale: ______________________________________________________________
Cellulare WhatsApp: __________________________________________________________
Genitore / Tutore del minore: ________________________________________________

1. ACCETTAZIONE REGOLAMENTO FESTE
Dichiaro di aver preso visione e di accettare integralmente il "Regolamento per lo
Svolgimento delle Feste" di Paradiso Party (in particolare: durata 3h + 30 min, 
orari tassativi, acconto 50%, condizioni meteo, parcheggio max 17 posti,
rapporto animazione 1:8 e prezzi al netto di IVA).

[ X ] ACCETTO IL REGOLAMENTO

2. INFORMATIVA PRIVACY (ARTT. 13-14 REG. UE 2016/679)
Dichiaro di essere stato informato che i dati personali miei e del minore saranno
trattati esclusivamente per l'esecuzione del servizio concordato, adempimenti di
legge e comunicazioni organizzative della festa.

[ X ] PRENDO ATTO DELL'INFORMATIVA PRIVACY

3. LIBERATORIA FOTO E VIDEO MINORI (FACOLTATIVA)
Autorizzo Paradiso Party a effettuare scatti fotografici e brevi video ricordo 
durante l'evento a scopo di cronaca interna e promozione delle attività dell'area:
[   ] ACCONSENTO alle riprese foto/video
[   ] NON ACCONSENTO alle riprese foto/video

Luogo e Data: __________________________, lì _____ / _____ / _________

Firma leggibile del Genitore: ________________________________________________
================================================================================
```

---

## 7. Riepilogo Strumenti Attivi sull'App

Sull'applicazione web [index.html](file:///c:/Users/Amminstr1/Desktop/CARTELLA%20AI/AREA%20FESTE/APP%20BOOKING%20FESTE/index.html) sono ora pienamente operativi:
1. **Pulsante Header *"🔒 Privacy & Minori GDPR"***: apre la modale completa con tutti gli articoli normativi;
2. **Pulsante Header *"📜 Regolamento Feste"***: apre il regolamento integrale in 9 punti;
3. **Banner Discreto di Prima Visita *"Privacy & Cookie Tecnico"*** con consenso rapido a norma Garante;
4. **Doppio Checkbox di Garanzia al Passo 3:** Regolamento Feste + Informativa Privacy con verifica vincolante prima dell'invio;
5. **Footer Istituzionale Completo:** link rapidi a Regolamento, Privacy Policy GDPR, Cookie & Storage, Sicurezza & Normativa;
6. **Menzione Dati Sanitari Art. 9 GDPR** sotto il riquadro allergie alimentari;
7. **Liberatoria Immagini L. 633/1941** con facoltà di revoca autonoma per i genitori;
8. **Archiviazione Sicura Locale:** ogni preventivo inviato viene registrato in `localStorage` per garanzia e riscontro del titolare.
