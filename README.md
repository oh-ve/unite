# 👷 UNITE!

##### English

[German below](#deutsch).

## Project Overview

View it [here](https://unite23.netlify.app/)!

Unite! is a web-based platform designed to facilitate communication and information exchange among employees and work council representatives in a company. The primary function of this platform is to enable employees to anonymously compare salaries, communicate with each other, and interact with their work council representatives.

The primary objective of Unite! is to establish a fair and equitable workplace by:

- Encouraging solidarity and unity among workers.
- Providing tools for fair salary negotiation.

This project was developed as the final project for the "Full-stack web and app development" bootcamp at WBS Coding School. For the demonstration, certain standard features have been adapted for simplicity. For instance, while a typical registration process would involve email confirmation by work council representatives, this requirement has been modified for ease of demonstration. The simplified registration process now includes an option to "Create new company space," allowing users to easily sign up either as work council representatives or as employees. This adaptation serves to demonstrate the core functionalities without the complexities of the full registration process. Future developments of the project could potentially expand on this feature, enabling work council members to establish and manage a new company space that organizes all employees within a company.

## Key Features

- **Salary Comparison**: Allows employees to anonymously compare their salaries with peers based on parameters like position, age, gender, and years of employment.
- **Contact work council**: Enables employees to directly and anonymously contact work council representatives.
- **Calendar**: Provides a shared calendar for employees to view and manage upcoming events and meetings relevant to the workplace.
- **Bulletin Board**: A digital bulletin board for posting announcements, updates, and information.

## Technical Specifications

### Technology Stack

- **Frontend**: Developed using React.js.
- **Backend**: Managed by Node.js and Express.js.
- **Database**: Utilizes MongoDB for data storage and management.

### Installation and Setup

1. Clone the repository: `git clone [repository URL]`
2. Navigate to the project directory: `cd [project directory]`
3. Install frontend dependencies: `cd unite-frontend` and then `npm install`
4. Install backend dependencies: `cd unite-backend` and then `npm install`

### Required npm Packages

#### Backend Dependencies

The backend of the Unite! platform, named `unite-backend`, requires the following npm packages:

- **bcrypt**: Used for hashing and securing passwords.
- **cors**: Middleware for enabling CORS (Cross-Origin Resource Sharing).
- **dotenv**: For loading environment variables from a `.env` file.
- **express**: Web application framework for Node.js.
- **jsonwebtoken**: For implementing JSON Web Tokens.
- **mongoose**: MongoDB object modeling tool for Node.js.
- **validator**: For validating and sanitizing strings.

Development Dependency:

- **nodemon**: Utility that monitors for any changes in the source and automatically restarts the server.

Start the backend server: `npm run dev` (in the backend directory)

#### Frontend Dependencies

The frontend of the Unite! platform, named `unite-frontend`, includes the following npm packages:

- **axios**: For making HTTP requests from the browser.
- **react-big-calendar, react-calendar, react-datepicker**: For calendar functionalities.
- **react-icons**: For including icons in the application.
- **react-jwt**: For handling JWTs in the React application.
- **react-router-dom**: For routing in the application.
- **rechart, recharts**: For adding charts to the application.
- **remixicon**: For additional icons.

Scripts defined in the `package.json` file help in starting, building, testing, and ejecting the application as needed.

For a complete list of dependencies and their versions, refer to the `package.json` files in the respective `unite-backend` and `unite-frontend` directories of the project repository.

Start the frontend application: `npm start` (in the frontend directory)

### Configuration

#### Environment Variables

- Set up the required environment variables in the `.env` file in the backend directory. Use the `sample.env` file as a template for setting up your environment variables.

#### Database Connection

- Users need to set up their own MongoDB database server. Configure the MongoDB connection by providing your database's URI in the `.env` file. This URI should point to your MongoDB server, which could be a local instance or a cloud-based service like MongoDB Atlas.

## Contact

Feel free to contact me for further questions 📧 maricic.ve@gmail.com.

# 👷 UNITE!

##### Deutsch

[Zurück zu englisch](#english).

## Projektübersicht

[Hier](https://unite23.netlify.app/) ansehen!

Unite! ist eine webbasierte Plattform, die den Austausch und die Kommunikation zwischen Mitarbeiter\*innen und Betriebsrat in einem Unternehmen erleichtern soll. Die Hauptfunktion dieser Plattform besteht darin, Mitarbeiter\*innen zu ermöglichen, Gehälter anonym zu vergleichen, miteinander zu kommunizieren und mit ihren Betriebsrät\*innen zu interagieren.

Das Hauptziel von Unite! ist es, einen fairen und gerechten Arbeitsplatz zu schaffen, indem:

- Solidarität und Einigkeit unter den Arbeitnehmern gefördert werden.
- Werkzeuge für eine faire Gehaltsverhandlung bereitgestellt werden.

Dieses Projekt wurde als Abschlussprojekt für das Bootcamp „Full-stack Web- and App-Development“ an der WBS Coding School entwickelt. Für die Demonstration wurden bestimmte Standardfunktionen vereinfacht. Beispielsweise würde ein typischer Registrierungsprozess eine E-Mail-Bestätigung durch den Betriebsrat erfordern, diese Anforderung wurde jedoch zur Vereinfachung der Demonstration geändert. Der vereinfachte Registrierungsprozess beinhaltet jetzt eine Option zum „Erstellen eines neuen Unternehmensbereichs“ ("Create new company space"), die es den Benutzer\*innen ermöglicht, sich entweder als Betriebsratsvertreter\*in oder als Mitarbeiter\*in anzumelden. Diese Anpassung dient dazu, die Kernfunktionalitäten ohne die Komplexitäten des vollständigen Registrierungsprozesses zu demonstrieren. Zukünftige Entwicklungen des Projekts könnten diese Funktion erweitern, um Betriebsratsmitgliedern die Einrichtung und Verwaltung eines neuen Unternehmensbereichs zu ermöglichen, der alle Mitarbeiter\*innen eines Unternehmens organisiert.

## Hauptmerkmale

- **Gehaltsvergleich**: Ermöglicht es Mitarbeiter\*innen, ihre Gehälter anonym mit Kollegen basierend auf Parametern wie Position, Alter, Geschlecht und Beschäftigungsjahren zu vergleichen.
- **Kontakt zum Betriebsrat**: Ermöglicht es Mitarbeiter\*innen, direkt und anonym Kontakt mit den Betriebsratsvertreter\*innen aufzunehmen.
- **Kalender**: Bietet einen gemeinsamen Kalender, damit Mitarbeiter\*innen bevorstehende Ereignisse und Besprechungen, die für den Arbeitsplatz relevant sind, einsehen und verwalten können.
- **Schwarzes Brett**: Ein digitales Schwarzes Brett für die Veröffentlichung von Ankündigungen, Updates und Informationen.

## Technische Spezifikationen

### Tech-Stack

- **Frontend**: Entwickelt mit React.js.
- **Backend**: Verwaltet von Node.js und Express.js.
- **Datenbank**: Nutzt MongoDB für Datenhaltung und -management.

### Installation und Einrichtung

1. Klone das Repository: `git clone [Repository-URL]`
2. Navigiere zum Projektverzeichnis: `cd [Projektverzeichnis]`
3. Installiere die Frontend-Abhängigkeiten: `cd unite-frontend` und dann `npm install`
4. Installiere die Backend-Abhängigkeiten: `cd unite-backend` und dann `npm install`

### Erforderliche npm-Pakete

#### Backend-Abhängigkeiten

Das Backend der Unite!-Plattform, genannt `unite-backend`, benötigt die folgenden npm-Pakete:

- **bcrypt**: Wird zur Hashing und Sicherung von Passwörtern verwendet.
- **cors**: Middleware zur Aktivierung von CORS (Cross-Origin Resource Sharing).
- **dotenv**: Zum Laden von Umgebungsvariablen aus einer `.env`-Datei.
- **express**: Webanwendungsframework für Node.js.
- **jsonwebtoken**: Zur Implementierung von JSON Web Tokens.
- **mongoose**: MongoDB-Objektmodellierungswerkzeug für Node.js.
- **validator**: Zur Validierung und Sanierung von Strings.

Entwicklungsabhängigkeit:

- **nodemon**: Hilfsprogramm, das Änderungen in der Quelle überwacht und den Server automatisch neu startet.

Starte den Backend-Server: `npm run dev` (im Backend-Verzeichnis)

#### Frontend-Abhängigkeiten

Das Frontend der Unite!-Plattform, genannt `unite-frontend`, enthält die folgenden npm-Pakete:

- **axios**: Für HTTP-Anfragen vom Browser.
- **react-big-calendar, react-calendar, react-datepicker**: Für Kalenderfunktionalitäten.
- **react-icons**: Zur Einbindung von Icons in die Anwendung.
- **react-jwt**: Zur Handhabung von JWTs in der React-Anwendung.
- **react-router-dom**: Für das Routing in der Anwendung.
- **rechart, recharts**: Zur Hinzufügung von Diagrammen zur Anwendung.
- **remixicon**: Für zusätzliche Icons.

Skripte, die in der `package.json`-Datei definiert sind, helfen beim Starten, Bauen, Testen und Auswerfen der Anwendung nach Bedarf.

Für eine vollständige Liste der Abhängigkeiten und deren Versionen siehe `package.json`-Dateien in den jeweiligen Verzeichnissen `unite-backend` und `unite-frontend` des Projekt-Repositorys.

Starte die Frontend-Anwendung: `npm start` (im Frontend-Verzeichnis)

### Konfiguration

#### Umgebungsvariablen

- Richte die erforderlichen Umgebungsvariablen in der `.env`-Datei im Backend-Verzeichnis ein. Verwende dafür die `sample.env`-Datei als Vorlage für das Einrichten deiner Umgebungsvariablen.

#### Datenbankverbindung

- Benutzer müssen ihren eigenen MongoDB-Datenbankserver einrichten. Konfiguriere die MongoDB-Verbindung, indem du die URI deiner Datenbank in der `.env`-Datei angibst. Diese URI sollte auf deinen MongoDB-Server zeigen, der entweder eine lokale Instanz oder ein cloudbasierter Dienst wie MongoDB Atlas sein könnte.

## Kontakt

Für weitere Fragen kannst du mich gerne kontaktieren! 📧 maricic.ve@gmail.com
