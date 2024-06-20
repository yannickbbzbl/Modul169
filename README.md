# Modul169

## Über das Projekt
Dies ist ein Projekt für die Schule, wo es um Docker geht, wie man mit diesen arbeitet und wie sie funktionieren. In meinem Projekt geht es um einen Wordpress Docker zusammen mit einer MySQL Datenbank Verknüpfung. Wordpress ist eine Webapplikation mit vielen Möglichkeiten darunter auch ein Marketplace, wo man sich verschiedene Applikation nach eigenem Wunsch installieren kann darunter auch Texteditor usw. Das ganze in einem Docker.

## Projekt starten
<a href="https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/yannickbbzbl/Modul-347">
  <img 
    src="https://img.shields.io/badge/Open_in-DevContainer-blue?logo=visual-studio-code" 
    alt="Open in DevContainer" 
    height="40"
  >
</a>

Um das Projekt zu starten auf das obere Icon klicken. das Projekt wird automatisch installiert. Um ohne eine Veränderung des Codes zu arbeiten im C:\ Speichermedium einen Ordner mit dem Namen: "db-docker" erstellen oder unter db:
                                                                                                                                                                                                                                   volumes:
                                                                                                                                                                                                                                   - "dein Pfad"\.db:/var/lib/mysql

Dannach folgenden Befehl im Terminal eingeben: ``docker compose up`` als zweites dann ``start docker``. 
Nun sollte der Docker mit Datenbank offen sein. Das ganze läuft auf dem Port
