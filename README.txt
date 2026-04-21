{\rtf1\ansi\ansicpg1252\cocoartf2869
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 Katzen Trink Monitor \'96 PWA + Telegram\
======================================\
\
Dateien:\
  index.html     \uc0\u8594  Haupt-App\
  manifest.json  \uc0\u8594  PWA-Manifest\
  sw.js          \uc0\u8594  Service Worker (Offline-F\'e4higkeit)\
  icon-192.png   \uc0\u8594  App-Icon\
  icon-512.png   \uc0\u8594  App-Icon gro\'df\
\
SCHNELLSTART\
------------\
1. Alle Dateien auf einen Webserver oder lokalen HTTP-Server legen\
   (z. B. mit "npx serve ." oder auf einen Hosting-Dienst wie GitHub Pages)\
2. URL in Chrome auf dem Redmi A2 \'f6ffnen\
3. Kamerazugriff erlauben\
4. Telegram Bot-Token + Chat-ID eintragen\
5. "Trinkbereich festlegen" \uc0\u8594  Rechteck \'fcber den Napf ziehen\
6. "Kamera starten" \uc0\u8594  "\'dcberwachung starten"\
7. Installation: Chrome-Men\'fc \uc0\u8594  "Zum Startbildschirm hinzuf\'fcgen"\
\
TELEGRAM BOT ERSTELLEN\
-----------------------\
1. In Telegram: @BotFather schreiben \uc0\u8594  /newbot\
2. Bot-Token kopieren \uc0\u8594  in App eintragen\
3. Chat-ID: @userinfobot anschreiben \uc0\u8594  ID kopieren \u8594  in App eintragen\
4. "Telegram testen" dr\'fccken \uc0\u8594  Foto sollte ankommen\
\
HINWEISE\
--------\
- Handy ans Ladeger\'e4t h\'e4ngen\
- Akku-Optimierung f\'fcr Chrome deaktivieren\
  (Einstellungen \uc0\u8594  Apps \u8594  Chrome \u8594  Akku \u8594  Nicht optimieren)\
- Bildschirm muss aktiv bleiben\
- F\'fcr Service Worker und PWA-Install: App \'fcber http(s) \'f6ffnen, nicht \'fcber file://}