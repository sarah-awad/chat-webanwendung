# Chat-Webanwendung

Eine Chat-Webanwendung aus dem Modul **Webtechnologien** an der Technischen Hochschule Ingolstadt, entwickelt im Team. Nutzer registrieren sich, verwalten Freundschaftsanfragen, chatten miteinander und passen ihr Profil an. Freundesliste und Nachrichten werden per AJAX nachgeladen, ohne dass die Seite neu lädt.

## Funktionen

- **Registrierung und Login** mit Prüfung auf vergebene Benutzernamen und Passwortregeln
- **Freunde:** Anfragen senden, annehmen oder ablehnen
- **Chat:** Nachrichtenverlauf laden und Nachrichten senden per AJAX
- **Profil und Einstellungen:** Beschreibung, Vorlieben und Chat-Layout anpassen
- **Responsive Oberfläche** mit Bootstrap 5

## Technik

| Bereich | Technik |
| --- | --- |
| Frontend | HTML, CSS, JavaScript, Bootstrap 5 |
| Backend | PHP mit Sessions |
| Kommunikation | AJAX-Endpunkte (`ajax_load_friends.php`, `ajax_load_messages.php`, `ajax_send_message.php`, `ajax_check_user.php`) |
| Struktur | Modellklassen `User` und `Friend`, `BackendService` für die Anbindung an die Chat-API |
| Zusammenarbeit | Git und GitHub mit Branches und Merges |

## Projektstruktur

```
Model/        Modellklassen (User, Friend)
Utils/        BackendService und HttpClient für die Chat-API
images/       Icons
*.php         Seiten (Login, Registrierung, Freunde, Chat, Profil, Einstellungen)
*.js          Clientlogik für Registrierung, Freunde und Chat
```

## Hinweis zum Starten

Die Anwendung nutzt als Backend den Chat-Server der Lehrveranstaltung an der THI (`start.php`). Ohne Zugang zu diesem Server lässt sie sich nicht vollständig ausführen. Der Code zeigt Aufbau und Umsetzung des Projekts.

## Team

- Sara Awad
- Zeljko
- Nina Artukovic
