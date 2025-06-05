# LB Projekt M347 - Containerisierte Dienste

## Übersicht

Dieses Projekt enthält folgende containerisierte Dienste:

- Wordpress (Port 8080)
- MediaWiki (Port 8181)
- Jira (Port 8081)
- Portainer (Port 9000)

## Installation

1. Repository clonen:
    ```bash
    git clone https://github.com/Svensemann93/LB-Projekt-M347.git
    cd LB-Projekt-M347/Projekt
    ```

2. In gewünschten Service-Ordner wechseln und Stack starten:
    ```bash
    cd wordpress
    docker compose up -d
    ```

3. Dienste im Browser testen.

## Stacks

| Dienst      | Port |
|-------------|------|
| Wordpress   | 8080 |
| MediaWiki   | 8181 |
| Portainer   | 9000 |
| Jira        | 8081 |

## Hinweise

- Ports müssen auf dem Host freigegeben sein.
- Datenpersistenz ist für alle Dienste implementiert.
- "Hands-off" Installation gemäss LB Vorgaben.
