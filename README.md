## PROGETTO 8: GESTIONE LOG CENTRALIZZATA E ANALISI
### Scenario 
  I log di Windows (System, Application, Security) devono essere raccolti, analizzati e archiviati centralmente per troubleshooting e compliance. 
### Obiettivi 
  1. Raccolta log Windows in formato strutturato 
  2. Filtro eventi critici ed errori 
  3. Analisi pattern e anomalie 
  4. Archiviazione log rotazionale 
  5. Dashboard di visualizzazione 
### Requisiti Tecnici 
  - Export log in CSV/JSON 
  - Filtri per tipo evento, source, livello 
  - Identificazione eventi ricorrenti 
  - Rotazione archivio (conserva 30 giorni) 
  - Report top 10 errori/warning 
### Divisione Compiti Suggerita 
  - **Membro A**: Raccolta ed export log 
  - **Membro B**: Analisi e filtri 
  - **Membro C**: Dashboard e visualizzazione 
### Deliverables Specifici 
  - `Collect-Logs.ps1` - Script raccolta 
  - `Analyze-Logs.ps1` - Script analisi 
  - Report top eventi 
  - Dashboard HTML 

# Comandi da inserire sul terminale per runnare il programma:
```
  powershell -ExecutionalPolicy Bypass -File "C:\Script\Progetto_8-RunAll.ps1"
  & "C:\Script\Progetto_8-RunAll.ps1"
```
