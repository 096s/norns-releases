# Norns POS · Auslieferung

Dieses Verzeichnis trägt ausschliesslich die signierten Installationspakete
von Norns POS und das Update-Verzeichnis, aus dem sich jede installierte
Kasse selbst aktualisiert. Quelltext liegt hier keiner.

## Installation

Die jeweils aktuelle Fassung steht unter Releases. Windows installiert über
die MSI-Datei, macOS über das App-Archiv. Nach der ersten Installation hält
sich die Kasse von selbst aktuell: sie prüft beim Start das Verzeichnis
`latest.json`, lädt die neue Fassung im Hintergrund und prüft vor dem
Einspielen die Signatur. Ein Paket ohne gültige Unterschrift wird verworfen.

## Herkunft

Jedes Paket entsteht auf einem sauberen Bauläufer, wird dort signiert und
erst veröffentlicht, wenn der gesamte Prüfweg getragen hat, unter anderem
der Start des Motors im fertig signierten Programm.

Fragen zu Betrieb und Einsatz: [norns.de](https://norns.de)
