# Project omschrijving

Help desk ticket systeem voor meerdere scholen. Voor vragen en problemen waarbij je kunt aangeven welke categorie het onder valt.

# Functionaliteiten

- Login systeem voor Beveiligde toegang
- Ticket aanmaken
- Tickets toewijzen aan personen
- Persoonlijk dashboard met welke tickets je hebt geaccepteerd
- Admin panel voor beheer van tickets, accounts en scholen
- Drie rollen: gebruikers die de tickets aanvragen, personen die de tickets oppakken en admin gebruikers die tickets, gebruikers en organisaties kunnen beheren

# Installatie Tailwind

1. Installeer de benodigde packages:

    ```bash
    npm install
    ```

2. Start de watcher (terminal ./project-1-basis-scrum-c2025-team-1 (main)):

    ```bash
    npm run watch
    ```

    Of als dat niet werkt, probeer:

    ```bash
    npx @tailwindcss/cli -i ./src/input.css -o ./public/style.css --watch
    ```

3. Controleer of alle paths naar `output.css` kloppen en dan zou het moeten werken!

# Installatie & Draaien (XAMPP)

Volg deze stappen om de backend en de database werkend te krijgen via XAMPP.

1. start de XAMPP op en start Apache en MySQL.

2. Open je browser en plak http://localhost/phpmyadmin/ in je browser of druk op de Admin knop in XAMPP bij MySQL.

3. Kopieer de `inport.sql` bij het knopje **SQL** en plak daarin de inport.sql file daarin.

4. Controleer eest het bestand waar de database-connectie wordt gemaakt (bijv. database.inc anders maak dan een `database.php` aan van behulp van `database.inc.php`). Zorg dat de gegevens overeenkomen met je XAMPP instellingen:

- Host: localhost

- User: bit_academy

- Password: (leeg laten) of eigen password invullen

- Database: quizzo

5. Je kunt de applicatie nu bereiken via je browser op de volgende URL:
http://localhost/naam-van-jouw-map/public/

	<sub> (Vervang naam-van-jouw-map door de werkelijke naam van je projectmap in htdocs). 	</sub>
