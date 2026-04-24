# NGINX Lab – Personlig startsida

Detta projekt är en kursuppgift för att installera och konfigurera NGINX på en Ubuntu Server och leverera en enkel personlig webbsida via HTTP på port 80.

## Projektets innehåll

- `index.html` – statisk startsida med animerad bakgrund och en rörlig textetikett.
- `installation.md` – steg-för-steg-dokumentation av installation och konfiguration.
- `nginx.png` – skärmdump som visar att startsidan levereras av NGINX.
- `wordpress-post.png` – skärmdump för WordPress-inlägg (bonusdel).
- `wordpress-page.png` – skärmdump för WordPress-sida (bonusdel).

## Syfte

Målet är att visa att en Ubuntu Server kan använda NGINX för att leverera en webbplats. Huvudfokus är:

- installera NGINX
- placera en egen `index.html` som startsida
- dokumentera installation och testning

## Filbeskrivning

- `index.html`
  - En enkel, responsiv startsida med gradientbakgrund och en rörlig `sahand-devops`-etikett.
  - Den ska användas som webbserverns rotfil (`/var/www/html/index.html`).
- `installation.md`
  - Dokumenterar de använda kommandona, viktiga loggfiler och konfigurationssteg.
- `nginx.png`
  - Visar webbläsaren med den publicerade startsidan.
- `wordpress-post.png` och `wordpress-page.png`
  - Används endast om WordPress-bonusdelen genomförs.

## Användning

1. Kopiera `index.html` till NGINX webbrotsmapp på Ubuntu Server.
2. Starta eller starta om NGINX.
3. Besök serverns IP-adress i webbläsaren på port 80.

## Notering

Dokumentationen i `installation.md` beskriver de faktiska kommandona och loggfilerna som används under installationen. Om bonusdelen genomförs finns WordPress-skapade skärmdumpar som stöd.
