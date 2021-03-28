---
created: 2021-03-28
keywords:
  - guide
  - redundant
  - selfhosting
  - linux
---
# Sinnvolle services
20210328212259

|        | Service    | Zweck                                                                           | Notizen               |
|--------|------------|---------------------------------------------------------------------------------|-----------------------|
| P _  A | etebase    | Zero knowledge Kontakte, Kalender, To-Do und Notizen sync mit etesync           |                       |
| P G A  | Nextcloud  | Cloud-Suite: One/g-Drive alternative                                            | A: Cryptomator        |
| P _  _ | Send       | Zero knowledge: Dateien versenden                                               | Früher Firefox Send   |
| P G A  | Synapse    | Matrix / Element: Verschlüsselte Privat und Gruppenchats                        |                       |
| _ G  _ | Mattermost | Team-kommunikation: Slack alternative                                           | Keine e2ee, "nur" ear |
| _ G  A | Cryptpad   | Zero knowledge WYSIWYG & Markdown Pads, Spreadsheets, Kanban, Polls und Dateien |                       |
| _ G  _ | Bookstack  | Wiki für Gruppen um Wissenhirarchien abzubauen                                  |                       |
| _ G  _ | wiki.js    | Wiki für Gruppen um Wissenhirarchien abzubauen                                  |                       |

Das alles sollte in containern gut voneinander getrennt sein.    
Why? Sollte eine instanz eine sicherheitslücke haben und privelige escalation is am happenen dann geht nicht gleich der ganze server flöten.

Mehr dazu später.

## Warum kein eMail?
Weil das scheiße aufwändig ist, schwer abzusichern, aufwändig zu betreuen und bei einem Domainumzug einfach nur noch komplett beschissen ist.
Hoste keine mails selber. Wirklich. Hol dir lieber Protonmail, Tutanota, Mailfence oder Posteo je nachdem was du für features möchtest.