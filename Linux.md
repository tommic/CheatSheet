
| Command                                                        | Beschreibung                                           |
| -------------------------------------------------------------- | ------------------------------------------------------ |
| `dpkg-reconfigure tzdata`                                      | Zum setzen der Zeitzone in einem System                |
| `crtime [filename]`                                            | crdate, modify date, letztes aufrufen einer Datei      |
| `echo "Testnachricht" \| mail -s "Test Mail" test@example.com` | Send a testmail                                        |
| `inxi`                                                         | Systeminformationen                                    |
| `hostnamevtl set-hostname [hostname]`                          | Hostname ändern (ggf. noch in der /etc/hosts anpassen) |
 
## Netzwerk

| Command                     | Beschreibung                 |
| --------------------------- | ---------------------------- |
| `route add default gw [IP]` | Setzen eines Gateways        |
| `netstat -atu`              | Verwendete Ports anzeigen    |
| `ss -ltn`                   | Offene Ports anzeigen lassen |
## Debugging


| Command                                    | Beschreibung                            |     |
| ------------------------------------------ | --------------------------------------- | --- |
| `journalctl -ex`                           | Öffnet das Journal am ende              |     |
| `journalctl --until "2025-01-14 00:00:00"` | Zeigt das Journal bis zu einer Zeit     |     |
| `journalctl --since "2025-01-10 23:25:00"` | Zeigt das Journal ab einer Zeit         |     |
| `journalctl --since -1h -u chrony`         | Kann auch als -1h usw. angegeben werden |     |
