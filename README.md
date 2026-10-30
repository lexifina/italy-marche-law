# Marche: law history in git

The law of the region of Marche (Regione Marche, Italy) as a git history: one file per article, one commit per change, dated the day it took effect. `git blame` names the law behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day (here: the text in force when it was retrieved).

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `it-57/`. Italy's national law is in [lexifina/italy-law](https://github.com/lexifina/italy-law).

The text is in Italian, exactly as the source prints it.

## What this repository holds

783 acts with 783 versions so far: the Statute (Statuto regionale) first, then the regional laws in force, added in parts of about fifty. Regulations and the amending statutory laws are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `statuto/` | Statuto della Regione Marche (Legge statutaria 8 marzo 2005, n. 1) | 1 | oldest version available: 30 October 2026 |
| `lr-1971-2/` | L.R. 16 dicembre 1971, n. 2: Istituzione delle tasse regionali di circolazione. | 1 | oldest version available: 30 October 2026 |
| `lr-1971-3/` | L.R. 16 dicembre 1971, n. 3: Istituzione dell'imposta regionale sulle concessioni statali dei beni del demanio e del patrimonio indisponibile. | 1 | oldest version available: 30 October 2026 |
| `lr-1972-1/` | L.R. 16 gennaio 1972, n. 1: Autorizzazione alla Giunta regionale all'esercizio provvisorio del bilancio dell'anno finanziario 1972. | 1 | oldest version available: 30 October 2026 |
| `lr-1972-3/` | L.R. 20 aprile 1972, n. 3: Bilancio di previsione per l'esercizio finanziario 1972. | 1 | oldest version available: 30 October 2026 |
| `lr-1972-5/` | L.R. 10 agosto 1972, n. 5: Disciplina transitoria per l'esercizio delle funzioni amministrative trasferite dallo Stato alla Regione. | 1 | oldest version available: 30 October 2026 |
| `lr-1972-6/` | L.R. 4 settembre 1972, n. 6: Variazioni al bilancio di previsione della Regione per l'anno finanziario 1972. | 1 | oldest version available: 30 October 2026 |
| `lr-1972-7/` | L.R. 27 ottobre 1972, n. 7: Variazioni da introdursi al bilancio di previsione per l'anno finanziario 1972 per l'esercizio delle funzioni trasferite. | 1 | oldest version available: 30 October 2026 |
| `lr-1973-1/` | L.R. 15 gennaio 1973, n. 1: Autorizzazione all'esercizio provvisorio del bilancio per l'anno finanziario 1973. | 1 | oldest version available: 30 October 2026 |
| `lr-1973-2/` | L.R. 30 gennaio 1973, n. 2: Proroga dei termini di cui agli artt. 1 e 2 della legge regionale 10 agosto 1972, n. 5. | 1 | oldest version available: 30 October 2026 |
| `lr-1973-3/` | L.R. 31 gennaio 1973, n. 3: Variazione da introdursi al bilancio di previsione per l'anno finanziario 1972 (Variazione n. 3) | 1 | oldest version available: 30 October 2026 |
| `lr-1973-4/` | L.R. 31 gennaio 1973, n. 4: Variazione allo stato di previsione della spesa per l'anno 1972 (Variazione n. 4). | 1 | oldest version available: 30 October 2026 |
| `lr-1973-5/` | L.R. 31 gennaio 1973, n. 5: Variazioni al bilancio per l'anno 1972. Esercizio delle funzioni delegate alla Regione dal Ministero della Sanità - Piani di profila | 1 | oldest version available: 30 October 2026 |
| `lr-1973-8/` | L.R. 20 aprile 1973, n. 8: Bilancio di previsione per l'anno 1973. | 1 | oldest version available: 30 October 2026 |
| `lr-1973-10/` | L.R. 21 maggio 1973, n. 10: Protrazione al 31 dicembre 1973 dei termini per la chiusura dell'esercizio finanaziario 1972. | 1 | oldest version available: 30 October 2026 |
| `lr-1973-13/` | L.R. 26 giugno 1973, n. 13: Variazione ai bilanci di previsione per gli anni finanziari 1972 e 1973. | 1 | oldest version available: 30 October 2026 |
| `lr-1973-14/` | L.R. 25 giugno 1973, n. 14: Variazione al bilancio per l'anno finanziario 1972 - Profilassi obbligatoria dell'afta epizootica e della peste suina classica e pro | 1 | oldest version available: 30 October 2026 |
| `lr-1973-15/` | L.R. 27 giugno 1973, n. 15: Concessione di un contributo annuo all'Istituto regionale per la storia del movimento di liberazione nelle Marche. | 1 | oldest version available: 30 October 2026 |
| `lr-1973-18/` | L.R. 23 luglio 1973, n. 18: Norme per la determinazione delle indennità e per la previdenza dei Consiglieri della Regione Marche. | 1 | oldest version available: 30 October 2026 |
| `lr-1973-19/` | L.R. 26 luglio 1973, n. 19: Assegnazione alle famiglie terremotate degli alloggi di edilizia residenziale pubblica acquistati o costruiti dall'Istituto autonomo | 1 | oldest version available: 30 October 2026 |
| `lr-1973-20/` | L.R. 27 luglio 1973, n. 20: Variazioni al bilancio per l' anno finanziario 1973, D.P.R. 15 gennaio 1972 n. 8, art. 13 - Trasferimento alle Regioni a statuto ord | 1 | oldest version available: 30 October 2026 |
| `lr-1973-22/` | L.R. 20 agosto 1973, n. 22: Norme per l'asercizio delle funzioni amministrative in ordine al fondo di solidarietà nazionale, delegate alla Regione dal D.P.R. 15 | 1 | oldest version available: 30 October 2026 |
| `lr-1973-26/` | L.R. 30 agosto 1973, n. 26: Rettifica della legge regionale n. 5 del 31 gennaio 1973. Variazioni al bilancio per l'anno finanziario 1972 esercizio delle funzion | 1 | oldest version available: 30 October 2026 |
| `lr-1973-31/` | L.R. 5 novembre 1973, n. 31: Variazioni da introdursi al bilancio per l'anno finanziario 1972 finanziamento alle Comunità montane per la redazione e l'attuazion | 1 | oldest version available: 30 October 2026 |
| `lr-1973-33/` | L.R. 15 novembre 1973, n. 33: Variazioni ai bilanci di previsione per l'anno 1972 (n. 10) e 1973 (n. 3). | 1 | oldest version available: 30 October 2026 |
| `lr-1973-35/` | L.R. 27 novembre 1973, n. 35: Storno del fondo di L. 15.000.000 iscritto al capitolo dello stato di previsione n. 2565 per l'anno finanziario 1972. | 1 | oldest version available: 30 October 2026 |
| `lr-1973-36/` | L.R. 3 dicembre 1973, n. 36: Variazione al bilancio di previsione per l'anno finanziario 1973 (variazione n. 4). | 1 | oldest version available: 30 October 2026 |
| `lr-1974-4/` | L.R. 16 gennaio 1974, n. 4: Opere di difesa del litorale marchigiano in zone di interesse turistico per la costruzione, completamento o miglioramento di porti c | 1 | oldest version available: 30 October 2026 |
| `lr-1974-5/` | L.R. 2 febbraio 1974, n. 5: Variazioni al bilancio di previsione per l'anno finanziario 1973 (Variazione n. 6). | 1 | oldest version available: 30 October 2026 |
| `lr-1974-6/` | L.R. 2 febbraio 1974, n. 6: Variazioni al bilancio di previsione per l'anno finanziario 1972 (Variazione n. 12). | 1 | oldest version available: 30 October 2026 |
| `lr-1974-7/` | L.R. 2 febbraio 1974, n. 7: Autorizzazione all'esercizio provvisorio del bilancio 1974. | 1 | oldest version available: 30 October 2026 |
| `lr-1974-8/` | L.R. 19 febbraio 1974, n. 8: Variazione al bilancio per l'anno finanziario 1973 (Variazione n. 5). | 1 | oldest version available: 30 October 2026 |
| `lr-1974-11/` | L.R. 7 maggio 1974, n. 11: Bilancio di previsione per l'anno finanziario 1974. | 1 | oldest version available: 30 October 2026 |
| `lr-1974-16/` | L.R. 30 luglio 1974, n. 16: Provvedimenti per i centri storici colpiti da eventi sismici. | 1 | oldest version available: 30 October 2026 |
| `lr-1974-23/` | L.R. 5 settembre 1974, n. 23: Iniziativa legislativa popolare. | 1 | oldest version available: 30 October 2026 |
| `lr-1974-24/` | L.R. 18 ottobre 1974, n. 24: Adesione della Regione Marche all'Associazione Italiana per il Consiglio dei Comuni d'Europa - A.I.C.C.E. - Sezione italiana del Co | 1 | oldest version available: 30 October 2026 |
| `lr-1974-25/` | L.R. 18 ottobre 1974, n. 25: Adesione della Regione Marche alla Comunità dei Porti Adriatici. | 1 | oldest version available: 30 October 2026 |
| `lr-1974-26/` | L.R. 18 ottobre 1974, n. 26: Adesione della Regione Marche al comitato permanente delle regioni periferiche marittime d'Europa. | 1 | oldest version available: 30 October 2026 |
| `lr-1974-34/` | L.R. 7 novembre 1974, n. 34: Variazione al bilancio per l'anno finanziario 1974 e autorizzazione all'acquisto e sistemazione di un fabbricato da destinare all'a | 1 | oldest version available: 30 October 2026 |
| `lr-1974-50/` | L.R. 9 dicembre 1974, n. 50: Approvazione del bilancio di previsione per l'anno finanziario 1973 e delle relative variazioni dell'Ente di Sviluppo nelle Marche. | 1 | oldest version available: 30 October 2026 |
| `lr-1974-52/` | L.R. 30 dicembre 1974, n. 52: Provvedimenti per la tutela degli ambienti naturali. | 1 | oldest version available: 30 October 2026 |
| `lr-1975-6/` | L.R. 30 gennaio 1975, n. 6: Autorizzazione all'esercizio provvisorio del bilancio 1975. | 1 | oldest version available: 30 October 2026 |
| `lr-1975-9/` | L.R. 5 marzo 1975, n. 9: Variazioni al bilancio di previsione per l'anno 1974 | 1 | oldest version available: 30 October 2026 |
| `lr-1975-15/` | L.R. 18 marzo 1975, n. 15: Adesione della Regione Marche all'Istituto nazionale per la sociologia rurale (INSOR). | 1 | oldest version available: 30 October 2026 |
| `lr-1975-21/` | L.R. 30 marzo 1975, n. 21: Modifica dell'art. 8 e 18 della legge regionale 20 marzo 1975, n. 17 concernente: provvedimenti per agevolare la realizzazione di ope | 1 | oldest version available: 30 October 2026 |
| `lr-1975-26/` | L.R. 2 maggio 1975, n. 26: Approvazione del bilancio di previsione per l'anno 1975. | 1 | oldest version available: 30 October 2026 |
| `lr-1975-27/` | L.R. 30 aprile 1975, n. 27: Rendiconti generali per l'anno 1972, protratto al 31 dicembre 1973 (legge regionale 21 maggio 1973, n. 10) e per l'anno 1973. | 1 | oldest version available: 30 October 2026 |
| `lr-1975-33/` | L.R. 19 maggio 1975, n. 33: Dotazione del capitolo relativo alle spese per la propaganda turistica per l'esercizio finanziario 1975 in ottemperanza alle osserva | 1 | oldest version available: 30 October 2026 |
| `lr-1975-34/` | L.R. 21 maggio 1975, n. 34: Interventi edificatori nelle zone di rispetto delle strade. | 1 | oldest version available: 30 October 2026 |
| `lr-1975-35/` | L.R. 19 maggio 1975, n. 35: Provvedimenti per agevolare l'attività di pianificazione urbanistica degli Enti locali. | 1 | oldest version available: 30 October 2026 |
| `lr-1975-45/` | L.R. 22 maggio 1975, n. 45: Vincoli preordinati alla espropriazione o che comportino inedificabilità contenuti nei programmi di fabbricazione. | 1 | oldest version available: 30 October 2026 |
| `lr-1975-46/` | L.R. 26 maggio 1975, n. 46: Utilizzazione degli avanzi di amministrazione accertati alla chiusura degli esercizi finanziari 1972 e 1973 | 1 | oldest version available: 30 October 2026 |
| `lr-1976-1/` | L.R. 16 gennaio 1976, n. 1: Convalida ai sensi dell'art. 14 della legge regionale 2 maggio 1975, n. 26, della deliberazione della Giunta regionale n. 2164 del 5 | 1 | oldest version available: 30 October 2026 |
| `lr-1976-2/` | L.R. 20 gennaio 1976, n. 2: Autorizzazione all'esercizio provvisorio del bilancio per l'anno 1976. | 1 | oldest version available: 30 October 2026 |
| `lr-1976-3/` | L.R. 28 gennaio 1976, n. 3: Variazione di bilancio di previsione della Regione per l'anno 1975. | 1 | oldest version available: 30 October 2026 |
| `lr-1976-4/` | L.R. 16 marzo 1976, n. 4: Bilancio di previsione per l'anno finanziario 1976. | 1 | oldest version available: 30 October 2026 |
| `lr-1976-6/` | L.R. 22 aprile 1976, n. 6: Convalida della deliberazione della Giunta regionale del 10 giugno 1975, n. 1638 concernente: "Assistenza ospedaliera - legge regiona | 1 | oldest version available: 30 October 2026 |
| `lr-1976-8/` | L.R. 6 maggio 1976, n. 8: Approvazione del rendiconto generale dell'esercizio 1974. | 1 | oldest version available: 30 October 2026 |
| `lr-1976-9/` | L.R. 6 maggio 1976, n. 9: Trasferimento, ad anni successivi, di autorizzazione di spesa stabilite per gli anni 1974/1975. | 1 | oldest version available: 30 October 2026 |
| `lr-1976-13/` | L.R. 24 maggio 1976, n. 13: Variazione al bilancio di previsione della spesa per l'anno 1976 in attuazione dell'art. 17 del D.L. 13 agosto 1975, n. 376, convert | 1 | oldest version available: 30 October 2026 |
| `lr-1976-23/` | L.R. 21 agosto 1976, n. 23: Variazione al bilancio di previsione per l'anno finanziario 1976 (II provvedimento). | 1 | oldest version available: 30 October 2026 |
| `lr-1976-29/` | L.R. 2 settembre 1976, n. 29: Approvazione del rendiconto generale della Regione per l'esercizio finanziario 1975. | 1 | oldest version available: 30 October 2026 |
| `lr-1977-1/` | L.R. 5 gennaio 1977, n. 1: Opere di difesa del litorale marchigiano in zone di interesse turistico per la costruzione, completamento o miglioramento di porti cl | 1 | oldest version available: 30 October 2026 |
| `lr-1977-2/` | L.R. 7 gennaio 1977, n. 2: Autorizzazione all'esercizio provvisorio del bilancio per l'anno 1977. | 1 | oldest version available: 30 October 2026 |
| `lr-1977-4/` | L.R. 20 gennaio 1977, n. 4: Variazioni del bilancio 1976. | 1 | oldest version available: 30 October 2026 |
| `lr-1977-12/` | L.R. 26 aprile 1977, n. 12: Opere di intervento straordinario e urgente per il miglioramento della funzionalità dei porti regionali di Fano e Senigallia in attu | 1 | oldest version available: 30 October 2026 |
| `lr-1977-13/` | L.R. 27 aprile 1977, n. 13: Acquisto di edificio ed aree annesse per la realizzazione della sede degli uffici regionali. | 1 | oldest version available: 30 October 2026 |
| `lr-1977-24/` | L.R. 6 luglio 1977, n. 24: Bilancio di previsione per l'anno finanziario 1977. | 1 | oldest version available: 30 October 2026 |
| `lr-1977-25/` | L.R. 7 luglio 1977, n. 25: Variazione al bilancio di previsione per l'anno 1977 convalida della delibera della Giunta Regionale del 6.4.1977, n. 1004. | 1 | oldest version available: 30 October 2026 |
| `lr-1977-28/` | L.R. 22 luglio 1977, n. 28: Adesione della Regione Marche all'Istituto Adriano Olivetti di studi per la gestione dell'economia e delle aziende. | 1 | oldest version available: 30 October 2026 |
| `lr-1977-34/` | L.R. 26 agosto 1977, n. 34: Trasferimento ad anni successivi di autorizzazioni di spesa stabilite per l'anno 1976 e anni anteriori. | 1 | oldest version available: 30 October 2026 |
| `lr-1977-38/` | L.R. 2 settembre 1977, n. 38: Assestamento del bilancio per l'anno finanziario 1977. | 1 | oldest version available: 30 October 2026 |
| `lr-1977-39/` | L.R. 3 settembre 1977, n. 39: Approvazione del rendiconto generale della regione per l'esercizio finanziario 1976. | 1 | oldest version available: 30 October 2026 |
| `lr-1977-40/` | L.R. 5 settembre 1977, n. 40: Adozione bilancio pluriennale per il periodo 1977/1981. | 1 | oldest version available: 30 October 2026 |
| `lr-1977-42/` | L.R. 28 ottobre 1977, n. 42: Attuazione delle direttive 72/159-160-161/CEE, 75/268/CEE e delle leggi 9.5.1975, n. 153 e 10.5.1976, n. 352 per la riforma dell'ag | 1 | oldest version available: 30 October 2026 |
| `lr-1977-48/` | L.R. 16 dicembre 1977, n. 48: Variazione al bilancio di previsione per l'anno finanziario 1977 (II provvedimento). | 1 | oldest version available: 30 October 2026 |
| `lr-1977-50/` | L.R. 24 dicembre 1977, n. 50: Variazione al bilancio 1977 III provvedimento. | 1 | oldest version available: 30 October 2026 |
| `lr-1978-1/` | L.R. 3 gennaio 1978, n. 1: Autorizzazione all'esercizio provvisorio del bilancio per l'anno 1978. | 1 | oldest version available: 30 October 2026 |
| `lr-1978-8/` | L.R. 26 aprile 1978, n. 8: Disciplina per la soppressione dei patronati scolastici e dei consorzi dei patronati scolastici. | 1 | oldest version available: 30 October 2026 |
| `lr-1978-9/` | L.R. 27 aprile 1978, n. 9: Bilancio di previsione per l'anno finanziario 1978. | 1 | oldest version available: 30 October 2026 |
| `lr-1978-20/` | L.R. 2 novembre 1978, n. 20: Istituzione in Ancona del centro regionale immunologia clinica e di tipizzazione tissutale. | 1 | oldest version available: 30 October 2026 |
| `lr-1978-22/` | L.R. 4 novembre 1978, n. 22: Trasferimento, ad anni successivi, di autorizzazione di spesa stabilite per l'anno 1977. | 1 | oldest version available: 30 October 2026 |
| `lr-1978-23/` | L.R. 5 novembre 1978, n. 23: Approvazione del rendiconto generale della Regione per l'esercizio finanziario 1977. | 1 | oldest version available: 30 October 2026 |
| `lr-1978-24/` | L.R. 6 novembre 1978, n. 24: Assestamento del bilancio per l'anno finanziario 1978. | 1 | oldest version available: 30 October 2026 |
| `lr-1979-1/` | L.R. 2 gennaio 1979, n. 1: Variazioni al bilancio della Regione per l'anno finanziario 1978 per l'applicazione del D.P.R. 24.7.1977, n. 616. Primo provvedimento | 1 | oldest version available: 30 October 2026 |
| `lr-1979-2/` | L.R. 3 gennaio 1979, n. 2: Variazioni al bilancio di previsione per l'anno finanziario 1978. Secondo provvedimento. | 1 | oldest version available: 30 October 2026 |
| `lr-1979-4/` | L.R. 4 gennaio 1979, n. 4: Opere straordinarie per il miglioramento della funzionalità dei porti regionali di Fano e di Senigallia in attuazione dei relativi pi | 1 | oldest version available: 30 October 2026 |
| `lr-1979-5/` | L.R. 4 gennaio 1979, n. 5: Delega alle province delle attività istruttorie relative alla tenuta dell'albo provinciale degli autotrasporti di merci. D.P.R. 24.7. | 1 | oldest version available: 30 October 2026 |
| `lr-1979-6/` | L.R. 13 gennaio 1979, n. 6: Autorizzazione all'esercizio provvisorio del bilancio per l'anno 1979. | 1 | oldest version available: 30 October 2026 |
| `lr-1979-17/` | L.R. 18 aprile 1979, n. 17: Legge dei lavori pubblici della Regione Marche. | 1 | oldest version available: 30 October 2026 |
| `lr-1979-20/` | L.R. 18 maggio 1979, n. 20: Approvazione del bilancio di previsione per l'anno 1979. | 1 | oldest version available: 30 October 2026 |
| `lr-1979-31/` | L.R. 4 settembre 1979, n. 31: Interventi edificatori nelle zone di completamento previste dagli strumenti urbanistici generali comunali. | 1 | oldest version available: 30 October 2026 |
| `lr-1979-33/` | L.R. 30 ottobre 1979, n. 33: Trasferimento ad anni successivi di autorizzazioni di spesa stabilite per l'anno 1978. | 1 | oldest version available: 30 October 2026 |
| `lr-1979-34/` | L.R. 31 ottobre 1979, n. 34: Approvazione del rendiconto della Regione per l'esercizio finanziario 1978. | 1 | oldest version available: 30 October 2026 |
| `lr-1979-35/` | L.R. 2 novembre 1979, n. 35: Assestamento del bilancio per l'anno finanziario 1978. | 1 | oldest version available: 30 October 2026 |
| `lr-1980-4/` | L.R. 4 gennaio 1980, n. 4: Contributi ai comuni e agli enti gestori dei mercati ittici all'ingrosso e loro forme associative per opere di ricostruzione, ristrut | 1 | oldest version available: 30 October 2026 |
| `lr-1980-5/` | L.R. 14 gennaio 1980, n. 5: Autorizzazione all'esercizio provvisorio del bilancio per l'anno 1980. | 1 | oldest version available: 30 October 2026 |
| `lr-1980-13/` | L.R. 15 marzo 1980, n. 13: Adozione dello stemma e delle insegne della Regione Marche ai sensi dell'art. 2 dello statuto. | 1 | oldest version available: 30 October 2026 |
| `lr-1980-17/` | L.R. 2 aprile 1980, n. 17: Partecipazione finanziaria della regione alla realizzazione dei progetti di interesse agricolo ammessi ai benefici del fondo europeo | 1 | oldest version available: 30 October 2026 |
| `lr-1980-18/` | L.R. 5 aprile 1980, n. 18: Norme sui referendum previsti dallo Statuto. | 1 | oldest version available: 30 October 2026 |
| `lr-1980-22/` | L.R. 22 aprile 1980, n. 22: Approvazione del bilancio di previsione per l'anno 1980. | 1 | oldest version available: 30 October 2026 |
| `lr-1980-25/` | L.R. 30 aprile 1980, n. 25: Ordinamento contabile della Regione e procedure di programmazione. | 1 | oldest version available: 30 October 2026 |
| `lr-1980-27/` | L.R. 13 maggio 1980, n. 27: Trattamento di quiescenza al personale collocato a riposo nel periodo intercorrente tra la data di trasferimento e quella di entrata | 1 | oldest version available: 30 October 2026 |
| `lr-1980-31/` | L.R. 21 maggio 1980, n. 31: Rifinanziamento della legge regionale 5.1.1977, n. 1. Opere di difesa del litorale marchigiano in zone di interesse turistico per la | 1 | oldest version available: 30 October 2026 |
| `lr-1980-34/` | L.R. 21 maggio 1980, n. 34: Articolo 13 legge regionale di approvazione del bilancio di previsione per l'esercizio finanziario 1980. Programma di interventi per | 1 | oldest version available: 30 October 2026 |
| `lr-1980-45/` | L.R. 30 maggio 1980, n. 45: Variazioni al bilancio per l'anno 1980 nuove e maggiori autorizzazioni di spesa. | 1 | oldest version available: 30 October 2026 |
| `lr-1980-55/` | L.R. 31 dicembre 1980, n. 55: Assestamento del bilancio per l'anno finanziario 1980. | 1 | oldest version available: 30 October 2026 |
| `lr-1981-1/` | L.R. 12 gennaio 1981, n. 1: Trasferimenti ad anni successivi, riduzioni e revoche di autorizzazioni di spesa stabilite per l'anno 1979 e anni precedenti. | 1 | oldest version available: 30 October 2026 |
| `lr-1981-2/` | L.R. 2 febbraio 1981, n. 2: Autorizzazione all'esercizio provvisorio del bilancio per l'anno 1981. | 1 | oldest version available: 30 October 2026 |
| `lr-1981-3/` | L.R. 18 febbraio 1981, n. 3: Approvazione del rendiconto della Regione per l'esercizio finanziario 1979. | 1 | oldest version available: 30 October 2026 |
| `lr-1981-8/` | L.R. 24 marzo 1981, n. 8: Rimessione in termini per gli interventi edificatori nelle zone di completamento previste dagli strumenti urbanistici generali comunal | 1 | oldest version available: 30 October 2026 |
| `lr-1981-11/` | L.R. 11 maggio 1981, n. 11: Approvazione del bilancio di previsione per l'anno 1981. | 1 | oldest version available: 30 October 2026 |
| `lr-1981-28/` | L.R. 3 settembre 1981, n. 28: Istituzione di cantieri di lavoro e concessione dei contributi regionali a favore degli enti gestori. | 1 | oldest version available: 30 October 2026 |
| `lr-1981-36/` | L.R. 24 novembre 1981, n. 36: Approvazione del rendiconto generale dell'esercizio 1980. | 1 | oldest version available: 30 October 2026 |
| `lr-1981-37/` | L.R. 14 dicembre 1981, n. 37: Assestamento del bilancio per l'anno 1981. | 1 | oldest version available: 30 October 2026 |
| `lr-1981-41/` | L.R. 18 dicembre 1981, n. 41: Riordino del servizio veterinario e norme per l'esercizio delle funzioni amministrative in materia veterinaria nelle unità sanitar | 1 | oldest version available: 30 October 2026 |
| `lr-1981-43/` | L.R. 30 dicembre 1981, n. 43: Proroga dei piani di ricostruzione dei comuni terremotati. | 1 | oldest version available: 30 October 2026 |
| `lr-1982-1/` | L.R. 11 gennaio 1982, n. 1: Autorizzazione all'esercizio provvisorio del bilancio per l'anno 1982. | 1 | oldest version available: 30 October 2026 |
| `lr-1982-7/` | L.R. 3 marzo 1982, n. 7: Norme per l'esercizio delle funzioni in materia di igiene e sanità pubblica e vigilanza sulle farmacie ai sensi dell'art. 32 della L. 2 | 1 | oldest version available: 30 October 2026 |
| `lr-1982-11/` | L.R. 3 aprile 1982, n. 11: Approvazione del bilancio di previsione per l'anno 1982. | 1 | oldest version available: 30 October 2026 |
| `lr-1982-14/` | L.R. 3 maggio 1982, n. 14: Costituzione del consorzio interregionale tra le Regioni Lazio, Marche, Toscana e Umbria per la formazione dei divulgatori agricoli i | 1 | oldest version available: 30 October 2026 |
| `lr-1982-17/` | L.R. 11 maggio 1982, n. 17: Efficacia dei programmi pluriennali di attuazione (P.P.A.) ai fini dei vincoli di inedificabilità ed espropriabilità previsti nei pr | 1 | oldest version available: 30 October 2026 |
| `lr-1982-29/` | L.R. 5 agosto 1982, n. 29: Contributi una tantum alle imprese per l'adeguamento degli scarichi dei rifiuti liquidi e/o lo smaltimento dei fanghi di risulta in a | 1 | oldest version available: 30 October 2026 |
| `lr-1982-32/` | L.R. 23 agosto 1982, n. 32: Disciplina della ricerca, coltivazione ed utilizzazione delle acque minerali e termali nella Regione Marche. | 1 | oldest version available: 30 October 2026 |
| `lr-1982-48/` | L.R. 23 dicembre 1982, n. 48: Assestamento di bilancio 1982. | 1 | oldest version available: 30 October 2026 |
| `lr-1983-1/` | L.R. 3 gennaio 1983, n. 1: Autorizzazione all'esercizio provvisorio del bilancio per l'anno 1983. | 1 | oldest version available: 30 October 2026 |
| `lr-1983-7/` | L.R. 22 febbraio 1983, n. 7: Approvazione del rendiconto generale dell'esercizio 1981. | 1 | oldest version available: 30 October 2026 |
| `lr-1983-10/` | L.R. 18 maggio 1983, n. 10: Approvazione del bilancio di previsione per l'anno 1983. | 1 | oldest version available: 30 October 2026 |
| `lr-1983-11/` | L.R. 24 maggio 1983, n. 11: Garanzie fidejussorie regionali sui mutui contratti dagli enti locali per l'esecuzione di opere pubbliche. | 1 | oldest version available: 30 October 2026 |
| `lr-1983-23/` | L.R. 13 agosto 1983, n. 23: Intervento regionale per il potenziamento dell'organizzazione del soccorso alpino e per la conoscenza e difesa della montagna marchi | 1 | oldest version available: 30 October 2026 |
| `lr-1983-32/` | L.R. 20 ottobre 1983, n. 32: Provvedimenti tributari. | 1 | oldest version available: 30 October 2026 |
| `lr-1983-34/` | L.R. 26 ottobre 1983, n. 34: Norme per disciplinare la produzione di sementi di piante allogame. | 1 | oldest version available: 30 October 2026 |
| `lr-1983-40/` | L.R. 24 dicembre 1983, n. 40: Assestamento del bilancio 1983. | 1 | oldest version available: 30 October 2026 |
| `lr-1983-41/` | L.R. 26 dicembre 1983, n. 41: Norme di attuazione della L. 2 maggio 1983 n. 156 concernente: "Provvidenze in favore della popolazione di Ancona colpita dal movi | 1 | oldest version available: 30 October 2026 |
| `lr-1984-1/` | L.R. 4 gennaio 1984, n. 1: Autorizzazione all'esercizio provvisorio del bilancio 1984. | 1 | oldest version available: 30 October 2026 |
| `lr-1984-10/` | L.R. 26 aprile 1984, n. 10: Norme di attuazione del D.P.R. 20 dicembre 1979, n. 761 in materia di procedure concorsuali e di disciplina del rapporto di impiego | 1 | oldest version available: 30 October 2026 |
| `lr-1984-11/` | L.R. 27 aprile 1984, n. 11: Approvazione del rendiconto generale dell'amministrazione per l'anno 1982. | 1 | oldest version available: 30 October 2026 |
| `lr-1984-13/` | L.R. 16 giugno 1984, n. 13: Approvazione del bilancio di previsione per l'anno 1984. | 1 | oldest version available: 30 October 2026 |
| `lr-1984-17/` | L.R. 9 luglio 1984, n. 17: Modificazione ed integrazione della L.R. 28 ottobre 1977 n. 42. | 1 | oldest version available: 30 October 2026 |
| `lr-1984-19/` | L.R. 1 agosto 1984, n. 19: Approvazione dei bilanci di previsione per l'anno 1984 degli enti turistici. | 1 | oldest version available: 30 October 2026 |
| `lr-1984-20/` | L.R. 2 agosto 1984, n. 20: Disciplina delle indennità spettanti agli amministratori degli enti pubblici operanti in materie di competenza regionale e ai compone | 1 | oldest version available: 30 October 2026 |
| `lr-1984-25/` | L.R. 22 agosto 1984, n. 25: Modifiche e integrazioni alla L.R. 5 agosto 1982, n. 29 recante contributi "una tantum" alle imprese per l'adeguamento degli scarich | 1 | oldest version available: 30 October 2026 |
| `lr-1984-34/` | L.R. 3 novembre 1984, n. 34: Trattamento di previdenza dei dipendenti regionali. | 1 | oldest version available: 30 October 2026 |
| `lr-1984-41/` | L.R. 21 dicembre 1984, n. 41: Assestamento del bilancio per l'anno 1984. | 1 | oldest version available: 30 October 2026 |
| `lr-1985-1/` | L.R. 12 gennaio 1985, n. 1: Autorizzazione all'esercizio provvisorio del bilancio 1986. | 1 | oldest version available: 30 October 2026 |
| `lr-1985-2/` | L.R. 16 gennaio 1985, n. 2: Esercizio delle funzioni in materia di consultori familiari. | 1 | oldest version available: 30 October 2026 |
| `lr-1985-11/` | L.R. 8 aprile 1985, n. 11: Adesione della Regione Marche all'Istituto Nazionale di Urbanistica. | 1 | oldest version available: 30 October 2026 |
| `lr-1985-24/` | L.R. 30 aprile 1985, n. 24: Interventi per favorire il funzionamento degli organi e delle strutture delle associazioni che perseguono la tutela e la promozione | 1 | oldest version available: 30 October 2026 |
| `lr-1985-26/` | L.R. 2 maggio 1985, n. 26: Approvazione del bilancio di previsione per l'anno 1985. | 1 | oldest version available: 30 October 2026 |
| `lr-1985-28/` | L.R. 3 maggio 1985, n. 28: Modifiche ed integrazioni alla L.R. 2 agosto 1984, n. 20, concernente: "Disciplina delle indennità spettanti agli amministratori degl | 1 | oldest version available: 30 October 2026 |
| `lr-1985-29/` | L.R. 3 maggio 1985, n. 29: Norme in materia di opere idrauliche di competenza regionale. | 1 | oldest version available: 30 October 2026 |
| `lr-1985-30/` | L.R. 3 maggio 1985, n. 30: Attuazione della Legge 5 marzo 1982, n. 62. Smaltimento dei liquami e dei fanghi residuati dalle lavorazioni industriali o dai proces | 1 | oldest version available: 30 October 2026 |
| `lr-1986-1/` | L.R. 2 gennaio 1986, n. 1: Approvazione del rendiconto generale dell'Amministrazione per l'anno 1983. | 1 | oldest version available: 30 October 2026 |
| `lr-1986-2/` | L.R. 21 gennaio 1986, n. 2: Modifiche ed integrazioni della L.R. 3 marzo 1982, n. 7 "Norme per l'esercizio delle funzioni in materia di igiene e sanità pubblica | 1 | oldest version available: 30 October 2026 |
| `lr-1986-4/` | L.R. 23 gennaio 1986, n. 4: Autorizzazione all'esercizio provvisorio del bilancio 1986. | 1 | oldest version available: 30 October 2026 |
| `lr-1986-5/` | L.R. 30 gennaio 1986, n. 5: Assestamento del bilancio per l'anno 1985. | 1 | oldest version available: 30 October 2026 |
| `lr-1986-6/` | L.R. 24 marzo 1986, n. 6: Partecipazione della Regione Marche alla costituenda società Aerdorica - Sogesam S.p.A. | 1 | oldest version available: 30 October 2026 |
| `lr-1986-9/` | L.R. 18 aprile 1986, n. 9: Commissione regionale per le pari opportunità tra uomo e donna. | 1 | oldest version available: 30 October 2026 |
| `lr-1986-10/` | L.R. 23 maggio 1986, n. 10: Approvazione del bilancio di previsione per l'anno 1986. | 1 | oldest version available: 30 October 2026 |
| `lr-1986-14/` | L.R. 18 giugno 1986, n. 14: Norme regionali in materia di controllo e snellimento di procedure urbanistico-edilizie ed in materia di sanzioni e sanatoria delle | 1 | oldest version available: 30 October 2026 |
| `lr-1986-15/` | L.R. 23 giugno 1986, n. 15: Partecipazione della Regione Marche alla costituenda società consortile denominata Centro merci intermodale delle Marche (CE.M.I.M.) | 1 | oldest version available: 30 October 2026 |
| `lr-1986-17/` | L.R. 26 giugno 1986, n. 17: Approvazione del rendiconto generale dell'Amministrazione per l'anno 1984. | 1 | oldest version available: 30 October 2026 |
| `lr-1986-25/` | L.R. 1 settembre 1986, n. 25: Delega al Comune di Urbino delle funzioni in materia di opere ed interventi previsti dalla L. 22 agosto 1985, n. 462. | 1 | oldest version available: 30 October 2026 |
| `lr-1986-26/` | L.R. 20 dicembre 1986, n. 26: Compensi ai componenti le commissioni e sottocommissioni esaminatrici di concorsi e delle selezioni per l'assunzione del personale | 1 | oldest version available: 30 October 2026 |
| `lr-1986-28/` | L.R. 23 dicembre 1986, n. 28: Finanziamento di interventi regionali in agricoltura di cui alle disponibilità del bilancio di previsione per l'anno 1986. | 1 | oldest version available: 30 October 2026 |
| `lr-1986-29/` | L.R. 30 dicembre 1986, n. 29: Assestamento del bilancio per l'anno 1986. | 1 | oldest version available: 30 October 2026 |
| `lr-1987-1/` | L.R. 3 gennaio 1987, n. 1: Autorizzazione all'esercizio provvisorio del bilancio per l'anno 1987. | 1 | oldest version available: 30 October 2026 |
| `lr-1987-9/` | L.R. 19 gennaio 1987, n. 9: Adesione della Regione Marche al centro di ecologia e climatologia con sede a Macerata. | 1 | oldest version available: 30 October 2026 |
| `lr-1987-12/` | L.R. 21 febbraio 1987, n. 12: Autorizzazione all'esercizio provvisorio del bilancio per l'anno 1987. | 1 | oldest version available: 30 October 2026 |
| `lr-1987-18/` | L.R. 27 marzo 1987, n. 18: Modifiche della L.R. 3 novembre 1984, n. 33 riguardante "Norme per le costruzioni in zone sismiche". | 1 | oldest version available: 30 October 2026 |
| `lr-1987-19/` | L.R. 21 aprile 1987, n. 19: Norme per il libero accesso all'informazione ambientale. | 1 | oldest version available: 30 October 2026 |
| `lr-1987-21/` | L.R. 23 aprile 1987, n. 21: Istituzione del parco regionale del Conero. | 1 | oldest version available: 30 October 2026 |
| `lr-1987-23/` | L.R. 16 maggio 1987, n. 23: Approvazione del rendiconto generale dell'amministrazione per l'anno 1985. | 1 | oldest version available: 30 October 2026 |
| `lr-1987-24/` | L.R. 18 maggio 1987, n. 24: Approvazione del bilancio di previsione per l'anno 1987 e adozione del bilancio pluriennale per il triennio 1987-1989. | 1 | oldest version available: 30 October 2026 |
| `lr-1987-32/` | L.R. 20 giugno 1987, n. 32: Norme di attuazione nel territorio regionale della Legge 1 dicembre 1986, n. 879, avente ad oggetto: "Disposizioni per il completame | 1 | oldest version available: 30 October 2026 |
| `lr-1987-37/` | L.R. 7 dicembre 1987, n. 37: Interventi in agricoltura con le disponibilità del bilancio di previsione per l'anno 1987 e modificazioni della L.R. 29 dicembre 19 | 1 | oldest version available: 30 October 2026 |
| `lr-1987-41/` | L.R. 28 dicembre 1987, n. 41: Assestamento del bilancio per l'anno 1987. | 1 | oldest version available: 30 October 2026 |
| `lr-1987-42/` | L.R. 31 dicembre 1987, n. 42: Approvazione delle variazioni dei bilanci per l'anno 1986 degli enti turistici marchigiani. | 1 | oldest version available: 30 October 2026 |
| `lr-1987-45/` | L.R. 31 dicembre 1987, n. 45: Approvazione del bilancio di previsione per l'anno 1987 degli enti turistici marchigiani. | 1 | oldest version available: 30 October 2026 |
| `lr-1988-1/` | L.R. 7 gennaio 1988, n. 1: Autorizzizione all'esercizio provvisorio per l'anno 1988. | 1 | oldest version available: 30 October 2026 |
| `lr-1988-3/` | L.R. 21 gennaio 1988, n. 3: Modificazione ed integrazione della L.R. 26 dicembre 1983, n. 41 recante "Norme di attuazione della L. 2 maggio 1983, n. 156, concer | 1 | oldest version available: 30 October 2026 |
| `lr-1988-5/` | L.R. 8 marzo 1988, n. 5: Autorizzazione all'esercizio provvisorio del bilancio per l'anno 1988. | 1 | oldest version available: 30 October 2026 |
| `lr-1988-7/` | L.R. 5 aprile 1988, n. 7: Modificazioni ed integrazioni della L.R. 2 agosto 1984, n. 20 recante "Disciplina delle indennità spettanti agli amministratori degli | 1 | oldest version available: 30 October 2026 |
| `lr-1988-17/` | L.R. 4 giugno 1988, n. 17: Bilancio di previsione per l'anno 1988 e adozione del bilancio pluriennale per il triennio 1988-1990. | 1 | oldest version available: 30 October 2026 |
| `lr-1988-19/` | L.R. 6 giugno 1988, n. 19: Norme in materia di opere concernenti linee ed impianti elettrici fino a 150.000 Volt. | 1 | oldest version available: 30 October 2026 |
| `lr-1988-21/` | L.R. 8 giugno 1988, n. 21: Approvazione del rendiconto generale dell'amministrazione regionale per l'anno 1986. | 1 | oldest version available: 30 October 2026 |
| `lr-1988-25/` | L.R. 15 luglio 1988, n. 25: Divieto dell'uso dei fitofarmaci nei centri abitati. | 1 | oldest version available: 30 October 2026 |
| `lr-1988-32/` | L.R. 29 luglio 1988, n. 32: Modifiche ed integrazioni alla L.R. 23 giugno 1986, n. 15 riguardante: "Partecipazione della Regione alla costituenda società consor | 1 | oldest version available: 30 October 2026 |
| `lr-1988-34/` | L.R. 10 agosto 1988, n. 34: Finanziamento delle attività dei gruppi consiliari. | 1 | oldest version available: 30 October 2026 |
| `lr-1988-35/` | L.R. 22 agosto 1988, n. 35: Riordino dell'ente di sviluppo agricolo nelle Marche (ESAM). | 1 | oldest version available: 30 October 2026 |
| `lr-1988-41/` | L.R. 3 novembre 1988, n. 41: Interventi per la valorizzazione e il recupero ambientale. | 1 | oldest version available: 30 October 2026 |
| `lr-1988-45/` | L.R. 28 dicembre 1988, n. 45: Assestamento del bilancio per l'anno 1988. | 1 | oldest version available: 30 October 2026 |
| `lr-1989-2/` | L.R. 9 gennaio 1989, n. 2: Autorizzazione all'esercizio provvisorio per l'anno 1989. | 1 | oldest version available: 30 October 2026 |
| `lr-1989-3/` | L.R. 4 febbraio 1989, n. 3: Autorizzazione all'esercizio provvisorio per l'anno 1989 II provvedimento. | 1 | oldest version available: 30 October 2026 |
| `lr-1989-9/` | L.R. 3 maggio 1989, n. 9: Interventi per il miglioramento della funzionalità dei porti di Fano, Senigallia, Civitanova Marche e San Benedetto del Tronto della p | 1 | oldest version available: 30 October 2026 |
| `lr-1989-14/` | L.R. 24 luglio 1989, n. 14: Approvazione del rendiconto generale dell'amministrazione per l'anno 1987. | 1 | oldest version available: 30 October 2026 |
| `lr-1989-15/` | L.R. 25 luglio 1989, n. 15: Soppressione del Consorzio di Bonifica Montana del fiume Corno e Medio Nera (Norcia). | 1 | oldest version available: 30 October 2026 |
| `lr-1989-16/` | L.R. 26 luglio 1989, n. 16: Acquisto e sistemazione del complesso immobiliare sito in Macerata località Piediripa, da destinare a sede della Scuola di Formazion | 1 | oldest version available: 30 October 2026 |
| `lr-1989-25/` | L.R. 31 ottobre 1989, n. 25: Istituzione del fondo regionale per l'ambiente. | 1 | oldest version available: 30 October 2026 |
| `lr-1989-28/` | L.R. 23 dicembre 1989, n. 28: Assestamento del bilancio per l'anno 1989. | 1 | oldest version available: 30 October 2026 |
| `lr-1989-29/` | L.R. 27 dicembre 1989, n. 29: Modifiche alla L.R. 26 luglio 1989, n. 16 concernente l'acquisto e la sistemazione del complesso immobiliare sito in Macerata, loc | 1 | oldest version available: 30 October 2026 |
| `lr-1989-33/` | L.R. 30 dicembre 1989, n. 33: Organizzazione e disciplina delle strutture Nefro-Dialitiche nella Regione Marche. | 1 | oldest version available: 30 October 2026 |
| `lr-1990-1/` | L.R. 13 gennaio 1990, n. 1: Autorizzazione all'esercizio provvisorio per l'anno 1990. | 1 | oldest version available: 30 October 2026 |
| `lr-1990-7/` | L.R. 3 febbraio 1990, n. 7: Autorizzazione esercizio provvisorio per l'anno 1990, 2° provvedimento. | 1 | oldest version available: 30 October 2026 |
| `lr-1990-13/` | L.R. 8 marzo 1990, n. 13: Norme edilizie per il territorio agricolo. | 1 | oldest version available: 30 October 2026 |
| `lr-1990-15/` | L.R. 12 marzo 1990, n. 15: Norme in materia di circolazione dei trasporti e dei veicoli eccezionali per l'esercizio delle funzioni attribuite alla Regione dall' | 1 | oldest version available: 30 October 2026 |
| `lr-1990-16/` | L.R. 26 marzo 1990, n. 16: Ordinamento del sistema regionale di formazione professionale. | 1 | oldest version available: 30 October 2026 |
| `lr-1990-17/` | L.R. 27 marzo 1990, n. 17: Ulteriori modificazioni della L.R. 26 dicembre 1983, n. 41 recante "Norme di attuazione della Legge 2 maggio 1983, n. 156 concernente | 1 | oldest version available: 30 October 2026 |
| `lr-1990-19/` | L.R. 29 marzo 1990, n. 19: Istituzione e disciplina dei servizi autonomi di Allergologia Respiratoria (AR). | 1 | oldest version available: 30 October 2026 |
| `lr-1990-20/` | L.R. 29 marzo 1990, n. 20: Integrazione alla Legge Regionale "Istituzione e disciplina dei servizi autonomi di Allergologia Respiratoria "approvata dal Consigli | 1 | oldest version available: 30 October 2026 |
| `lr-1990-21/` | L.R. 30 marzo 1990, n. 21: Realizzazione di un complesso immobiliare da destinare agli uffici della Regione. | 1 | oldest version available: 30 October 2026 |
| `lr-1990-24/` | L.R. 21 aprile 1990, n. 24: Modificazione della L.R. 6 giugno 1988, n. 19 relativa a norme in materia di opere concernenti linee ed impianti elettrici fino a 15 | 1 | oldest version available: 30 October 2026 |
| `lr-1990-25/` | L.R. 23 aprile 1990, n. 25: Contributo annuale alla Associazione Italiana per il World Wildlife Fund, delegazione delle Marche per la gestione del Centro Recupe | 1 | oldest version available: 30 October 2026 |
| `lr-1990-26/` | L.R. 24 aprile 1990, n. 26: Approvazione del conto consuntivo dell'Esercizio Finanziario 1988. | 1 | oldest version available: 30 October 2026 |
| `lr-1990-27/` | L.R. 26 aprile 1990, n. 27: Approvazione del Bilancio di Previsione per l'anno 1990 e adozione del Bilancio Pluriennale per il triennio 1990/1992. | 1 | oldest version available: 30 October 2026 |
| `lr-1990-39/` | L.R. 26 aprile 1990, n. 39: Acquisto di un fabbricato in Ancona da destinare a sede di rappresentanza del Consiglio Regionale. | 1 | oldest version available: 30 October 2026 |
| `lr-1990-45/` | L.R. 27 aprile 1990, n. 45: Nuove modificazioni alla L.R. 26 dicembre 1983, n. 41 recante "Norme di attuazione della legge 2 maggio 1983, n. 156 concernente "Pr | 1 | oldest version available: 30 October 2026 |
| `lr-1990-46/` | L.R. 27 aprile 1990, n. 46: Continuità delle prestazioni assistenziali a favore dei soggetti dimessi dagli ex ospedali neuropsichiatrici ai sensi della legge 13 | 1 | oldest version available: 30 October 2026 |
| `lr-1990-52/` | L.R. 27 aprile 1990, n. 52: Abbattimento delle barriere architettoniche in edifici pubblici o privati aperti al pubblico e modifica alla L.R. 3 marzo 1990, n. 9 | 1 | oldest version available: 30 October 2026 |
| `lr-1990-55/` | L.R. 30 novembre 1990, n. 55: Determinazione dell'aliquota della tassa automobilistica regionale. | 1 | oldest version available: 30 October 2026 |
| `lr-1990-56/` | L.R. 3 dicembre 1990, n. 56: Provvedimenti tributari. | 1 | oldest version available: 30 October 2026 |
| `lr-1990-58/` | L.R. 24 dicembre 1990, n. 58: Assestamento del bilancio per l'anno 1990. | 1 | oldest version available: 30 October 2026 |
| `lr-1991-2/` | L.R. 18 gennaio 1991, n. 2: Acquisto di un fabbricato da destinare a sede degli uffici del Consiglio Regionale. | 1 | oldest version available: 30 October 2026 |
| `lr-1991-3/` | L.R. 19 gennaio 1991, n. 3: Autorizzazione all'esercizio provvisorio per l'anno 1991. | 1 | oldest version available: 30 October 2026 |
| `lr-1991-6/` | L.R. 16 marzo 1991, n. 6: Autorizzazione all'esercizio provvisorio per l'anno 1991. | 1 | oldest version available: 30 October 2026 |
| `lr-1991-12/` | L.R. 29 maggio 1991, n. 12: Approvazione del rendiconto generale dell'Amministrazione per l'Esercizio Finanziario 1989. | 1 | oldest version available: 30 October 2026 |
| `lr-1991-13/` | L.R. 30 maggio 1991, n. 13: Approvazione Bilancio di Previsione per l'anno 1991 e adozione del Bilancio Pluriennale per il triennio 1991/1993. | 1 | oldest version available: 30 October 2026 |
| `lr-1991-16/` | L.R. 29 giugno 1991, n. 16: Misure e provvedimenti a favore della Zootecnia. | 1 | oldest version available: 30 October 2026 |
| `lr-1991-19/` | L.R. 17 luglio 1991, n. 19: Modifica L.R. 5 agosto 1982, n. 29 concernente contributi alle imprese per l'adeguamento degli scarichi e lo smaltimento dei fanghi | 1 | oldest version available: 30 October 2026 |
| `lr-1991-21/` | L.R. 19 luglio 1991, n. 21: Modificazioni della L.R. 20 giugno 1987, n. 32 "Norme di attuazione della Legge 1 dicembre 1986, n. 879" e della L.R. 26 dicembre 19 | 1 | oldest version available: 30 October 2026 |
| `lr-1991-23/` | L.R. 29 luglio 1991, n. 23: Interventi per la promozione delle università della terza età nelle Marche. | 1 | oldest version available: 30 October 2026 |
| `lr-1991-29/` | L.R. 12 agosto 1991, n. 29: Erogazione di contributi ai comitati provinciali dell'associazione nazionale famiglie dei caduti e dispersi in guerra e alle federaz | 1 | oldest version available: 30 October 2026 |
| `lr-1991-34/` | L.R. 19 novembre 1991, n. 34: Accelerazione dell'attuazione del Piano Paesaggistico Ambientale Regionale (PPAR) e coordinamento di Leggi Regionali riguardanti i | 1 | oldest version available: 30 October 2026 |
| `lr-1991-37/` | L.R. 19 dicembre 1991, n. 37: Modifiche alla L.R. 18 gennaio 1991, n. 2 concernente l'acquisto di un fabbricato da destinare a sede degli uffici del Consiglio R | 1 | oldest version available: 30 October 2026 |
| `lr-1991-39/` | L.R. 28 dicembre 1991, n. 39: Assestamento del bilancio di previsione per l'anno 1991. | 1 | oldest version available: 30 October 2026 |
| `lr-1992-1/` | L.R. 2 gennaio 1992, n. 1: Istituzione degli albi regionali degli enti gestori di strutture per la riabilitazione e il reinserimento sociale dei tossicodipenden | 1 | oldest version available: 30 October 2026 |
| `lr-1992-2/` | L.R. 14 gennaio 1992, n. 2: Norme concernenti il diritto di accesso ai documenti amministrativi e sulla trasparenza dell'attività amministrativa regionale. | 1 | oldest version available: 30 October 2026 |
| `lr-1992-3/` | L.R. 14 gennaio 1992, n. 3: Approvazione dei Bilanci di previsione per l'anno 1990 degli Enti Turistici Marchigiani. | 1 | oldest version available: 30 October 2026 |
| `lr-1992-12/` | L.R. 24 gennaio 1992, n. 12: Disciplina del fondo per le opere di urbanizzazione. | 1 | oldest version available: 30 October 2026 |
| `lr-1992-14/` | L.R. 19 febbraio 1992, n. 14: Autorizzazione all'esercizio provvisorio del Bilancio per l'anno 1992. | 1 | oldest version available: 30 October 2026 |
| `lr-1992-17/` | L.R. 27 aprile 1992, n. 17: Formazione e sviluppo della proprietà coltivatrice ulteriore rifinanziamento della L.R. 29 dicembre 1984, n. 42. | 1 | oldest version available: 30 October 2026 |
| `lr-1992-18/` | L.R. 28 aprile 1992, n. 18: Contributi a favore dei pescatori costretti al fermo dell'attività di pesca in conseguenza dei danni provocati dalle mucillagini e d | 1 | oldest version available: 30 October 2026 |
| `lr-1992-21/` | L.R. 2 giugno 1992, n. 21: Nuove norme per la promozione di attività di educazione permanente. | 1 | oldest version available: 30 October 2026 |
| `lr-1992-24/` | L.R. 12 giugno 1992, n. 24: Approvazione del rendiconto generale dell'Amministrazione per l'esercizio finanziario 1990. | 1 | oldest version available: 30 October 2026 |
| `lr-1992-25/` | L.R. 16 giugno 1992, n. 25: Rifinanziamento della L.R. 1 agosto 1989, n. 20 e disposizioni urgenti in favore delle imprese colpite dalle avversità atmosferiche | 1 | oldest version available: 30 October 2026 |
| `lr-1992-28/` | L.R. 17 luglio 1992, n. 28: Modifiche all'articolo 7 della L.R. 23 agosto 1982, n. 32 concernente la disciplina della ricerca, coltivazione e utilizzazione dell | 1 | oldest version available: 30 October 2026 |
| `lr-1992-29/` | L.R. 19 luglio 1992, n. 29: Disciplina del servizio volontario di Vigilanza Ecologica. | 1 | oldest version available: 30 October 2026 |
| `lr-1992-33/` | L.R. 30 luglio 1992, n. 33: Approvazione del Bilancio di Previsione per l'anno 1992 e adozione del Bilancio Pluriennale per il triennio 1992/1994. | 1 | oldest version available: 30 October 2026 |
| `lr-1992-34/` | L.R. 5 agosto 1992, n. 34: Norme in materia urbanistica, paesaggistica e di assetto del territorio. | 1 | oldest version available: 30 October 2026 |
| `lr-1992-35/` | L.R. 19 agosto 1992, n. 35: Modifica alla legge regionale approvata dal Consiglio regionale nella seduta del 23 giugno 1992, n. 82 concernente: "Approvazione de | 1 | oldest version available: 30 October 2026 |
| `lr-1992-38/` | L.R. 2 settembre 1992, n. 38: Soppressione delle associazioni dei Comuni. | 1 | oldest version available: 30 October 2026 |
| `lr-1992-40/` | L.R. 3 settembre 1992, n. 40: Attuazione del programma operativo plurifondo per lo sviluppo delle zone rurali della Regione Marche (Regolamento CEE 2052/1988 - | 1 | oldest version available: 30 October 2026 |
| `lr-1992-42/` | L.R. 4 settembre 1992, n. 42: Norme in materia di assistenza scolastica del diritto allo studio. | 1 | oldest version available: 30 October 2026 |
| `lr-1992-46/` | L.R. 5 settembre 1992, n. 46: Norme sulle procedure della programmazione regionale e locale. | 1 | oldest version available: 30 October 2026 |
| `lr-1992-48/` | L.R. 19 ottobre 1992, n. 48: Interventi della Regione a favore del patrimonio vegetale della Riviera delle Palme. | 1 | oldest version available: 30 October 2026 |
| `lr-1992-50/` | L.R. 28 dicembre 1992, n. 50: Assestamento del bilancio di previsione per l'anno 1992. | 1 | oldest version available: 30 October 2026 |
| `lr-1992-52/` | L.R. 29 dicembre 1992, n. 52: Approvazione del rendiconto generale dell'Amministrazione per l'anno 1991. | 1 | oldest version available: 30 October 2026 |
| `lr-1993-3/` | L.R. 15 gennaio 1993, n. 3: Trattamento di quiescenza e di fine servizio del personale delle aziende di promozione turistica. | 1 | oldest version available: 30 October 2026 |
| `lr-1993-4/` | L.R. 22 gennaio 1993, n. 4: Autorizzazione all'esercizio provvisorio del Bilancio per l'anno 1993. | 1 | oldest version available: 30 October 2026 |
| `lr-1993-11/` | L.R. 15 febbraio 1993, n. 11: Modifica alla L.R. 30 dicembre 1989, n. 33 relativa alla organizzazione e disciplina delle strutture nefrodialitiche nella Regione | 1 | oldest version available: 30 October 2026 |
| `lr-1993-12/` | L.R. 8 marzo 1993, n. 12: Autorizzazione all'esercizio provvisorio del bilancio per l'anno 1993. | 1 | oldest version available: 30 October 2026 |
| `lr-1993-14/` | L.R. 22 aprile 1993, n. 14: Modifica dell'articolo 66 del Piano Paesistico Territoriale del Comprensorio del Conero. | 1 | oldest version available: 30 October 2026 |
| `lr-1993-15/` | L.R. 11 maggio 1993, n. 15: Bilancio di previsione per l'anno 1993 e adozione del bilancio pluriennale per il triennio 1993/1995. | 1 | oldest version available: 30 October 2026 |
| `lr-1993-16/` | L.R. 28 giugno 1993, n. 16: Istituzione del servizio di Oncoematologia Pediatrica all'ospedale dei Bambini Salesi di Ancona. | 1 | oldest version available: 30 October 2026 |
| `lr-1993-19/` | L.R. 29 giugno 1993, n. 19: Modifiche alla L.R. 11 maggio 1993, n. 15 "Bilancio di Previsione per l'anno 1993 e adozione del Bilancio Pluriennale per il trienni | 1 | oldest version available: 30 October 2026 |
| `lr-1993-23/` | L.R. 9 settembre 1993, n. 23: Modifiche all'articolo 10 della L.R. 11.5.1993 n. 15 "Bilancio di previsione per l'anno 1993 e adozione del Bilancio pluriennale p | 1 | oldest version available: 30 October 2026 |
| `lr-1993-32/` | L.R. 17 dicembre 1993, n. 32: Attuazione e finanziamento dei progetti "Agriturismo nelle zone rurali" e "Debrex" relativi al programma "Ouverture". | 1 | oldest version available: 30 October 2026 |
| `lr-1993-36/` | L.R. 27 dicembre 1993, n. 36: Approvazione del Rendiconto Generale dell'Amministrazione per l'anno 1992. | 1 | oldest version available: 30 October 2026 |
| `lr-1994-2/` | L.R. 3 gennaio 1994, n. 2: Assestamento del Bilancio 1993. | 1 | oldest version available: 30 October 2026 |
| `lr-1994-4/` | L.R. 24 gennaio 1994, n. 4: Autorizzazione all'esercizio provvisorio del Bilancio per l'anno 1994. | 1 | oldest version available: 30 October 2026 |
| `lr-1994-6/` | L.R. 1 febbraio 1994, n. 6: Promozione, tramite la Società Finanziaria Regionale Marche S.p.A, della costituzione di una Società per Azioni denominata interport | 1 | oldest version available: 30 October 2026 |
| `lr-1994-7/` | L.R. 14 marzo 1994, n. 7: Rifinanziamento dell'articolo 50 della L.R. 5 novembre 1988, n. 43 norme per il riordino delle funzioni di assistenza sociale di compe | 1 | oldest version available: 30 October 2026 |
| `lr-1994-8/` | L.R. 14 marzo 1994, n. 8: Modifiche all'articolo 1 della Legge Regionale approvata dal Consiglio Regionale nella seduta dell'8 febbraio 1994, n. 170 concernente | 1 | oldest version available: 30 October 2026 |
| `lr-1994-15/` | L.R. 28 aprile 1994, n. 15: Norme per l'istituzione e gestione delle aree protette naturali. | 1 | oldest version available: 30 October 2026 |
| `lr-1994-21/` | L.R. 22 giugno 1994, n. 21: Approvazione del Bilancio di Previsione per l'anno 1994 ed adozione del Bilancio Pluriennale per il triennio 1994/1996. | 1 | oldest version available: 30 October 2026 |
| `lr-1994-23/` | L.R. 4 luglio 1994, n. 23: Modifiche alla L.R. 2 agosto 1984, n. 20 "Disciplina delle indennità spettanti agli amministratori degli Enti Pubblici operanti in ma | 1 | oldest version available: 30 October 2026 |
| `lr-1994-25/` | L.R. 25 luglio 1994, n. 25: Modifica alla L.R. 3 settembre 1992, n. 40 recante "Attuazione del Programma Operativo Plurifondo per lo sviluppo delle zone rurali | 1 | oldest version available: 30 October 2026 |
| `lr-1994-28/` | L.R. 11 agosto 1994, n. 28: Norme concernenti le caratteristiche, la fornitura e l'uso delle uniformi per il personale in servizio presso la Regione. | 1 | oldest version available: 30 October 2026 |
| `lr-1994-29/` | L.R. 11 agosto 1994, n. 29: Partecipazione all'attività della conferenza dei presidenti dell'assemblea dei Consigli Regionali e delle Province autonome. | 1 | oldest version available: 30 October 2026 |
| `lr-1994-32/` | L.R. 12 agosto 1994, n. 32: Interventi regionali per la promozione e lo sviluppo delle imprese cooperative integrate con soci handicappati. | 1 | oldest version available: 30 October 2026 |
| `lr-1994-33/` | L.R. 12 agosto 1994, n. 33: Medicina dello sport e tutela sanitaria delle attività sportive. | 1 | oldest version available: 30 October 2026 |
| `lr-1994-36/` | L.R. 29 agosto 1994, n. 36: Concessione al Comune di Ancona di un finanziamento straordinario per il completamento degli interventi necessitati dai movimenti fr | 1 | oldest version available: 30 October 2026 |
| `lr-1994-39/` | L.R. 30 agosto 1994, n. 39: Modificazione alla L.R. 28 aprile 1992, n. 18 recante: "Contributi a favore dei pescatori costretti al fermo dell'attività di pesca | 1 | oldest version available: 30 October 2026 |
| `lr-1994-44/` | L.R. 31 ottobre 1994, n. 44: Norme concernenti la democratizzazione e la semplificazione dell'attività Amministrativa Regionale. | 1 | oldest version available: 30 October 2026 |
| `lr-1994-47/` | L.R. 21 dicembre 1994, n. 47: Ulteriori modificazioni della L.R. 26 dicembre 1983, n. 41 recante norme di attuazione della Legge 156/1983 concernente provvidenz | 1 | oldest version available: 30 October 2026 |
| `lr-1994-48/` | L.R. 21 dicembre 1994, n. 48: Integrazione della L.R. 31 ottobre 1994, n. 44 contenente "Norme concernenti la democratizzazione e la semplificazione dell'attivi | 1 | oldest version available: 30 October 2026 |
| `lr-1995-1/` | L.R. 2 gennaio 1995, n. 1: Approvazione del rendiconto generale dell'amministrazione per l'anno 1993. | 1 | oldest version available: 30 October 2026 |
| `lr-1995-2/` | L.R. 2 gennaio 1995, n. 2: Assestamento del Bilancio 1994. | 1 | oldest version available: 30 October 2026 |
| `lr-1995-5/` | L.R. 3 gennaio 1995, n. 5: Provvedimenti per la valorizzazione dei prodotti vitivinicoli e agroalimentari tipici marchigiani. | 1 | oldest version available: 30 October 2026 |
| `lr-1995-7/` | L.R. 5 gennaio 1995, n. 7: Norme per la protezione della fauna selvatica e per la tutela dell'equilibrio ambientale e disciplina dell'attività venatoria. | 1 | oldest version available: 30 October 2026 |
| `lr-1995-8/` | L.R. 5 gennaio 1995, n. 8: Modifica della Legge Regionale approvata dal Consiglio Regionale nella seduta del 14 dicembre 1994 avente ad oggetto: "Norme per la p | 1 | oldest version available: 30 October 2026 |
| `lr-1995-9/` | L.R. 11 gennaio 1995, n. 9: Modifica ed integrazione alla L.R. 2 gennaio 1992, n. 1 recante "Istituzione degli albi regionali degli enti gestori di strutture pe | 1 | oldest version available: 30 October 2026 |
| `lr-1995-10/` | L.R. 16 gennaio 1995, n. 10: Norme sul riordinamento territoriale dei Comuni e delle Province nella Regione Marche. | 1 | oldest version available: 30 October 2026 |
| `lr-1995-11/` | L.R. 16 gennaio 1995, n. 11: Istituzione del servizio fitosanitario regionale. | 1 | oldest version available: 30 October 2026 |
| `lr-1995-14/` | L.R. 1 febbraio 1995, n. 14: Autorizzazione all'esercizio provvisorio del Bilancio per l'anno 1995. | 1 | oldest version available: 30 October 2026 |
| `lr-1995-15/` | L.R. 20 febbraio 1995, n. 15: Riscossione coattiva dei tributi regionali, delle sanzioni amministrative, delle addizionali e delle entrate patrimoniali ed assim | 1 | oldest version available: 30 October 2026 |
| `lr-1995-16/` | L.R. 20 febbraio 1995, n. 16: Riconoscimento agli effetti economici dell'anzianità di servizio prestato presso lo Stato, enti pubblici, enti locali e Regioni, n | 1 | oldest version available: 30 October 2026 |
| `lr-1995-17/` | L.R. 20 febbraio 1995, n. 17: Interventi e indennizzi per danni causati al patrimonio zootecnico da specie animali di notevole interesse scientifico e da cani r | 1 | oldest version available: 30 October 2026 |
| `lr-1995-18/` | L.R. 20 febbraio 1995, n. 18: Disciplina delle tasse sulle concessioni regionali. | 1 | oldest version available: 30 October 2026 |
| `lr-1995-20/` | L.R. 20 febbraio 1995, n. 20: Comitato d'intesa Regione - ANCI - UPI - UNCEM - AICCRE - Lega delle autonomie locali | 1 | oldest version available: 30 October 2026 |
| `lr-1995-21/` | L.R. 2 marzo 1995, n. 21: Modificazioni alla L.R. 1 febbraio 1995, n. 14 concernente: Autorizzazione all'esercizio provvisorio del bilancio di previsione per l' | 1 | oldest version available: 30 October 2026 |
| `lr-1995-23/` | L.R. 13 marzo 1995, n. 23: Disposizioni in materia di trattamento indennitario dei Consiglieri regionali. | 1 | oldest version available: 30 October 2026 |
| `lr-1995-26/` | L.R. 28 marzo 1995, n. 26: Approvazione del Bilancio di Previsione per l'anno 1995 ed approvazione del Bilancio Pluriennale per il triennio 1995/1997. | 1 | oldest version available: 30 October 2026 |
| `lr-1995-27/` | L.R. 28 marzo 1995, n. 27: Istituzione del servizio di Unità Spinale. | 1 | oldest version available: 30 October 2026 |
| `lr-1995-28/` | L.R. 28 marzo 1995, n. 28: Piano sangue e plasma: organizzazione e funzionamento dei servizi trasfusionali della Regione. | 1 | oldest version available: 30 October 2026 |
| `lr-1995-31/` | L.R. 7 aprile 1995, n. 31: Modifiche alla tabella degli ambiti territoriali delle Unità Sanitarie Locali allegata alla L.R. 28 giugno 1994, n. 22. | 1 | oldest version available: 30 October 2026 |
| `lr-1995-35/` | L.R. 12 aprile 1995, n. 35: Promozione della diffusione di veicoli elettrici dotati di accumulatori e relative infrastrutture nelle aree urbane. | 1 | oldest version available: 30 October 2026 |
| `lr-1995-36/` | L.R. 12 aprile 1995, n. 36: Realizzazione di residenze sanitarie assistenziali denominate "Casa alloggio per giovani disabili affetti da sclerosi multipla o dis | 1 | oldest version available: 30 October 2026 |
| `lr-1995-39/` | L.R. 12 aprile 1995, n. 39: Finanziamento all'Istituto Nazionale di Riposo e cura per Anziani (INRCA) per la realizzazione delle opere di cui all'articolo 2 del | 1 | oldest version available: 30 October 2026 |
| `lr-1995-40/` | L.R. 12 aprile 1995, n. 40: Primi interventi per la realizzazione della metropolitana leggera nell'area urbana di Ancona. | 1 | oldest version available: 30 October 2026 |
| `lr-1995-43/` | L.R. 12 aprile 1995, n. 43: Partecipazione della Regione Marche alla costituenda società regionale di garanzia per gli interventi nelle zone della Regione March | 1 | oldest version available: 30 October 2026 |
| `lr-1995-44/` | L.R. 12 aprile 1995, n. 44: Rifinanziamento della L.R. 28 aprile 1994, n. 15 "Norme per l'istituzione e la gestione delle aree protette naturali". | 1 | oldest version available: 30 October 2026 |
| `lr-1995-45/` | L.R. 12 aprile 1995, n. 45: Interventi a favore del porto di Ancona e delle infrastrutture del trasporto merci. | 1 | oldest version available: 30 October 2026 |
| `lr-1995-51/` | L.R. 13 aprile 1995, n. 51: Interventi regionali per la riorganizzazione del sistema cooperativo agroalimentare e dell'associazionismo del settore. | 1 | oldest version available: 30 October 2026 |
| `lr-1995-54/` | L.R. 8 agosto 1995, n. 54: Modifiche alla legge regionale 10 agosto 1988, n. 34: "Finanziamento della attività dei gruppi consiliari". | 1 | oldest version available: 30 October 2026 |
| `lr-1995-57/` | L.R. 28 agosto 1995, n. 57: Modifica dell'articolo 37 della L. R. 28 marzo 1995, n. 26. Tasso massimo di interesse per la contrazione dei mutui a carico della R | 1 | oldest version available: 30 October 2026 |
| `lr-1995-59/` | L.R. 5 settembre 1995, n. 59: Attuazione del Regolamento CEE n. 2081/93. Coordinamento dei fondi strutturali partecipazione finanziaria regionale. | 1 | oldest version available: 30 October 2026 |
| `lr-1995-61/` | L.R. 31 ottobre 1995, n. 61: Variazione al bilancio di previsione per l'anno 1995. | 1 | oldest version available: 30 October 2026 |
| `lr-1995-63/` | L.R. 20 novembre 1995, n. 63: Provvedimenti a favore delle scuole marchigiane e della società civile per contribuire allo sviluppo della coscienza civile, costi | 1 | oldest version available: 30 October 2026 |
| `lr-1995-65/` | L.R. 5 dicembre 1995, n. 65: Disposizioni finanziarie relative all'attuazione del programma operativo di iniziativa comunitaria "Pesca". | 1 | oldest version available: 30 October 2026 |
| `lr-1995-67/` | L.R. 28 dicembre 1995, n. 67: Modifiche alla Legge Regionale 2 agosto 1984, n. 20 disciplina delle indennità spettanti agli amministratori degli enti pubblici o | 1 | oldest version available: 30 October 2026 |
| `lr-1996-1/` | L.R. 15 gennaio 1996, n. 1: Autorizzazione all'esercizio provvisorio del Bilancio per l'anno 1996. | 1 | oldest version available: 30 October 2026 |
| `lr-1996-2/` | L.R. 18 gennaio 1996, n. 2: Delega alle Province delle funzioni amministrative relative alle attività formative cofinanziate dall'Unione Europea. | 1 | oldest version available: 30 October 2026 |
| `lr-1996-4/` | L.R. 23 gennaio 1996, n. 4: Disciplina delle attività professionali nei settori del Turismo e del Tempo Libero. | 1 | oldest version available: 30 October 2026 |
| `lr-1996-6/` | L.R. 26 febbraio 1996, n. 6: Approvazione del rendiconto generale dell'Amministrazione per l'anno 1994. | 1 | oldest version available: 30 October 2026 |
| `lr-1996-7/` | L.R. 26 febbraio 1996, n. 7: Assestamento del bilancio per l'anno 1995. | 1 | oldest version available: 30 October 2026 |
| `lr-1996-8/` | L.R. 9 marzo 1996, n. 8: Approvazione del bilancio di previsione per l'anno 1996 e del bilancio pluriennale 1996/1998. | 1 | oldest version available: 30 October 2026 |
| `lr-1996-9/` | L.R. 25 marzo 1996, n. 9: Modificazioni alla L.R. 28 giugno 1994, n. 22 "Ridelimitazione degli ambiti territoriali e norme per la gestione transitoria delle Uni | 1 | oldest version available: 30 October 2026 |
| `lr-1996-12/` | L.R. 4 aprile 1996, n. 12: Variazione al bilancio di previsione per l'anno 1996. | 1 | oldest version available: 30 October 2026 |
| `lr-1996-16/` | L.R. 29 aprile 1996, n. 16: Interventi per incentivare l'uso della bicicletta e per la creazione di percorsi pedonali sicuri. | 1 | oldest version available: 30 October 2026 |
| `lr-1996-18/` | L.R. 4 giugno 1996, n. 18: Promozione e coordinamento delle politiche di intervento in favore delle persone in condizione di disabilità. | 1 | oldest version available: 30 October 2026 |
| `lr-1996-19/` | L.R. 4 giugno 1996, n. 19: Modificazioni alla Legge Regionale approvata dal Consiglio Regionale nella seduta del 30 aprile 1996, n. 42 avente ad oggetto: "Promo | 1 | oldest version available: 30 October 2026 |
| `lr-1996-23/` | L.R. 26 giugno 1996, n. 23: Partecipazione della Regione Marche al costituendo consorzio Interform. | 1 | oldest version available: 30 October 2026 |
| `lr-1996-24/` | L.R. 27 giugno 1996, n. 24: Adesione della Regione Marche al Centro delle regioni euromediterranee per l'ambiente (CREA) | 1 | oldest version available: 30 October 2026 |
| `lr-1996-25/` | L.R. 27 giugno 1996, n. 25: Seconda variazione al Bilancio di previsione per l'anno 1996. | 1 | oldest version available: 30 October 2026 |
| `lr-1996-26/` | L.R. 17 luglio 1996, n. 26: Riordino del servizio sanitario regionale. | 1 | oldest version available: 30 October 2026 |
| `lr-1996-28/` | L.R. 23 luglio 1996, n. 28: Provvidenze in favore degli invalidi di guerra e per servizio. | 1 | oldest version available: 30 October 2026 |
| `lr-1996-30/` | L.R. 23 luglio 1996, n. 30: Organizzazione e funzionamento della Commissione di esame per il rilascio del certificato di idoneità all'esecuzione delle operazion | 1 | oldest version available: 30 October 2026 |
| `lr-1996-34/` | L.R. 5 agosto 1996, n. 34: Norme per le nomine e designazioni di spettanza della Regione. | 1 | oldest version available: 30 October 2026 |
| `lr-1996-35/` | L.R. 19 agosto 1996, n. 35: Modifica della Legge Regionale 13 marzo 1995, n. 23 avente per oggetto: "Disposizioni in materia di trattamento indennitario dei Con | 1 | oldest version available: 30 October 2026 |
| `lr-1996-42/` | L.R. 15 ottobre 1996, n. 42: Finanziamento dell'attività dei centri scientifici e di ricerca operanti nelle materie di competenza regionale. | 1 | oldest version available: 30 October 2026 |
| `lr-1996-43/` | L.R. 15 ottobre 1996, n. 43: Integrazione alla Legge Regionale 16 gennaio 1995, n. 11 "Istituzione del servizio fitosanitario regionale". | 1 | oldest version available: 30 October 2026 |
| `lr-1996-44/` | L.R. 5 novembre 1996, n. 44: Approvazione del rendiconto generale dell'Amministrazione per l'anno 1995. | 1 | oldest version available: 30 October 2026 |
| `lr-1996-45/` | L.R. 5 novembre 1996, n. 45: Assestamento del bilancio per l'anno 1996. | 1 | oldest version available: 30 October 2026 |
| `lr-1996-46/` | L.R. 15 novembre 1996, n. 46: Contributi per l'attività inerente l'assistenza tecnica attuata dalla Finanziaria Regionale Marche S.p.A. | 1 | oldest version available: 30 October 2026 |
| `lr-1996-47/` | L.R. 19 novembre 1996, n. 47: Norme in materia di programmazione, contabilità e controllo delle Aziende sanitarie. | 1 | oldest version available: 30 October 2026 |
| `lr-1996-48/` | L.R. 19 novembre 1996, n. 48: Ordinamento dei Consorzi di sviluppo industriale. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-5/` | L.R. 9 gennaio 1997, n. 5: Adesione all'associazione "ITACA". | 1 | oldest version available: 30 October 2026 |
| `lr-1997-6/` | L.R. 9 gennaio 1997, n. 6: Interventi per il miglioramento della funzionalità del Porto di Ancona. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-7/` | L.R. 9 gennaio 1997, n. 7: Modifiche alla Legge regionale 20 febbraio 1995, n. 20 recante "Comitato d'intesa regione - ANCI - UPI - UNCEM - AICCRE". | 1 | oldest version available: 30 October 2026 |
| `lr-1997-9/` | L.R. 14 gennaio 1997, n. 9: Istituzione dell'agenzia per i servizi nel settore agroalimentare delle Marche (ASSAM). Soppressione dell'Ente di Sviluppo Agricolo | 1 | oldest version available: 30 October 2026 |
| `lr-1997-10/` | L.R. 20 gennaio 1997, n. 10: Norme in materia di animali da affezione e prevenzione del randagismo. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-13/` | L.R. 20 gennaio 1997, n. 13: Autorizzazione all'esercizio provvisorio del bilancio per l'anno 1997. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-14/` | L.R. 20 gennaio 1997, n. 14: Norme per la semplificazione delle procedure per la partecipazione delle imprese alle gare pubbliche. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-15/` | L.R. 20 gennaio 1997, n. 15: Disciplina del tributo speciale per il deposito in discarica dei rifiuti solidi. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-17/` | L.R. 24 febbraio 1997, n. 17: Modifica alla legge regionale 4 giugno 1996, n. 18 recante "Promozione e coordinamento delle politiche di intervento in favore del | 1 | oldest version available: 30 October 2026 |
| `lr-1997-19/` | L.R. 24 febbraio 1997, n. 19: Aggiornamento del piano smaltimento rifiuti prima fase. Ambito di smaltimento n. 1: Fagnano di Sotto, Comune di Talamello (PS). Mo | 1 | oldest version available: 30 October 2026 |
| `lr-1997-21/` | L.R. 3 marzo 1997, n. 21: Intervento straordinario sulle strutture sanitarie minori. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-23/` | L.R. 3 marzo 1997, n. 23: Istituzione del fondo per la progettazione della rete stradale. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-25/` | L.R. 18 marzo 1997, n. 25: Contributo una tantum ad associazioni protezionistiche che gestiscono canili e rifugi per cani. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-26/` | L.R. 2 aprile 1997, n. 26: Modifica alla Legge Regionale 1 febbraio 1994, n. 6 concernente "Promozione, tramite la Società Finanziaria Marche S.p.A., della cost | 1 | oldest version available: 30 October 2026 |
| `lr-1997-28/` | L.R. 5 maggio 1997, n. 28: Provvedimento generale di rifinanziamento e di modifica di leggi regionali per la formazione del bilancio annuale e pluriennale della | 1 | oldest version available: 30 October 2026 |
| `lr-1997-29/` | L.R. 5 maggio 1997, n. 29: Approvazione del bilancio di previsione per l'anno 1997 ed adozione del bilancio pluriennale per il triennio 1997/1999. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-36/` | L.R. 20 giugno 1997, n. 36: Utilizzazione per iniziative internazionali di carattere umanitario e di cooperazione dei beni mobili inutilizzabili dalle aziende U | 1 | oldest version available: 30 October 2026 |
| `lr-1997-38/` | L.R. 30 giugno 1997, n. 38: Modifica dell'articolo 9 della Legge Regionale 3 ottobre 1991, n. 32 "Norme per l'istituzione ed il funzionamento del comitato regio | 1 | oldest version available: 30 October 2026 |
| `lr-1997-39/` | L.R. 30 giugno 1997, n. 39: Interventi a favore dei marchigiani all'estero. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-40/` | L.R. 30 giugno 1997, n. 40: Norme speciali di semplificazione delle procedure contabili relative alla realizzazione di programmi comunitari. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-42/` | L.R. 14 luglio 1997, n. 42: Trasferimento all'azienda ospedaliera "Torrette-Umberto I" delle competenze e dei finanziamenti disponibili per l'ampliamento e il c | 1 | oldest version available: 30 October 2026 |
| `lr-1997-55/` | L.R. 2 settembre 1997, n. 55: Semplificazione delle procedure dettate da Leggi Regionali di spesa. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-56/` | L.R. 2 settembre 1997, n. 56: Procedure relative agli aiuti compatibili con le disposizioni del Trattato di Roma con riguardo agli interventi straordinari nel s | 1 | oldest version available: 30 October 2026 |
| `lr-1997-57/` | L.R. 2 settembre 1997, n. 57: Istituzione del Parco naturale regionale della Gola della Rossa e di Frasassi. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-58/` | L.R. 2 settembre 1997, n. 58: Assestamento del bilancio per l'anno 1997. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-59/` | L.R. 2 settembre 1997, n. 59: Rendiconto generale dell'Amministrazione per l'anno 1996. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-60/` | L.R. 2 settembre 1997, n. 60: Istituzione dell'agenzia regionale per la protezione ambientale delle Marche (ARPAM) | 1 | oldest version available: 30 October 2026 |
| `lr-1997-61/` | L.R. 2 settembre 1997, n. 61: Lotta alle neoplasie nella Regione Marche. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-62/` | L.R. 1 ottobre 1997, n. 62: Interventi urgenti per fronteggiare lo stato di emergenza derivante dagli eventi sismici del 26 settembre 1997. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-63/` | L.R. 6 novembre 1997, n. 63: Ulteriori interventi urgenti per fronteggiare lo stato di emergenza derivante dagli eventi sismici iniziati il 26 settembre 1997. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-64/` | L.R. 7 novembre 1997, n. 64: Contributo straordinario alla Società Interporto Marche S.p.A.. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-65/` | L.R. 17 novembre 1997, n. 65: Provvidenze a favore di soggetti sottoposti a trapianto d'organi. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-69/` | L.R. 1 dicembre 1997, n. 69: Acquisto di un fabbricato in Ancona da destinare a sede degli uffici della Giunta Regionale. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-70/` | L.R. 1 dicembre 1997, n. 70: Interventi finanziari a favore delle Province. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-71/` | L.R. 1 dicembre 1997, n. 71: Norme per la disciplina delle attività estrattive. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-74/` | L.R. 29 dicembre 1997, n. 74: Modificazioni alla Legge Regionale 20 gennaio 1997, n. 10 "Norme in materia di animali da affezione e prevenzione del randagismo". | 1 | oldest version available: 30 October 2026 |
| `lr-1997-76/` | L.R. 29 dicembre 1997, n. 76: Disciplina dell'agricoltura biologica. | 1 | oldest version available: 30 October 2026 |
| `lr-1997-77/` | L.R. 29 dicembre 1997, n. 77: Autorizzazione all'esercizio provvisorio del bilancio per l'anno 1998. | 1 | oldest version available: 30 October 2026 |
| `lr-1998-1/` | L.R. 7 febbraio 1998, n. 1: Modifica della legge regionale 1 ottobre 1997, n. 62 "interventi urgenti per fronteggiare lo stato di emergenza derivante dagli even | 1 | oldest version available: 30 October 2026 |
| `lr-1998-4/` | L.R. 17 marzo 1998, n. 4: Istituzione della struttura regionale di collegamento presso l'Unione Europea ex articolo 58 della legge 6 febbraio 1996, n. 52. | 1 | oldest version available: 30 October 2026 |
| `lr-1998-5/` | L.R. 17 marzo 1998, n. 5: Norme sulla partecipazione della Regione Marche alla società cooperativa "verso la banca etica soc. coop. a r.l.", e a sostegno dell'a | 1 | oldest version available: 30 October 2026 |
| `lr-1998-8/` | L.R. 31 marzo 1998, n. 8: Modifica dell'articolo 33 della Legge regionale 28 aprile 1994, n. 15 concernente la norma transitoria per il Parco del Conero. | 1 | oldest version available: 30 October 2026 |
| `lr-1998-9/` | L.R. 6 aprile 1998, n. 9: Modifiche ed integrazioni alla Legge regionale 5 agosto 1982, n. 29 e disposizioni in materia di scarichi. | 1 | oldest version available: 30 October 2026 |
| `lr-1998-10/` | L.R. 6 aprile 1998, n. 10: Norme in materia di trasporto di persone mediante il servizio di taxi ed il servizio di noleggio di veicoli con conducente. | 1 | oldest version available: 30 October 2026 |
| `lr-1998-12/` | L.R. 5 maggio 1998, n. 12: Provvedimento generale di rifinanziamento e modifica di leggi regionali per la formazione del Bilancio annuale e pluriennale della Re | 1 | oldest version available: 30 October 2026 |
| `lr-1998-13/` | L.R. 5 maggio 1998, n. 13: Approvazione del bilancio di previsione per l'anno 1998 ed adozione del bilancio pluriennale per il triennio 1998/2000. | 1 | oldest version available: 30 October 2026 |
| `lr-1998-17/` | L.R. 16 giugno 1998, n. 17: Modifiche ed integrazioni alla Legge regionale 23 gennaio 1996, n. 4 "Disciplina delle attività professionali nei settori del turism | 1 | oldest version available: 30 October 2026 |
| `lr-1998-22/` | L.R. 27 luglio 1998, n. 22: Diritti della partoriente, del nuovo nato e del bambino spedalizzato. | 1 | oldest version available: 30 October 2026 |
| `lr-1998-23/` | L.R. 27 luglio 1998, n. 23: Gestione dei diritti di reimpianto di vigneti. | 1 | oldest version available: 30 October 2026 |
| `lr-1998-24/` | L.R. 27 luglio 1998, n. 24: Disciplina organica dell'esercizio delle funzioni amministrative in materia agro-alimentare, forestale, di caccia e di pesca nel ter | 1 | oldest version available: 30 October 2026 |
| `lr-1998-26/` | L.R. 27 luglio 1998, n. 26: Interventi regionali per l'istituzione dei Parchi Urbani. Abrogazione Legge Regionale 2 settembre 1996, n. 41. | 1 | oldest version available: 30 October 2026 |
| `lr-1998-29/` | L.R. 3 agosto 1998, n. 29: Modifiche alla legge regionale 20 gennaio 1997, n. 15 concernente la disciplina del tributo speciale per il deposito in discarica dei | 1 | oldest version available: 30 October 2026 |
| `lr-1998-31/` | L.R. 10 agosto 1998, n. 31: Inquadramento nel ruolo unico regionale del personale operante nella formazione professionale. Modifiche ed integrazioni alle leggi | 1 | oldest version available: 30 October 2026 |
| `lr-1998-33/` | L.R. 10 agosto 1998, n. 33: Disciplina generale e delega per l'applicazione delle sanzioni amministrative di competenza regionale. | 1 | oldest version available: 30 October 2026 |
| `lr-1998-34/` | L.R. 20 ottobre 1998, n. 34: Piano Sanitario Regionale 1998/2000. | 1 | oldest version available: 30 October 2026 |
| `lr-1998-36/` | L.R. 30 ottobre 1998, n. 36: Sistema di emergenza sanitaria. | 1 | oldest version available: 30 October 2026 |
| `lr-1998-37/` | L.R. 3 novembre 1998, n. 37: Interventi in materia di riproduzione animale. | 1 | oldest version available: 30 October 2026 |
| `lr-1998-39/` | L.R. 16 novembre 1998, n. 39: Rendiconto generale dell'Amministrazione per l'anno 1997. | 1 | oldest version available: 30 October 2026 |
| `lr-1998-40/` | L.R. 16 novembre 1998, n. 40: Assestamento del Bilancio per l'anno 1998. | 1 | oldest version available: 30 October 2026 |
| `lr-1998-42/` | L.R. 14 dicembre 1998, n. 42: Modificazioni alla Legge regionale 17 marzo 1998, n. 5 concernente "Norme sulla partecipazione della Regione alla società cooperat | 1 | oldest version available: 30 October 2026 |
| `lr-1998-44/` | L.R. 23 dicembre 1998, n. 44: Interventi a favore delle attività produttive che hanno subito danni in conseguenza della crisi sismica iniziata il 26 settembre 1 | 1 | oldest version available: 30 October 2026 |
| `lr-1998-45/` | L.R. 24 dicembre 1998, n. 45: Norme per il riordino del trasporto pubblico regionale e locale nelle Marche. | 1 | oldest version available: 30 October 2026 |
| `lr-1998-47/` | L.R. 24 dicembre 1998, n. 47: Disposizioni in materia di tasse sulle concessioni regionali. | 1 | oldest version available: 30 October 2026 |
| `lr-1999-1/` | L.R. 11 gennaio 1999, n. 1: Autorizzazione all'esercizio provvisorio del bilancio per l'anno 1999. | 1 | oldest version available: 30 October 2026 |
| `lr-1999-2/` | L.R. 18 gennaio 1999, n. 2: Costituzione della "Fondazione orchestra regionale delle Marche". | 1 | oldest version available: 30 October 2026 |
| `lr-1999-6/` | L.R. 29 marzo 1999, n. 6: Norme sull'attività statistica nella Regione Marche. | 1 | oldest version available: 30 October 2026 |
| `lr-1999-7/` | L.R. 11 maggio 1999, n. 7: Provvedimento generale di rifinanziamento o modifica di leggi regionali per la formazione del bilancio annuale e pluriennale della Re | 1 | oldest version available: 30 October 2026 |
| `lr-1999-8/` | L.R. 11 maggio 1999, n. 8: Modifica alla deliberazione legislativa concernente: "Provvedimento generale di rifinanziamento o modifica di leggi regionali per la | 1 | oldest version available: 30 October 2026 |
| `lr-1999-9/` | L.R. 12 maggio 1999, n. 9: Approvazione del bilancio di previsione per l'anno 1999 ed adozione del bilancio pluriennale per il triennio 1999/2001. | 1 | oldest version available: 30 October 2026 |
| `lr-1999-10/` | L.R. 17 maggio 1999, n. 10: Riordino delle funzioni amministrative della Regione e degli Enti locali nei settori dello sviluppo economico ed attività produttive | 1 | oldest version available: 30 October 2026 |
| `lr-1999-11/` | L.R. 25 maggio 1999, n. 11: Integrazione alla legge regionale 23 gennaio 1996, n. 4 e successive modificazioni ed integrazioni "Disciplina delle attività profes | 1 | oldest version available: 30 October 2026 |
| `lr-1999-12/` | L.R. 25 maggio 1999, n. 12: Conferimento alle Province delle funzioni amministrative in materia di inquinamento atmosferico. | 1 | oldest version available: 30 October 2026 |
| `lr-1999-13/` | L.R. 25 maggio 1999, n. 13: Disciplina regionale della difesa del suolo. | 1 | oldest version available: 30 October 2026 |
| `lr-1999-14/` | L.R. 25 maggio 1999, n. 14: Modificazioni alla legge regionale 4 settembre 1992, n. 42 concernente: "Norme in materia di assistenza scolastica del diritto allo | 1 | oldest version available: 30 October 2026 |
| `lr-1999-16/` | L.R. 1 giugno 1999, n. 16: Istituzione del Consorzio di sviluppo industriale del Fermano. | 1 | oldest version available: 30 October 2026 |
| `lr-1999-22/` | L.R. 2 agosto 1999, n. 22: Deviazione del traffico pesante dalla strada statale 16 all'autostrada A 14 nel periodo luglio-settembre 1999. | 1 | oldest version available: 30 October 2026 |
| `lr-1999-24/` | L.R. 31 agosto 1999, n. 24: Modificazioni alla legge regionale 17 novembre 1997, n. 65 concernente: "Provvidenza a favore di soggetti sottoposti a trapianto d'o | 1 | oldest version available: 30 October 2026 |
| `lr-1999-25/` | L.R. 31 agosto 1999, n. 25: Interventi per la realizzazione di infrastrutture e di servizi nel settore del trasporto delle merci e la ristrutturazione dell'auto | 1 | oldest version available: 30 October 2026 |
| `lr-1999-30/` | L.R. 28 ottobre 1999, n. 30: Modificazioni della L.R. 6 giugno 1988, n. 19, concernente: "Norme in materia di opere concernenti linee ed impianti elettrici fino | 1 | oldest version available: 30 October 2026 |
| `lr-1999-31/` | L.R. 30 novembre 1999, n. 31: Approvazione del Rendiconto generale dell'Amministrazione per l'anno 1998. | 1 | oldest version available: 30 October 2026 |
| `lr-1999-32/` | L.R. 30 novembre 1999, n. 32: Assestamento del Bilancio per l'anno 1999. | 1 | oldest version available: 30 October 2026 |
| `lr-1999-33/` | L.R. 17 dicembre 1999, n. 33: Nuove norme e modifiche alla legge regionale 1 dicembre 1997, n. 71 "Norme per la disciplina delle attività estrattive". | 1 | oldest version available: 30 October 2026 |
| `lr-1999-35/` | L.R. 17 dicembre 1999, n. 35: Disposizione in materia di informazione territoriale e cartografia regionale. | 1 | oldest version available: 30 October 2026 |
| `lr-1999-36/` | L.R. 17 dicembre 1999, n. 36: Modifiche ed integrazioni alla Legge regionale 5 agosto 1982, n. 29 e disposizioni in materia di scarichi. | 1 | oldest version available: 30 October 2026 |
| `lr-1999-37/` | L.R. 23 dicembre 1999, n. 37: Disciplina dei servizi per lo sviluppo del sistema agroalimentare regionale. | 1 | oldest version available: 30 October 2026 |
| `lr-1999-39/` | L.R. 31 dicembre 1999, n. 39: Autorizzazione all'esercizio provvisorio del bilancio per l'anno 2000. | 1 | oldest version available: 30 October 2026 |
| `lr-2000-2/` | L.R. 10 gennaio 2000, n. 2: Integrazioni e modifiche alle Leggi regionali 5 agosto 1996, n. 34: "Norme per le nomine e designazioni di spettanza della Regione" | 1 | oldest version available: 30 October 2026 |
| `lr-2000-3/` | L.R. 24 gennaio 2000, n. 3: Modifiche ed integrazioni alla legge regionale 23 dicembre 1998, n. 44 "Interventi a favore delle attività produttive che hanno subi | 1 | oldest version available: 30 October 2026 |
| `lr-2000-4/` | L.R. 24 gennaio 2000, n. 4: Modifiche alla legge regionale 24 dicembre 1998, n. 45 "Norme per il riordino del trasporto pubblico regionale e locale nelle Marche | 1 | oldest version available: 30 October 2026 |
| `lr-2000-9/` | L.R. 23 febbraio 2000, n. 9: Norme in materia di consumo di prodotti geneticamente modificati nelle mense scolastiche, negli ospedali e nei luoghi di cura. | 1 | oldest version available: 30 October 2026 |
| `lr-2000-10/` | L.R. 23 febbraio 2000, n. 10: Modificazione della Legge Regionale 10 agosto 1998, n. 30 concernente "Interventi a favore della famiglia". | 1 | oldest version available: 30 October 2026 |
| `lr-2000-11/` | L.R. 23 febbraio 2000, n. 11: Interventi in favore dei soggetti non udenti. | 1 | oldest version available: 30 October 2026 |
| `lr-2000-12/` | L.R. 23 febbraio 2000, n. 12: Norme sulla speleologia. | 1 | oldest version available: 30 October 2026 |
| `lr-2000-16/` | L.R. 23 febbraio 2000, n. 16: Modificazioni alla Legge Regionale 17 novembre 1997, n. 65 concernente "Provvidenze a favore dei soggetti sottoposti a trapianto d | 1 | oldest version available: 30 October 2026 |
| `lr-2000-18/` | L.R. 16 marzo 2000, n. 18: Modificazioni ed integrazioni della Legge Regionale 30 ottobre 1998, n. 36: "Sistema di emergenza sanitaria". | 1 | oldest version available: 30 October 2026 |
| `lr-2000-19/` | L.R. 16 marzo 2000, n. 19: Norme concernenti l'assistenza sanitaria di base. | 1 | oldest version available: 30 October 2026 |
| `lr-2000-21/` | L.R. 23 marzo 2000, n. 21: Provvedimento generale di rifinanziamento e modifica di leggi regionali per la formazione del bilancio annuale e pluriennale della Re | 1 | oldest version available: 30 October 2026 |
| `lr-2000-22/` | L.R. 23 marzo 2000, n. 22: Approvazione del Bilancio di previsione per l'anno 2000 ed adozione del bilancio pluriennale per il triennio 2000/2002. | 1 | oldest version available: 30 October 2026 |
| `lr-2000-23/` | L.R. 3 aprile 2000, n. 23: Prime disposizioni in materia di incompatibilità ed indennità degli assessori non consiglieri regionali. | 1 | oldest version available: 30 October 2026 |
| `lr-2000-26/` | L.R. 3 aprile 2000, n. 26: Modifiche ed integrazioni alla L.R. 20 gennaio 1997, n. 10 "Norme in materia di animali da affezione e prevenzione del randagismo". | 1 | oldest version available: 30 October 2026 |
| `lr-2000-27/` | L.R. 3 novembre 2000, n. 27: Norme per l'acquisto di quote partecipative del capitale della Finanziaria regionale Marche SpA. | 1 | oldest version available: 30 October 2026 |
| `lr-2000-28/` | L.R. 21 novembre 2000, n. 28: Modifiche ed integrazioni alla Legge Regionale 4 giugno 1996, n. 18 "Promozione e coordinamento delle politiche di intervento in f | 1 | oldest version available: 30 October 2026 |
| `lr-2000-29/` | L.R. 18 dicembre 2000, n. 29: Approvazione del Rendiconto generale dell'amministrazione per l'anno 1999. | 1 | oldest version available: 30 October 2026 |
| `lr-2000-30/` | L.R. 28 dicembre 2000, n. 30: Assestamento del bilancio 2000. | 1 | oldest version available: 30 October 2026 |
| `lr-2001-1/` | L.R. 12 gennaio 2001, n. 1: Autorizzazione all'esercizio provvisorio del bilancio per l'anno 2001. | 1 | oldest version available: 30 October 2026 |
| `lr-2001-2/` | L.R. 12 gennaio 2001, n. 2: Modificazioni ed integrazioni alla legge regionale 24 dicembre 1998, n. 45 sul riordino del trasporto pubblico locale nelle Marche. | 1 | oldest version available: 30 October 2026 |
| `lr-2001-4/` | L.R. 5 febbraio 2001, n. 4: Gratuità delle prestazioni di emergenza e urgenza erogate dal pronto soccorso. Modificazioni all'articolo 20 della legge regionale 3 | 1 | oldest version available: 30 October 2026 |
| `lr-2001-8/` | L.R. 27 marzo 2001, n. 8: Istituzione, organizzazione e funzionamento del Comitato regionale per le Comunicazioni (CORECOM). | 1 | oldest version available: 30 October 2026 |
| `lr-2001-10/` | L.R. 18 aprile 2001, n. 10: Semplificazione del sistema normativo regionale mediante abrogazione di disposizioni normative. | 1 | oldest version available: 30 October 2026 |
| `lr-2001-11/` | L.R. 7 maggio 2001, n. 11: Provvedimento generale di rifinanziamento e modifica di leggi regionali per la formazione del Bilancio annuale e pluriennale della Re | 1 | oldest version available: 30 October 2026 |
| `lr-2001-12/` | L.R. 7 maggio 2001, n. 12: Approvazione del Bilancio di previsione per l'anno 2001 ed adozione del Bilancio pluriennale per il triennio 2001/2003. | 1 | oldest version available: 30 October 2026 |
| `lr-2001-14/` | L.R. 19 giugno 2001, n. 14: Modifica alla Legge Regionale 7 maggio 2001, n. 11 concernente: "Provvedimento generale di rifinanziamento e modifica di Leggi Regio | 1 | oldest version available: 30 October 2026 |
| `lr-2001-16/` | L.R. 16 luglio 2001, n. 16: Modifica del comma 12 dell'articolo 6 della L.R. 7 maggio 2001, n. 11 "Provvedimento generale di rifinanziamento e modifica di leggi | 1 | oldest version available: 30 October 2026 |
| `lr-2001-18/` | L.R. 16 agosto 2001, n. 18: Delega al Comune di Ancona delle funzioni relative agli interventi di cui alla legge 12 agosto 1993, n. 317. | 1 | oldest version available: 30 October 2026 |
| `lr-2001-20/` | L.R. 15 ottobre 2001, n. 20: Norme in materia di organizzazione e di personale della Regione. | 1 | oldest version available: 30 October 2026 |
| `lr-2001-21/` | L.R. 22 ottobre 2001, n. 21: Modifiche alla legge regionale 30 dicembre 1974, n. 52 "Provvedimenti per la tutela degli ambienti naturali". | 1 | oldest version available: 30 October 2026 |
| `lr-2001-22/` | L.R. 22 ottobre 2001, n. 22: Disciplina degli impianti di trasporto a fune in servizio pubblico, delle piste da sci e dei sistemi di innevamento programmato. | 1 | oldest version available: 30 October 2026 |
| `lr-2001-26/` | L.R. 13 novembre 2001, n. 26: Sospensione della terapia elettroconvulsivante, della lobotomia prefrontale e transorbitale ed altri simili interventi di psicochi | 1 | oldest version available: 30 October 2026 |
| `lr-2001-27/` | L.R. 13 novembre 2001, n. 27: Interventi per il coordinamento dei tempi delle città e la promozione dell'uso del tempo per fini di solidarietà sociale. | 1 | oldest version available: 30 October 2026 |
| `lr-2001-28/` | L.R. 14 novembre 2001, n. 28: Norme per la tutela dell'ambiente esterno e dell'ambiente abitativo dall'inquinamento acustico nella Regione Marche. | 1 | oldest version available: 30 October 2026 |
| `lr-2001-29/` | L.R. 28 novembre 2001, n. 29: Approvazione del Rendiconto Generale dell'Amministrazione per l'anno 2000. | 1 | oldest version available: 30 October 2026 |
| `lr-2001-30/` | L.R. 28 novembre 2001, n. 30: Assestamento del Bilancio 2001. | 1 | oldest version available: 30 October 2026 |
| `lr-2001-31/` | L.R. 11 dicembre 2001, n. 31: Ordinamento contabile della Regione Marche e strumenti di programmazione. | 1 | oldest version available: 30 October 2026 |
| `lr-2001-33/` | L.R. 13 dicembre 2001, n. 33: Autorizzazione all'esercizio provvisorio del Bilancio per l'anno 2002. | 1 | oldest version available: 30 October 2026 |
| `lr-2001-34/` | L.R. 18 dicembre 2001, n. 34: Promozione e sviluppo della cooperazione sociale. | 1 | oldest version available: 30 October 2026 |
| `lr-2001-35/` | L.R. 19 dicembre 2001, n. 35: Provvedimenti tributari in materia di addizionale regionale all'IRPEF, di tasse automobilistiche e di imposta regionale sulle atti | 1 | oldest version available: 30 October 2026 |
| `lr-2002-2/` | L.R. 22 marzo 2002, n. 2: Proroga dell'autorizzazione all'esercizio provvisorio del Bilancio per l'anno 2002. | 1 | oldest version available: 30 October 2026 |
| `lr-2002-4/` | L.R. 3 aprile 2002, n. 4: Modificazioni della legge regionale 29 dicembre 1997, n. 76 "Disciplina dell'agricoltura biologica". | 1 | oldest version available: 30 October 2026 |
| `lr-2002-5/` | L.R. 3 aprile 2002, n. 5: Integrazioni della legge regionale 26 dicembre 1983, n. 41 sulle provvidenze in favore della popolazione di Ancona colpita dalla frana | 1 | oldest version available: 30 October 2026 |
| `lr-2002-6/` | L.R. 23 aprile 2002, n. 6: Provvedimento generale di rifinanziamento e modifica di leggi regionali per la formazione del Bilancio annuale e pluriennale della Re | 1 | oldest version available: 30 October 2026 |
| `lr-2002-7/` | L.R. 23 aprile 2002, n. 7: Approvazione del Bilancio di previsione per l'anno 2002 ed adozione del Bilancio pluriennale per il triennio 2002/2004. | 1 | oldest version available: 30 October 2026 |
| `lr-2002-8/` | L.R. 14 maggio 2002, n. 8: Comune di Monte Grimano mutamento di denominazione in Monte Grimano Terme. | 1 | oldest version available: 30 October 2026 |
| `lr-2002-9/` | L.R. 18 giugno 2002, n. 9: Attività regionali per la promozione dei diritti umani, della cultura di pace, della cooperazione allo sviluppo e della solidarietà i | 1 | oldest version available: 30 October 2026 |
| `lr-2002-10/` | L.R. 24 luglio 2002, n. 10: Misure urgenti in materia di risparmio energetico e contenimento dell'inquinamento luminoso. | 1 | oldest version available: 30 October 2026 |
| `lr-2002-12/` | L.R. 24 luglio 2002, n. 12: Norme sulla detenzione e sul commercio di animali esotici. | 1 | oldest version available: 30 October 2026 |
| `lr-2002-14/` | L.R. 24 luglio 2002, n. 14: Modificazioni alla L.R. 17 dicembre 1999, n. 33 concernente: "nuove norme e modifiche alla L.R. 1 dicembre 1997, n. 71: "Norme per l | 1 | oldest version available: 30 October 2026 |
| `lr-2002-16/` | L.R. 24 luglio 2002, n. 16: Modifiche alla L.R. 2 agosto 1984, n. 20 concernente: "Disciplina delle indennità spettanti agli amministratori degli enti pubblici | 1 | oldest version available: 30 October 2026 |
| `lr-2002-23/` | L.R. 6 novembre 2002, n. 23: Modifica delle leggi regionali 17 maggio 1999, n. 10 sul riordino delle funzioni amministrative della regione e degli enti locali, | 1 | oldest version available: 30 October 2026 |
| `lr-2002-24/` | L.R. 25 novembre 2002, n. 24: Approvazione del rendiconto generale dell'amministrazione per l'anno 2001. | 1 | oldest version available: 30 October 2026 |
| `lr-2002-25/` | L.R. 25 novembre 2002, n. 25: Assestamento del bilancio per l'anno 2002. | 1 | oldest version available: 30 October 2026 |
| `lr-2002-26/` | L.R. 18 dicembre 2002, n. 26: Autorizzazione all'esercizio provvisorio del bilancio per l'anno 2003. | 1 | oldest version available: 30 October 2026 |
| `lr-2002-27/` | L.R. 18 dicembre 2002, n. 27: Proroga dei commissari straordinari delle aziende sanitarie regionali. | 1 | oldest version available: 30 October 2026 |
| `lr-2002-28/` | L.R. 23 dicembre 2002, n. 28: Norme in materia di referendum sulle leggi regionali di revisione statutaria. | 1 | oldest version available: 30 October 2026 |
| `lr-2003-1/` | L.R. 28 gennaio 2003, n. 1: Modifica della Legge regionale 18 gennaio 1996, n. 2 concernente: "Delega alle province delle funzioni amministrative relative alle | 1 | oldest version available: 30 October 2026 |
| `lr-2003-3/` | L.R. 11 marzo 2003, n. 3: Provvedimento generale di rifinanziamento e modifica di leggi regionali per la formazione del bilancio annuale e pluriennale della Reg | 1 | oldest version available: 30 October 2026 |
| `lr-2003-4/` | L.R. 11 marzo 2003, n. 4: Approvazione del Bilancio di previsione per l'anno 2003 ed adozione del Bilancio pluriennale per il triennio 2003/2005. | 1 | oldest version available: 30 October 2026 |
| `lr-2003-5/` | L.R. 16 aprile 2003, n. 5: Provvedimenti per favorire lo sviluppo della cooperazione. | 1 | oldest version available: 30 October 2026 |
| `lr-2003-7/` | L.R. 12 maggio 2003, n. 7: Soppressione del Comitato regionale di controllo e delegificazione in materia di organismi regionali. Semplificazione del sistema nor | 1 | oldest version available: 30 October 2026 |
| `lr-2003-8/` | L.R. 12 maggio 2003, n. 8: Modifiche alla legge regionale 15 ottobre 2001, n. 20 sull'organizzazione e personale della Regione e disposizioni in materia di pers | 1 | oldest version available: 30 October 2026 |
| `lr-2003-9/` | L.R. 13 maggio 2003, n. 9: Disciplina per la realizzazione e gestione dei servizi per l'infanzia, per l'adolescenza e per il sostegno alle funzioni genitoriali | 1 | oldest version available: 30 October 2026 |
| `lr-2003-10/` | L.R. 3 giugno 2003, n. 10: Intervento regionale in favore dell'Associazione per la formazione al giornalismo. | 1 | oldest version available: 30 October 2026 |
| `lr-2003-11/` | L.R. 3 giugno 2003, n. 11: Norme per l'incremento e la tutela della fauna ittica e disciplina della pesca nelle acque interne. | 1 | oldest version available: 30 October 2026 |
| `lr-2003-12/` | L.R. 3 giugno 2003, n. 12: Tutela delle risorse genetiche animali e vegetali del territorio marchigiano. | 1 | oldest version available: 30 October 2026 |
| `lr-2003-14/` | L.R. 30 giugno 2003, n. 14: Riorganizzazione della struttura amministrativa del Consiglio Regionale. | 1 | oldest version available: 30 October 2026 |
| `lr-2003-15/` | L.R. 30 giugno 2003, n. 15: Modifiche ed integrazioni alla L.R. 1° dicembre 1997, n. 71 concernente "Norme per la disciplina delle attività estrattive". | 1 | oldest version available: 30 October 2026 |
| `lr-2003-17/` | L.R. 28 luglio 2003, n. 17: Norme in materia di ordinamento del bollettino ufficiale della regione e di diritto all'informazione sugli atti amministrativi. | 1 | oldest version available: 30 October 2026 |
| `lr-2003-18/` | L.R. 22 ottobre 2003, n. 18: Rendiconto generale dell'amministrazione per l'anno 2002. | 1 | oldest version available: 30 October 2026 |
| `lr-2003-19/` | L.R. 28 ottobre 2003, n. 19: Assestamento del bilancio 2003. | 1 | oldest version available: 30 October 2026 |
| `lr-2003-20/` | L.R. 28 ottobre 2003, n. 20: Partecipazioni societarie della Regione | 1 | oldest version available: 30 October 2026 |
| `lr-2003-21/` | L.R. 10 dicembre 2003, n. 21: Trasformazione in costruzioni a carattere permanente degli alloggi prefabbricati temporanei installati a seguito degli eventi sism | 1 | oldest version available: 30 October 2026 |
| `lr-2003-23/` | L.R. 10 dicembre 2003, n. 23: Interventi per il sostegno dei sistemi di certificazione della qualità e della tracciabilità delle produzioni agricole ed agroalim | 1 | oldest version available: 30 October 2026 |
| `lr-2003-24/` | L.R. 18 dicembre 2003, n. 24: Modifiche alla legge regionale 18 giugno 2002, n. 9 recante: "Attività regionali per la promozione dei diritti umani, della cultur | 1 | oldest version available: 30 October 2026 |
| `lr-2003-25/` | L.R. 22 dicembre 2003, n. 25: Ulteriori provvedimenti tributari in materia di imposta regionale sulle attività produttive, di addizionale regionale all'Irpef e | 1 | oldest version available: 30 October 2026 |
| `lr-2003-26/` | L.R. 22 dicembre 2003, n. 26: Autorizzazione all'esercizio provvisorio del bilancio per l'anno 2004. | 1 | oldest version available: 30 October 2026 |
| `lr-2003-27/` | L.R. 22 dicembre 2003, n. 27: Interventi regionali nel settore della zootecnia | 1 | oldest version available: 30 October 2026 |
| `lr-2003-28/` | L.R. 22 dicembre 2003, n. 28: Modifica alla legge regionale 24 dicembre 1998, n. 45 "Norme per il riordino del trasporto pubblico regionale e locale nelle March | 1 | oldest version available: 30 October 2026 |
| `lr-2004-1/` | L.R. 20 gennaio 2004, n. 1: Modificazioni delle leggi regionali contenenti disposizioni che attribuiscono il potere regolamentare alla Giunta regionale. | 1 | oldest version available: 30 October 2026 |
| `lr-2004-2/` | L.R. 19 febbraio 2004, n. 2: Provvedimento generale di rifinanziamento e modifica di leggi regionali per la formazione del bilancio annuale e pluriennale della | 1 | oldest version available: 30 October 2026 |
| `lr-2004-3/` | L.R. 19 febbraio 2004, n. 3: Approvazione del bilancio di previsione per l'anno 2004 ed adozione del bilancio pluriennale per il triennio 2004/2006. | 1 | oldest version available: 30 October 2026 |
| `lr-2004-4/` | L.R. 24 febbraio 2004, n. 4: Disposizioni eccezionali e straordinarie in attuazione del piano sanitario regionale 2003/2006 relative al personale delle struttur | 1 | oldest version available: 30 October 2026 |
| `lr-2004-5/` | L.R. 3 marzo 2004, n. 5: Disposizioni in materia di salvaguardia delle produzioni agricole, tipiche, di qualità e biologiche. | 1 | oldest version available: 30 October 2026 |
| `lr-2004-6/` | L.R. 6 aprile 2004, n. 6: Disciplina delle aree ad elevato rischio di crisi ambientale. | 1 | oldest version available: 30 October 2026 |
| `lr-2004-11/` | L.R. 13 maggio 2004, n. 11: Norme in materia di pesca marittima e acquacoltura. | 1 | oldest version available: 30 October 2026 |
| `lr-2004-12/` | L.R. 13 maggio 2004, n. 12: Fusione dei Consorzi di Bonifica dell'Aso, del Tenna e del Tronto. | 1 | oldest version available: 30 October 2026 |
| `lr-2004-13/` | L.R. 18 maggio 2004, n. 13: Norme concernenti le agenzie, gli enti dipendenti e le aziende operanti in materia di competenza regionale. | 1 | oldest version available: 30 October 2026 |
| `lr-2004-14/` | L.R. 14 luglio 2004, n. 14: Modifiche alla legge regionale 28 aprile 1994, n. 15 "Norme per l'istituzione e gestione delle aree protette naturali". | 1 | oldest version available: 30 October 2026 |
| `lr-2004-15/` | L.R. 14 luglio 2004, n. 15: Disciplina delle funzioni in materia di difesa della costa. | 1 | oldest version available: 30 October 2026 |
| `lr-2004-16/` | L.R. 2 agosto 2004, n. 16: Rendiconto generale dell'amministrazione per l'anno 2003. | 1 | oldest version available: 30 October 2026 |
| `lr-2004-17/` | L.R. 2 agosto 2004, n. 17: Assestamento del bilancio 2004. | 1 | oldest version available: 30 October 2026 |
| `lr-2004-18/` | L.R. 4 ottobre 2004, n. 18: Norme relative al controllo del pericolo di incidenti rilevanti. Decreto legislativo 17 agosto 1999, n. 334 sul rischio industriale. | 1 | oldest version available: 30 October 2026 |
| `lr-2004-19/` | L.R. 4 ottobre 2004, n. 19: Modifiche alla legge regionale 30 giugno 1997, n. 39 recante interventi a favore dei marchigiani all'estero. | 1 | oldest version available: 30 October 2026 |
| `lr-2004-20/` | L.R. 4 ottobre 2004, n. 20: Istituzione dell'Albo regionale delle società di mutuo soccorso ed interventi a tutela del loro patrimonio storico e culturale. | 1 | oldest version available: 30 October 2026 |
| `lr-2004-21/` | L.R. 12 ottobre 2004, n. 21: Modifica della legge regionale 6 aprile 2004, n. 6 "Disciplina delle aree ad elevato rischio di crisi ambientale" | 1 | oldest version available: 30 October 2026 |
| `lr-2004-22/` | L.R. 21 ottobre 2004, n. 22: Modifiche ed integrazioni alla legge regionale 24 dicembre 1998, n. 45: "Norme per il riordino del trasporto pubblico regionale e l | 1 | oldest version available: 30 October 2026 |
| `lr-2004-23/` | L.R. 29 ottobre 2004, n. 23: Norme sulla sanatoria degli abusi edilizi | 1 | oldest version available: 30 October 2026 |
| `lr-2004-25/` | L.R. 4 dicembre 2004, n. 25: Modifiche alla legge regionale 22 ottobre 2001, n. 22 concernente: "Disciplina degli impianti di trasporto a fune in servizio pubbl | 1 | oldest version available: 30 October 2026 |
| `lr-2004-26/` | L.R. 4 dicembre 2004, n. 26: Modifiche alla legge regionale 27 luglio 1998, n. 24 concernente: "Disciplina organica dell'esercizio delle funzioni amministrative | 1 | oldest version available: 30 October 2026 |
| `lr-2004-27/` | L.R. 16 dicembre 2004, n. 27: Norme per l'elezione del Consiglio e del Presidente della Giunta regionale. | 1 | oldest version available: 30 October 2026 |
| `lr-2004-28/` | L.R. 17 dicembre 2004, n. 28: Integrazione e modifica della legge regionale 3 giugno 2003, n. 12 "Tutela delle risorse genetiche animali e vegetali del territor | 1 | oldest version available: 30 October 2026 |
| `lr-2004-29/` | L.R. 24 dicembre 2004, n. 29: Disposizioni per la formazione del bilancio annuale e pluriennale della Regione (legge finanziaria 2005). | 1 | oldest version available: 30 October 2026 |
| `lr-2004-30/` | L.R. 24 dicembre 2004, n. 30: Bilancio di previsione per l'anno 2005 ed adozione del bilancio pluriennale per il triennio 2005/2007. | 1 | oldest version available: 30 October 2026 |
| `lr-2005-2/` | L.R. 25 gennaio 2005, n. 2: Norme regionali per l'occupazione, la tutela e la qualità del lavoro | 1 | oldest version available: 30 October 2026 |
| `lr-2005-3/` | L.R. 1 febbraio 2005, n. 3: Norme in materia di attività e servizi necroscopici funebri e cimiteriali | 1 | oldest version available: 30 October 2026 |
| `lr-2005-5/` | L.R. 1 febbraio 2005, n. 5: Norme relative alle elezioni regionali dell'anno 2005 - Modifica della legge regionale 16 dicembre 2004, n.27 "Norme per l'elezione | 1 | oldest version available: 30 October 2026 |
| `lr-2005-6/` | L.R. 23 febbraio 2005, n. 6: Legge forestale regionale | 1 | oldest version available: 30 October 2026 |
| `lr-2005-7/` | L.R. 23 febbraio 2005, n. 7: Promozione della cooperazione per lo sviluppo rurale | 1 | oldest version available: 30 October 2026 |
| `lr-2005-8/` | L.R. 23 febbraio 2005, n. 8: Norme in materia di accertamento della regolarità contributiva delle imprese | 1 | oldest version available: 30 October 2026 |
| `lr-2005-10/` | L.R. 23 febbraio 2005, n. 10: Modificazioni alla legge regionale 5 agosto 1996, n. 34 "Norme per le nomine e designazioni di spettanza della Regione" | 1 | oldest version available: 30 October 2026 |
| `lr-2005-11/` | L.R. 23 febbraio 2005, n. 11: Interventi per la promozione di prassi socialmente responsabili, per la certificazione dei sistemi di qualità, del rispetto dell'a | 1 | oldest version available: 30 October 2026 |
| `lr-2005-12/` | L.R. 23 febbraio 2005, n. 12: Modifiche alle leggi regionali in materia sanitaria 17 luglio 1996, n. 26, 19 novembre 1996, n. 47 e 16 marzo 2000, n. 20 | 1 | oldest version available: 30 October 2026 |
| `lr-2005-15/` | L.R. 23 febbraio 2005, n. 15: Istituzioni del sistema regionale del servizio civile. | 1 | oldest version available: 30 October 2026 |
| `lr-2005-18/` | L.R. 13 luglio 2005, n. 18: Acquisizione tramite contratto di leasing di un immobile in Ancona da destinare a sede degli uffici della Giunta regionale. | 1 | oldest version available: 30 October 2026 |
| `lr-2005-19/` | L.R. 1 agosto 2005, n. 19: Modifiche alla legge regionale 15 ottobre 2001, n. 20 "Norme in materia di organizzazione e di personale della Regione". | 1 | oldest version available: 30 October 2026 |
| `lr-2005-20/` | L.R. 1 agosto 2005, n. 20: Modifica alla legge regionale 24 dicembre 1998, n. 45 "Norme per il riordino del trasporto pubblico regionale e locale nelle Marche" | 1 | oldest version available: 30 October 2026 |
| `lr-2005-21/` | L.R. 15 settembre 2005, n. 21: Disciplina per l'applicazione delle sanzioni amministrative in materia di interventi cofinanziati dal Fondo Europeo Agricolo di O | 1 | oldest version available: 30 October 2026 |
| `lr-2005-23/` | L.R. 11 ottobre 2005, n. 23: Rendiconto generale dell'amministrazione per l'anno 2004. | 1 | oldest version available: 30 October 2026 |
| `lr-2005-24/` | L.R. 11 ottobre 2005, n. 24: Assestamento del bilancio 2005. | 1 | oldest version available: 30 October 2026 |
| `lr-2005-26/` | L.R. 1 dicembre 2005, n. 26: Istituzione della "Giornata delle Marche" | 1 | oldest version available: 30 October 2026 |
| `lr-2005-27/` | L.R. 1 dicembre 2005, n. 27: Modificazioni alla legge regionale 5 agosto 1996, n. 34 "Norme per le nomine e designazioni di spettanza della Regione" | 1 | oldest version available: 30 October 2026 |
| `lr-2005-28/` | L.R. 9 dicembre 2005, n. 28: Istituzione del registro degli amministratori di condominio e di immobili. | 1 | oldest version available: 30 October 2026 |
| `lr-2005-29/` | L.R. 9 dicembre 2005, n. 29: Società per la valorizzazione del patrimonio immobiliare regionale. | 1 | oldest version available: 30 October 2026 |
| `lr-2005-31/` | L.R. 14 dicembre 2005, n. 31: Autorizzazione all'esercizio provvisorio del bilancio per l'anno 2006. | 1 | oldest version available: 30 October 2026 |
| `lr-2005-35/` | L.R. 16 dicembre 2005, n. 35: Riordino o soppressione di Enti e Agenzie operanti in materia di competenza regionale. | 1 | oldest version available: 30 October 2026 |
| `lr-2005-36/` | L.R. 16 dicembre 2005, n. 36: Riordino del sistema regionale delle politiche abitative. | 1 | oldest version available: 30 October 2026 |
| `lr-2006-1/` | L.R. 24 gennaio 2006, n. 1: Modifiche alla l.r. 16 aprile 2003, n. 5 "Provvedimenti per favorire lo sviluppo della cooperazione". | 1 | oldest version available: 30 October 2026 |
| `lr-2006-2/` | L.R. 10 febbraio 2006, n. 2: Disposizioni per la formazione del bilancio annuale e pluriennale della Regione (Legge Finanziaria 2006). | 1 | oldest version available: 30 October 2026 |
| `lr-2006-3/` | L.R. 10 febbraio 2006, n. 3: Bilancio di previsione per l'anno 2006 ed adozione del bilancio pluriennale per il triennio 2006/2008. | 1 | oldest version available: 30 October 2026 |
| `lr-2006-4/` | L.R. 10 febbraio 2006, n. 4: Modifiche ed integrazioni alla legge regionale 25 gennaio 2005, n. 2 "Norme regionali per l'occupazione, la tutela e la qualità del | 1 | oldest version available: 30 October 2026 |
| `lr-2006-5/` | L.R. 9 giugno 2006, n. 5: Disciplina delle derivazioni di acqua pubblica e delle occupazioni del demanio idrico. | 1 | oldest version available: 30 October 2026 |
| `lr-2006-6/` | L.R. 9 giugno 2006, n. 6: Modifiche alla legge regionale 10 agosto 1988, n. 34: "Finanziamento delle attività dei gruppi consiliari" e alla legge regionale 8 ag | 1 | oldest version available: 30 October 2026 |
| `lr-2006-7/` | L.R. 23 giugno 2006, n. 7: Modificazioni alla legge regionale 28 aprile 1994, n. 15 concernente: "Norme per l'istituzione e gestione delle aree protette natural | 1 | oldest version available: 30 October 2026 |
| `lr-2006-9/` | L.R. 11 luglio 2006, n. 9: Testo unico delle norme regionali in materia di turismo | 1 | oldest version available: 30 October 2026 |
| `lr-2006-10/` | L.R. 2 agosto 2006, n. 10: Modifiche alla legge regionale 23 febbraio 2005, n. 8: "Norme in materia di accertamento della regolarità contributiva delle imprese" | 1 | oldest version available: 30 October 2026 |
| `lr-2006-11/` | L.R. 2 agosto 2006, n. 11: Istituzione dell'Ente parco regionale del Conero. | 1 | oldest version available: 30 October 2026 |
| `lr-2006-12/` | L.R. 2 agosto 2006, n. 12: Rendiconto generale dell'Amministrazione per l'anno 2005. | 1 | oldest version available: 30 October 2026 |
| `lr-2006-13/` | L.R. 2 agosto 2006, n. 13: Assestamento del bilancio 2006. | 1 | oldest version available: 30 October 2026 |
| `lr-2006-14/` | L.R. 2 ottobre 2006, n. 14: Disposizioni sulla partecipazione della Regione Marche al processo normativo comunitario e sulle procedure relative all'attuazione d | 1 | oldest version available: 30 October 2026 |
| `lr-2006-15/` | L.R. 15 dicembre 2006, n. 15: Autorizzazione all'esercizio provvisorio del bilancio per l'anno 2007 | 1 | oldest version available: 30 October 2026 |
| `lr-2006-16/` | L.R. 15 dicembre 2006, n. 16: Modifica alla legge regionale 14 luglio 2004, n. 15 "Disciplina delle funzioni in materia di difesa della costa" | 1 | oldest version available: 30 October 2026 |
| `lr-2006-20/` | L.R. 21 dicembre 2006, n. 20: Disposizioni in materia di tributi regionali | 1 | oldest version available: 30 October 2026 |
| `lr-2006-21/` | L.R. 21 dicembre 2006, n. 21: Disposizioni in materia di riordino della disciplina dell'Istituto ricovero e cura a carattere scientifico "INRCA" di Ancona | 1 | oldest version available: 30 October 2026 |
| `lr-2006-22/` | L.R. 27 dicembre 2006, n. 22: Modificazioni ed integrazioni alla l.r. 16 dicembre 2005, n. 36: "Riordino del sistema regionale delle politiche abitative" | 1 | oldest version available: 30 October 2026 |
| `lr-2007-1/` | L.R. 5 febbraio 2007, n. 1: Modifiche alla legge regionale 13 maggio 2004, n. 11 concernente: "Norme in materia di pesca marittima e acquacoltura" e alla legge | 1 | oldest version available: 30 October 2026 |
| `lr-2007-2/` | L.R. 23 febbraio 2007, n. 2: Disposizioni per la formazione del Bilancio annuale e pluriennale della Regione (Legge finanziaria 2007). | 1 | oldest version available: 30 October 2026 |
| `lr-2007-3/` | L.R. 23 febbraio 2007, n. 3: Bilancio di previsione per l'anno 2007 ed adozione del bilancio pluriennale per il triennio 2007/2009 | 1 | oldest version available: 30 October 2026 |
| `lr-2007-4/` | L.R. 10 aprile 2007, n. 4: Disciplina del Consiglio delle autonomie locali | 1 | oldest version available: 30 October 2026 |
| `lr-2007-5/` | L.R. 14 maggio 2007, n. 5: Modifiche ed integrazioni alla legge regionale 16 dicembre 2005, n. 36 (Riordino del sistema regionale delle politiche abitative) e a | 1 | oldest version available: 30 October 2026 |
| `lr-2007-6/` | L.R. 12 giugno 2007, n. 6: Modifiche ed integrazioni alle leggi regionali 14 aprile 2004, n. 7, 5 agosto 1992, n. 34, 28 ottobre 1999, n. 28, 23 febbraio 2005, | 1 | oldest version available: 30 October 2026 |
| `lr-2007-7/` | L.R. 16 luglio 2007, n. 7: Modifiche alla legge regionale 1° dicembre 1997, n. 71 "Norme per la disciplina delle attività estrattive" | 1 | oldest version available: 30 October 2026 |
| `lr-2007-8/` | L.R. 16 luglio 2007, n. 8: Disciplina delle deroghe previste dalla direttiva 79/409/CEE del 2 aprile 1979 e dell'articolo 19 bis della legge 11 febbraio 1992, n | 1 | oldest version available: 30 October 2026 |
| `lr-2007-9/` | L.R. 17 luglio 2007, n. 9: Modifiche alla deliberazione legislativa approvata dal Consiglio regionale nella seduta del 3 luglio 2007, n. 71 "Modifiche alla legg | 1 | oldest version available: 30 October 2026 |
| `lr-2007-10/` | L.R. 2 agosto 2007, n. 10: Riconoscimento dell'Associazione dei consiglieri della Regione Marche cessati dal mandato | 1 | oldest version available: 30 October 2026 |
| `lr-2007-12/` | L.R. 22 ottobre 2007, n. 12: Anticipazione finanziaria al Comune di Falconara Marittima | 1 | oldest version available: 30 October 2026 |
| `lr-2007-13/` | L.R. 23 ottobre 2007, n. 13: Rendiconto generale dell'amministrazione per l'anno 2006 | 1 | oldest version available: 30 October 2026 |
| `lr-2007-14/` | L.R. 23 ottobre 2007, n. 14: Assestamento del bilancio 2007 | 1 | oldest version available: 30 October 2026 |
| `lr-2007-17/` | L.R. 20 novembre 2007, n. 17: Disciplina dell'attività di acconciatore e di estetista | 1 | oldest version available: 30 October 2026 |
| `lr-2007-18/` | L.R. 30 novembre 2007, n. 18: Deroghe al vincolo di indivisibilità per i terreni della proprietà diretto-coltivatrice | 1 | oldest version available: 30 October 2026 |
| `lr-2007-19/` | L.R. 27 dicembre 2007, n. 19: Disposizioni per la formazione del bilancio annuale e pluriennale della Regione (Legge finanziaria 2008) | 1 | oldest version available: 30 October 2026 |
| `lr-2007-20/` | L.R. 27 dicembre 2007, n. 20: Bilancio di previsione per l'anno 2008 ed adozione del bilancio pluriennale per il triennio 2008/2010 | 1 | oldest version available: 30 October 2026 |
| `lr-2008-1/` | L.R. 29 gennaio 2008, n. 1: Modifiche alla legge regionale 16 dicembre 2005, n. 36 "Riordino del sistema regionale delle politiche abitative", alla legge region | 1 | oldest version available: 30 October 2026 |
| `lr-2008-2/` | L.R. 5 febbraio 2008, n. 2: Modifiche alla Legge regionale 27 luglio 1998, n. 22: "Diritti della partoriente, del nuovo nato e del bambino spedalizzato" | 1 | oldest version available: 30 October 2026 |
| `lr-2008-4/` | L.R. 26 febbraio 2008, n. 4: Trasferimento ai Comuni di alloggi di edilizia sovvenzionata realizzati ai sensi dell'articolo 7 della legge 30 marzo 1998, n. 61: | 1 | oldest version available: 30 October 2026 |
| `lr-2008-5/` | L.R. 26 febbraio 2008, n. 5: Riordino delle istituzioni pubbliche di assistenza e beneficenza (IPAB) e disciplina delle Aziende pubbliche di servizi alla person | 1 | oldest version available: 30 October 2026 |
| `lr-2008-6/` | L.R. 29 aprile 2008, n. 6: Proroga delle funzioni del Garante per l'infanzia e l'adolescenza | 1 | oldest version available: 30 October 2026 |
| `lr-2008-7/` | L.R. 29 aprile 2008, n. 7: Modifiche ed integrazioni alla legge regionale 10 agosto 1988, n. 34 "Finanziamento delle attività dei gruppi consiliari" | 1 | oldest version available: 30 October 2026 |
| `lr-2008-8/` | L.R. 29 aprile 2008, n. 8: Interventi di sostegno e promozione del commercio equo e solidale | 1 | oldest version available: 30 October 2026 |
| `lr-2008-10/` | L.R. 27 maggio 2008, n. 10: Modifica della legge regionale 2 agosto 1984, n. 20 "Disciplina delle indennità spettanti agli amministratori degli enti pubblici op | 1 | oldest version available: 30 October 2026 |
| `lr-2008-11/` | L.R. 27 maggio 2008, n. 11: Interpretazione autentica dell'articolo 2 della legge regionale 29 ottobre 2004, n. 23 "Norme sulla sanatoria degli abusi edilizi" | 1 | oldest version available: 30 October 2026 |
| `lr-2008-12/` | L.R. 27 maggio 2008, n. 12: Modifiche alla legge regionale 27 dicembre 2007, n. 19 "Disposizioni per la formazione del bilancio annuale e pluriennale della Regi | 1 | oldest version available: 30 October 2026 |
| `lr-2008-13/` | L.R. 10 giugno 2008, n. 13: Gestione del trasporto sanitario. Modificazioni ed integrazioni alla legge regionale 30 ottobre 1998, n. 36 "Sistema di emergenza sa | 1 | oldest version available: 30 October 2026 |
| `lr-2008-14/` | L.R. 17 giugno 2008, n. 14: Norme per l'edilizia sostenibile | 1 | oldest version available: 30 October 2026 |
| `lr-2008-15/` | L.R. 26 giugno 2008, n. 15: Disciplina del Consiglio regionale dell'economia e del lavoro (CREL) | 1 | oldest version available: 30 October 2026 |
| `lr-2008-17/` | L.R. 26 giugno 2008, n. 17: Adesione della Regione ad enti, fondazioni, associazioni, comitati ed altri organismi | 1 | oldest version available: 30 October 2026 |
| `lr-2008-18/` | L.R. 1 luglio 2008, n. 18: Norme in materia di Comunità montane e di esercizio associato di funzioni e servizi comunali | 1 | oldest version available: 30 October 2026 |
| `lr-2008-19/` | L.R. 15 luglio 2008, n. 19: Norme relative all'impiego dei fondi assegnati alla Regione ai sensi dell'articolo 2, comma 107, lettera e), della legge 24 dicembre | 1 | oldest version available: 30 October 2026 |
| `lr-2008-20/` | L.R. 15 luglio 2008, n. 20: Modifiche alla legge regionale 20 gennaio 1997, n. 15 "Disciplina del tributo speciale per il deposito in discarica dei rifiuti soli | 1 | oldest version available: 30 October 2026 |
| `lr-2008-21/` | L.R. 15 luglio 2008, n. 21: Modifiche alla legge regionale 26 giugno 2008, n. 15 "Disciplina del Consiglio regionale dell'economia e del lavoro (CREL)" | 1 | oldest version available: 30 October 2026 |
| `lr-2008-22/` | L.R. 15 luglio 2008, n. 22: Modifica all'articolo 6, comma 4, della legge regionale 10 agosto 1988, n. 34 "Finanziamento dell'attività dei gruppi consiliari" | 1 | oldest version available: 30 October 2026 |
| `lr-2008-23/` | L.R. 28 luglio 2008, n. 23: Garante regionale dei diritti della persona | 1 | oldest version available: 30 October 2026 |
| `lr-2008-24/` | L.R. 29 luglio 2008, n. 24: Rendiconto generale dell'Amministrazione per l'anno 2007 | 1 | oldest version available: 30 October 2026 |
| `lr-2008-25/` | L.R. 29 luglio 2008, n. 25: Assestamento del bilancio 2008 | 1 | oldest version available: 30 October 2026 |
| `lr-2008-26/` | L.R. 4 agosto 2008, n. 26: Modifiche alla legge regionale 30 giugno 2003, n. 14 "Riorganizzazione della struttura amministrativa del Consiglio regionale" | 1 | oldest version available: 30 October 2026 |
| `lr-2008-27/` | L.R. 4 agosto 2008, n. 27: Modifiche alla legge regionale 15 ottobre 2001, n. 20 "Norme in materia di organizzazione e di personale della Regione", alla legge r | 1 | oldest version available: 30 October 2026 |
| `lr-2008-28/` | L.R. 13 ottobre 2008, n. 28: Sistema regionale integrato degli interventi a favore dei soggetti adulti e minorenni sottoposti a provvedimenti dell'Autorità giud | 1 | oldest version available: 30 October 2026 |
| `lr-2008-30/` | L.R. 30 ottobre 2008, n. 30: Disciplina delle attività regionali in materia di commercio estero, promozione economica ed internazionalizzazione delle imprese e | 1 | oldest version available: 30 October 2026 |
| `lr-2008-31/` | L.R. 11 novembre 2008, n. 31: Interventi per la valorizzazione della funzione sociale ed educativa svolta dagli oratori e dagli enti religiosi che svolgono atti | 1 | oldest version available: 30 October 2026 |
| `lr-2008-32/` | L.R. 11 novembre 2008, n. 32: Interventi contro la violenza sulle donne | 1 | oldest version available: 30 October 2026 |
| `lr-2008-33/` | L.R. 18 novembre 2008, n. 33: Norme in materia di costi per la prevenzione degli infortuni e la tutela della salute nei cantieri temporanei o mobili | 1 | oldest version available: 30 October 2026 |
| `lr-2008-35/` | L.R. 4 dicembre 2008, n. 35: Riordino del Consorzio di sviluppo industriale delle Valli del Tronto, dell'Aso e del Tesino | 1 | oldest version available: 30 October 2026 |
| `lr-2008-36/` | L.R. 16 dicembre 2008, n. 36: Legge comunitaria regionale 2008 | 1 | oldest version available: 30 October 2026 |
| `lr-2008-37/` | L.R. 24 dicembre 2008, n. 37: Disposizioni per la formazione del bilancio annuale 2009 e pluriennale 2009/2011 della Regione (Legge finanziaria 2009) | 1 | oldest version available: 30 October 2026 |
| `lr-2008-38/` | L.R. 24 dicembre 2008, n. 38: Bilancio di previsione per l'anno 2009 ed adozione del Bilancio pluriennale per il triennio 2009/2011 | 1 | oldest version available: 30 October 2026 |
| `lr-2009-2/` | L.R. 2 marzo 2009, n. 2: Modifiche agli articoli 9 e 10 della legge regionale 24 dicembre 2008, n. 37 "Legge finanziaria 2009" | 1 | oldest version available: 30 October 2026 |
| `lr-2009-3/` | L.R. 2 marzo 2009, n. 3: Integrazione alla legge regionale 11 luglio 2006, n. 9 "Testo unico delle norme regionali in materia di turismo" | 1 | oldest version available: 30 October 2026 |
| `lr-2009-5/` | L.R. 17 marzo 2009, n. 5: Partecipazione della Regione alla Rete europea degli enti locali e regionali per l'attuazione della convenzione europea del paesaggio | 1 | oldest version available: 30 October 2026 |
| `lr-2009-6/` | L.R. 17 marzo 2009, n. 6: Attività della società di gestione dell'aeroporto delle Marche. Legge regionale 24 marzo 1986, n. 6 | 1 | oldest version available: 30 October 2026 |
| `lr-2009-7/` | L.R. 31 marzo 2009, n. 7: Sostegno del cinema e dell'audiovisivo | 1 | oldest version available: 30 October 2026 |
| `lr-2009-8/` | L.R. 3 aprile 2009, n. 8: Ulteriori modifiche all'articolo 9 della legge regionale 24 dicembre 2008, n. 37 "Legge finanziaria 2009" | 1 | oldest version available: 30 October 2026 |
| `lr-2009-9/` | L.R. 3 aprile 2009, n. 9: Modifiche alle leggi regionali 17 maggio 1999, n. 10, 16 dicembre 2005, n. 36 e 29 gennaio 2008, n. 1 in materia di riordino del siste | 1 | oldest version available: 30 October 2026 |
| `lr-2009-11/` | L.R. 3 aprile 2009, n. 11: Disciplina degli interventi regionali in materia di spettacolo | 1 | oldest version available: 30 October 2026 |
| `lr-2009-12/` | L.R. 26 maggio 2009, n. 12: Sanzioni in materia di trasporto pubblico locale | 1 | oldest version available: 30 October 2026 |
| `lr-2009-13/` | L.R. 26 maggio 2009, n. 13: Disposizioni a sostegno dei diritti e dell'integrazione dei cittadini stranieri immigrati | 1 | oldest version available: 30 October 2026 |
| `lr-2009-15/` | L.R. 7 luglio 2009, n. 15: Norme in materia di delocalizzazioni e incentivi alle imprese | 1 | oldest version available: 30 October 2026 |
| `lr-2009-16/` | L.R. 7 luglio 2009, n. 16: Norme a sostegno del consumo dei prodotti agricoli di origine regionale | 1 | oldest version available: 30 October 2026 |
| `lr-2009-17/` | L.R. 28 luglio 2009, n. 17: Rendiconto generale dell'Amministrazione per l'anno 2008 | 1 | oldest version available: 30 October 2026 |
| `lr-2009-18/` | L.R. 28 luglio 2009, n. 18: Assestamento del bilancio 2009 | 1 | oldest version available: 30 October 2026 |
| `lr-2009-19/` | L.R. 4 agosto 2009, n. 19: Riconoscimento delle associazioni dei marchigiani residenti in altre regioni d'Italia | 1 | oldest version available: 30 October 2026 |
| `lr-2009-20/` | L.R. 4 agosto 2009, n. 20: Modifiche alla legge regionale 1° luglio 2008, n. 18 "Norme in materia di Comunità montane e di esercizio associato di funzioni e ser | 1 | oldest version available: 30 October 2026 |
| `lr-2009-21/` | L.R. 22 settembre 2009, n. 21: Istituzione dell'Azienda ospedaliera "Ospedali Riuniti Marche Nord" | 1 | oldest version available: 30 October 2026 |
| `lr-2009-23/` | L.R. 12 ottobre 2009, n. 23: Modifica alla legge regionale 2 settembre 1997, n. 60 "Istituzione dell'Agenzia regionale per la protezione ambientale delle Marche | 1 | oldest version available: 30 October 2026 |
| `lr-2009-24/` | L.R. 12 ottobre 2009, n. 24: Disciplina regionale in materia di gestione integrata dei rifiuti e bonifica dei siti inquinati | 1 | oldest version available: 30 October 2026 |
| `lr-2009-25/` | L.R. 26 ottobre 2009, n. 25: Misure di sostegno alla trasmissione d'impresa in favore di lavoratori riuniti in cooperativa per finalità di salvaguardia occupazi | 1 | oldest version available: 30 October 2026 |
| `lr-2009-26/` | L.R. 2 novembre 2009, n. 26: Norme per la valorizzazione degli archivi storici dei partiti politici, dei movimenti politici, di personalità politiche e dei sind | 1 | oldest version available: 30 October 2026 |
| `lr-2009-28/` | L.R. 30 novembre 2009, n. 28: Modifiche alla legge regionale 26 maggio 2009, n. 13 "Disposizioni a sostegno dei diritti e dell'integrazione dei cittadini strani | 1 | oldest version available: 30 October 2026 |
| `lr-2009-30/` | L.R. 7 dicembre 2009, n. 30: Nuove norme in materia di attività estrattive e modifiche ed integrazioni alla legge regionale 1° dicembre 1997, n. 71 "Norme per l | 1 | oldest version available: 30 October 2026 |
| `lr-2009-31/` | L.R. 22 dicembre 2009, n. 31: Disposizioni per la formazione del bilancio annuale 2010 e pluriennale 2010/2012 della Regione (Legge finanziaria 2010) | 1 | oldest version available: 30 October 2026 |
| `lr-2009-32/` | L.R. 22 dicembre 2009, n. 32: Bilancio di previsione per l'anno 2010 ed adozione del bilancio pluriennale per il triennio 2010/2012 | 1 | oldest version available: 30 October 2026 |
| `lr-2009-33/` | L.R. 22 dicembre 2009, n. 33: Modifiche alle leggi regionali 15 ottobre 2001, n. 20 "Norme in materia di organizzazione e di personale della Regione", 10 agosto | 1 | oldest version available: 30 October 2026 |
| `lr-2010-2/` | L.R. 18 gennaio 2010, n. 2: Istituzione della rete escursionistica della Regione Marche | 1 | oldest version available: 30 October 2026 |
| `lr-2010-3/` | L.R. 18 gennaio 2010, n. 3: Modifica alla legge regionale 9 giugno 2006, n. 5 "Disciplina delle derivazioni di acqua pubblica e delle occupazioni del demanio id | 1 | oldest version available: 30 October 2026 |
| `lr-2010-4/` | L.R. 9 febbraio 2010, n. 4: Norme in materia di beni e attività culturali | 1 | oldest version available: 30 October 2026 |
| `lr-2010-5/` | L.R. 9 febbraio 2010, n. 5: Valorizzazione dei luoghi della memoria storica risorgimentale relativi alla battaglia di Tolentino e Castelfidardo e divulgazione d | 1 | oldest version available: 30 October 2026 |
| `lr-2010-7/` | L.R. 11 febbraio 2010, n. 7: Norme per l'attuazione delle funzioni amministrative in materia di demanio marittimo | 1 | oldest version available: 30 October 2026 |
| `lr-2010-8/` | L.R. 11 febbraio 2010, n. 8: Disposizioni contro le discriminazioni determinate dall'orientamento sessuale o dall'identità di genere | 1 | oldest version available: 30 October 2026 |
| `lr-2010-10/` | L.R. 27 luglio 2010, n. 10: Modifica alla legge regionale 10 agosto 1998, n. 30 "Interventi a favore della famiglia" e disposizioni riguardanti la trasformazion | 1 | oldest version available: 30 October 2026 |
| `lr-2010-11/` | L.R. 3 agosto 2010, n. 11: Misure urgenti in materia di contenimento della spesa | 1 | oldest version available: 30 October 2026 |
| `lr-2010-12/` | L.R. 4 agosto 2010, n. 12: Modifica alla legge regionale 14 aprile 2004, n. 7 "Disciplina della procedura di valutazione di impatto ambientale" | 1 | oldest version available: 30 October 2026 |
| `lr-2010-13/` | L.R. 11 ottobre 2010, n. 13: Modifica alla legge regionale 18 aprile 1986, n. 9 "Commissione regionale per le pari opportunità tra uomo e donna" | 1 | oldest version available: 30 October 2026 |
| `lr-2010-14/` | L.R. 25 ottobre 2010, n. 14: Soppressione dell'Ente regionale per le manifestazioni fieristiche (ERF) | 1 | oldest version available: 30 October 2026 |
| `lr-2010-15/` | L.R. 15 novembre 2010, n. 15: Rendiconto generale dell'Amministrazione per l'anno 2009 | 1 | oldest version available: 30 October 2026 |
| `lr-2010-16/` | L.R. 15 novembre 2010, n. 16: Assestamento del bilancio 2010 | 1 | oldest version available: 30 October 2026 |
| `lr-2010-17/` | L.R. 22 novembre 2010, n. 17: Modifiche alla legge regionale 20 giugno 2003, n. 13 "Riorganizzazione del Servizio sanitario regionale" | 1 | oldest version available: 30 October 2026 |
| `lr-2010-18/` | L.R. 6 dicembre 2010, n. 18: Modifiche alla Legge regionale 18 gennaio 2010, n. 2 "Istituzione della rete escursionistica della Regione Marche" | 1 | oldest version available: 30 October 2026 |
| `lr-2010-20/` | L.R. 28 dicembre 2010, n. 20: Disposizioni per la formazione del Bilancio annuale 2011 e pluriennale 2011/2013 della Regione (Legge Finanziaria 2011) | 1 | oldest version available: 30 October 2026 |
| `lr-2010-21/` | L.R. 28 dicembre 2010, n. 21: Bilancio di previsione per l'anno 2011 ed adozione del bilancio pluriennale per il triennio 2011/2013 | 1 | oldest version available: 30 October 2026 |
| `lr-2011-3/` | L.R. 10 febbraio 2011, n. 3: Modifica alla Legge regionale 17 gennaio 2011, n. 1 "Proroga degli Organi degli ERSU" | 1 | oldest version available: 30 October 2026 |
| `lr-2011-4/` | L.R. 4 aprile 2011, n. 4: Criteri di premialità connessi alla tutela della salute e della sicurezza nei luoghi di lavoro nelle procedure di aggiudicazione di la | 1 | oldest version available: 30 October 2026 |
| `lr-2011-5/` | L.R. 4 aprile 2011, n. 5: Interventi regionali per il sostegno e la promozione dei locali storici | 1 | oldest version available: 30 October 2026 |
| `lr-2011-6/` | L.R. 11 aprile 2011, n. 6: Criteri gestione del trasporto sanitario modifiche ed integrazioni alla legge regionale 30 ottobre 1998, n. 36: "Sistema di emergenza | 1 | oldest version available: 30 October 2026 |
| `lr-2011-7/` | L.R. 29 aprile 2011, n. 7: Attuazione della Direttiva 2006/123/CE sui servizi nel mercato interno e altre disposizioni per l'applicazione di norme dell'Unione E | 1 | oldest version available: 30 October 2026 |
| `lr-2011-9/` | L.R. 9 maggio 2011, n. 9: Modifiche alle Leggi regionali: 14 aprile 2004, n. 7 "Disciplina della procedura di valutazione di impatto ambientale", 12 ottobre 200 | 1 | oldest version available: 30 October 2026 |
| `lr-2011-10/` | L.R. 9 maggio 2011, n. 10: Norme sulle sponsorizzazioni, sui patrocini e compartecipazioni dell'Assemblea legislativa regionale | 1 | oldest version available: 30 October 2026 |
| `lr-2011-11/` | L.R. 24 maggio 2011, n. 11: Disposizioni per l'ottimizzazione dell'attività amministrativa e il contenimento della spesa della Regione e degli Enti del Servizio | 1 | oldest version available: 30 October 2026 |
| `lr-2011-12/` | L.R. 17 giugno 2011, n. 12: Riordino degli enti regionali per l'abitazione pubblica (ERAP) | 1 | oldest version available: 30 October 2026 |
| `lr-2011-13/` | L.R. 6 luglio 2011, n. 13: Modifiche alle leggi regionali: 1° giugno 1999, n. 17 "Costituzione società regionale di sviluppo", 2 settembre 1997, n. 60 "Istituzi | 1 | oldest version available: 30 October 2026 |
| `lr-2011-14/` | L.R. 15 luglio 2011, n. 14: Proroga della scadenza del Comitato Regionale per le comunicazioni | 1 | oldest version available: 30 October 2026 |
| `lr-2011-15/` | L.R. 18 luglio 2011, n. 15: Modifiche alla Legge Regionale 5 gennaio 1995, n. 7 "Norme per la protezione della fauna selvatica e per la tutela dell'equilibrio a | 1 | oldest version available: 30 October 2026 |
| `lr-2011-16/` | L.R. 1 agosto 2011, n. 16: Modifica alla Legge regionale 13 ottobre 2008, n. 28: "Sistema regionale integrato degli interventi a favore dei soggetti adulti e mi | 1 | oldest version available: 30 October 2026 |
| `lr-2011-17/` | L.R. 1 agosto 2011, n. 17: Ulteriori modifiche della Legge Regionale 20 giugno 2003, n. 13: "Riorganizzazione del Servizio Sanitario Regionale", della Legge reg | 1 | oldest version available: 30 October 2026 |
| `lr-2011-18/` | L.R. 25 ottobre 2011, n. 18: Attribuzione delle funzioni in materia di servizio di gestione integrata dei rifiuti urbani e modifiche alla legge regionale 12 ott | 1 | oldest version available: 30 October 2026 |
| `lr-2011-19/` | L.R. 31 ottobre 2011, n. 19: Rendiconto generale della Regione per l'anno 2010 | 1 | oldest version available: 30 October 2026 |
| `lr-2011-20/` | L.R. 31 ottobre 2011, n. 20: Assestamento del Bilancio 2011 | 1 | oldest version available: 30 October 2026 |
| `lr-2011-21/` | L.R. 14 novembre 2011, n. 21: Disposizioni regionali in materia di multifunzionalità dell'azienda agricola e diversificazione in agricoltura | 1 | oldest version available: 30 October 2026 |
| `lr-2011-23/` | L.R. 23 novembre 2011, n. 23: Norme urgenti in materia di passaggio al digitale terrestre | 1 | oldest version available: 30 October 2026 |
| `lr-2011-24/` | L.R. 5 dicembre 2011, n. 24: Norme in materia di politiche giovanili | 1 | oldest version available: 30 October 2026 |
| `lr-2011-25/` | L.R. 5 dicembre 2011, n. 25: Disciplina dell'attività di tintolavanderia | 1 | oldest version available: 30 October 2026 |
| `lr-2011-27/` | L.R. 23 dicembre 2011, n. 27: Modifiche alla Legge regionale 13 marzo 1995, N. 23: "Disposizioni in materia di trattamento indennitario dei Consiglieri Regional | 1 | oldest version available: 30 October 2026 |
| `lr-2011-28/` | L.R. 28 dicembre 2011, n. 28: Disposizioni per la formazione del bilancio annuale 2012 e pluriennale 2012/2014 della Regione (Legge Finanziaria 2012) | 1 | oldest version available: 30 October 2026 |
| `lr-2011-29/` | L.R. 28 dicembre 2011, n. 29: Bilancio di previsione per l'anno 2012 ed adozione del Bilancio Pluriennale per il triennio 2012/2014 | 1 | oldest version available: 30 October 2026 |
| `lr-2011-30/` | L.R. 28 dicembre 2011, n. 30: Disposizioni in materia di risorse idriche e di servizio idrico integrato | 1 | oldest version available: 30 October 2026 |
| `lr-2012-1/` | L.R. 19 gennaio 2012, n. 1: Modifiche alla Legge regionale 31 ottobre 2011, n. 20 "Assestamento di Bilancio 2011" | 1 | oldest version available: 30 October 2026 |
| `lr-2012-2/` | L.R. 20 marzo 2012, n. 2: Abrogazione dell'articolo 10 della Legge regionale 31 ottobre 2011, n. 20: "Assestamento di bilancio 2011" e modifica dell'articolo 27 | 1 | oldest version available: 30 October 2026 |
| `lr-2012-4/` | L.R. 26 marzo 2012, n. 4: Modifiche alle Leggi regionali: 12 ottobre 2009, n. 24: "Disciplina regionale in materia di gestione integrata dei rifiuti e bonifica | 1 | oldest version available: 30 October 2026 |
| `lr-2012-5/` | L.R. 2 aprile 2012, n. 5: Disposizioni regionali in materia di sport e tempo libero | 1 | oldest version available: 30 October 2026 |
| `lr-2012-6/` | L.R. 10 aprile 2012, n. 6: Osservatorio Epidemiologico Regionale. Registri regionali delle cause di morte e di patologia | 1 | oldest version available: 30 October 2026 |
| `lr-2012-7/` | L.R. 10 aprile 2012, n. 7: Ulteriori modifiche alla Legge Regionale 5 gennaio 1995, n. 7: "Norme per la protezione della fauna selvatica e per la tutela dell'eq | 1 | oldest version available: 30 October 2026 |
| `lr-2012-8/` | L.R. 20 aprile 2012, n. 8: Attività della Regione Marche per l'affermazione dei valori del ricordo del martirio e dell'esodo Giuliano-Dalmata-Istriano | 1 | oldest version available: 30 October 2026 |
| `lr-2012-9/` | L.R. 20 aprile 2012, n. 9: Modifiche alle Leggi regionali: 20 gennaio 1997, N. 15: "Disciplina del tributo speciale per il deposito in discarica dei rifiuti sol | 1 | oldest version available: 30 October 2026 |
| `lr-2012-10/` | L.R. 20 aprile 2012, n. 10: Ulteriori modifiche alla Legge Regionale 23 febbraio 2005, n. 8 "Norme in materia di accertamento della regolarità contributiva dell | 1 | oldest version available: 30 October 2026 |
| `lr-2012-11/` | L.R. 2 maggio 2012, n. 11: Disciplina dei Distretti Rurali e dei Distretti Agroalimentari di qualità | 1 | oldest version available: 30 October 2026 |
| `lr-2012-12/` | L.R. 14 maggio 2012, n. 12: Istituzione della Stazione Unica Appaltante della Regione Marche (SUAM) | 1 | oldest version available: 30 October 2026 |
| `lr-2012-13/` | L.R. 14 maggio 2012, n. 13: Riordino degli Enti di gestione dei Parchi Naturali Regionali. Modifiche alla Legge regionale 28 aprile 1994, n. 15 "Norme per l'ist | 1 | oldest version available: 30 October 2026 |
| `lr-2012-14/` | L.R. 17 maggio 2012, n. 14: Modifica alla Legge regionale 25 gennaio 2005, n. 2 "Norme regionali per l'occupazione, la tutela e la qualità del lavoro" | 1 | oldest version available: 30 October 2026 |
| `lr-2012-16/` | L.R. 30 maggio 2012, n. 16: Offensiva sulla linea gotica estate-autunno 1944: valorizzazione dei documenti e dei luoghi | 1 | oldest version available: 30 October 2026 |
| `lr-2012-17/` | L.R. 30 maggio 2012, n. 17: Modifica alla legge regionale 15 ottobre 2001 n. 20 "Norme in materia di organizzazione e di personale della regione" | 1 | oldest version available: 30 October 2026 |
| `lr-2012-18/` | L.R. 4 giugno 2012, n. 18: Istituzione dell'ente regionale per l'abitazione pubblica delle Marche (ERAP Marche). Soppressione degli enti regionali per l'abitazi | 1 | oldest version available: 30 October 2026 |
| `lr-2012-20/` | L.R. 4 giugno 2012, n. 20: Modifiche alla legge regionale 23 febbraio 2005, n. 6: "Legge forestale regionale" | 1 | oldest version available: 30 October 2026 |
| `lr-2012-21/` | L.R. 11 giugno 2012, n. 21: Modifiche ed integrazioni alla legge regionale 22 ottobre 2001, n. 22: "Disciplina degli impianti di trasporto a fune in servizio pu | 1 | oldest version available: 30 October 2026 |
| `lr-2012-22/` | L.R. 29 giugno 2012, n. 22: Disposizioni per il personale dei consorzi di sviluppo industriale e modifica della legge regionale 15 novembre 2010, n. 16: "Assest | 1 | oldest version available: 30 October 2026 |
| `lr-2012-23/` | L.R. 23 luglio 2012, n. 23: Integrazione delle politiche di pari opportunità di genere nella Regione. Modifiche alla Legge regionale 5 agosto 1996, n. 34 "Norme | 1 | oldest version available: 30 October 2026 |
| `lr-2012-24/` | L.R. 23 luglio 2012, n. 24: Scadenza del consiglio di indirizzo e verifica
dell'istituto di ricovero e cura a carattere scientifico "INRCA" di Ancona. | 1 | oldest version available: 30 October 2026 |
| `lr-2012-26/` | L.R. 1 agosto 2012, n. 26: Misure urgenti in materia di contenimento della spesa | 1 | oldest version available: 30 October 2026 |
| `lr-2012-27/` | L.R. 1 agosto 2012, n. 27: Ulteriori modifiche alla Legge regionale 5 gennaio 1995, n. 7: "Norme per la protezione della fauna selvatica e per la tutela dell'eq | 1 | oldest version available: 30 October 2026 |
| `lr-2012-30/` | L.R. 19 ottobre 2012, n. 30: Individuazione delle aree non idonee all'installazione di impianti alimentati da biomasse o biogas e modifiche alla legge regionale | 1 | oldest version available: 30 October 2026 |
| `lr-2012-31/` | L.R. 12 novembre 2012, n. 31: Norme in materia di gestione dei corsi d'acqua | 1 | oldest version available: 30 October 2026 |
| `lr-2012-32/` | L.R. 19 novembre 2012, n. 32: Interventi in favore delle persone con disturbi specifici di apprendimento (DSA) | 1 | oldest version available: 30 October 2026 |
| `lr-2012-34/` | L.R. 26 novembre 2012, n. 34: Interventi per la valorizzazione del pensiero e dell'opera di Maria Montessori | 1 | oldest version available: 30 October 2026 |
| `lr-2012-35/` | L.R. 26 novembre 2012, n. 35: Disposizioni in materia di microzonazione sismica | 1 | oldest version available: 30 October 2026 |
| `lr-2012-38/` | L.R. 3 dicembre 2012, n. 38: Interventi per favorire lo sviluppo della mobilità ciclistica | 1 | oldest version available: 30 October 2026 |
| `lr-2012-41/` | L.R. 17 dicembre 2012, n. 41: Norme per la pubblicità e la trasparenza della situazione patrimoniale dei componenti gli organi della regione e dei titolari di c | 1 | oldest version available: 30 October 2026 |
| `lr-2012-42/` | L.R. 21 dicembre 2012, n. 42: Modifiche alla Legge regionale 13 marzo 1995, n. 23 "Disposizioni in materia di trattamento indennitario dei Consiglieri regionali | 1 | oldest version available: 30 October 2026 |
| `lr-2012-43/` | L.R. 21 dicembre 2012, n. 43: Modifiche alla legge regionale 10 agosto 1988, n. 34 "Finanziamento dell'attività dei gruppi consiliari" in attuazione del Decreto | 1 | oldest version available: 30 October 2026 |
| `lr-2012-44/` | L.R. 21 dicembre 2012, n. 44: Individuazione del limite demografico minimo delle Unioni dei Comuni e modifica alla Legge regionale 1° luglio 2008, n. 18 
"Norm | 1 | oldest version available: 30 October 2026 |
| `lr-2012-45/` | L.R. 27 dicembre 2012, n. 45: Disposizioni per la formazione del Bilancio annuale 2013 e pluriennale 2013/2015 della Regione (Legge Finanziaria 2013) | 1 | oldest version available: 30 October 2026 |
| `lr-2012-46/` | L.R. 27 dicembre 2012, n. 46: Bilancio di previsione per l'anno 2013 ed adozione del Bilancio Pluriennale per il triennio 2013/2015 | 1 | oldest version available: 30 October 2026 |
| `lr-2013-2/` | L.R. 5 febbraio 2013, n. 2: Norme in materia di rete ecologica delle Marche e di tutela del paesaggio e modifiche alla Legge Regionale 15 novembre 2010, n. 16 " | 1 | oldest version available: 30 October 2026 |
| `lr-2013-4/` | L.R. 8 febbraio 2013, n. 4: Modifiche alla Legge Regionale 5 aprile 1980, n. 18 "Norme sui referendum previsti dallo statuto" | 1 | oldest version available: 30 October 2026 |
| `lr-2013-5/` | L.R. 3 aprile 2013, n. 5: Norme in materia di raccolta e coltivazione dei tartufi e di valorizzazione del patrimonio tartufigeno | 1 | oldest version available: 30 October 2026 |
| `lr-2013-7/` | L.R. 30 aprile 2013, n. 7: Costituzione della società pubblica di progetto per la realizzazione della strada di grande comunicazione Fano-Grosseto | 1 | oldest version available: 30 October 2026 |
| `lr-2013-10/` | L.R. 10 maggio 2013, n. 10: Disposizioni di semplificazione e adeguamento della normativa regionale | 1 | oldest version available: 30 October 2026 |
| `lr-2013-12/` | L.R. 6 giugno 2013, n. 12: Disposizioni particolari per il sostegno dell'attività edilizia | 1 | oldest version available: 30 October 2026 |
| `lr-2013-13/` | L.R. 17 giugno 2013, n. 13: Riordino degli interventi in materia di Bonifica e di Irrigazione. Costituzione del Consorzio di Bonifica delle Marche e fusione dei | 1 | oldest version available: 30 October 2026 |
| `lr-2013-17/` | L.R. 9 luglio 2013, n. 17: Modifiche alla legge regionale 30 ottobre 1998, n. 36 "Sistema di Emergenza Sanitaria" | 1 | oldest version available: 30 October 2026 |
| `lr-2013-18/` | L.R. 22 luglio 2013, n. 18: Istituzione di un nuovo Comune mediante fusione dei Comuni di Castel Colonna, Monterado e Ripe, ai sensi dell'articolo 2, comma 1, l | 1 | oldest version available: 30 October 2026 |
| `lr-2013-20/` | L.R. 29 luglio 2013, n. 20: Disposizioni relative al pagamento dei debiti della Regione certi, liquidi ed esigibili, diversi da quelli finanziari e sanitari, ma | 1 | oldest version available: 30 October 2026 |
| `lr-2013-21/` | L.R. 29 luglio 2013, n. 21: Ulteriori modifiche alle Leggi Regionali 20 gennaio 1997, n. 15 "Disciplina del Tributo Speciale per il deposito in discarica dei ri | 1 | oldest version available: 30 October 2026 |
| `lr-2013-22/` | L.R. 29 luglio 2013, n. 22: Modifiche alla Legge Regionale 5 aprile 1980, n. 18 "Norme sui Referendum previsti dallo Statuto" e alla Legge Regionale 16 gennaio | 1 | oldest version available: 30 October 2026 |
| `lr-2013-23/` | L.R. 2 agosto 2013, n. 23: Modifiche alla Legge Regionale 28 Aprile 1994, N. 15: "Norme per l'Istituzione e Gestione delle Aree Protette Naturali" e alla Legge | 1 | oldest version available: 30 October 2026 |
| `lr-2013-25/` | L.R. 2 agosto 2013, n. 25: Modifiche alla Legge Regionale 5 Gennaio 1995, N. 7 "Norme per la Protezione della Fauna Selvatica e per la tutela dell'equilibrio am | 1 | oldest version available: 30 October 2026 |
| `lr-2013-26/` | L.R. 2 agosto 2013, n. 26: Disposizioni per gli Enti del Servizio Sanitario Regionale | 1 | oldest version available: 30 October 2026 |
| `lr-2013-27/` | L.R. 2 agosto 2013, n. 27: Approvazione dell'intesa tra le Regioni Emilia-Romagna e Marche concernente l'istituzione del Parco Interregionale del Sasso Simone e | 1 | oldest version available: 30 October 2026 |
| `lr-2013-29/` | L.R. 16 settembre 2013, n. 29: Riconoscimento della particolare specificità dell'attività multidisciplinare svolta dalla Lega del Filo d'Oro | 1 | oldest version available: 30 October 2026 |
| `lr-2013-30/` | L.R. 30 settembre 2013, n. 30: "Limes" - Territori di confine - Proposte e progetti condivisi e cofinanziati per lo sviluppo e l'integrazione delle aree di conf | 1 | oldest version available: 30 October 2026 |
| `lr-2013-33/` | L.R. 14 ottobre 2013, n. 33: Misure organizzative per il contenimento della spesa. Modifica delle leggi regionali 15 ottobre 2001, n. 20 "Norme in materia di or | 1 | oldest version available: 30 October 2026 |
| `lr-2013-35/` | L.R. 11 novembre 2013, n. 35: Norme in materia di Unioni montane e di esercizio associato delle funzioni dei Comuni montani | 1 | oldest version available: 30 October 2026 |
| `lr-2013-38/` | L.R. 18 novembre 2013, n. 38: Disciplina dell'attività di tatuaggio e piercing. | 1 | oldest version available: 30 October 2026 |
| `lr-2013-39/` | L.R. 18 novembre 2013, n. 39: Modifiche alla legge regionale 4 aprile 2011, n. 5 "Interventi regionali per il sostegno e la promozione di osterie, locande, tave | 1 | oldest version available: 30 October 2026 |
| `lr-2013-40/` | L.R. 25 novembre 2013, n. 40: Approvazione dell'intesa tra la Regione Umbria e la Regione Marche concernente il riordino dell'Istituto zooprofilattico speriment | 1 | oldest version available: 30 October 2026 |
| `lr-2013-41/` | L.R. 25 novembre 2013, n. 41: Interventi per il sostegno delle azioni di prevenzione della produzione dei rifiuti solidi urbani e modifica alla legge regionale | 1 | oldest version available: 30 October 2026 |
| `lr-2013-42/` | L.R. 25 novembre 2013, n. 42: Modifica alle leggi regionali 28 dicembre 2011, n. 28 "Disposizioni per la formazione del bilancio annuale 2012 e 
pluriennale 20 | 1 | oldest version available: 30 October 2026 |
| `lr-2013-43/` | L.R. 25 novembre 2013, n. 43: Modalità di esercizio delle medicine complementari. | 1 | oldest version available: 30 October 2026 |
| `lr-2013-44/` | L.R. 29 novembre 2013, n. 44: Assestamento di bilancio 2013 | 1 | oldest version available: 30 October 2026 |
| `lr-2013-45/` | L.R. 9 dicembre 2013, n. 45: Modifiche al Titolo VI della legge regionale 10 novembre 2009, n. 27 "Testo unico in materia di commercio" concernente il sistema f | 1 | oldest version available: 30 October 2026 |
| `lr-2013-46/` | L.R. 9 dicembre 2013, n. 46: Disposizioni finalizzate ad incentivare l'integrazione istituzionale e territoriale | 1 | oldest version available: 30 October 2026 |
| `lr-2013-47/` | L.R. 13 dicembre 2013, n. 47: Istituzione di un nuovo Comune mediante fusione dei Comuni di Colbordolo e Sant'Angelo in Lizzola, ai sensi dell'articolo 2, comma | 1 | oldest version available: 30 October 2026 |
| `lr-2013-48/` | L.R. 16 dicembre 2013, n. 48: Disposizioni in materia di manutenzione dei corsi d''acqua | 1 | oldest version available: 30 October 2026 |
| `lr-2013-49/` | L.R. 23 dicembre 2013, n. 49: Disposizioni per la formazione del bilancio annuale 2014 e pluriennale 2014/2016 della Regione (Legge finanziaria 2014) | 1 | oldest version available: 30 October 2026 |
| `lr-2013-50/` | L.R. 23 dicembre 2013, n. 50: Bilancio di previsione per l'anno 2014 ed adozione del bilancio pluriennale per il triennio 2014/2016 | 1 | oldest version available: 30 October 2026 |
| `lr-2013-51/` | L.R. 23 dicembre 2013, n. 51: Modifiche alla legge regionale 5 gennaio 1995, n. 7 "Norme per la protezione della fauna selvatica e per la tutela dell'equilibrio | 1 | oldest version available: 30 October 2026 |
| `lr-2014-1/` | L.R. 17 febbraio 2014, n. 1: Disciplina in materia di ordinamento della polizia locale | 1 | oldest version available: 30 October 2026 |
| `lr-2014-2/` | L.R. 24 febbraio 2014, n. 2: Sistema regionale per la difesa dall'inquinamento di idrocarburi o altre sostanze nocive causato da incidenti marini | 1 | oldest version available: 30 October 2026 |
| `lr-2014-4/` | L.R. 21 marzo 2014, n. 4: Interventi a favore della sicurezza stradale | 1 | oldest version available: 30 October 2026 |
| `lr-2014-5/` | L.R. 14 aprile 2014, n. 5: Modifiche alla legge regionale 11 novembre 2013, n. 35 "Norme in materia di Unioni montane e di esercizio associato delle funzioni de | 1 | oldest version available: 30 October 2026 |
| `lr-2014-7/` | L.R. 22 aprile 2014, n. 7: Norme sulle misure di prevenzione e protezione dai rischi di caduta dall'alto da predisporre negli edifici per l'esecuzione dei lavor | 1 | oldest version available: 30 October 2026 |
| `lr-2014-8/` | L.R. 22 aprile 2014, n. 8: Modifiche alla legge regionale 3 dicembre 2012, n. 40: "Istituzione del Collegio dei Revisori dei Conti della Regione Marche" | 1 | oldest version available: 30 October 2026 |
| `lr-2014-9/` | L.R. 6 maggio 2014, n. 9: Modifiche alla legge regionale 11 luglio 2006, n. 9 "Testo unico delle norme regionali in materia di turismo" e alla legge regionale 2 | 1 | oldest version available: 30 October 2026 |
| `lr-2014-10/` | L.R. 15 maggio 2014, n. 10: Modifica alla legge regionale 11 novembre 2013, n. 36 "Disciplina del controllo sugli atti degli enti del servizio sanitario regiona | 1 | oldest version available: 30 October 2026 |
| `lr-2014-11/` | L.R. 30 maggio 2014, n. 11: Modifica alla Legge Regionale 3 Aprile 2002, n. 5: "Integrazione della Legge Regionale 26 dicembre 1983, n. 41 sulle provvidenze in | 1 | oldest version available: 30 October 2026 |
| `lr-2014-12/` | L.R. 16 giugno 2014, n. 12: Norme per la tutela e la valorizzazione della produzione orto-floro-frutticola e delle piante ornamentali | 1 | oldest version available: 30 October 2026 |
| `lr-2014-13/` | L.R. 16 giugno 2014, n. 13: Contributi ai Comuni per il mantenimento degli uffici del giudice di pace | 1 | oldest version available: 30 October 2026 |
| `lr-2014-14/` | L.R. 16 giugno 2014, n. 14: Misure di contenimento della spesa di personale in attuazione del decreto legge 31 maggio 2010 n. 78 convertito, con modificazioni, | 1 | oldest version available: 30 October 2026 |
| `lr-2014-15/` | L.R. 23 giugno 2014, n. 15: Distacco della frazione di Marotta dal Comune di Fano e incorporazione nel Comune di Mondolfo. Mutamento delle rispettive circoscriz | 1 | oldest version available: 30 October 2026 |
| `lr-2014-18/` | L.R. 10 luglio 2014, n. 18: Disposizioni in materia di terapie complementari: terapia del sorriso e pet therapy | 1 | oldest version available: 30 October 2026 |
| `lr-2014-19/` | L.R. 28 luglio 2014, n. 19: Modifiche alla legge regionale 10 agosto 1988, n. 34 "Finanziamento delle attività dei gruppi consiliari" | 1 | oldest version available: 30 October 2026 |
| `lr-2014-20/` | L.R. 4 agosto 2014, n. 20: Disposizioni per l'attuazione degli articoli 14, comma 1, lettere b) e f), e 47 del decreto legislativo 14 marzo 2013, n. 33 "Riordin | 1 | oldest version available: 30 October 2026 |
| `lr-2014-21/` | L.R. 4 agosto 2014, n. 21: Approvazione delle modifiche all'intesa tra la Regione Umbria e la Regione Marche concernente il riordino dell'Istituto zooprofilatti | 1 | oldest version available: 30 October 2026 |

