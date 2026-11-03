<!doctype html>
<html lang="fr">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="theme-color" content="#0B7A6B">
<title>Jauge Énergie</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Familjen+Grotesk:wght@500;700&family=IBM+Plex+Mono:wght@400;500&display=swap">
<style>
/* Mise en page : une colonne étroite façon tableau de bord d'instrument, jauge circulaire en tête, mesures en grille 2 colonnes, courbe pleine largeur. */
:root{
  --bg:#EDF2F0; --surface:#FFFFFF; --fg:#13211F; --muted:#5A6E6A; --line:#D3DEDB;
  --accent:#0B7A6B; --accent-soft:#D5EEE9; --warn:#C7721B; --crit:#B8362B; --ok:#1F8A4C;
  --display:"Familjen Grotesk","Helvetica Neue",Arial,sans-serif;
  --mono:"IBM Plex Mono",ui-monospace,Menlo,Consolas,monospace;
}
@media (prefers-color-scheme:dark){
  :root:not([data-theme="light"]){
    --bg:#0D1614; --surface:#15211F; --fg:#E5EEEC; --muted:#8FA6A1; --line:#26373A;
    --accent:#3FC7B0; --accent-soft:#17332F; --warn:#E59A4A; --crit:#EE7468; --ok:#5CCB86;
    color-scheme:dark;
  }
}
:root[data-theme="dark"]{
  --bg:#0D1614; --surface:#15211F; --fg:#E5EEEC; --muted:#8FA6A1; --line:#26373A;
  --accent:#3FC7B0; --accent-soft:#17332F; --warn:#E59A4A; --crit:#EE7468; --ok:#5CCB86;
  color-scheme:dark;