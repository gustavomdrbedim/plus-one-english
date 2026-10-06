# PLUS ONE — V13

V12 visual + integração preparada para Google Sheets / Google Drive.

## Estrutura
- `plus-one-v12/web/` — versão Web
- `plus-one-v12/app/` — versão App
- `apps-script/Code.gs` — backend Google Apps Script

## Fluxo
Aluno responde → navegador envia JSON → Apps Script → planilha mestre + uma planilha individual no Drive.

Antes de publicar, substitua `COLE_AQUI_A_URL_DO_APPS_SCRIPT` nos dois `script.js` pela URL `/exec` do Web App.
