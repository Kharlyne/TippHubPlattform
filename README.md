# TippHubPlattform

TippHubPlattform ist eine Webanwendung für eine Wett- und Community-Plattform.  
Das Projekt umfasst ein Angular-Frontend sowie ein Java-Backend mit Vert.x. Ziel ist es, eine Plattform bereitzustellen, auf der Nutzer Communities beitreten, Events verwalten und an Wettaktivitäten teilnehmen können.

## Aktueller Stand

Das Projekt befindet sich derzeit noch in der Entwicklung.  
Die grundlegende Struktur mit Frontend und Backend ist bereits vorhanden, jedoch ist die Anwendung noch nicht vollständig fertiggestellt und wird weiterhin schrittweise erweitert und verbessert.

## Projektstruktur

- `tipp-hub-frontend` 
- `Backend`
## Voraussetzungen

- Node.js und npm
- Angular CLI
- Java 21
- Maven
- MariaDB

## Projekt starten

### 1. Repository klonen

```bash
git clone https://github.com/Kharlyne/TippHubPlattform.git
cd TippHubPlattform
```

### 2. Backend starten

``` bash
cd Backend
mvn clean compile
mvn exec:java
```

Backend läuft auf:

http://localhost:8888

### 3. Frontend starten

In einem neuen Terminal:

``` bash
cd tipp-hub-frontend
npm install
ng serve
```

Frontend läuft auf:

http://localhost:4200

-------

## Technologien
- Angular
- TypeScript
- Java
- Vert.x
- Maven
- MariaDB
