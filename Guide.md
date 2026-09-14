# MCM Memory - Settings Backup and Restore 1.4.0

MCM Memory è un plugin SKSE, senza ESP e senza script Papyrus propri. 
Mantiene uno o più profili JSON esterni contenenti i valori delle MCM.
Il profilo attivo viene aggiornato quando cambi le impostazioni oppure quando fai un backup esplicito

I profili vengono conservati in: Data\SKSE\Plugins\MCMMemory\Profiles
e ogni profilo contiene insieme le configurazioni delle varie MCM.

- Automatic Backup: Aggiorna automaticamente il profilo attivo quando modifichi una MCM supportata
- Back Up Now: Legge tutte le MCM registrate e crea/aggiorna il backup completo
- Selected: Decide quali MCM coinvolgere quando premi Back Up Selected / Restore Selected
- Saved Settings: Indica quanti valori di quella MCM sono presenti nel profilo
- Auto Restore: Decide se quella specifica MCM deve essere ripristinata automaticamente quando inizi una nuova partita

## Cosa significa un “Failed”

Un singolo Failed non significa necessariamente che MCM Memory sia rotto, né che il profilo sia compromesso.
MCM Memory deve comunicare con MCM progettate da autori diversi, alcune delle quali usano controlli SkyUI standard.
MCM Memory supporta normalmente: toggle, slider, menu, colori, text input, keymap e diversi altri controlli SkyUI/MCM Helper.
Ma alcune mod usano controlli personalizzati, la 1.4.0 non riesce ancora a leggere correttamente tutti questi controlli.
