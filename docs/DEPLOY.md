# Documentazione Deploy - Seeweb
Procedura manuale di deploy tramite FTP/SFTP.

## Step 1: Backup Pre-deploy
Eseguire un backup completo con Akeeba Backup prima di ogni aggiornamento critico.

## Step 2: Trasferimento File
1. Connettersi al server Seeweb tramite SFTP.
2. Trasferire i file in `/public_html/`.
3. Assicurarsi che le cartelle abbiano i permessi `755` e i file `644`.

## Step 3: Configurazione Database
Importare il file `.sql` da `database/` nel pannello phpMyAdmin di Seeweb.

## Step 4: Post-deploy Check
- Verificare che il file `configuration.php` punti ai nuovi percorsi (`$log_path`, `$tmp_path`).
- Controllare la validità degli header di sicurezza nel file `.htaccess`.
- Eseguire un audit Lighthouse post-online.

## Note
Non condividere MAI le credenziali FTP/SFTP in questo file.