## Source

The law database of the Consiglio regionale delle Marche, <https://www.consiglio.marche.it/banche_dati_e_documentazione/leggi/>, archive of texts in force ("archivio dei testi vigenti"): for each regional law, its original text or, when it has been amended, its consolidated text, with editor's notes naming the amending laws. The notes are not copied. Each text here is the page of one law in that archive.

## Dates

- Each act's text is the consolidated text in force on the retrieval day (30 October 2026), as the Consiglio regionale delle Marche's law database publishes it. The source gives no dated past versions in its archive of texts in force (its other archive holds each law only as first published); laws read after that day are dated, the same way, the day their page was read, so each act has one commit, its **oldest version available**, dated at **noon, Europe/Rome, on 30 October 2026** and credited to the Consiglio regionale delle Marche's law database as publisher, naming the act itself.
- This is not the date the text took effect: it is the day the text was read. Earlier wordings are not in this record.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Art. 5, `art-005-bis.md` Art. 5 bis; `preambolo.md` holds anything printed before the first article. Headings of titles, chapters and sections stay in the file of the article they stand before. Acts are named `lr-<year>-<number>`; the Statute is `statuto/`. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the Consiglio regionale delle Marche's law database's own text of that version (read by a second, independent reader), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

Every commit here is an "oldest version available" commit, authored by the publisher, the Consiglio regionale delle Marche's law database, with an e-mail address that cannot exist. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the Bollettino Ufficiale della Regione Marche. Only the current text of each act is recorded, not its earlier wordings. Only the acts listed above are included.
