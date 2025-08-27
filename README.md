# Uppgift 1 – NGINX

## Syfte

Att självständigt kunna installera och konfigurera serverprogramvara med hjälp av dokumentation på internet.

## Översikt

Uppgiften består av två delar:

1. Grunddel (obligatorisk) – krävs för att klara kursen.
2. Bonusdel (frivillig) – ger **2 extra poäng** på tentan och de två första omtentorna.

I båda delarna ska du aktivt söka information och dokumentera alla steg.

Dokumentationen ska skrivas i Markdown och lämnas in i filen `installation.md` enligt följande krav:

- Använd endast Markdown – inga HTML-taggar.
- Använd tydliga rubriker.
- Håll styckena korta (ingen ”wall of text” någonstans).
- Använd "inline code" och "code blocks" för kommandon och konfiguration.

Observera att den här uppgiften ska utföras på Ubuntu Server precis som den andra. Uppgifterna "krockar" inte, så du kan utföra båda på samma Ubuntu Server-installation.

Läs igenom hela dokumentet noggrannt innan du börjar för att minimera risken för missförstånd.

## Grunddel – NGINX *(obligatorisk)*

Din Ubuntu Server ska leverera en personlig webbsida med hjälp av NGINX via HTTP på port 80.

### Beskrivning

- Installera NGINX Server på Ubuntu Server.
- Använd den bifogade filen `index.html` som startsida.

  - Ersätt `Username` med ditt GitHub-användarnamn.

- Dokumentera arbetet i `installation.md`:

  - Beskriv varje steg du utför. Skriv en kort text följt av kommandon.
  - Beskriv viktiga loggfiler, var de finns och varför de är relevanta.

- Skärmdump: `nginx.png`:

  - Visa webbläsaren med startsidan.
  - Länka bilden i `installation.md` så att den visas i Preview.

## Bonusdel – WordPress *(frivillig, 2 poäng)*

Din Ubuntu Server ska köra Wordpress via HTTP på port 80.

- Installera och konfigurera MySQL eller MariaDB för WordPress.
- Installera och konfigurera WordPress så att det visas via NGINX på port 80.

  - Startsidan från grunddelen ersätts; skärmdumpen från grunddelen räcker som bevis.

- Skapa en Post (ett inlägg) i WordPress som innehåller ditt GitHub-användarnamn.
- Skapa en Page (en statisk sida) som innehåller texten "Statisk sida" och ditt GitHub-användarnamn.
- Dokumentera arbetet under rubriken ”WordPress” sist i `installation.md`.

  - Beskriv varje steg du utför. Skriv en kort text följt av kommandon.
  - Beskriv viktiga loggfiler för databasen, var de finns och varför de är relevanta.

- Skärmdump #1: `wordpress-post.png`:

  - Visa webbläsaren med WordPress och ditt inlägg med ditt GitHub-användarnamn.
  - Länka bilden i `installation.md` så att den visas i Preview.

- Skärmdump #2: `wordpress-page.png`:

  - Visa webbläsaren med WordPress och din statiska sida med texten "Statisk sida" och ditt GitHub-användarnamn.
  - Länka bilden i `installation.md` så att den visas i Preview.

## Filer att lämna in

Du ska lämna in tre filer:

- `installation.md` – dokumentation
- `nginx.png` – skärmdump för grunddelen
- `wordpress-post.png` – skärmdump #1 för Wordpress om du gör bonusdelen
- `wordpress-page.png` – skärmdump #2 för Wordpress om du gör bonusdelen

### Inlämningsinstruktioner

Läs dokumentet [Studentguide till GitHub Classroom][1].

[1]: https://github.com/nackc8/kursmaterial/blob/main/shared/studentguide-till-github-classroom.md
